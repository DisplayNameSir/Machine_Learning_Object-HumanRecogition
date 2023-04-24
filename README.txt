This file will include instructions explaining the steps needed to operate each
program successfully without running into any errors. A video demonstrations will also
be included in this file for users that wish to watch a demonstration of each program
being executed.

Youtube Links
===================================================================================================================================================================================================================================================================
Train and recognize a new object
https://youtu.be/6Ma_yK8egPc

Train and Recognize Yourself
https://youtu.be/OCNfLVCEps8

Sleeping Dragons - Game Development
https://www.youtube.com/watch?v=nXmUNwSksxY

============================================================================================================================================================================================================================================================================================================================================================

GITHUB Respository:
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Sleeping Dragons
https://github.com/DisplayNameSir/Sleeping_Dragons_GD

Train and recognize yourself + one object


+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

DISCLAIMER:
Users that wish to run the following programs will need to install libraries that were
previously uploaded to python to give access to devlopers to a wider range of commands and programs.
It is essential to download the following libraries in order to run the program sueccessfully.


How to download libraries:
To install the modules needed for the program or verify that its installed, users will open their anaconda powershell and type the following commands
1. Open Anaconda Powershell Prompt
2. Type "pip install (missing module name)"
3. Allow the powershell to install the module
4. Once its finished repeat the same steps for the other modules
5. Allow that module to finish downloading and the program should be ready to go!
6. If the program runs into any issues try updating spyder or restarting the IDE.

Installed Modules:
-numpy
-scipy
-math
-matplotlib
-pint
-pandas
-pgzrun
-pygame
-pgzero
-sympy
-random
-heartpy
-tensorflow
-keras
-ultralytics
-YOLOV8
-CUDA
-UPDATE NUMPY

=====================================================================================================================================================================================================================================================================================================================
Description of each program and brief instructions:
=====================================================================================================================================================================================================================================================================================================================
Part 1: Train and recognize a new object
The following program utilizes Ultralytics and machine learning to recognize new objects. Add your own set of pictures into the right dataset folder and train the model
by setting your custom amount of images to train the module. First train the module then let the program predict new images with the model given onto a webcam to recognize the new object that has been
added into the class.

-Run and Launch Anaconda PowerShell Prompt as administrator
-Change Directory to the Ultralytics File
-Input the following command to run the program and ensure that a working webcam is plugged in before running the program
yolo task=detect mode=predict model=C:/ultralytics/runs/detect/train/weights/best.pt source=0 show=True

*Command could require revision if directory is different than listed*
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
Part 2: Train and recognize yourself
The following program will be an addition to the previous program. Use the same command below to run the program which is set to recognize me (Peter Nguyen) and my bottle

yolo task=detect mode=predict model=C:/ultralytics/runs/detect/train/weights/best.pt source=0 show=True

*Command could require revision if directory is different than listed*

/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
Part 3: Game Development - Sleeping Dragons
The following program is a CO-OP Game that enables two players to work together to capture as much eggs as possible. Work a strategy with your partner to learn when to capture the eggs without getting hit by the 
dragon's fire breath!

To run the following program, install the modules in the modules section of the README File and run the program onto Spyder. When the program is open use the following
commands to control each of the characters:
Character 1:                Character 2:
Upward   = W                Upward   = "Arrow Up Key"                
Downward = s                Downward = "Arrow Down Key"
Right    = D                Right    = "Right Arrow Key"
Left     = A                Left     = "Left Arrow Key"

With each of the characters being moved, invite another player in the household to collect as much eggs as possible without getting hit by each of the dragons. The dragons have randomized wake times
so be careful when to approach each of the dragon.
			  
