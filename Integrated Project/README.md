# DOOR LOCKING SYSTEM

 Made by Aman Sharma
 
 99007484

## REQUIREMENTS

### HIGH LEVEL REQUIREMEMTS

|S.NO|REQUIREMENTS|
|----|------------|
|HLR1 |Ignition should be ON |
|HLR2 |The car locking system should respond to the pressing of the button on the door |
|HLR3 |Doors should auto-lock when the car is moving|

### LOW LEVEL REQUIREMENTS

|S.NO|REQUIREMENTS|
|----|--------------------|
|LLR1.1 |The car's engine should be on |
|LLR1.2 |The button on the driver door should lock/unlock every doors in the car |
|LLR2.1 |The doors of the car should auto-lock when the car is moving at more than speed of 20km/h |

## Market Analysis
Key players in the market- Major players operating in the global Car Door Lock market include Standex International Corporation, Robert Bosch GmbH, Hirschmann Automotive GmbH, Sensata Technologies, Inc., HELLA GmbH & Co. KGaA, Hitachi Ltd., Mitsubishi Electric Corporation, DENSO CORPORATION, Johnson Electric, and Continental AG among others.
Globally, the Car Door Lock market is segmented by lock type, by distribution channel type, by vehicle type and by geographic coverage. Based on material type, the market is further segmented into manual and automatic. Automatic door locks or power locks are operated by using mechanical and electronic components. These are technically systematic locks that can be operated by remote control, and remote devices appear in the form of convenient compact battery-powered devices. Recent advances have led to the development and introduction of wearable remote-control devices that can be worn on the user’s wrist. Automatic door locks also have functions such as a central locking system. Most newer cars have a remote keyless system that can be controlled remotely using the remote-control key. When the gearbox is moved away from the "parking" position, the doors of some cars will lock. In other vehicles, when the vehicle reaches a certain speed, the door will automatically lock. These are one of some safety features that can cause people to prefer specific or specific car models. By distribution channel the market is segmented into OEM and aftermarket. The original equipment manufacturer (OEM) market segment is expected to lead the rare opportunity of vending machine lock sensor failure. In addition, the door lock sensor for the car needs to be replaced only in the event of a serious traffic accident. The slow pace of expansion of the aftermarket market is due to technological progress and increased awareness of vehicle users to maintain vehicle systems. By vehicle type the market is segmented into passenger cars, light commercial vehicles and heavy commercial vehicles. Passenger cars segment dominate the market over the forecast period. Increasing sale of passenger cars is one of the prime reasons for the dominance of car door lock over the forecast period. As more and more commercial vehicles are adopted worldwide, LCV has a considerable share. The booming logistics industry is increasing the demand for car door over the forecast period.

## TEST PLAN

### HIGH LEVEL TESTPLAN
|S.NO|REQUIREMENTS|
|----|------------|
|1 |The car locking system should respond to the pressing of the buttons on the key fob|
|2 |The car locking system should respond to the pressing of the buttons on the door |
|3 |Auto-lock the doors when moving |


### LOW LEVEL TESTPLAN
|S.NO|REQUIREMENTS|
|----|--------------------|
|1.1 |The car should unlock and lock when the key is inserted and rotated.
|1.2 |When the lock button is pressed on the key fob the car should lock.
|1.3 |When the unlock button is pressed on the key fob the car should unlock.
|1.4 |When the alarm button is pressed the alarm system should be enabled

|S.NO|REQUIREMENTS|
|----|--------------------|
|2.1 |When the driver presses the lock-toggle switch, the doors should be locked.
|2.2 |When the driver presses the unlock-toggle switch, the doors should be unlocked

|S.NO|REQUIREMENTS|
|----|--------------------|
|3.1 |The doors of the car should auto-lock when the car is at a particular speed.



# AUTO FOLD MIRROR SLIDING MODEL
Made by Tanmay Padhi

99007482

## REQUIREMENTS

### HIGH LEVEL REQUIREMEMTS

|ID|Title|Body Control Model|
|--|-----|------------------|
|Sys_1|Requirement|Engine Should be in either IDLE condition or running|
|Sys_2|Requirement|The touch sensor should be in ADJUST mode to adjust the mirror|
|Sys_3|Requirement|The electronic button should be by default at the centre i.e PAUSE|
|Sys_4|Requirement|Either UP or DOWN button can be performed at an instant|

### LOW LEVEL REQUIREMENTS

|ID|Title|Body Control Model|
|--|-----|------------------|
|Sys_1|Requirement|The Engine could be in three states: Engine OFF,Engine running at IDLE Speed and Engine running at different vehicle speed|
|Sys_2|Requirement|The transmission can be either manual or automatic|
|Sys_3|Requirement|Touch Sensor should have following feature:|
|     |           |1.Swipe left to rotate the mirror towards left|
|     |           |2.Swipe right to rotate the mirror towards right|
|Sys_4|Requirement|The user must press the ADJ button to enable the touch sensor in order to adjust the mirror|
|Sys_5|Requirement|The user must press the SET button once the mirror is adjusted as per the need|
|Sys_6|Requirement|The mirror folding button must only work when the vehicle is turned ON|
|Sys_7|Requirement|When turned off the button is non-functional and will not respond to any communications sent|
|Sys_8|Requirement|The UP button will unfold the mirror when action is performed|
|Sys_9|Requirement|The DOWN button must fold the mirror when action is performed by the user|
|Sys_10|Requirement|There is also a PAUSE button in between the UP and DOWN button which will not perform any action|
|Sys_11|Requirement|Both UP and DOWN button cannot be pressed simuntaneously|




