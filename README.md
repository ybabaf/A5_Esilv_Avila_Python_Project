# A5_Esilv_Avila_Python_Project


The dataset choosen is the Avila dataset. The Avila bible is a document written during the XII century by italians and spanishes.
From 800 images, 10 features have been extracted to determined who wrote a page of the bible.
12 copyists have been found.

Here is a quick explanation of the 10 features : 

  - The upper margin and the lower margin of the page and the inter-column distance are very useful to highlight chronological and/or typological differences.
  - the number of rows in the column and the column exploitation coefficient are measure of how much the column is filled with ink, and it is computed as the ratio of the number of black pixels on the total number of pixels in a column.
  - The weight is a measure of how much a row is filled with ink and it is computed as the ratio of the number of black pixels on the total number of
pixels in a row. 
  - The modular ratio estimates the dimension of handwriting characters, and it is a typical palaeographic feature.
  - Modular ratio, interline spacing and modular ratio/interline spacing ratio characterize the way of writing of a single scribe and they may also hint to geographical and/or chronological distinctions.

The task here is to predict from a sample of image, who is the writer of a page.

(source document is joined in this repository)

We used the Random forest model for our prediction, which showed a 98% accuracy.


C. De Stefano, M. Maniaci, F. Fontanella, A. Scotto di Freca,
Reliable writer identification in medieval manuscripts through page layout features: The "Avila" Bible case, Engineering Applications of Artificial Intelligence, Volume 72, 2018, pp. 99-110.
