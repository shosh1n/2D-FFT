# 2D-FFT 
Loads a simple 1024 x 1024 greyscale gradient .png image

The 2D-FFT uses a recursive function.
Steps include:

- FT of the x-Dimension 
-->Transpose
- FT of the y-Dimension

Results can be verified with the visual comparision of numpys fft & fft2 function

**Note: this is not the cleanest implementation. It works. 
The double For loop is problematic
I tried to refrain from one big function/class because I favored re-usability of small functions.

Credit goes to https://www.katjaas.nl/home/home.html#anchor3 and Simon Xu https://www.youtube.com/watch?v=mkGsMWi_j4Q&t=7s
