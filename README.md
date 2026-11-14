# Intelligent Equipment Fault Detection System

### Signals and Systems (SSN) Project

An Arduino-based intelligent equipment fault detection prototype developed using Tinkercad Circuits.

## Project Overview

This project demonstrates how digital signal processing can be applied to industrial equipment condition monitoring and early fault detection.

The system generates simulated motor vibration signals, applies a second-order Butterworth low-pass filter, and performs Fast Fourier Transform (FFT) analysis to extract important signal characteristics.

Based on predefined thresholds, the system classifies equipment conditions into:

- Normal Operation
- Motor Imbalance
- Bearing Fault

## Hardware Components

- Arduino Uno R3
- 16×2 LCD
- DC Motor
- TIP120 Transistor
- Flyback Diode
- 4 Potentiometers (10 kΩ)
- 3 LEDs (Green, Yellow, Red)
- Piezo Buzzer
- Resistors and Breadboard
- Motor Battery Supply

## Signal Processing Techniques

1. Simulated vibration signal generation
2. Discrete-time signal sampling
3. Second-order Butterworth low-pass filtering
4. 64-point Fast Fourier Transform (FFT)
5. RMS and peak amplitude extraction
6. Dominant frequency analysis
7. Bearing-frequency-band energy analysis
8. Threshold-based fault classification

## System Operation

| Condition | Indicator | Buzzer |
|---|---|---|
| Normal | Green LED | OFF |
| Motor Imbalance | Yellow LED | OFF |
| Bearing Fault | Red LED | ON |

The LCD displays equipment condition, RMS amplitude, and dominant frequency.

## Potentiometer Functions

| Potentiometer | Function |
|---|---|
| 1 | LCD Contrast |
| 2 | Vibration Amplitude |
| 3 | Bearing Fault Intensity |
| 4 | Motor Frequency |

## Simulation Platform

Tinkercad Circuits with Arduino Uno.

## Limitations

The vibration signals are generated in software and controlled using potentiometers. The DC motor demonstrates equipment operation but is not connected to a physical vibration sensor. The fault thresholds are illustrative and are not calibrated for real industrial machinery.

## Applications

- Industrial equipment condition monitoring
- Predictive maintenance demonstrations
- Motor vibration analysis
- Digital signal processing education

## Future Scope

- Integration of a physical accelerometer
- Real-time vibration acquisition
- Advanced fault classification
- IoT-based monitoring dashboard

  
## Tinkercad Simulation

https://www.tinkercad.com/things/gun7Fa496qI-intelligent-equipment-fault-detection-system
