# 3-Phase-Motor-Control-and-Safety-Implementation

BY CECIL TAKUNDA MHIKE
3 Phase Forward and Backward Motor Operation

How to execute the Code
_________________________________________________
-Download the "Direct Drive and FW_BW Drive Motor.esc" file and open it in the EKTS software
-Start simulation and toggle inputs to see performance

Nb. No sensors were used, its just the basic layout and operation
principle investigation.
___________________________________________________
OPERATION
FORWARD OPERATION

For the motor to operate in the forward direction, the Start Button ST1 is pressed turning on Contactor C1.
The Open Contact C1 then closes with the Normally Closed remaining Closed completing the Circuit.

When C1 is ON, C2 is OFF as a result of an open circuit caused by the C1 Normally Closed opening as Contactor 1 is now open.

BACKWARD OPERATION

For the motor to operate in Backward direction, the Start Button ST2 is pressed and allowing the circuit to be complete.
Contactor 2 is turned ON and C1 Closed Contact Remains Closed as Contactor 1 is OFF.

FUNCTION OF THE PS BUTTON

The PS Button is an emergency switch that turns OFF the whole System incase of danger or malfunction.

Use of C2 and C1 closed contacts helps in avoiding the Motor operating both in Forward and Backward direction.
