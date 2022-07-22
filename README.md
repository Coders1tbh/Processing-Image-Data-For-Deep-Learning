# Processing-Image-Data-For-Deep-Learning

Here, in this short project, we are going to process the image data for deep learning for prediction. For that we need the image to be of numerical value and also the dimensions must be of the same value. For that , we are going to change the image data to numerical array as well as resizing its dimension.

In this project, we are taking a colourful image of a dog. For accesing the image data, we can utilize three types of packages i.e. matplotlib.image, pillow and opencv.If we observe its dimensions , the first two values represent the length and width of the image, the last value represents the color scale which is 3 which implies that the image is coloured (as 3 represents the three primary colors Red(R), Green(G) and Blue(B) whereas value = 1 represents grayscale image).

By printing the image array after conversion, we obtain a total of 6 arrays as it is evident from the calculation that 2( Length and Breadth ) x 3( R,G,B ) = 6. Also, the color scales will be from 0(darkest) to 255(brightest) .

We can even transform such image arrays back to the image.

For resizing purpose so as to accomodate the coditions undertaken by DL, we use a package PIL and we import its sublibrary Image. From this library, we can easily resize it to our required shape ( In our case, we have taken (200,200)).
