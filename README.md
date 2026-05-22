# Smart Security System
The goal of the project is to create an affordable home security system that can be accessed anywhere on any device, displaying security updates and extra data that the user might find helpful for home management.

The project falls in line with the Sustainable Development Goal (SDG) number seven, providing an affordable and clean energy way of monitoring a home, and goal eleven providing the community with a sustainable community, and goal sixteen proving the user with peace of mind and a way to serve justice Justis for any wrong doing done to the owner’s home or property.

The project uses three Esp32 microcontrollers connected via Esp-Now, an ultrasonic sensor, an moisture and humidity sensor, a LCD display, a GPS module, key-pad and a RFID card reader. The Esp32’s are all on separate boards, one is for the sensors , one is for the key-pad and two factor authentication via the RFID and the last Esp32 is the main Esp that receives all the data from the two other Esp32’s and acts as the alarm while also sending the data via MQTT to a public MQTT broker.

In conclusion, the project is an affordable, easy to use and maintain smart home security system that can send live data to a externally hosted webserver that can be accessed anywhere at any time whether or not the user is connected locally or non-locally.
