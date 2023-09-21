# Cargonomics
Problem Statement: Overloading and Underloading Problem in 
Coal Wagons. 


ObjecƟves: The primary objecƟves of addressing the overloading and 
underloading problem in coal wagons are as follows: 
- Enhance safety by prevenƟng overloading and underloading incidents.
- Ensure compliance with regulatory standards and guidelines. 
- Improve operaƟonal efficiency and reduce costly delays.
- Implement real-Ɵme monitoring and reporƟng mechanisms.

  
Components : 
Certainly, I can provide a more detailed explanaƟon of the circuit connecƟons for 
your project. Here's how to connect the components: 
The components used are : 
1. Arduino Uno 
2. Load Cell (with HX711 module) 
3. Servo Motor 
4. 16x2 LCD (Liquid Crystal Display) 
5. LED 
6. 220-ohm Resistor 
7. Push BuƩon (for calibraƟon)

   
ConnecƟons: 
1. Load Cell (with HX711 module): 
 - Connect the red wire (VCC) of the HX711 module to 5V on the Arduino. 
 - Connect the black wire (GND) of the HX711 module to GND on the Arduino.

 - 
 - Connect the white wire (DT - Data) of the HX711 module to A0 on the Arduino. 
 - Connect the yellow wire (SCK - Clock) of the HX711 module to A1 on the 
Arduino. 
2. Servo Motor: 
 - Connect the red wire of the servo to 5V on the Arduino. 
 - Connect the brown wire of the servo to GND on the Arduino. 
 - Connect the orange or yellow wire of the servo to pin 10 on the Arduino. 
3. 16x2 LCD: 
 - Connect the VSS (Ground) pin of the LCD to GND on the Arduino. 
- Connect the VDD (Power) pin of the LCD to 5V on the Arduino. 
 - Connect the VO (Contrast Adjustment) pin of the LCD to the middle pin of a 
potenƟometer, and connect the other two potenƟometer pins to 5V and GND 
respecƟvely.
 - Connect the RS (Register Select) pin of the LCD to pin 7 on the Arduino. 
 - Connect the RW (Read/Write) pin of the LCD to GND on the Arduino.

 - 
 - Connect the E (Enable) pin of the LCD to pin 6 on the Arduino. 
 - Connect the D4, D5, D6, and D7 pins of the LCD to pins 5, 4, 3, and 2 on the 
Arduino. 
4. LED: 
 - Connect the longer leg (anode) of the LED to a 220-ohm resistor. 
 - Connect the other end of the resistor to pin 8 on the Arduino. 
 - Connect the shorter leg (cathode) of the LED directly to GND on the Arduino.


   
5. Push BuƩon (for calibraƟon, opƟonal): 
 - Connect one leg of the push buƩon to a digital pin (e.g., pin 9) on the Arduino.
 - Connect the other leg of the push buƩon to GND on the Arduino.
 - You may also want to use a pull-up resistor (e.g., 10k ohms) between the digital 
pin and 5V to ensure reliable buƩon readings. Connect one end of the resistor to 
the digital pin and the other end to 5V. 
6. Power: 
 - Power the Arduino using a USB cable or an external 5V power supply. 
7. Grounding: 
 - Ensure that all components share a common ground by connecƟng their GND 
pins to the Arduino's GND. 
Please note that the LCD wiring may vary depending on the specific model of your 
16x2 LCD display, so check the datasheet or documentaƟon for your parƟcular 
display to confirm the pinout. AddiƟonally, if you have a different servo model, 
make sure to connect it according to the manufacturer's specificaƟons
