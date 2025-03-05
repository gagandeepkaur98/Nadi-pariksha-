PulseVision: AI-Driven Nadi Pariksha for Ayurvedic Health Diagnosis
Overview
PulseVision is an AI-powered system designed to modernize and automate the traditional Nadi Pariksha diagnostic process in Ayurvedic medicine. This project leverages machine learning techniques to analyze pulse-derived diagnostic attributes, enabling accurate, scalable, and objective health assessments. By integrating computational intelligence into Ayurveda, PulseVision bridges the gap between ancient wisdom and modern technology, offering a data-driven approach to personalized medicine.

Key Features
AI-Based Dosha Classification: Identifies the dominant dosha (Vata, Pitta, Kapha, or a mixture) using a Random Forest classifier.
High Accuracy: Achieves 98.47% accuracy with 5-fold cross-validation, ensuring robustness and reliability.
Data Visualization & Interpretability: Implements feature distribution histograms, correlation heatmaps, and class distribution plots to provide insights into feature importance and dosha classification.
Scalable & Objective Diagnosis: Provides a systematic AI-driven approach to enhance Ayurvedic integrative medicine.
Methodology
Data Collection & Preprocessing

A structured dataset containing pulse-derived attributes was compiled.
Features were preprocessed and normalized for optimal machine learning performance.
Model Selection & Training

Implemented a Random Forest classifier for reliable dosha prediction.
Performed 5-fold cross-validation to validate the model’s accuracy and generalizability.
Interpretability & Insights

Visualized key correlations between features and dosha classification.
Used correlation heatmaps, histograms, and class distribution plots to enhance transparency and trust in AI predictions.
Results
The model achieved a 98.47% accuracy, demonstrating strong predictive performance.
The use of visual analytics improved the interpretability of Ayurvedic diagnostics.
PulseVision provides a potential AI-assisted tool for Ayurvedic practitioners, enabling a data-driven and evidence-based approach to diagnosis.
Potential Applications
Ayurvedic Health Diagnosis: Assists Ayurvedic practitioners in dosha identification based on pulse readings.
Personalized Medicine: Enables tailored Ayurvedic treatments using AI-driven insights.
Scalable Healthcare Solutions: Offers a cost-effective, AI-enhanced diagnostic tool that can be integrated into telemedicine and mobile health applications.
Installation & Usage
Prerequisites
Ensure you have the following installed:

Python (≥3.8)
Jupyter Notebook (optional, for visualization)
Required libraries: pandas, numpy, scikit-learn, matplotlib, seaborn
Setup
Clone the repository:

sh
Copy
Edit
git clone https://github.com/your-username/PulseVision.git
cd PulseVision
Install dependencies:

sh
Copy
Edit
pip install -r requirements.txt
Run the model:

sh
Copy
Edit
python pulsevision_model.py
Future Enhancements
Integration with deep learning models (CNNs, LSTMs) for improved accuracy.
Deployment as a web or mobile application for wider accessibility.
Incorporation of real-time pulse sensing devices for live diagnostics.
Contributors
[GAGANDEEP KAUR]-AI & ML Researcher
[JUSTINA J]-AI & ML Researcher
[NANDANI AGRAWAL]– AI & ML Researcher
Collaborators (if any)
License
This project is licensed under the MIT License – feel free to use and modify it!

