Breathing LED with PWM – Arduino UNO Project
This project demonstrates how to simulate a "breathing" effect using Pulse Width Modulation (PWM) on an LED. The LED gradually gets brighter and then slowly dims in a loop, resembling the rhythm of human or animal breathing.

 Components Required
1 × Arduino UNO

1 × USB Cable

1 × LED

1 × 220Ω Resistor

1 × Breadboard

Several Jumper Wires

Principle
PWM (Pulse Width Modulation) is a technique used to simulate analog output using digital signals. By quickly turning the digital pin on and off, we control the "average" voltage seen by devices like LEDs.

Duty Cycle: The percentage of time the signal is ON in one PWM cycle.

analogWrite(0) → Always OFF (0% duty cycle)

analogWrite(127) → 50% duty cycle

analogWrite(255) → Always ON (100% duty cycle)

The Arduino UNO provides PWM output on digital pins: 3, 5, 6, 9, 10, and 11.

Step 1: Build the Circuit
Connect the anode (long leg) of the LED to pin 9 of Arduino (or any PWM pin) through a 220Ω resistor.

Connect the cathode (short leg) to GND.

Use a breadboard and jumper wires for clean connections.

Step 2: Upload the Code
Open the Arduino IDE.

📸 Expected Output
The LED will fade in and out gradually, resembling a breathing pattern.

The effect will repeat continuously in a smooth, natural loop.

