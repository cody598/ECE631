What was the goal of this lab?

Implement pwm on the trigger pin for ultra sonic sensor, which then receives the "distance" which in turn is transmitted back via the "ECHO" signal.
Then an interrupt needed to be implemented in order to determine pulse width. Finally, we implemented a moving average filter to lessen/destroy all noise affecting our output.

What skills/tools/techniques used in this lab?

We used JSON serialization to publish the calculated distance to the MQTT server. We used the built in functions to setup the interrupt pins and output pin, so not much work was needed.

Diagrams?

ESP32 => UltraSonic Sensor => ESP32 => MQTT server

