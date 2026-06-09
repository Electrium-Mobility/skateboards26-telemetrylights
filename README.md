# Design

This is a mixed telemetry + lights board. We will use sensors (accelerometer) to gather information, a STM to process the info, and lights/display to display the result. Depending on the acceleration of the skateboard, the lights change to a different color. Data will also be displayed on a LCD/OLED screen.

Items displayed are:

* Acceleration
* Current/voltage draw of our board
* Precharge current sense
  * For the last two points, assume a separate power distribution board will be connected, and will be providing those signals through connectors.
