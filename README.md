# LennartJonesPot_animation

This code creates an animation of n-bodies arranged in a grid and located in a Lennart-Jones potential.

The creation of the animation is shown in two different ways, depending on the magnitudes of the given inputs. 
If you decide to use very small numbers, Matplotlib tends to take a very long time. Then the FFmpeg version is a good choice, where you first create the images and later convert them to video in the console. 
