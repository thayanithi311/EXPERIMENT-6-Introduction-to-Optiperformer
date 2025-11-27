
## Exp 6 Simulation of Optical Communication System
## Introduction to OptiPerformer 
## Objective
Download and install OptiPerformer software on your computer and run a sample file.


## Overview

Optiwave introduces **OptiPerformer**, a free photonic design automation tool that harnesses the full power of OptiSystem and creates specific dynamic design scenarios for student use.

In this exercise, you will:
- Download and install OptiPerformer on your PC/laptop.
- Use your license to load and run OptiSystem simulations prepared for this course.

The first simulation file (`Introduction_OptiPerformer.osp`) models a basic fiber optic system consisting of:
- A transmitter
- A fiber
- A receiver

The system includes:
- An optical power meter at the receiver input (fiber output)
- A Bit Error Rate (BER) analyzer


## Instructions

1. Download and install OptiPerformer from [optiwave.com](https://optiwave.com).  
2. Copy the `Introduction_OptiPerformer.osp` file to your PC.  
3. Launch OptiPerformer.  
4. Use the **File** menu or **Open File** button to open the fiber optic system file.  
5. Study the layout:
   - **Transmitter** section includes:
     - Binary source (PRBS generator)
     - Electrical pulse generator
     - Laser diode
     - External modulator  
   - **Receiver** section includes:
     - Photodiode
     - Low-pass filter
     - Decision circuit with BER analyzer  
6. Run the simulation using the **Start** button.  
   - Progress will be displayed.
   - Message “Calculation Finished!” appears upon completion.  
7. Double-click the **optical power meter** and **BER analyzer** windows.  
   - Check “Show Eye Diagram” in the BER window.  
   - Optical power meter shows power in watts and dBm.  
   - BER window displays:
     - Eye diagram
     - Max Q Factor
     - Min BER  
8. The simulation runs 5 iterations with fiber length varying from 50 to 150 km.  
   - Use forward/reverse buttons to step through iterations.  
   - Observe changes in received power, BER, Q factor, and eye diagram.


## Report

1. Cover sheet (as per attached example).  
2. Tabulation of received power, Q factor, and BER for 5 fiber lengths.  
3. Plot of received power, Q factor, and BER vs. fiber length.  
4. Description of eye diagram changes with increasing fiber length.


## Tabulation

**Transmission Analysis Across Fiber Lengths**


| S. No | Fiber Length (m) | Optical Power (Watts) | Optical Power (dBm) | Max Q-factor | Min BER | Eye Height     | Decision Instant at Max Q / Min BER |
| ----- | ---------------- | --------------------- | ------------------- | ------------ | ------- | -------------- | ----------------------------------- |
| 1     | 56               | 36.746                | 14.34               | 100.121      | 0       | 7.86875 × 10⁻⁵ | 0.546875 / 0                        |
| 2     | 57               | 34.527                | 14.61               | 95.3597      | 0       | 7.0309 × 10⁻⁵  | 0.546875 / 0                        |
| 3     | 58               | 32.433                | 14.890              | 97.60832     | 0       | 6.70621 × 10⁻⁵ | 0.546875 / 0                        |
| 4     | 59               | 32.320                | 14.878              | 82.22062     | 0       | 6.38268 × 10⁻⁵ | 0.546875 / 0                        |
| 5     | 60               | 31.656                | 15.079              | 88.7921      | 0       | 6.11632 × 10⁻⁵ | 0.546875 / 0                        |


## Graphs

<img width="1097" height="399" alt="image" src="https://github.com/user-attachments/assets/4f130b5b-e145-4062-aea9-d896856c5d7b" />

---

## RESULT

The simulation of optical communication system was executed and verified successfully.
