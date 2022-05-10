# AUTO FOLD MIRROR SLIDING MODEL 
# REQUIREMENTS

## HIGH LEVEL REQUIREMEMTS

|S.NO|REQUIREMENTS|
|----|------------|
|1 |Touch Sensor should be enabled in the model |
|2 |An electronic button to slide on and off the side mirror  |

LOW LEVEL REQUIREMENTS

|S.NO|HIGH LEVEL REFERENCE|REQUIREMENTS|
|----|--------------------|------------|
|1 |HLR1 |The touch sensor should have the left and right navigation enabled to adjust the side mirror |
|2 |HLR1 |By default, the mirror should be in centre of the frame |
|3 |HLR2 |The button must have 3 modes. Mirror open, close and neutral |
|4 |HLR2 |It should only work when the vehicle is ON |

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



