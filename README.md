# Converting-Color-Image-to-Gray-Scale-Image


The code starts by fetching a random dog image URL from an API. It does this using the Fetch API, which is a modern
method for making network requests in JavaScript.


The code also loads the same image in another canvas element (canvas2) and then applies a grayscale filter to it.
It does so by taking the RGB values of each pixel, converting them to grayscale using a weighted average formula
(where red, green, and blue channels are combined with specific weights), and replacing the original color.


To trigger the grayscale conversion, the code adds a click event listener to the canvas2. When you click on the grayscale
image, it gets converted to grayscale.
