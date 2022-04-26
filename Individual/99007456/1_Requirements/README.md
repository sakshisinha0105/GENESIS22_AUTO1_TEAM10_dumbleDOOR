<h1 align="center"> Mobile missile system </h1>
<i><h3 align = "center"> Pocket missile system for your car </h3></i>

<p align = "center">  
  <img src="https://github.com/Y-133/GENESIS22_AUTO1_TEAM10_dumbleDOOR/blob/main/Individual/99007456/IMAGES/missile%20car.jpg" alt="car with missile system"> </p>

--------------------------------------------------------------
## Features:
1) Capacity to hold 5 missile
2) Launch missile
3) Lock on target
4) View the availability of the missiles
5) System functioning data 
6) Auto reload of the missiles
7) Control the missile pointer using the joystick like controler on the steering wheel 
8) Auto detach of system when in danger/damaged
9) Free release of missile 
10) Ethernet bus is used for the camera feed
11) CAN bus is used in the missile control unit
#
# REQUIREMENTS
## HIGH LEVEL REQUIREMEMTS

|HLR_ID|REQUIREMENTS|
| :----: |------------|
| HLR_1 | Initilaize the missile system |
| HLR_2 | Open the missile holder in the door |
| HLR_3 | Fix the target manually using the joystick |
| HLR_4 | Launch the missile |
| HLR_5| Auto detach when the system is damaged| 
| HLR_6| The battery is charged using the dynamo|
#
## LOW LEVEL REQUIREMENTS

| HLR_ID   | LLR_ID   | LOW LEVEL REQUIREMENTS  |
| :------: | :------: | ----------------------- | 
| HLR_1 | LLR_1.1 | When the car is turned on the software shall check the battery health and charge level |
| | LLR_1.2 | The battery health and charge level status shall be displayed in the digital cluster display | 
| | LLR_1.3 | The missile system shall be powered using the batteries when the car is turned on irrespective of engine on/off  | 
| | LLR_1.4 | The software checks the missile system health by checking the if the current flow completes in the system to the system | 
|  | LLR_1.5 | Check the missiles availability using weight sensor in each missile holder| 
| | LLR_1.6| Display the information in the digital cluster | 
| HLR_2 | LLR_2.1 | Opening the missile holder to an angle of 45 degree using the stepper variant motor within 5 second| 
| | LLR_2.2 | Automatic monitoring for any possible crash with the objects while moving using sensor for every 1 millisecond| 
| | LLR_2.3 | Closing the missile holder opened if any crash is detected in either front or sideward | 
| HLR_3 | LLR3.1 | Fix the target using the camera feed displayed on the overhead unit screen|
| | LLR_3.2 |Use the joysticks in the steering to move the missile holder position to some degree | 
| | LLR_3.3 | Lock on the target using the lock push button |
| | LLR_3.4 | The stepper motor holds its position | 
| HLR_4| LLR_4.1| The missile is fired using the compressed air technology when the fire button is pressed | 
| | LLR_4.2 |The missile availability is checked after every launch |
| | LLR_4.3| Missile availability is updated and displayed in the dasboard after every launch |
| | LLR_4.4| When the fire button is pressed again the next consecutive missile in the system is fired |
| | LLR_4.5| When the missiles are below 3, warn the user with continuous beep and red light when in missile system mode|    
| HLR_5| LLR_5.1| The system alerts the user with different continuous beep for 7 seconds to warn the user when the missile system is damaged|
| | LLR_5.2 | The missile system gets detached automattically when the system damaged badly using the air compressor|
| | LLR_5.3| The missile system can also be detached mannually when the detach button is pressed|  
| HLR_6| LLR_6.1 | The battery is charged using the dynamo in the four wheels|
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
|    H_01     | Check if the missile system unit gets turned on or not | Mannually turn use key to turn on the system | Turning on the missile system | | |
| H_02 | Check if the missile holder opens when the system is turned on | Input from the sensor | When the system is powered the holder opens |  |  |
| H_03 | Fix on the target | Manual fix on the target using the joystick |Fixing the target and display on the dashboard | | |
| H_04 | Launch the missile | When the user presses the switch the missile gets powered | Missile is launched| | 
| HLR_5| Auto detach when the system is damaged| The system malfunction is detected using the software |  | | |
| HLR_6| The battery is charged using the dynamo| The dynamo chaarges the battery automatically | | | | 
------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Table no: Low level test plan

