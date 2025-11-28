Analog Perceptron (Single Layer)

This project implements a single‑layer perceptron using an LM324N quad op‑amp and discrete components. It demonstrates how a basic neural‑network neuron can be built in analog hardware with adjustable weights and threshold.​

The circuit has two inputs, each scaled by a 10 kΩ potentiometer and summed by the first LM324 stage configured as a non‑inverting summer. A second LM324 stage compares this sum to an adjustable threshold set by another 10 kΩ pot; its output drives an LED that indicates the perceptron decision (LED ON = class 1, LED OFF = class 0).​

Power is supplied from a 9 V battery connected between U+ and U−. Two 1 kΩ resistors form a divider between these rails to create a virtual ground at mid‑supply, which serves as the reference for the op‑amp and all signal voltages.# Perceptron