## Market Analysis
A side-view mirror also known as a wing mirror, is a mirror placed on the exterior of motor vehicles for the purposes of helping the driver see areas behind and to the sides of the vehicle, outside the driver's peripheral vision. 
The side mirror is equipped for manual or remote vertical and horizontal adjustment so as to provide adequate coverage to drivers of differing height and seated position.
Over the years, the mirror has been transformed from manual control to electronic control. Earlier the vehicle had manual control which had a joystick to adjust the blind spot and the mirror can be folded manually.
After 2010, there were many vehicles which enabled the electronic button to fold and unfold the mirror once the vehicle is turned on. Later few vehicles also gave the touch screen at the driver door which enables them to adjust the view as per their requirements. Like in the Maruti Suzuki Swift, there was manual setting along with the joystick till 2015, later models however included the electronic folding system, however the mirror adjustment is still done manually by the person driving the vehicle
Now it is an estimation that in upcoming years we can expect vehicle having intelligence sensor which will automatically detect the blind spot and adjust the mirror as per the driver without having any human intervention. In Tesla Model S, if you are driving for the first time, it asks about the personal information of the driver and next time it automatically sets the driver seat and side mirrors as the driver used it the last time used. 

## TEST PLAN

### HIGH LEVEL TESTPLAN
|S.NO|TESTPLAN|
|----|--------|
|1|Touch sensor should rotate the mirror right and left as per the driver’s instruction|
|2|The button to fold the mirror should be in middle by default| 

### LOW LEVEL TESTPLAN
|S.NO|HIGH LEVEL REFERENCE|TESTPLAN|
|----|--------------------|--------|
|1|HLR1|The mirror should rotate right when the user slides towards right in touch sensor|
|2|HLR1|The mirror should rotate left when the user slides towards left in touch sensor|
|3|HLR2|The mirror should unfold when the electronic button is pressed down|
|4|HLR2|The mirror should fold when the electronic button is pressed up|

## WINDOW SYSTEM 
Made by Sakshi Sinha

99007560

## REQUIREMENTS

### HIGH LEVEL REQUIREMEMTS

|S.NO|REQUIREMENTS|
|----|------------|
|1 |Window should roll up/down manually. |
|2 |Window should get adjusted.  |

### LOW LEVEL REQUIREMENTS

|S.NO|LOW LEVEL REQUIREMENTS|REQUIREMENTS|
|----|--------------------|------------|
|1 |LLR1 |When window should roll up and down when: Ignition is on, pressed window  up/down |
|2 |LLR2 |The window should stop pressed stop ignition |
|3 |LLR3 |The window should stop when unclick the button of windows up amd down. |

### Market Analysis
* Power windows or electric windows are automobile windows which can be raised and lowered by pressing a button or switch, as opposed to using a crank handle. Power assists originated in the need and desire to move convertible body-style tops up and down by some means other than human effort. The earliest power assists were vacuum-operated and were offered on Chrysler Corporation vehicles, particularly the low-cost Plymouth convertibles in the late 1930s. The "Hydro-Electric" system (windows, front seat adjustment and convertible top) was standard on 1947 model year. The seat and window assist system became available on GM closed cars (standard on some Cadillac Series 75 models and all Series 60 Specials, commonly called "Fleetwood" beginning with the 1948). The full system was standard only on the high-end GM convertibles made by Oldsmobile, Buick, and Cadillac. It was only available as a package; that is, power assisted windows, front seat, and convertible top (where applicable). This feature can be identified in 1948 and later General Motors model numbers with an "X" at the end, such as the 1951 Cadillac Sixty Special sedan, model 6019X. The electrically operated hydraulic pump system was shared by Hudson and Packard for their 1948 through 1950 models. The driver's door contained four buttons in addition to the remaining individual windows. 

## TEST PLAN

### HIGH LEVEL TESTPLAN
|S.NO|TESTPLAN|
|----|--------|
|1|Door should have up and down switches. |
|2|Optic sensor should detect if any obstacle is present.| 

### LOW LEVEL TESTPLAN
|S.NO|LOW LEVEL REQUIREMENTS|TESTPLAN|
|----|--------------------|--------|
|1|LLR1|When switch up is pressed then slider should roll up |
|2|LLR1|When swtich down is pressed then slider should roll down.|
|3|LLR2|Optic sensor should stop the slider when obstacle comes in between the slider and sensor.|
|4|LLR2|Optic sensor should roll down the window slider when obstacle comes in between.|



--------------------------------------------------------------------------------------------------------------
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








