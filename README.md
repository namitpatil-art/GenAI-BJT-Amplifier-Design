# Generative AI-Based Synthesis of Single-Stage BJT Amplifiers with Gain Validation

## Project Overview

This project presents an AI-driven framework for automated design of single-stage BJT amplifiers using a Topology-Aware Conditional Generative Adversarial Network (cGAN).

The system accepts amplifier specifications such as configuration type, gain requirement, and supply voltage (Vcc), and automatically generates suitable circuit parameters including RC, RE, RG, and Vout.

The generated design is further validated through gain estimation, waveform visualization, and automatic circuit schematic generation.

---

## Features

* Automated BJT amplifier design
* Supports CE, CC, and CG configurations
* Topology-aware Conditional GAN
* Gain validation
* Input and output waveform generation
* Automatic circuit schematic generation
* Google Colab implementation
* PyTorch-based deep learning framework

---

## Dataset Features

The dataset contains:

* Config
* Gain
* Vcc
* Vout
* RC
* RE
* RG

Supported Configurations:

* CE (Common Emitter)
* CC (Common Collector)
* CG (Common Gate)

---

## Technologies Used

* Python
* Google Colab
* PyTorch
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Schemdraw

---

## System Workflow

User Input

→ Configuration (CE / CC / CG)

→ Desired Gain

→ Supply Voltage (Vcc)

↓

Conditional GAN

↓

Generated Parameters

* RC
* RE
* RG
* Vout

↓

Gain Validation

↓

Waveform Generation

↓

Circuit Diagram Generation

---

## Repository Structure

Dataset/
Notebook/
PPT/
Results/

---

## Results

The model generates:

* Amplifier component values
* Gain estimation
* Waveform plots
* Circuit schematics

Project outputs and screenshots are available in the Results folder.

---

## Future Scope

* Multi-stage amplifier design
* MOSFET amplifier automation
* CMOS analog circuit synthesis
* Diffusion-model-based circuit generation
* Reinforcement-learning-assisted optimization

---

## Author

Namit Patil

B.Tech Engineering Student

Project: GenAI-Based BJT Amplifier Design
