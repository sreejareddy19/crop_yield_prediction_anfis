# README – Crop Yield Prediction Using ANFIS

## 1. Project Title
**Crop Yield Prediction Using Adaptive Neuro-Fuzzy Inference System (ANFIS)**

## 2. Research Paper Details
- **Paper Title:** Adaptive Neuro-Fuzzy Inference System Based Multicrop Yield Prediction in the Semi-Arid Region of India
- **Authors:** Kalpesh Borse, P. G. Agnihotri, Muralitharan Jothimani, and Romesh Kumar Jena
- **Journal:** Scientific Reports
- **Publication Year:** 2025
- **DOI:** 10.1038/s41598-025-03334-8

## 3. Abstract
This research focuses on predicting the yield of multiple crops using an Adaptive Neuro-Fuzzy Inference System (ANFIS). The model uses climatic factors such as rainfall, minimum temperature, maximum temperature, relative humidity, and evaporation to estimate crop yield. The study was conducted in the semi-arid Nashik region of Maharashtra, India. It demonstrates how combining neural networks and fuzzy logic can help model complex relationships between climate conditions and agricultural production.

## 4. Objectives
- Predict the yield of multiple crops using ANFIS.
- Study the relationship between climatic conditions and crop production.
- Improve agricultural planning through data-driven yield estimation.
- Support farmers and agricultural decision-making.

## 5. Study Area and Crops
**Study Area:** Nashik, Maharashtra, India.

**Crops considered:**
- Rice
- Sorghum
- Maize
- Groundnut
- Sugarcane

## 6. Input Parameters
The model uses five climatic parameters:
1. Average Rainfall
2. Minimum Average Temperature
3. Maximum Average Temperature
4. Relative Humidity
5. Average Evaporation

**Output:** Predicted crop yield.

## 7. Methodology
1. Collect historical climate and crop-yield data.
2. Check the data for outliers.
3. Generate additional samples using statistical distribution methods.
4. Select climatic parameters as ANFIS inputs.
5. Train individual crop-yield prediction models.
6. Use 70% of the data for calibration and 30% for validation.
7. Evaluate model performance using RMSE, nRMSE, NSE, correlation, and R².

## 8. Technology Used
- Adaptive Neuro-Fuzzy Inference System (ANFIS)
- Artificial Intelligence
- Fuzzy Logic
- Neural Networks
- Statistical Data Analysis
- MATLAB

## 9. Results
The research reports that ANFIS can model the relationship between climatic conditions and crop yield. During validation, the sugarcane model achieved a correlation of 0.91 between observed and predicted yield. The study concludes that ANFIS is a promising approach for multi-crop yield prediction in semi-arid regions.

## 10. Limitations
- The study considers climatic parameters but does not include all agricultural factors.
- Soil type, fertilizer use, and irrigation can also affect crop yield.
- The model was developed for the Nashik region, so other regions require suitable local data.
- A larger number of inputs can increase the complexity of the fuzzy rule base.

## 11. Future Scope
- Include soil nutrients and soil type.
- Integrate irrigation and fertilizer information.
- Extend predictions to more crops and geographical regions.
- Develop a farmer-friendly web or mobile application.
- Provide early crop-yield estimates for agricultural planning.

## 12. Research Paper Link
https://www.nature.com/articles/s41598-025-03334-8.pdf

## 13. Conclusion
The study demonstrates the usefulness of ANFIS for predicting the yield of multiple crops using climatic parameters. It combines the learning capability of neural networks with the reasoning ability of fuzzy logic, offering a useful approach for agricultural yield estimation and planning.
