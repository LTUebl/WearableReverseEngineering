# Wearable Technology Reverse Engineering & Design Studio

**Lawrence Technological University &middot; Department of Biomedical Engineering**  
**Experimental Biomechanics Laboratory (EBL) & Wearable Technology Innovation Center (WTIC)**  
*Author: Dr. Eric G. Meyer, PhD*

[![Live Site](https://img.shields.io/badge/Live_Site-GitHub_Pages-002D62?style=flat-square&logo=github)](https://ltuebl.github.io/WearableReverseEngineering/)
[![KEEN Card](https://img.shields.io/badge/KEEN_Card-%235823-0079C2?style=flat-square)](https://engineeringunleashed.com/card/5823)
[![Course](https://img.shields.io/badge/Curriculum-BME_3113_%26_Summer_Camp-059669?style=flat-square)](https://ltu.edu)

---

## Overview

This repository hosts the standalone interactive web platform for the **Wearable Technology Reverse Engineering, Design Thinking, and SCAMPER Ideation Studio**. Deployed in **BME 3113: Bioinstrumentation & Wearables**, **Intro to BME**, and LTU's **High School Biomedical Engineering Summer Camp**, this curriculum equips students to deconstruct smart hardware, leverage generative AI for bill-of-materials and circuit estimation, and invent commercially viable wearable solutions.

The learning modules are aligned with Entrepreneurial Minded Learning (EML) principles disseminated nationally via **KEEN Engineering Unleashed Card #5823**.

---

## Curricular Architecture

### Module 1: Design Frameworks Reflection
- **Fitbit Design Philosophy**: Reviewing consumer empathy, behavioral nudges, and industrial form factors with Fitbit designers ([YouTube Video](https://www.youtube.com/watch?v=m4hdtSyyigc)).
- **Design Lessons from Big Tech**: Synthesis of Apple, Google, and Amazon hardware engineering practices ([Model Thinkers Playbook](https://modelthinkers.com/playbook/design-lessons-from-big-tech)).
- **Wearable Technology Insights**: Investigating cutting-edge clinical, sports, and consumer sensing breakthroughs ([Wearable Tech Insights](https://www.wearabletechnologyinsights.com/)).

### Module 2: In-Class Pedometer Teardown & Reverse Engineering
Hands-on mechanical and electronic deconstruction of electro-mechanical step counters.
- **Pre-Lab Component Hypothesis**: Students forecast internal assemblies prior to opening the housing.
- **Disassembly & Connectivity Documentation**: Step-by-step documentation of fasteners, snap-fits, and solder joints.
- **Bill of Materials (BOM) & Manufacturing Estimation**: Reverse engineering part functions, production methods (injection molding, SMT, stamping), and volume manufacturing cost estimates ($0.05–$0.40 range).
- **AI-Assisted Circuit & Process Diagramming**: Utilizing multimodal generative AI to generate block diagrams, component schematics, and functional signal paths from physical PCB photographs.
- **Reference Assets**:
  - `PedometerTeardownGuide.pdf`
  - `AIGenerated_CircuitDiagram_BOM_Pedometer.pdf`

### Module 3: Design Thinking & SCAMPER Ideation Studio
A structured 17-slide innovation sprint from unmet human needs to evaluated concept matrices.
- **Need-Finding Formula**: `[User demographic]` needs a way to `[user need]` because `[deep insight/pain point]`.
- **Zero-Fidelity Prototyping & Bisociation**: Combining unrelated design disciplines to ignite unexpected form factors.
- **SCAMPER Creative Transformation**:
  - **S**ubstitute &middot; **C**ombine &middot; **A**dapt &middot; **M**odify/Magnify &middot; **P**ut to another use &middot; **E**liminate &middot; **R**everse
- **Custom Gemini GEM Assistant**: AI-powered ideation coach ([Gemini GEM: 33a41862bd77](https://gemini.google.com/gem/33a41862bd77)).
- **Concept Selection Matrix**: Quantitative Pugh scoring across feasibility, clinical utility, ergonomics, and cost.

### Module 4: Individual Homework Assignment 1 &ndash; Wearable Devices Interactive Presentation
Students build their first professional digital portfolio hosted directly on **GitHub Pages**:
- **Deliverable Structure (10 Interactive Slides)**:
  1. *Title Slide*
  2. *Clickable Navigation Menu / Overview Diagram*
  3. *Value Proposition & Problem Solved*
  4. *User Inputs, Outputs & Sensor Modalities*
  5. *Mobile App & BLE Cloud Connectivity*
  6. *Retail, Pricing & Business Strategy*
  7. *Hardware Teardown Components & PCB Architecture*
  8. *Fabrication, Materials & Assembly Process*
  9. *Personal Engineering & Ergonomic Review*
  10. *References, Benchmarks & External Sources*
- **Research & Teardown Resources**:
  - Benchmarking teardown reviews (e.g., [Apple Watch Teardown Analysis](https://www.youtube.com/watch?v=E0GufWmT4mU))
  - [Adafruit YouTube Teardown Channel](https://www.youtube.com/c/adafruit/search?query=wearable+teardown)
  - Live Exemplar: [Ringly Luxe Smart Ring Interactive Presentation](https://ltuebl.github.io/ringly-smart-ring-presentation/)
  - Guide Document: `Ringly_SmartRing_WearableStudio_Example.pdf`

---

## Repository Structure

```text
├── index.html                                    # Main interactive web application
├── styles.css                                    # Responsive LTU Blue CSS stylesheet
├── PedometerTeardownGuide.pdf                    # Physical pedometer teardown guide
├── AIGenerated_CircuitDiagram_BOM_Pedometer.pdf  # AI circuit schematic & parts list
├── DesignThinking_SCAMPER_WearableStudio.pdf     # 17-page Design Thinking & SCAMPER slide deck
├── Ringly_SmartRing_WearableStudio_Example.pdf   # 10-slide HW1 exemplar PDF
├── WearableTechnology_Studio_ReverseEngineering.pdf # Complete studio slide deck
├── README.md                                     # Curricular documentation
└── *.png                                         # Architectural, schematic & teardown diagrams
```

---

## Contact & Credits

**Dr. Eric G. Meyer, PhD**  
Director, Experimental Biomechanics Laboratory (EBL)  
Associate Professor, Biomedical Engineering  
Lawrence Technological University &middot; Southfield, MI  
Email: [emeyer@ltu.edu](mailto:emeyer@ltu.edu) &middot; [EBL Main Hub](https://ltuebl.github.io/)
