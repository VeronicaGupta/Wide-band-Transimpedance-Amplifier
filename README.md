# TIA-Project Overview

## Course Details
- **Course**: ECE-GY 9423
- **Instructor**: Hamed Rahmani
- **Institution**: New York University
- **Term**: Fall 2024

## Project Deliverables
- **Electronic Files Submission**: Cadence Library due by November 7, 2024, 11:59 PM EST
- **Reports Due**: December 8, 2024, before 5 PM
- **Project Presentations**: December 9, 2024, 11:00 AM - 1:30 PM EST

## Project Description
This project focuses on designing a transimpedance amplifier (TIA) for an optical receiver front-end. The design integrates a photoconductive diode to convert current signals from photodetectors into measurable voltage signals, crucial for applications in optical communications.

### Key Objectives:
- Design a CMOS-based TIA emphasizing low noise performance, high gain, and bandwidth.
- Achieve a flat gain over a wide bandwidth to ensure efficient signal processing at high speeds.

### Design Challenges:
- Integrating chiplet technology for enhanced performance and scalability.
- Utilizing Co-Packaged Optics (CPO) to improve data transfer rates while reducing power consumption.

## Images Overview
- **Image 1**: Shows the concept of chiplet-based system architectures. (Refer to `chiplet_architecture.png`)
- **Image 2**: Illustrates the integration of optical and electrical domains within CPO. (Refer to `CPO_integration.png`)
- **Image 3**: Illustrated test bench to get circuit performance. (Refer to `Test_bench_.png`)

## Design Specifications
- **Input**: Single-ended photo-diode with 0.5pF shunt capacitor.
- **Outputs**: Differential, connected to two 50-ohm loads.
- **Supply Voltage**: 1.2V
- **Power Budget**: Less than 50mW
- **Transimpedance Gain**: Greater than 74 dB
- **Bandwidth**: Exceeding 5GHz
- **Differential Output Swing**: Over 100mV
- **Optional**: Input-referred noise less than 50pA/sqrt(Hz).

## Simulation and Analysis
- Conduct simulations to verify design against specifications.
- Include analytical predictions and simulated results, address any discrepancies.

## Final Submission
- Provide a comprehensive report detailing all aspects of the design and simulation results.
- Prepare for a presentation outlining the project scope, methodology, results, and key learnings.
