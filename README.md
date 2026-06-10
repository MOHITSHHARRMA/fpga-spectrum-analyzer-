# FPGA Spectrum Analyzer

A real-time FPGA-based Spectrum Analyzer that performs frequency-domain analysis of signals using the Fast Fourier Transform (FFT).

The project combines Digital Signal Processing (DSP), FPGA design, and embedded systems concepts to acquire, process, and visualize signals in the frequency domain.

## Objectives

- Acquire sampled signals using Arduino/Wokwi.
- Implement FFT processing on FPGA using Verilog.
- Calculate frequency spectrum magnitude.
- Visualize spectral components using Python.
- Learn practical DSP and FPGA design workflows.

## Technologies Used

- Verilog HDL
- FPGA Design
- Digital Signal Processing (DSP)
- Fast Fourier Transform (FFT)
- Arduino
- Wokwi
- Python
- NumPy
- Matplotlib
- GTKWave
- Icarus Verilog

## System Architecture

Signal Source
→ Sampling
→ FPGA Buffer
→ FFT Engine
→ Magnitude Calculation
→ Frequency Bins
→ Python Visualization

## Features

- Signal acquisition and sampling
- FFT-based frequency analysis
- Real-time spectrum visualization
- Verilog simulation and testing
- Modular FPGA architecture
- Extensible design for audio and communication signals

## Learning Outcomes

This project demonstrates concepts from:

- Signals and Systems
- Digital Signal Processing
- Digital Electronics
- FPGA Design
- Embedded Systems
- Communication Engineering

## Future Enhancements

- FIR/IIR Filtering
- Audio Spectrum Analysis
- Real-Time Microphone Input
- Web Dashboard
- SDR (Software Defined Radio) Integration
- FPGA Hardware Deployment
