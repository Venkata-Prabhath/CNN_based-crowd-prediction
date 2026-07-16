Slide 1: Title
Explainable AI-Based Crowd Risk Prediction Using CCTV Surveillance

Presented by:

Name : Venkata Prabhath 
Reg No : 23BDS0168
Department : SCOPE
College Name : VIT vellore

Slide 2: Problem Statement
Problem Statement

Large public places such as railway stations, airports, stadiums, shopping malls, and festivals often experience overcrowding. Manual monitoring of CCTV cameras is difficult and may lead to delayed responses during emergencies.

The proposed system aims to automatically analyze CCTV footage, estimate crowd density, predict crowd risk levels, and provide explainable results using Artificial Intelligence.

Slide 3: Objectives
Objectives
Detect crowds from CCTV images or videos.
Estimate crowd density and crowd count.
Predict crowd risk levels.
Classify risk into:
🟢 Green – Safe
🟠 Orange – Moderate Risk
🔴 Red – High Risk
Provide explanations for AI predictions using Explainable AI techniques.
Slide 4: Proposed Methodology
Proposed Workflow
CCTV Image / Video
        ↓
Image Preprocessing
        ↓
CNN-Based Feature Extraction
        ↓
Crowd Detection
        ↓
Crowd Counting
        ↓
Risk Prediction
        ↓
Explainable AI
 (Grad-CAM, LIME, SHAP)
        ↓
Risk Level Display
(Green / Orange / Red)

Mention:

The system processes CCTV footage, detects people, estimates crowd density, predicts the level of risk, and highlights the regions responsible for the prediction.

Slide 5: Technologies
Technologies

Programming Language

Python

Development Platform

Google Colab
Jupyter Notebook

Libraries

TensorFlow
PyTorch (optional)
OpenCV
NumPy
Pandas
Matplotlib

Explainable AI

Grad-CAM
LIME
SHAP

Dataset

Kaggle Crowd Counting Dataset
CCTV Crowd Dataset
Slide 6: Expected Output
Expected Results

Input:

CCTV Image or Video

Output:

Crowd Count
Crowd Density
Risk Prediction

Risk Levels:

🟢 Green → Safe Crowd

🟠 Orange → Moderate Crowd

🔴 Red → High Crowd Risk

Explainable AI Output:

Heatmaps highlighting important regions.
Visual explanation of why the model predicted the risk level.
Slide 7: Future Scope
Future Improvements
Real-time CCTV monitoring.
Integration with Smart City surveillance.
Early warning system for crowd disasters.
Emergency alert generation.
Deployment on edge devices for faster prediction.
Slide 8: Conclusion
Conclusion

This project proposes an Explainable AI-based crowd risk prediction system that combines crowd detection, crowd counting, and CNN-based classification with Explainable AI techniques such as Grad-CAM, LIME, and SHAP.

The system aims to improve surveillance by providing accurate risk prediction along with transparent explanations, helping authorities make informed decisions during crowded situations.

"What is the novelty?"


Existing systems often predict crowd density but do not clearly explain why a particular risk level was assigned. Our proposed work integrates Explainable AI techniques with CNN-based crowd analysis to provide visual explanations, making the predictions more transparent and reliable. We also plan to explore improvements in CNN feature extraction to enhance prediction accuracy.
