# Code Availability
Shi et al. Nature Chemical Engineering 2023
Introduction
This README file provides crucial information regarding the system requirements and dependencies needed to run Python scripts used for epicardial recordings analysis from Intantech files.

System Requirements
To effectively run the provided Python scripts, you will need the following:

A computer system running a Python-supported operating system (Windows, MacOS, Linux etc.)
Python version 3.9.16 installed on your system.
Dependencies
The scripts make use of several Python packages for data analysis and visualization. Please ensure you have the following packages installed with the corresponding version numbers:

For Epicardial Recordings:
Scipy version 1.10.0
Numpy version 1.23.5
Matplotlib version 3.7.0
Pandas version 1.5.3
Installation
Ensure you have Python 3.9.16 installed on your system. If not, you can download it from the official Python website.

To install the required packages, you can use pip, Python's package installer. Open your system's command prompt or terminal and run the following commands:
pip install numpy==1.23.5
pip install matplotlib==3.7.0
pip install scipy==1.10.0
pip install pandas==1.5.3

The typical installation time is within 2 hr.

Expected output:
Example ECG analysis code.ipynb: It reads the recorded multichannel signals from Intantech rhd file. It allows the plotting of multichannel data and analysis of the peaks. It helps generating a isochrone map. It works well for clean and typical ECG waveforms. However, manual adjustment of the scripts may be required in certain cases when the signals become messy and complicated. 

The typical run time should be within 1 min unless customized manipulation is needed.
