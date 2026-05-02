# esp32-stepper-controller
This project is a complete mechatronic system combining electronics design, embedded control, and mechanical CAD modeling. It focuses on controlling two stepper motors independently using an ESP32-based controller and custom-designed mechanical components.
he system uses an ESP32 DevKit to control two stepper motors via A4988 drivers, enabling precise motion control for applications such as robotics, positioning systems, or CNC-like mechanisms.

The project includes:
Custom PCB design (EasyEDA)
Complete schematic and routing
Multiple 3D mechanical parts (Blender)
Integration of electronics with mechanical structures
Hardware Architecture
Microcontroller: ESP32 DevKit
Motor Drivers: 2 × A4988
Power Supply: 12V input with regulated 5V rail
Control Signals: STEP / DIR for each motor
Microstepping Control: MS1, MS2, MS3 pins configurable
Decoupling & Filtering: Electrolytic and ceramic capacitors for stability


PCB Design
Designed in EasyEDA
Dual driver layout with clean routing for:
Power distribution
Signal integrity
Integrated headers for:
Motors
Control interfaces
Compact and modular layout for easy integration


All mechanical components were modeled in Blender, including:
Motor mounting brackets
Gear system (spur/helical gear)
Structural supports and housings
Custom enclosures and covers


Design considerations:
Fit and alignment with stepper motors
Structural rigidity
Manufacturability (3D printing / prototyping)
Key Features
Independent control of two stepper motors
Expandable architecture (additional sensors/modules possible)
Fully custom hardware (PCB + mechanics)
Integration-ready design for embedded systems projects
