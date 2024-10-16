# Simulating Synaptic Dynamics and Decision-Making in Neuronal Populations

This project implements simulations of synaptic interactions between neuron populations, focusing on the mechanisms of synaptic transmission and neuronal decision-making. It models excitatory and inhibitory neuron populations, explores different connectivity patterns, and investigates neuron responses to noisy and non-noisy inputs using various synaptic dynamics.

## Table of Contents
- [Project Overview](#project-overview)
- [Implemented Features](#implemented-features)
- [Simulation Inputs](#simulation-inputs)
- [How to Run](#how-to-run)
- [Results](#results)
- [References](#references)

## Project Overview
This project is part of the second neural computation course project for the academic year 1402-1403. The main goals are to understand how synaptic mechanisms work, analyze the behavior of neuron populations under different stimulation conditions, and simulate decision-making processes in neural circuits.

## Implemented Features
1. **Synaptic Mechanisms**: 
   - Implementation of synapses using the **Dirac Delta function** to model spike timing and transmission.
   - Comparison of dynamic synapses based on conductance.

2. **Neuronal Populations**: 
   - Two distinct neuron populations: **Excitatory** (80%) and **Inhibitory** (20%) neurons, modeled with different parameters.
   - Connectivity between neurons using various strategies such as **full connectivity**, **fixed coupling probability**, and **fixed number of presynaptic partners**.

3. **Noisy Inputs**: 
   - Simulation of neuron population responses to both **noisy** and **non-noisy** input currents, analyzing the sensitivity and firing rates under different conditions.

4. **Decision-Making Simulation**: 
   - Simulation of decision-making processes when two neuron populations receive inputs, demonstrating competition and activity dynamics between excitatory and inhibitory neurons.

## Simulation Inputs
The project investigates several types of inputs, including:
- **Constant Input**
- **Noisy Input**
- **Step Input**
- **Random Input Currents**

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/neural-computation-project-02.git
2. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the simulation notebooks:
   - **For Synaptic Mechanisms**: Open and run `synaptic_mechanisms.ipynb`
   - **For Population Behavior**: Open and run `population_behavior.ipynb`
   - **For Decision-Making Simulation**: Open and run `decision_making.ipynb`

   Launch the notebooks by executing:
   ```bash
   jupyter notebook

## Results
Results from the simulations, including raster plots of neuronal activity, connectivity graphs, and decision-making dynamics, can be found in the [report](./Report/Report.pdf).

## References
- [PymoNNtorch Framework]( https://github.com/cnrl/PymoNNtorch)
- [Neural Dynamics](https://neuronaldynamics.epfl.ch)
- Dirac Delta Function: [Wikipedia Article](https://en.wikipedia.org/wiki/Dirac_delta_function)

