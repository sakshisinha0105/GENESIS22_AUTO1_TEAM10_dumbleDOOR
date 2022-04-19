# DOOR LOCKING SYSTEM


## REQUIREMENTS

### HIGH LEVEL REQUIREMEMTS

|S.NO|REQUIREMENTS|
|----|------------|
|HLR1 |A key fob is required |
|HLR2 |A toggle switch is required |
|HLR3 |Auto-lock the doors when moving |

### LOW LEVEL REQUIREMENTS

|S.NO|REQUIREMENTS|
|----|--------------------|
|LLR1.1 |A key is required to lock/unlock the car manually. |
|LLR1.1 |A key fob is required to lock/unlock the car using buttons |
|LLR2.1 |A toggle switch is required on the door to lock/unlock the doors of the car |
|LLR3.1 |The doors of the car should auto-lock when the car is at a particular speed |

## Market Analysis
In 1911, Bosch started supplying ignition switches requiring a key. In 1980, Ford Motor Company introduced an external keypad-type keyless entry system, wherein the driver entered a numeric combination —either pre-programmed at the factory or one programmed by the owner— to unlock the car without the key. Early- to mid-1980s Nissan Maximas could also be installed with a keypad, which would also retract the windows and moonroof once the car was successfully unlocked by pushing a specific button on the keypad. During the 1990s the Subaru Legacy could also be opened by pulling the driver's external door handle a specific number of times to enter a passcode number that would unlock the driver's door only.
Today, many cars with power door locks also have a radio frequency remote keyless system, which allows a person to press a button on a remote control key fob, the first being available on the French-made Renault Fuego in 1982. Currently, many luxury makers also allow the windows to be opened or closed by pressing and holding a button on the remote control key fob, or by inserting the ignition key and holding it in the lock or unlock position in the external driver's door lock.
The remote locking system confirms successful locking and unlocking through either a light or a horn signal, and usually offers an option to switch easily between these two variants. Both provide almost the same functionality, though light signals are more discreet while horn signals might create a nuisance in residential neighborhoods and other busy parking areas (e.g. short-term parking lots). Some manufacturers offer the ability to adjust the horn signal volume.
Other cars have a proximity system that is triggered if a keylike transducer (Advanced Key or handsfree) is within a certain distance of the car.

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

## REQUIREMENTS

### HIGH LEVEL REQUIREMEMTS

|S.NO|REQUIREMENTS|
|----|------------|
|1 |Touch Sensor should be enabled in the model |
|2 |An electronic button to slide on and off the side mirror  |

### LOW LEVEL REQUIREMENTS

|S.NO|HIGH LEVEL REFERENCE|REQUIREMENTS|
|----|--------------------|------------|
|1 |HLR1 |The touch sensor should have the left and right navigation enabled to adjust the side mirror |
|2 |HLR1 |By default, the mirror should be in centre of the frame |
|3 |HLR2 |The button must have 3 modes. Mirror open, close and neutral |
|4 |HLR2 |It should only work when the vehicle is ON |




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





