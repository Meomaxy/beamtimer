# beamtimer
A timer for use in gymnastics balance beam competitions. Implemented as web page with a Javascript.

# Usage
Beam Timer is designed to be used for timing women's gymnastics balance beam events. While rules vary, it is intended to be flexible enough to be used for USAG, Xcel, and USAIGC/IGC.

### Initial Setup
* Edit the Routine Time and the Fall Time by clicking on the numbers and typing the desired starting time.

### Timing a Routine
* When the gymnast starts her routine, press the first button to start the Routine timer. The Routine timer will begin counting down the remaining time.
* When the gymnast completes her routine, press the first button again to stop the Routine timer.

### Fall Timing
* If the gymnast falls during the routine, press the second button to start the Fall timer. The Routine timer will pause, and the Fall timer will begin counting down the remaining fall time.
* When the gymnast gets back on the beam, press the second button to pause the Fall timer.
* When the gymnast resumes her routine, press the first button to resume the Routine timer.
* If your rules don't require you to stop the Fall Timer separate from resuming the Routine timer, you can skip the step of pausing the Fall timer and just resume the Routine timer when the gymnast resumes her routine. This will also have the effect of pausing the Fall timer if it is still running. 

### Warning Bells and Overtime
* For both timers, as the timer counts down, there is a warning bell when there is 10 seconds remaining, and an overtime bell when time expires. The timer continues counting up after time is up to measure the amount of overtime.

### Resetting the Timers
* When the timers are stopped, you can press the Reset button to reset the time values to their initial start time. If you need to change the start times for the next gymnast, see "Initial Setup" above.
