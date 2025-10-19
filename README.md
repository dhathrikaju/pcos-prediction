PCOS Prediction Web App  
A machine learning web app that predicts the likelihood of Polycystic Ovary Syndrome (PCOS) based on user-input health parameters. Built using Streamlit, powered by a Support Vector Classifier (SVC) model, and deployed for public use.

🚀 Live Demo
🔗 [Click to try]


 Features
Real-time PCOS prediction based on health metrics
User-friendly web interface using Streamlit
Built-in visual feedback for better understanding
Hosted online for accessible use

Tech Stack
Frontend & Deployment: Streamlit
Machine Learning: Scikit-learn (SVC)
Data Handling: Pandas, NumPy
Visualization: Matplotlib
Deployment: Streamlit Cloud


Dataset
Source:  Kaggle PCOS Dataset
Features: BMI, insulin, hormone levels, cycle length, etc.
Label: PCOS diagnosis (yes/no)

How It Works
User inputs health data (BMI, insulin, FSH, LH, etc.)
Input is passed to a trained SVC model
The model outputs a prediction score
Streamlit displays the result with helpful visuals

Model Performance
The Support Vector Classifier (SVC) achieved:
Training Accuracy: 90.95%
Test Accuracy: 96.29%


Run Locally
cd pcospredictionwebapp
pip install -r requirements.txt
streamlit run pcospredict.py  

Future Enhancements
Add classification models (e.g., Random Forest, Decision Tree)
Upload patient history from Excel/CSV
Downloadable prediction report
Secure login for doctor/admin view





