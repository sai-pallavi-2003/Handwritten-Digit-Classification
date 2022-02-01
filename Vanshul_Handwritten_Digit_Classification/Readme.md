<center><h1>HandWritten Digit Classification</h1></center>
<h1>This project is made under UAceIT Winter of Mentorship 2.0</h1>
<h2>Libraries Used: </h2>
<ul>
    <li>Numpy</li>
    <li>Pandas</li>
    <li>Matplotlib</li>
</ul>
<h3>To classify the handwritten digits, we have used <b>KNN Algorithm</b>, stands for K-Nearest Neighbor Algorithm.</h3>

<h3>About KNN Algorithm</h3>
<li>K-Nearest Neighbour is one of the simplest Machine Learning algorithms based on Supervised Learning technique. K-NN algorithm assumes the similarity between the new case/data and available cases and put the new case into the category that is most similar to the available categories. K-NN algorithm can be used for Regression as well as for Classification but mostly it is used for the Classification problems.</li>


<h3>Data Information:</h3>

<li>
The file <bold>train.csv</bold> from MNIST dataset, contain gray-scale images of hand-drawn digits, from zero to nine.</li>

<!-- Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive.

The training data set, (train.csv), has 785 columns.

The first column, called "label", is the digit that was drawn by the user.

The rest of the columns contain the pixel-values of the associated image.

Each pixel column in the training set has a name like pixelx, where x is an integer between 0 and 783, inclusive. To locate this pixel on the image, suppose that we have decomposed x as x = i * 28 + j, where i and j are integers between 0 and 27, inclusive. Then pixelx is located on row i and column j of a 28 x 28 matrix, (indexing by zero).

For example,
pixel31 indicates the pixel that is in the fourth column from the left, and the second row from the top, as in the ascii-diagram below.
Visually, if we omit the "pixel" prefix, the pixels make up the image like this: -->
