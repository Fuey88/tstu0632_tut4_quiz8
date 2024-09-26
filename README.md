
# Quiz 8 - Design Research
_Tom Studley - tstu0632_
<br>
## Part 1: Pixel Sorting Effect
Pixel sorting is a glitch art imaging effect that rearranges pixels in an image based on those pixels properties. This creates a dynamic distortion effect as indivudal pixels are being deconstructed and reconstructed.

<br></br>
![image](assets/colour.png)
_The Starry Night after colour sorting_
<br></br>
![image](assets/brightness.png)
_Girl with the Pearl Earring after brightness sorting_
<br></br>

This technique will benefit our major assignment since it can be easily integrated with perlin noise, randomisation, and time-based animation. I am interested in the technique because of its abstract, dynamic aesthetic as well as its potential as a deconstructionist motif.

## Part 2: Implementation
To implement pixel sorting in p5.js, the approach will involve loading the pixel data of an image and rearranging them based on a specific criterion. This can be achieved by:
            
1. Creating a pixel array
2. Applying a sorting algorithm
3. Updating the canvas<br>

There are countless possibilities for the implementation of a sorting algorithm. It can influence elements of directionality, colour, brightness, animation, area-specificity, and randomisation. You can see one great code example combining some of these elements [here](https://happycoding.io/tutorials/p5js/images/pixel-sorter) creating a dynamic effect. Its outcome is demonstrated in the gif below.
<br>
<br>
![image](assets/example.gif)
<br>
_Lighter pixels are moved up, and darker pixels are moved down._
