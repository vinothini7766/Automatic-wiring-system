

🔌 Automatic Wiring System for Panel Boards

📌 Project Overview

The Automatic Wiring System is designed to automate the wiring process in electrical panel boards. Traditional wiring is manual, time-consuming, and error-prone. This system uses a combination of microcontrollers/PLC, sensors, and actuators to automatically cut, strip, crimp, and route wires to their correct terminals.

The project aims to reduce wiring time, improve accuracy, and enhance safety in electrical installations.


---

⚡ Features

Automatic wire cutting and stripping

Crimping of connectors/lugs

Robotic/actuator-based wire routing

Predefined wiring sequence using PLC/Arduino

Error detection using sensors

Continuity testing after wiring



---

🛠️ Components Used

Arduino Mega / PLC controller

Stepper motors & Servo motors

Wire feeder mechanism

Wire cutter & stripper unit

Crimping tool attachment

Limit switches & proximity sensors

Relay module for control

LCD / HMI for user interface



---

🔧 Working Principle

1. Input wiring diagram → stored in controller memory.


2. Wire is fed, cut, and stripped automatically.


3. Crimping is done before routing.


4. Motors/actuators place wire into terminal slots.


5. Sensors verify correct placement.


6. Final wiring is tested for continuity.




---

📂 Project Structure

Automatic-Wiring-System/
│── docs/                # Documentation (report, diagrams, flowcharts)  
│── hardware/            # Circuit diagrams, mechanical designs  
│── code/                # Arduino/PLC source code  
│── images/              # Project images, setup photos  
│── README.md            # Project details (this file)


---

🚀 Getting Started

Requirements

Arduino IDE (for Arduino-based version)

Proteus / TinkerCAD (for circuit simulation)

SolidWorks / AutoCAD (for mechanical design)


Steps to Run

1. Clone the repo:

git clone https://github.com/your-username/automatic-wiring-system.git
cd automatic-wiring-system


2. Upload the code to Arduino/PLC.


3. Connect hardware components as per circuit diagram.


4. Run the system and monitor via LCD/HMI.




---

📊 Applications

Industrial panel board wiring

Automotive wiring harness

Building electrical systems

Smart factories



---

✅ Future Enhancements

AI-based error prediction

Full robotic arm for wiring

Integration with IoT for remote monitoring

Auto-layout recognition from CAD files





