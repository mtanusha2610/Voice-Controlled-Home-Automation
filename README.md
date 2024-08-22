# Voice-Controlled-Home-Automation
Voice Controlled Home Automation in robotics involves designing and implementing a system that allows users to control home appliances using voice commands. The system consists of two main components: a voice recognition system and a wireless system.
The voice recognition system uses a voice-controlled Android application to
recognize and process voice commands. The application is connected to a
microcontroller, such as Arduino, which receives the voice commands and controls
the home appliances accordingly.
The wireless system uses a communication module, such as Bluetooth or Wi-Fi, to
establish a connection between the microcontroller and the home appliances. The
microcontroller sends signals to the appliances to turn them on or off based on the
voice commands received

## COMPONENTS REQUIRED:-
+ Arduino UNO
+ HC-05 Bluetooth Module 
+ 2-channel Relay Module(5v) 
+ 2 holders
+ 2 Bulb
+ 220v Electrical wire with a 2-pin male socket 
+ Sun board Piece
+ Jumper wires
+ Nuts & bolts
+ And a Smartphone

## STEPS TO CONNECT:

## Relay Module to Arduino:
+VCC of the Relay Module to 5V on the Arduino.
+GND of the Relay Module to GND on the Arduino.
+IN1 of the Relay Module to Pin 8 on the Arduino.
+IN2 of the Relay Module to Pin 9 on the Arduino.


## HC-05 Bluetooth Module to Arduino:
+VCC of the HC-05 to 3.3V or 5V on the Arduino (depending on your module's requirement).
+GND of the HC-05 to GND on the Arduino.
+TXD of the HC-05 to Pin 10 on the Arduino (use a voltage divider if needed, as HC-05 operates at 3.3V logic).
+RXD of the HC-05 to Pin 11 on the Arduino.


## AC Bulb Connection:
+One terminal of the AC Bulb to the Normally Open (NO) terminal of the Relay.
+Other terminal of the AC Bulb to the AC mains Live (L) wire.
+AC mains Neutral (N) wire to the Common (COM) terminal of the Relay.


## AC Mains (220V):
+Live wire (from AC mains) goes to the COM terminal of the Relay.
+Neutral wire connects directly to the Bulb as mentioned in the previous step.
