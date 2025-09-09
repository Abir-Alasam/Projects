# Embedded Systems & Robotics Portfolio

A collection of projects focused on mechatronics, embedded systems, and autonomous robotics, developed during my studies in Engineering.

## Projects
### [The Wrangler - Design II](The%20Wrangler.pdf)
The Wrangler - Design II is an autonomous robot built to compete in a ball-shooting challenge. It features a custom gravity-fed launching mechanism powered by geared DC motors and rubber wheels for optimal projectile grip and distance.
  
  The robot is controlled by an Arduino microcontroller, which processes data from an ultrasonic sensor to make strategic decisions on when to move forward, reverse, and fire its three balls. Its two-tiered base provides a stable and organized       platform for the electronics, while its versatile holonomic drive allows for omnidirectional movement.
  
**Key Features:**
- **Autonomous Targeting:** Uses an ultrasonic sensor to detect opponents and adjust strategy.
- **Adjustable Launcher:** An angled, torque-based mechanism allows for precise range calibration.
- **Omnidirectional Drive:** Four-wheel holonomic drive provides full movement flexibility.
- **Arduino Control:** Custom algorithm dictates movement and firing sequences based on sensor input.

**Key Skills:** `Arduino` `Mechanical Design` `DC Motors` `Ultrasonic Sensors` `Algorithm Design`

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


### [Lobster X](LostorX%20Robot%E2%80%99s%20design%20and%20implementation.pdf)
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

