# Deep Learning for Non-Intrusive Load Monitoring (NILM)

## Overview

This repository contains the code demo for the paper titled "Enhanced Multi-label Classification in NILM using a DL CtRNN Model with Improved Energy Efficiency". The paper introduces a novel Deep Learning (DL) model for Non-Intrusive Load Monitoring (NILM) with a focus on improved computation and energy efficiency.

## Abstract

Non-intrusive load monitoring (NILM) involves obtaining appliance-level data from a single metering point to measure total electricity consumption. This repository presents a DL CtRNN (Convolutional Transposed Recurrent Neural Network) architecture designed for enhanced multi-label classification in NILM. The model aims to improve computation and energy efficiency compared to classical machine learning and deep learning techniques.

## Key Features

- Novel DL CtRNN architecture inspired by VGG family for NILM disaggregation.
- Evaluation methodology for comparing models using synthesized data from measurement datasets.
- Analysis of performance and energy efficiency in relation to the number of devices in the household.

## CtRNN Architecture

To achieve high classification performance with improved energy efficiency, we introduced a new DL CtRNN architecture. The architecture comprises four blocks, each with convolutional layers, average pooling layers, a transposed convolutional layer, and a gated recurrent unit (GRU) layer. The output layer adapts based on specific dataset requirements.

![CtRNN Architecture](/path/to/figure4.png)

The architecture is also displayed in code under the Section 3: Architectures. 

## Usage
If you wish to run the code as it is, we recommend that your system has the following specifications:
- RAM: 256GB+
- GPU: gtx 4090 or better
