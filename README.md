//data set are from OASIS and ADNI.
.

🔍 Project Overview
The project uses Convolutional Neural Networks (CNN) and Support Vector Machines (SVM) to classify MRI brain images into different Alzheimer’s Disease categories. By combining the power of deep learning for feature extraction with the precision of SVM classification, the model achieves high accuracy in distinguishing between stages of the disease.

🛠 Tech Stack & Tools
Programming Language: Python

Libraries & Frameworks:

TensorFlow / Keras – CNN model building

scikit-learn – SVM classification, metrics evaluation

NumPy – Numerical computation

Pandas – Data manipulation

Matplotlib & Seaborn – Visualization

Dataset: Alzheimer’s MRI image dataset (Kaggle)

📊 Workflow
Data Collection – MRI image dataset from Kaggle.

Data Preprocessing – Resizing images, normalization, data augmentation.

Feature Extraction – CNN used to extract deep features from MRI images.

Classification – Extracted features fed into SVM for classification.

Evaluation – Accuracy, precision, recall, F1-score, and confusion matrix used for performance evaluation.

🧪 Model Details
CNN – Acts as an automatic feature extractor for image data.

SVM – Classifies extracted features into Alzheimer’s stages:

Non-Demented

Very Mild Demented

Mild Demented

Moderate Demented

📈 Results & Insights
Achieved high classification accuracy combining CNN + SVM.

Data augmentation improved generalization on unseen images.

Early-stage detection potential for aiding healthcare systems.

📂 Repository Structure
lua
Copy
Edit
📁 Alzheimer-Disease-Detection
│-- 📄 README.md
│-- 📄 Alzheimer_Detection.ipynb
│-- 📄 dataset/  
│-- 📄 models/  
│-- 📄 requirements.txt
🚀 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/alzheimer-disease-detection.git
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the notebook or script:

bash
Copy
Edit
jupyter notebook Alzheimer_Detection.ipynb
📜 License
This project is licensed under the MIT License – you are free to use and modify it with attribution.
