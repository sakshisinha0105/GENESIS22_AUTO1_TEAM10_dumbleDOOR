# AUTO FOLD MIRROR SLIDING MODEL 
## REQUIREMENTS

### HIGH LEVEL REQUIREMEMTS

|ID|Title|Body Control Model|
|--|-----|------------------|
|Sys_1|Requirement|Engine Should be in either IDLE condition or running|
|Sys_2|Requirement|The electronic button should be by default at the centre i.e PAUSE|
|Sys_3|Requirement|Either UP or DOWN button can be performed at an instant|
|Sys_4|Requirement|The mirror cannot be folded or unfolded if ignition is OFF|
|Sys_5|Requirement|The mirror will automatically unfold if the vehicle speed is above 40kmph|

### LOW LEVEL REQUIREMENTS

|ID|Title|Body Control Model|
|--|-----|------------------|
|Sys_1|Requirement|The Engine could be in three states: Engine OFF,Engine running at IDLE Speed and Engine running at different vehicle speed|
|Sys_2|Requirement|The transmission can be either manual or automatic|
|Sys_3|Requirement|The mirror folding button must only work when the vehicle is turned ON|
|Sys_4|Requirement|When turned off the button is non-functional and will not respond to any communications sent|
|Sys_5|Requirement|The UP button will unfold the mirror when action is performed|
|Sys_6|Requirement|The DOWN button must fold the mirror when action is performed by the user|
|Sys_7|Requirement|There is also a PAUSE button in between the UP and DOWN button which will not perform any action|
|Sys_8|Requirement|Both UP and DOWN button cannot be pressed simuntaneously|

# Market Analysis

## History Of Side Mirror

In the early 1940s, the roads in Europe were unpaved and consist of two lanes. Each lane for one direction. Due to this, there was a huge complexity in traffic signals for the drivers as they have to look back and both sides to avoid a major accident. Hence the OEMs came up with the idea of implementing the rear mirror placed inside the vehicle. However, the side mirror was optional for the users as it was expensive those days.  

## Progress of Side Mirror in Vehicles

In the 1970s and 1980s, the side mirror were found in most of the vehicle and it was no longer a luxury as we witnessed in early 1940s. As things progressed, side mirror became a by default mandatory component of every vehicle. 
Then in 2000, few of the automobile sectors came up with the idea of adjusting the mirror position as per the wish of the driver as earlier there was no specific function to change the view or angle of the mirror. With the advancement of technology, side mirror were later folded and unfolded using a manual joystick placed near the driver's staring wheel.

In the modern time, mirrors come with the function of folding and unfolding using a electronic button and a touch sensor to change the view of the mirror. 
After 2010, there were many vehicles which enabled the electronic button to fold and unfold the mirror once the vehicle is turned on. Later few vehicles also gave the touch screen at the driver door which enables them to adjust the view as per their requirements. Like in the Maruti Suzuki Swift, there was manual setting along with the joystick till 2015, later models however included the electronic folding system, however the mirror adjustment is still done manually by the person driving the vehicle
Now it is an estimation that in upcoming years we can expect vehicle having intelligence sensor which will automatically detect the blind spot and adjust the mirror as per the driver without having any human intervention. In Tesla Model S, if you are driving for the first time, it asks about the personal information of the driver and next time it automatically sets the driver seat and side mirrors as the driver used it the last time used. 

# TEST PLAN

## HIGH LEVEL TESTPLAN
|S.NO|TESTPLAN|
|----|--------|
|1|Touch sensor should rotate the mirror right and left as per the driver’s instruction|
|2|The button to fold the mirror should be in middle by default| 

## LOW LEVEL TESTPLAN
|S.NO|HIGH LEVEL REFERENCE|TESTPLAN|
|----|--------------------|--------|
|1|HLR1|The mirror should rotate right when the user slides towards right in touch sensor|
|2|HLR1|The mirror should rotate left when the user slides towards left in touch sensor|
|3|HLR2|The mirror should unfold when the electronic button is pressed down|
|4|HLR2|The mirror should fold when the electronic button is pressed up|



