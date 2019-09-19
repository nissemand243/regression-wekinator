# regression-wekinator

LeapMotion guide:
Start by connection the leapmotion into an open usb port. Next to go leapmotions website, scroll to the bottom and press setup. Now download the setup file for the system you are running and the leapmotion should then be good 2 go.

Regression sketch guide:

Start this step by downloading any missing sketch libraries to the processing!!!!

The regression sketch has been modified from the base of Rebecca Fiebrink's course work and examples from the kadenze session about machinelearning. The specific file used is originaly named "LeapMotion_Fingertips_15inputs" and i have used a bit of code from the document "Processing_SimpleColor_1Continous" and used the void oscEvent part as a starting point. i have made 3 outputs instead of 1 and imported the bit of code into the leapMotion document and renamed that in order to make is easier to setup wekinator when seting it all up.

Wekinator guide:

The wekinator sketch has been modified in order to take inputs from fingers and display outputs in the term of different colors on the screen. The thumb has the values of the myHue, the index and middle fingers control the myHue2 and the ring and index fingers control the myHue3. It shall be trained with a closed fist as the point of zero (make sure that the leapmotiong detects your hand as a closed fist) and the value of 1 on all the outputs is when your hand is fully open, that makes the wekinator run the processing sketch like a poppet control, you roll the fingers and it rolls the colors. Pretty neat.


Usage guide:

The program is used to change the background color of the running java enviroment sketch opened via processing. The Myhue is a variabel that defines the red color of the background, myHue2 is controlling the green color and myHue3 controls the blue color of the background. The sketch is made to visualize how inputs can control outputs directly via machinelearning. I have used a leapmotion device to do this because my webcam is not functional and therefor i had to change plans.
