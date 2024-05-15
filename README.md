# GPvesseltracking
Tracking and diameter estimation of blood vessels using Gaussian process and Radon transform

This script aims to monitor the center points and diameters of blood vessels, a continuous challenge in medical image analysis. Our hypothesis suggests that the curvature and diameter of blood vessels follow Gaussian processes (GPs). We employ the Local Radon transform, known for its noise resilience, to extract features and train the GPs. By understanding the kernelized covariance matrix through training data, we estimate the vessel direction and diameter. To identify bifurcations, we utilize multiple GPs and quantify the variance between their predicted directions.
