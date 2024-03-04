# Energy Efficient Deep Multi-Label ON/OFF Classification of Low Frequency Metered Home Appliances

## Overview

This repository contains the code demo for the paper titled "Enhanced Multi-label Classification in NILM using a DL CtRNN Model with Improved Energy Efficiency". 

## Contents

Non-intrusive load monitoring (NILM) involves obtaining appliance-level data from a single metering point to measure total electricity consumption. 

Notebook in this repository presents:
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
