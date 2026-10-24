# Signals and Systems MATLAB Project

## Overview
This repository contains the MATLAB scripts, workspace data, and the final analytical report for our Signals and Systems course project[cite: 1, 12]. The project focuses on bridging analytical signal theory with computational implementation using MATLAB, covering topics like frequency spectrums, bandwidth efficiency, and Fourier series.

## Authors
* **Samer Fouad Magdy** 
* **Mohamed Walid**

## Key Concepts Explored
* **Spectrum Analysis & Exponential Smoothing:** Analyzing how shifted exponential signals introduce phase shifts and smooth the spectrum by reducing high-frequency components[cite: 7].
* **Bandwidth Efficiency:** Comparing the bandwidth efficiency of different signals and observing the effects of time-domain truncation (e.g., sinc side lobes)[cite: 7].
* **Fourier Series:** Calculating and plotting Fourier series coefficients ($D_n$) and average signal values[cite: 6].
* **Signal Generation:** Creating piecewise functions and manipulating amplitudes, frequencies, and breakpoints[cite: 11].

## Repository Contents
* `Q1.m` & `Q1.mat`: Script and workspace data for generating signal energy, spectrum analysis, and plotting[cite: 8].
* `Q2Marlab.m` & `Q2Marlab.mat`: Script and data focusing on rectangular pulses, carrier signals, and bandwidth efficiency comparisons[cite: 9].
* `Q3Matlab.m` & `Q3Matlab.mat`: Script and data for calculating Fourier series coefficients and signal reconstruction[cite: 10].
* `part2.m` & `part2.mat`: Script and data for generating signals based on specific breakpoints and slopes[cite: 11].
* `Signals And Systems Project.pdf`: The complete analytical report containing step-by-step theoretical solutions and the corresponding MATLAB figures[cite: 1, 2, 3, 4, 5, 6].

## How to Run
1. Clone the repository to your local machine.
2. Open MATLAB and navigate to the repository folder.
3. Ensure the `.mat` data files are in the same directory as the `.m` scripts, as the scripts rely on loading these variables[cite: 8, 9, 10, 11].
4. Run the individual scripts (`Q1.m`, `Q2Marlab.m`, etc.) to generate the figures shown in the PDF report.
