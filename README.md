# Arduino LED Toggle with Buzzer Using Push Button

## Description
This project demonstrates an Arduino-based system where an LED is toggled ON and OFF using a push button.
Additionally, a buzzer provides audio feedback for a short duration whenever the button is pressed.

## Components Used
- Arduino UNO
- LED
- Push Button
- Buzzer
- 220Ω Resistor (for LED)
- 10kΩ Resistor (for Button pull-down)
- Jumper Wires

## Circuit Working
- When the push button is pressed, the LED toggles its state (ON to OFF or OFF to ON).
- At the same time, the buzzer sounds briefly to indicate a button press.
- Each button press produces one toggle action and one buzzer alert.

## Logic Used
- The push button input is read using a digital pin.
- A toggle logic is implemented to switch the LED state.
- A debounce delay is added to avoid false triggering.
- The buzzer is activated for a short duration to provide audio feedback.

## Platform
- Arduino UNO
- Simulated using Wokwi Arduino Simulator

## Output
- Button Press → LED ON + Buzzer Beep
- Next Button Press → LED OFF + Buzzer Beep
