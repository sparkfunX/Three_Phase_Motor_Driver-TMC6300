SparkFun 3-Phase BLDC Motor Driver - TMC6300
========================================

[![SparkFun 3-Phase BLDC Motor Driver - TMC6300](https://cdn.sparkfun.com//assets/parts/2/0/9/8/8/21220-_ROB-_01.jpg)](https://www.sparkfun.com/products/21220)

[*SparkFun 3-Phase BLDC Motor Driver - TMC6300(ROB-21220)*](https://www.sparkfun.com/products/21220)

The TMC6300 from Trinamic is a powerful, yet easy to use three phase brushless DC (BLDC) motor driver. Separate high side and low side controls allow for incredible control up to 2A of current. The driver is temperature and short circuit protected with a diagnostic output pin to indicate system issues. With an operating voltage down to 2V, the TMC6300 is suitable for battery powered designs.

We've designed an innovative 2 sided, 4 layer breakout board to make hookup as easy as possible. The board is mounted with LEDs and labels facing up, IC down. This allows the thermal pad on the board to be access if cooling is required. 

Controlling 3-phase BLDC motors is not trivial. This board requires 6 PWM signals to fully control one motor. We've found the [*Arduino Simple Field Oriented Control*](https://docs.simplefoc.com/) library to be very good. The [open loop example](https://github.com/simplefoc/Arduino-FOC/blob/master/examples/motion_control/open_loop_motor_control/open_loop_velocity_example/open_loop_velocity_example.ino) combined with the [6 channel PWM method](https://docs.simplefoc.com/bldcdriver6pwm) and *every* PWM pin on the Arduino Uno gets this board working. Note the [pairs of PWM pins](https://docs.simplefoc.com/bldcdriver6pwm) that must be used. 

This board was designed to control our [3-phase Brushless Gimbal Stabilizer Motor](https://www.sparkfun.com/products/20441) but can be used with any 3-phase motor up to 2A.

SparkFun labored with love to create this code. Feel like supporting open source hardware? 
Buy a [breakout board](https://www.sparkfun.com/products/21220) from SparkFun!

Repository Contents
-------------------

* **/Documents** - Datasheet and User Manual
* **/Hardware** - Eagle design files (.brd, .sch)

License Information
-------------------

This product is _**open source**_! 

Please review the LICENSE.md file for license information. 

If you have any questions or concerns on licensing, please contact techsupport@sparkfun.com.

Please use, reuse, and modify these files as you see fit. Please maintain attribution to SparkFun Electronics and release any derivative under the same license.

Distributed as-is; no warranty is given.

- Your friends at SparkFun.
