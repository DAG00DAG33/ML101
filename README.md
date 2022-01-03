# ML101
The goal of this project is to do a ML project as simple as poosible to explain people without any previous knowladge what a NN is.

The goal is to classify words into two categories. Words are represented a a 2D vector, so it is easy to see how the NN works, and computations can be verified manually.

To do this I use as pretrained word to vec dictionary and reduce the dimensionality with PCA. This is not important for the NN explanation, and should be explained as a black box. It is just important to understand that it is like a dictionary the computer can consult and the numbers (vector) it gives is like a description of the word, and contains its information. That can be shown and explained saying that dog - cat is smaller that cat - armchar.
