# Adaptive-traffic-light-system-project
 An intelligent traffic management system that optimizes traffic flow by adjusting signal timings in real-time based on traffic density and pedestrian activity.   
Here’s a well-structured GitHub README file draft based on your project report on the Adaptive Traffic Light Control System.

🚦 Adaptive Traffic Light Control System

An Arduino-based Adaptive Traffic Light Control System (ATCS) designed to optimize traffic flow by dynamically adjusting signal timings based on real-time traffic conditions. The system demonstrates the potential of intelligent traffic management for Smart Cities using IoT and AI principles.

🧠 Project Overview

Traditional fixed-time traffic signals lead to unnecessary waiting, congestion, and energy wastage. This project introduces an adaptive solution that:

Collects real-time traffic data (simulated).

Dynamically modifies signal durations.

Synchronizes multiple intersections for smooth flow.

Reduces travel time, emissions, and collisions.

The prototype uses an Arduino Uno, LEDs, and a Python controller script for simulation and testing.

🧩 Features

🔄 Dynamic Signal Timing: Adjusts signal durations based on simulated traffic density.

🕹️ Real-time Control: Commands sent from a Python script to Arduino via serial communication.

🌱 Eco-Efficient: Reduces idle time, fuel consumption, and emissions.

🧰 Expandable Design: Supports integration of sensors and smart city networks.

🛠️ Hardware Components

ComponentPurposeArduino UnoMain controllerLEDs (Red, Yellow, Green)Traffic signal indicators100Ω Resistors ×3Current limiting for LEDsBreadboardCircuit prototypingJumper WiresComponent connections 

💻 Software Requirements

Arduino IDE

Python 3.x

pyserial library (pip install pyserial)

⚙️ System Architecture

Input → Processing → Output

Input: Python script sends control commands (‘R’, ‘Y’, ‘G’) via serial.

Processing: Arduino interprets commands and executes logic.

Output: Corresponding LED lights up to simulate real traffic signal.

🧾 Implementation

🔸 Arduino Code Overview

Defines LED pins and configures them as outputs.

Reads serial input (‘R’, ‘Y’, ‘G’) from PC.

Activates corresponding LED with appropriate delay.

🔸 Python Script Overview

Establishes serial connection to Arduino.

Sends commands sequentially for red, yellow, and green lights.

Implements delays to simulate real traffic cycles.

📊 Results

⏱ Travel time reduced by ~10% compared to fixed-time control.

🧍‍♂️ Collisions reduced by up to 90% in simulation scenarios.

🌍 Fuel consumption and emissions decreased through smoother flow.

🧭 Future Enhancements

🚗 Integration with real-time sensors (IR, ultrasonic, cameras).

🧠 AI-based predictive traffic modeling.

🆘 Emergency vehicle prioritization.

🚶 Pedestrian detection and smart crossings.

🌐 IoT-enabled Smart City integration.

👥 Authors

Bhoomi Chauhan (2420694)

Bhoomika Rana (2420695)

Bhumika (2420696)

Bitu Sahu (2420697)

Under Guidance of: Er. Shubham Sharma

Department of Computer Science & Engineering
Chandigarh Engineering College, Jhanjeri (Mohali)

📚 References

Based on academic research and implementation described in the project report (2025).
Includes references from IEEE, MDPI, and AI-based smart traffic systems literature.
Would you like me to include the Arduino and Python code sections (in markdown code blocks) for direct GitHub use?
