<h1 align="center"> Mobile missile system for VVIP </h1>
<i><h3 align = "center"> Your pocket missile </h3></i>

![](https://github.com/Y-133/GENESIS22_AUTO1_TEAM10_dumbleDOOR/blob/main/Individual/99007456/IMAGES/missile%20car.jpg)

#
# REQUIREMENTS

## HIGH LEVEL REQUIREMEMTS

|HLR_ID|REQUIREMENTS|
| :----: |------------|
| HLR_1 | Initilaize the missile system |
| HLR_2 | Open the missile holder in the door |
| HLR_3 | Fix the target manually |
| HLR_4 | Launch the missile |
#
## LOW LEVEL REQUIREMENTS

| HLR_ID | LLR_ID | LOW LEVEL REQUIREMENTS|
| :------: | :------: | ----------------------- | 
| HLR_1 | LLR_1.1 | Power the system using the batteries | 
| | LLR_1.2 | Check the system working or not | 
|  | LLR_1.3| Check the missiles availability | 
| | LLR_1.4| Display the information in the dasboard | 
| HLR_2 | LLR_2.1 | Opening the missile holder to an angle of 45 degree using the stepper variant motor | 
| | LLR_2.2 | Automatic monitoring for any possible crash with the objects while moving | 
| | LLR2.3 | Closing the holder opening if crash is detected | 
| HLR_3 | LLR3.1 | Fix the target using the camera feed displayed in the dashboard|
| | LLR_3.2 |Use the joysticks in the steering to fix the target | 
| | LLR_3.3 | Choose the target | 
| HLR_4| LLR_4.1| Fire the missiles | 
| | LLR_4.2 | Check for the missile availability |
| | LLR_4.3| Display the missile availability in the dasboard |

-------------------------------------------------------------------------
# Market Analysis
<p align="center">
The proposed feature of mobile missile system is one of the kind that helps the VVIP to protect them while travelling or the security force while in action.
This missile system consists of the missile, missile holder, launch system, user control which is in the steering wheel and display the information.  Most of the existing systems are used for military vehicles.
But the propsed system targets the commerially produced vehicles for the VVIP / security force. 
</p>

-------------------------------------------------------------------------

# TEST PLAN:
 * Test plans are very helpful in checking the behaviour of the program, variables and function for different values
 
## High level test plan

## TABLE_NO: HL_1 ##
| **Test ID** | **Description**                                              | **Exp I/P** | **Exp O/P** | **Actual Out** |**Type Of Test** |    
| :---------: | :----------------------------------------------------------: | :---------: | :---------: | :------------: | :-------------: |
|  H_01       | Check if the system gets turned on or not | User input to turn the system | Turning on the system | | |
| H_02 | Check if the missile holder opens when the system is turned on | Input from the sensor | When the system is powered the holder opens |  |  |
| H_03 | Fix on the target | Manual fix on the target using the joystick |Fixing the target and display on the dashboard | | |
| H_04 | Launch the missile | When the user presses the switch the missile gets powered | Missile is launched| |
------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Table no: Low level test plan

## TABLE_NO: LL_1 ##
| **High_leve_Test ID** | **Low_leve_Test ID** | **Description**       | **Exp IN** | **Exp OUT** | **Actual Out** |**Type Of Test**  |    
| :-------------------: | :------------------: | :-------------------: | :--------: | :---------: |:-------------: | :--------------: |
| H_01 | L_01.1 | Power the system using the batteries | Button turn on the system | | | | 
| | LLR_1.2 | Check the system working or not | Turning on / off the using button multiple times | 
| | LLR_1.3| Check the missiles availability | Checking the dashboard and real missile availability manually | | | | 
| | LLR_1.4| Display the information in the dasboard | Checking the dashboard and real missile availability manually | | | | 
| H_02 | LLR_2.1 | Opening the missile holder to an angle of 45 degree using the stepper variant motor | Perform repeated turn on/off the system to check the functionality of the holder | | | | 
| | LLR_2.2 | Automatic monitoring for any possible crash with the objects while moving | Test the PIR sensor by hindering its path | | | |
| | LLR2.3 | Closing the holder opening if crash is detected | Test the PIR sensor by hindering its path | | | |
| H_03 | LLR3.1 | Fix the target using the camera feed displayed in the dashboard| Test the camera working | | | |
| | LLR_3.2 |Use the joysticks in the steering to fix the target | Check if the joystick is woking and accurately | | | |
| H_04| LLR_4.1| Fire the missiles | Checking if the missiles gets detached and fired up | | | |
| | LLR_4.2 | Check for the missile availability | Check the number using the weight sensor in the holder | | | | 
| | LLR_4.3| Display the missile availability in the dasboard | Checking the dashboard and real missile availability manually | | | | 
-------------------------------------------------------------------------

## REFERENCE: 
1) https://en.wikipedia.org/wiki/M1128_Mobile_Gun_System
