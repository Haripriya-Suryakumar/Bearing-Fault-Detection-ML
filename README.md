# Bearing Fault Detection using Machine Learning (CWRU Dataset)

This project performs bearing fault classification using Machine Learning techniques on the Case Western Reserve University (CWRU) vibration dataset.

## Features Used
- Mean  
- Std (Standard Deviation)  
- RMS  
- Min, Max, Peak-to-Peak  
- Skewness  
- Kurtosis  
- Crest Factor  
- Energy  

## Pipeline
1. Load raw `.mat` vibration signals  
2. Slice into windows  
3. Extract statistical features  
4. Build ML dataset  
5. Train Random Forest Classifier  
6. Evaluate and generate EDA plots  

## Accuracy
Random Forest Classifier achieved: ~ 96% 
