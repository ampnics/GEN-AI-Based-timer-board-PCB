Gen-AI-Based Timer Board using KiCad and DeepSeek
This project demonstrates the design of a timer control board created using traditional EDA tools supported by generative AI guidance. The goal was to explore how AI can assist in real-world hardware development, from concept to PCB.

Overview
This timer board is designed for applications such as:

Delay-based relay switching

Countdown-based automation

General purpose timing control in embedded systems

It features an ESP-based controller, a relay driver circuit, an OLED display for user feedback, and input buttons for setting time values.

AI Collaboration using DeepSeek
Throughout the project, DeepSeek AI was used to accelerate and refine different stages of the hardware design process:

Block Diagram: AI-generated block-level architecture based on system description.

Schematic Design: Assisted in part selection, logic validation, and drawing guidance.

Design Review: Suggested improvements for schematic correctness and layout optimization.

PCB Layout: Provided tips for routing, placement, EMI handling, and power distribution.

Design Feedback: Rated final design and recommended minor refinements.

Tools Used
KiCad 7.x for schematic and PCB design

DeepSeek AI for design assistance and review

ESP-based microcontroller

Relay module and driver circuitry

OLED I2C display

Tactile push buttons

Repository Structure
/kicad_project: Contains KiCad schematic and PCB layout files

/gerbers: Fabrication-ready Gerber files

/images: Block diagram, schematic snapshots, and board render

/docs: Design notes, AI feedback logs, and changelog

How to Use
Clone the repository

Open the KiCad project from the kicad_project folder

Review or modify the schematic as needed

Generate or inspect Gerber files for fabrication

Refer to the /docs folder for design rationale and review feedback

License
This project is open-sourced under the MIT License. You are free to use, modify, and distribute it for personal or commercial use.
