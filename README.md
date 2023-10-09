# Temperature-Monitoring
Code for the temperature monitoring device to monitor and upload the recordings on iOT


**Components:**
1. Arduino board with IoT capabilities
2. Temperature Sensor
3. resistor
4. Breadboard and jumper wires
5. An active Arduino Cloud account (https://create.arduino.cc/iot/)

**Steps:**
_1. Setting up the Hardware:_
1. Connect the  VCC pin to the Arduino's 3.3V pin.
2. Connect the  GND pin to the Arduino's GND pin.
3. Connect the pin to any digital pin on the Arduino (e.g., D2).
4. Place the resistor between the VCC and DATA pins (this acts as a pull-up resistor).


_2. Arduino IoT Cloud Setup:_
Log in to your Arduino Cloud account.
Click on the "Things" tab and create a new "Thing".
Click on your new "Thing" and then on the "Add Property" button. Create a new property named "Temperature" with type "float".
Once created, you'll be provided with a unique thing ID, which you'll need later.
