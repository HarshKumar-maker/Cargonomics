

Objectives: The primary goals in addressing the load management issue in coal transportation are as follows:

1. Enhancing safety by preventing load overages and shortages.
2. Ensuring strict compliance with established regulatory standards and guidelines.
3. Enhancing operational efficiency and minimizing costly delays.
4. Implementing real-time monitoring and reporting mechanisms.

Components:

In order to provide a more detailed explanation of the circuit connections for your project, here is how to connect the various components:

1. Arduino Uno
2. Load Cell (with HX711 module)
3. Servo Motor
4. 16x2 LCD (Liquid Crystal Display)
5. LED
6. 220-ohm Resistor
7. Push Button (for calibration)

Connections:

1. Load Cell (with HX711 module):
   - Connect the red wire (VCC) of the HX711 module to the 5V terminal on the Arduino.
   - Connect the black wire (GND) of the HX711 module to the GND terminal on the Arduino.
   - Connect the white wire (DT - Data) of the HX711 module to the A0 terminal on the Arduino.
   - Connect the yellow wire (SCK - Clock) of the HX711 module to the A1 terminal on the Arduino.

2. Servo Motor:
   - Connect the red wire of the servo to the 5V terminal on the Arduino.
   - Connect the brown wire of the servo to the GND terminal on the Arduino.
   - Connect the orange or yellow wire of the servo to pin 10 on the Arduino.

3. 16x2 LCD:
   - Connect the VSS (Ground) pin of the LCD to the GND terminal on the Arduino.
   - Connect the VDD (Power) pin of the LCD to the 5V terminal on the Arduino.
   - Connect the VO (Contrast Adjustment) pin of the LCD to the middle pin of a potentiometer. Connect the other two potentiometer pins to 5V and GND respectively.
   - Connect the RS (Register Select) pin of the LCD to pin 7 on the Arduino.
   - Connect the RW (Read/Write) pin of the LCD to the GND terminal on the Arduino.
   - Connect the E (Enable) pin of the LCD to pin 6 on the Arduino.
   - Connect the D4, D5, D6, and D7 pins of the LCD to pins 5, 4, 3, and 2 on the Arduino.

4. LED:
   - Connect the longer leg (anode) of the LED to a 220-ohm resistor.
   - Connect the other end of the resistor to pin 8 on the Arduino.
   - Connect the shorter leg (cathode) of the LED directly to the GND terminal on the Arduino.

5. Push Button (for calibration, optional):
   - Connect one leg of the push button to a digital pin (e.g., pin 9) on the Arduino.
   - Connect the other leg of the push button to the GND terminal on the Arduino.
   - You may also want to use a pull-up resistor (e.g., 10k ohms) between the digital pin and 5V to ensure reliable button readings. Connect one end of the resistor to the digital pin and the other end to 5V.

6. Power:
   - Power the Arduino using a USB cable or an external 5V power supply.

7. Grounding:
   - Ensure that all components share a common ground by connecting their GND pins to the Arduino's GND.

Please be aware that the wiring for the LCD may vary depending on the specific model of your 16x2 LCD display, so consult the datasheet or documentation for your particular display to confirm the pinout. Additionally, if you are using a different servo model, adhere to the manufacturer's specifications for proper connection.
