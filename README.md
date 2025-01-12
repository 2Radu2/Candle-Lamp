# Candle-Lamp
The Candle Lamp is an Arduino-based project inspired by the SAV MAKER I board, combining electronics and programming to simulate the behavior of a real candle. It uses a relay and connected components to control a 220V lamp, turning it on and off based on inputs from a thermistor and a microphone.

How It Works:
Heat Detection: An NTC thermistor detects heat, triggering the relay to turn the lamp on when a specific temperature threshold is reached.
Blow Detection: A microphone detects a blow (or a significant change in input) and triggers the relay to turn the lamp off.
Continuous Functionality: The system allows for multiple on/off toggles while connected to the power supply, ensuring it replicates the natural behavior of a candle.
Components:

SAV MAKER I Board
5V Relay with Socket (for reuse)
NPN Bipolar Transistor (2N3904)
NTC Thermistor (value irrelevant)
Power Diode (1N400x)
Electret Microphone (unamplified)
Pre-drilled PCB
Two-way terminal block for lamp connection
Long-pin headers for easy connectivity

Features:

Heat detection to simulate lighting the "candle."
Sound detection to simulate blowing out the "candle."
Works with both a small LED for testing and a real 220V lamp for practical use.
Safe and cost-effective, with a compact layout designed for hands-on learning in electronics and Arduino programming.
This project is a perfect blend of creativity and functionality, offering a hands-on experience in embedded systems, relay control, and sensor integration. Check out the included Arduino code and schematic to get started or customize it further!


