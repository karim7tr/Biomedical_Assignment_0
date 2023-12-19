# Biomedical Robotics - Data Analysis Assignment 0

## Introduction
Welcome to the Biomedical Robotics Data Analysis Assignment 0. This assignment is designed to help you become familiar with biological data and refresh essential skills, such as generating informative plots and interpreting data. The provided Matlab code loads three datasets (data1.mat, data2.mat, and data3.mat), plots the data in the time domain, and computes the single-sided frequency domain for each dataset.

## Team Members
- Karim Triki (s5528602)
- Roumaissa Benkredda (s5434673)
- Ines Haouala (s5483776)

## Instructions
1. **Load the datasets**: The Matlab code loads data from three different datasets: data1.mat, data2.mat, and data3.mat.

2. **Plot each dataset**: The code generates plots for each dataset in the time domain with appropriate labels on the axes.

3. **Frequency domain analysis**: The code computes and plots the single-sided frequency domain for each dataset, allowing you to estimate the frequency content of the signals.

4. **Determine data type**: Based on the plots and frequency domain analysis, try to determine the type of data you are observing: EEG, EMG, or motion data.

## Frequency Content Estimation
For a more accurate estimation of frequency content, the code suggests adjusting the x-axis limits to visualize the relevant frequency range.

```matlab
% Adjusting x-axis limits for better frequency visualization
xlim([0, 100]);  % Modify as needed
```

## Getting Started
1. Clone this repository to your local machine.
   ```bash
   git clone https://github.com/karim7tr/BiomedicalRobotics_Assignment0.git
   ```

2. Navigate to the project directory.
   ```bash
   cd BiomedicalRobotics_Assignment0
   ```

3. Place the provided datasets (data1.mat, data2.mat, data3.mat) in the project folder.

4. Open and run the Matlab code to analyze and plot the data.

5. Adjust x-axis limits for better frequency visualization if needed.
