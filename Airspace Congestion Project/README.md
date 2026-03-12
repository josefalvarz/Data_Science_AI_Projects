# Airspace Congestion Prediction in German Airspace

This project analyzes aircraft trajectory data from the OpenSky Network to study potential congestion in German airspace.

The data is aggregated into spatial grid cells (0.5° × 0.5°).

## Steps in the Project

1. Data preprocessing and filtering for German airspace
2. Spatial grid creation
3. Aircraft density calculation per grid cell
4. Congestion labeling based on aircraft count threshold
5. Logistic regression model
6. Visualization of air traffic density

## Key Insight

Air traffic density is highest in central Germany, particularly around the Frankfurt region, which is one of the busiest aviation hubs in Europe.

## Tools Used

Python
Pandas
NumPy
Scikit-learn
Matplotlib