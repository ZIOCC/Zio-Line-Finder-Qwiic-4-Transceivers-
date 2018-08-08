# Zio-Line-Finder-Qwiic-4-Transceivers-
Zio Line Finder (Qwiic, 4 Transceivers)

Description:

This is a Qwiic I2C version of a line-following sensor array, intended especially for building robots that take advantage of I2C for communication between subsystems.


Like other line-following sensor modules, it has four IR reflectance-sensing sub-modules that can detect a line’s position. We use a PCA9539A I/O expander to detect when a given sub-module’s output voltage crosses its logic-level threshold, indicating the detection of the line. If one of the sub-module I/O channels is driven LOW, that’s where the line is.


There are four potentiometers to independently adjust the IR modules’ sensitivities to suit different robot platforms, accounting for differences in sensor mounting heights. There are four LEDs that provide a visual indicator for the detection status of each channel, which makes it easy to tune the sensitivity of each sensor channel.
Because the PCA9539A has 16 digital I/O channels, we’ve broken out the other 12 channels to standard-pitch pin-headers so you can take advantage of them as you see fit.


Specifications:

.Four Channel IR Sensors

.I2C sensor: PCA9539A

.Differential Comparator IC: LM339DR

.Extra Digital Sensor Channel: 12 Channels

.Dimension: 47.2x 36.5mm

.Weight: Main board: 7.4g, IR sensor board: 0.9g

Product Buy Link： https://www.smart-prototyping.com/Prototyping-Modules/zio/Zio-Rotary-Encoder-Sensor
