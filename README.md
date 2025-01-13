# Automated Power Backup

This repository contains the project details for the **Automated Power Backup**, completed as part of the Semester 2 EN1190 Electronic Design Project module. The project focuses on ensuring uninterrupted power for Wi-Fi routers during government-imposed blackouts, with additional features to enhance usability.

## Project Overview

The Automated Power Backup is designed to provide:
- Uninterrupted power to Wi-Fi routers during power outages.
- Additional functionalities such as:
  - **Portable Power Bank**
  - **Emergency Lamp**
  - **Battery Level Indicator**

### Key Features
1. **Automated Switching**: 
   - Seamlessly switches between grid power and backup battery supply.
   - Uses a relay and transistor-based mechanism to handle power changes.

2. **Voltage Regulation**:
   - Supplies stable 12V DC for Wi-Fi routers and 5V DC for USB devices and LED strips.
   - Incorporates regulator ICs (7812, 7805) for precise voltage output.

3. **Battery Level Indicator**:
   - Displays remaining battery power with five-level LED indicators.
   - Includes a switch to activate the display, conserving battery life.

4. **Portable Design**:
   - Lightweight and compact enclosure designed using SolidWorks 2020.
   - Dimensions: 100mm x 150mm x 60mm; Weight: 500g.

5. **Additional Features**:
   - USB charging port.
   - LED strip for emergency lighting.

## Technical Specifications
- **Input Voltage**: 12V DC (via the user’s existing Wi-Fi router adapter).
- **Backup Power**: 14.8V from four 18650 lithium-ion batteries.
- **Output Voltage**: Regulated 12V and 5V DC.
- **Trip Time**: Negligible, ensuring uninterrupted operation.

## Development Stages
1. **Problem Analysis**: Survey conducted with 300 students validated the need for uninterrupted Wi-Fi during blackouts.
2. **Design and Prototyping**:
   - **Schematics and PCB Layouts**: Designed using Altium Designer 2022.
   - **Enclosure Design**: Modeled and finalized using SolidWorks 2020.
3. **Testing and Validation**:
   - Verified functionality through simulations and physical testing.

## Project Results
The system successfully powers Wi-Fi routers during blackouts and meets the following requirements:
- Continuous operation for up to 3–5 hours.
- Reliable switching and voltage regulation.
- Enhanced user experience with added features like USB charging and emergency lighting.

## Budget
The total cost of the project was approximately **LKR 7,000**, including components, PCB, and enclosure printing.

## Acknowledgments
We extend our gratitude to our mentors and peers who provided invaluable guidance and support throughout the project.

---

### Directory Structure
- **/Reports**: Contains detailed documentation and survey results.
- **/Designs**: Includes schematics, PCB layouts, and enclosure design files.
- **/Source Code**: Contains relevant code for battery level indication and control mechanisms.

### How to Use
1. Refer to the schematic and PCB files to recreate the circuit.
2. Use the provided enclosure design to fabricate the case.
3. Follow the user manual in the documentation for assembly and operation instructions.

---

This project demonstrates practical engineering solutions for uninterrupted connectivity during power outages, with additional usability features for everyday convenience.
