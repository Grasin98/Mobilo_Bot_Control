# Mobilo_Bot_Control
For this, you need a CodeVisionAVR Software for programming and SinaProg for the dumping of code to hardware.

Create a new Project, Save it.
The a window will open up, select the micro-controller you need, In this case I have taken AtMega16A.

Select all the receiver modules you need, and the Ports.

In this case, I have selected the following ports:

Motor1:                     Motor2
EN- A7                       EN - C4 
A - C7                       A  - A5
B - C6                       B  - A6

C0,C1,C2 and C3 are the input ports from the DTMF( Dual Tone Multi Frequency).

The .c file contains the code for the Right, Left, Forward and the Backward Motion of the bot.
.prog contains the entire project.