## TABLE_NO: LL_1 ##
| **High_leve_Test ID** | **Low_leve_Test ID** | **Description**       | **Exp IN** | **Exp OUT** | **Actual Out** |**Type Of Test**  |    
| :-------------------: | :------------------: | :-------------------: | :--------: | :---------: |:-------------: | :--------------: |
| HLT_1 | LLT_1.1 | Car shall turn on |  |  |  | Mannual |
| | LLT_1.2| The software shall check the battery health and charge level | NA | charge level | | |
| | LLT_1.3 | The battery health and charge level status shall be displayed in the digital cluster display | NA | display the info  in the digitla cluster | | Manual | 
| | LLT_1.4| If the charge level input isn't showing right | software input | Show the charge status as cross mark | | Manual | 
| | LLT_1.5 | The missile system shall be powered using the batteries when the car is turned on irrespective of engine on/off  | Power from battery | The system is powered on | | Manual | 
| | LLT_1.6| If the system is not powered | No power| Show error in the digital cluster| | Manual|
|  | LLR_1.7 | Check the missiles availability using weight sensor in each missile holder| From load sensor |  | | Manual |  
| | LLR_1.8| If the sensor value is not in the range of 1.7 - 1.71| Input from the load cell | Check if the missile used count is equal to ecrease the missile number count  |   Display the information in the digital cluster | 
| HLR_2 | LLR_2.1 | Opening the missile holder to an angle of 45 degree using the stepper variant motor within 5 second| 
| | LLR_2.2 | Automatic monitoring for any possible crash with the objects while moving using sensor for every 1 millisecond| 
| | LLR_2.3 | Closing the missile holder opened if any crash is detected in either front or sideward | 
| HLR_3 | LLR3.1 | Fix the target using the camera feed displayed on the overhead unit screen|
| | LLR_3.2 |Use the joysticks in the steering to move the missile holder position to some degree | 
| | LLR_3.3 | Lock on the target using the lock push button |
| | LLR_3.4 | The stepper motor holds its position | 
| HLR_4| LLR_4.1| The missile is fired using the compressed air technology when the fire button is pressed | 
| | LLR_4.2 |The missile availability is checked after every launch |
| | LLR_4.3| Missile availability is updated and displayed in the dasboard after every launch |
| | LLR_4.4| When the fire button is pressed again the next consecutive missile in the system is fired |
| | LLR_4.5| When the missiles are below 3, warn the user with continuous beep and red light when in missile system mode|    
| HLR_5| LLR_5.1| The system alerts the user with different continuous beep for 7 seconds to warn the user when the missile system is damaged|
| | LLR_5.2 | The missile system gets detached automattically when the system damaged badly using the air compressor|
| | LLR_5.3| The missile system can also be detached mannually when the detach button is pressed|  
| HLR_6| LLR_6.1 | The battery is charged using the dynamo in the four wheels|

-------------------------------------------------------------------------
what to do if the sensor gives garbage value??

---------------------------------------------------------------------------------
## Vehicle architecture:
<p align = "center">  
  <img src="https://github.com/sakshisinha0105/GENESIS22_AUTO1_TEAM10_dumbleDOOR/blob/17f23d64617f7fc3934ba0a42c45e2354e60fe8b/Individual/99007456/images/missile_sys_archi.jpg" alt="Missile system architecture"> </p>
  
---------------------------------------------------------
## REFERENCE: 
1) https://en.wikipedia.org/wiki/M1128_Mobile_Gun_System
