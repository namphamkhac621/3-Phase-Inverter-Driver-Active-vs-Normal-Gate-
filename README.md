# Three-Phase Inverter Design (Normal Gate Implementation)

This project focuses on the hardware implementation of a Three-Phase Inverter using the Infineon 2EDR3140 driver IC. Developed as part of my graduation project at Hanoi University of Science and Technology (HUST), this board serves as a practical baseline to compare traditional gate driving with newer Active Gate technologies.

### 1. What's Inside (Overview)
I built this power stage to handle 3-phase motor loads while maintaining clean PWM signals. The main goal was to create a reliable hardware setup to test how Normal Gate driving handles switching losses and heat compared to Active Gate methods. I handled everything from choosing the right MOSFETs/IGBTs to the final PCB assembly, ensuring the board stays stable under high-load conditions.

### 2. Tech Stack & Implementation
* **Hardware:** Designed the schematic and multi-layer PCB in Altium Designer, focusing on signal isolation and solid power paths.
* **Gate Control:** Configured the 2EDR3140 for standard operation, integrated with FOC (Field Oriented Control) logic.
* **Testing:** Verified all designs through LTspice and MATLAB/Simulink before fabrication. Post-assembly, I used high-bandwidth oscilloscopes to debug the switching waveforms and check for EMI issues.

### 3. Resources
* **/Hardware**: Includes full Altium schematics and PCB layout files.
* **/Simulations**: Contains LTspice models and Simulink motor control blocks.
* **/Reports**: Technical documentation and data comparing Normal vs. Active Gate performance.
