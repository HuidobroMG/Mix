# Mix
In this repository you may find some codes which are not directly related to physics or to the other repositories. Some of them are not optimized and they might be slow but they all work and the outputs were my main motivation to develop the codes rather than any useful purpose.

Maze.py attempts to create a square maze building a random walk. It shows a nice output of the maze which becomes even more exotic for very large sizes, however the computation time might take too much time in that case. Besides, the solution may not even have a solution, but the code is quite easy to play with it and complete it as you wish.

Sounds.py is a very simple code to read and analyze a .wav file. It is just a kind of example of how to work with the FFT function and shows the wave and the spectrum of frequencies of the sound. As it was uploaded it reads a .wav file which is a LA (only the fundamental 440 Hz) note extracted from youtube.

String.py solves an extended version of the wave equation with two additional dispersive term. The effect of these terms is the generation of a more realistic guitar string sound. The solution to the equation is taken, shown as an animation (which may also be saved as a GIF) and converted into sound, so a .wav file is created. This code is mainly based on the solution given and explained in the YT video: https://www.youtube.com/watch?v=MavAU3adGk4

Conway_GoL.py is the generation of the Conway's game of life. The game starts with a random configuration and the time flows following the standard rules, the life of the cells is shown animated in time.

