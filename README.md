# Embedded Systems & Robotics Portfolio

A collection of projects focused on mechatronics, embedded systems, and autonomous robotics, developed during my studies in Engineering.

## Projects
### [SmartShelf - IoT Inventory Tracking System](EmbeddedSystem_intrenship.pdf)
SmartShelf is an IoT-enabled system designed to automate real-time inventory tracking and synchronize stock levels with **Odoo ERP**. It combines weight sensors, presence detection, and a camera to provide both quantitative and visual data for multiple products on a shelf.

The system uses an **ESP32 microcontroller** to acquire sensor data from **NAU7802 load cells** and **AK9753 presence sensors**, while a **Raspberry Pi** processes the data, converts weight into item counts, and updates Odoo automatically via XML-RPC. A **Tkinter GUI** displays a live planogram of the shelves, and **Grafana dashboards** provide historical trends and real-time analytics. Presence-based activation ensures sensors operate only when a user is nearby, improving power efficiency.

**Key Features:**
- Designed and developed a first-generation SmartShelf prototype for automated retail inventory tracking.  
- Developed firmware for real-time data acquisition, wireless communication, power management, and OTA updates.  
- Implemented a backend with Raspberry Pi, MQTT broker, database, and dashboards for visualization.  
- Integrated with Odoo ERP for automated stock updates.  
- Performed prototype calibration, validation, and resilience testing, including latency measurement and automated test scripts.  
- Added presence-triggered camera capture for future AI-driven analytics.  
- Built a GUI to visualize shelf activity, product counts, and planogram layouts in real time.  
- Designed and tested a custom multilayer PCB to integrate all components into a compact SmartShelf node.  

**Key Skills:** `ESP32` `Embedded C++` `Raspberry Pi` `Python` `MQTT` `Odoo API` `Tkinter` `Grafana` `IoT Architecture` `Flask`


### [Buoyancy Operated Aquatic Transport (B.O.A.T.)](Boat%20project.pdf)
Buoyancy Operated Aquatic Transport (B.O.A.T.) is a 3D-printed, motorized catamaran designed for a collegiate engineering design challenge. The goal was to create a sub-8-inch vessel capable of carrying a 50g payload and traversing a water channel within 30 seconds.

This project involved the full design cycle: conceptualizing three distinct hull designs, evaluating them based on propulsion, stability, and manufacturability, and selecting a dual-hull (catamaran) concept for its superior performance. The final design was modeled in SolidWorks, with buoyancy calculations confirming it would support its own weight and payload. Key features include a custom propeller, a lightweight platform connecting the two hulls, and an integrated motor assembly.

The physical prototype successfully met all competition requirements, demonstrating effective buoyancy, stability, and speed.

**Key Skills:** `SolidWorks` `3D Printing` `Engineering Design` `Buoyancy Calculation` `Prototyping`

### [IR Remote-Controlled DC Motor](IR%20Remote-controlled%20DC%20motor%20.pdf)
IR Remote-Controlled DC Motor is an embedded systems project that demonstrates wireless control of a DC motor using an infrared (IR) remote. The system uses an Arduino Uno microcontroller to interpret button presses from a standard IR remote, translating them into directional motor commands.

An HX1838 IR receiver captures the modulated signal from the remote, which is then decoded by the Arduino. The interpreted commands are sent to an H-bridge motor driver, which provides the necessary power and control logic to drive the DC motor forward, backward, left, right, and stop.

This project provided hands-on experience with key electrical engineering concepts, including IR signal modulation/demodulation, microcontroller programming, and motor driver circuitry, showcasing a fundamental building block for robotics and automation systems.

**Key Features:**
- **Wireless Control:** Uses an IR remote for intuitive user input.
- **H-Bridge Driver:** Safely controls motor direction and operation.
- **Arduino Integration:** Custom firmware decodes IR signals and executes motor commands.

**Key Skills:** `Arduino` `IR Communication` `H-Bridge` `Signal Modulation` `Circuit Design`


### [Lobster X](Lobster-X-Robot-Design.pdf)
Lobster X is a multi-functional, autonomous robot designed for a complex challenge involving navigation, object retrieval, and system disarming. The robot was developed by a multidisciplinary team over a 10-week period, following a full design and validation cycle.

The robot's capabilities include autonomous navigation using wall-following and waypoint tracking, disarming a magnetic "bomb" trigger, swiping an RFID card to disable an alarm, and using a custom gripper mechanism to collect and return "loot" to a starting area. The system integrates an Arduino-based control system with ultrasonic sensors, an IMU, servos, and an RFID module, all powered by a custom-regulated battery pack.

This project provided extensive experience in mechatronics, including mechanical design (SolidWorks), firmware development (sensor integration, PID control, state machines), electrical systems, and rigorous Verification & Validation (V&V) testing.

**Key Features:**
- **Autonomous Navigation:** Implements wall-following and waypoint algorithms.
- **Multi-Task Execution:** Integrates gripping, RFID swiping, and magnetic disarming routines.
- **3D-Printed Mechanics:** Features custom-designed arms, grippers, and component holders.
- **Structured V&V Process:** Employs a rigorous testing protocol to ensure all system requirements are met.

**Key Skills:** `SolidWorks` `Arduino` `C++` `Sensor Integration` `3D Printing` `Project Management` `V&V`

## 📁 Repository Structure
├── LostorX Robot’s design and Implementation.pdf
├── posterDesign 2.pdf
├── circuits_II_presentation.pdf
├── baut project.pdf
└── README.md

## 📬 Contact
- **Name:** Abir Alasam
- **Email:** abeer.alassam2001@gmail.com
- **LinkedIn:** [www.linkedin.com/in/abir-alasam-1b3329262]

---
*This repository serves as a portfolio of my practical work in engineering design and embedded systems.*

