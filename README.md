# Proportional only Controller for Flappy bird

Author : Vishal Shetty

The game was developed by Mingjing Zhang and posted on Mathworks file exchange. I modified the control of the game and interfaced it with a Proportional only controller.

1. For the original game code, see Mingjing Zhang’s code here: [https://www.mathworks.com/matlabcentral/fileexchange/45795-roteaugen-flappybird-for-matlab](https://www.mathworks.com/matlabcentral/fileexchange/45795-roteaugen-flappybird-for-matlab)

![Gif went Bad](https://github.com/VishalVShetty/FlappyBirdProportionalController/blob/master/flappybird.gif)

# Description

1. The game employs feedback and feed-forward control strategy for error calculation.
2.  The feedback element is the position of the bird on the Y-axis and the feed-forward element is the position of the gap present in the tube on the Y-axis which is randomly generated with each passing tube.
3. If the error is negative,the controller gives an instruction to jump and if the error is positve the controller will give the instruction to fall, to dodge the obstacles approaching the bird.
4. There are two tuning parameters : 
i. The position on the X-axis at the which the set-point is updated for the next tube.
ii. The distance of the set-point from the top section of the bottom tube.


## Usage 

Simply execute the Flappybird_Pcontroller.m file.


## Note
If you encounter any problem, or have any suggestions / feed-backs, please drop a comment down below. 

Enjoy truly endless flapping.