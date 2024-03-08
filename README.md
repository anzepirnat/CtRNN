# Energy Efficient Deep Multi-Label ON/OFF Classification of Low Frequency Metered Home Appliances
[Anže Pirnat](https://sensorlab.ijs.si/people/apirnat/)\*,
[Blaž Bertalanič](https://sensorlab.ijs.si/people/bbertalanic/)\,
[Gregor Cerar](https://sensorlab.ijs.si/people/gcerar/),
[Mihael Mohorčič](https://sensorlab.ijs.si/people/mmohorcic/),
[Carolina Fortuna](https://sensorlab.ijs.si/people/cfortuna/)<br>
Sensorlab, Jozef Stefan Institute

## Overview

This repository contains the code demo for the paper titled "Enhanced Multi-label Classification in NILM using a DL CtRNN Model with Improved Energy Efficiency", which showcases our proposed methodology and our architecture. The code may be used to reproduce SE and RE groups of mixed datasets for your evaluation needs.

## Contents

Non-intrusive load monitoring (NILM) involves obtaining appliance-level data from a single metering point to measure total electricity consumption. 

Notebook in this repository encompasses:
- DL CtRNN (Convolutional Transposed Recurrent Neural Network) architecture designed for enhanced multi-label classification in NILM. Architecture is implemented and depicted in the code. 
- Evaluation methodology consisting of RE and SE groups of mixed datasets. Code contains all functions that were used to process REFIT and UK-DALE datasets to shape any of the mixed datasets from RE and SE groups.

The notebook includes examples that showce the practical usage of functions, with comprehensive explanations provided in the accompanying markdowns.

## Contributions of our paper

- Novel DL CtRNN architecture inspired by VGG family for NILM disaggregation.
- Evaluation methodology for comparing models using synthesized data from measurement datasets.
- Analysis of performance and energy efficiency in relation to the number of devices in the household.

## CtRNN Architecture

To achieve high classification performance with improved energy efficiency, we introduced a new DL CtRNN architecture. The architecture comprises four blocks, each with convolutional layers, average pooling layers, a transposed convolutional layer, and a gated recurrent unit (GRU) layer. The output layer needs to be adapted based on specific dataset requirements.

![CtRNN Architecture](/notebook_pics/architecture.png)

The architecture is also displayed in code under the Section 3: Architectures. 


## Usage
For a seamless reading experience of the notebook, download the map "notebook_pics" in repository and place them into the same directory as the notebook.

If you wish to run the code, we recommend that your system has the following specifications:
- RAM: 256GB+
- GPU: 8GB+ VRAM (you might need to adjust batch size)
- CPU: 8 core, 16 threads or better

If you prefer to download the RE mixed dataset example instead of generating it with code (due to long wait time), you may contact me on ap6928@student.uni-lj.si and I will share it with you.

## Citation
If you find our work useful in your research, or if you are using any part of the code please consider citing our paper. 

### Ackwnoledgement
This work was funded in part by the Slovenian Research Agency under the grant P2-0016. This project has received funding from the
European Union’s Horizon Europe Framework Programme under grant agreement No 872525 (BD4OPEM).
