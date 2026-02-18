# 🩸 HematoVision - Advanced Blood Cell Classification Using Transfer Learning

HematoVision aims to develop an accurate and efficient model for classifying blood cells by employing transfer learning techniques. Utilizing the "Blood Cell Images" dataset from Kaggle containing 12,000 annotated blood cell images, categorized into distinct classes such as eosinophils, lymphocytes, monocytes, and neutrophils, the project leverages pre-trained convolutional neural networks (CNNs) to expedite training and improve classification accuracy. Transfer learning allows the model to benefit from pre-existing knowledge of image features, significantly enhancing its performance and reducing computational costs. This approach provides a reliable and scalable tool for pathologists and healthcare professionals, ensuring precise and efficient blood cell classification.

## 🔧 Features
- Classifies 4 types of white blood cells: Eosinophils, Lymphocytes, Monocytes, Neutrophils
- Built with MobileNetV2 and Flask using transfer learning
- Interactive web interface for file upload
- Real-time classification with detailed reports
- Educational mode for medical training
- Confusion matrix and evaluation metrics included

## 📊 Dataset
The project utilizes the "Blood Cell Images" dataset from Kaggle, containing 12,000 annotated blood cell images categorized into four classes:
- Eosinophils
- Lymphocytes  
- Monocytes
- Neutrophils

**Dataset Source:** [Kaggle - Blood Cell Images](https://www.kaggle.com/datasets/paultimothymooney/blood-cells)

The dataset is preprocessed and stored in the `Trained Data/dataset/` folder for model training and validation.

## 📋 Scenarios
### Scenario 1: Automated Diagnostic Systems for Healthcare
Integrating HematoVision into automated diagnostic systems in clinical settings can revolutionize blood analysis. By using transfer learning, the system quickly adapts to the specifics of blood cell classification, capturing images of blood samples, classifying the cells in real-time, and generating detailed reports. This automation reduces the manual workload on pathologists, speeds up diagnostic processes, and ensures high accuracy in results, ultimately improving patient care and treatment efficiency.

### Scenario 2: Remote Medical Consultations
HematoVision can be employed in telemedicine platforms to enhance remote consultations and diagnostics. With transfer learning, the model's ability to accurately classify blood cells from diverse sources is improved, allowing healthcare providers to upload blood cell images for automated analysis. This enables timely and accurate assessments without the need for in-person visits, facilitating better access to specialized medical expertise and improving healthcare delivery in remote or underserved areas.

### Scenario 3: Educational Tools for Medical Training
HematoVision's transfer learning-based classification model can be integrated into educational tools for medical training. By incorporating this advanced technology into interactive learning platforms, students and laboratory technicians can upload and analyze blood cell images to receive instant feedback. This hands-on learning experience enhances their understanding of blood cell morphology and classification, providing practical skills and knowledge that are crucial for accurate diagnostic practice and medical training.

## 🗂️ Folder Structure
- `Backend Code(Flask)/`: Contains Flask API and server logic
- `Frontend(templates)/`: HTML templates (home & result page)
- `Model Training/`: Model building, training notebook and saved `.h5` model
- `Results/`: Evaluation results and metrics
- `Trained Data/`: Processed dataset
- `Document/`: Comprehensive project documentation (Ideation to Demonstration)
- `Video demo/`: Demonstration videos

## 📖 Documentation
Detailed documentation is available in the `Document/` folder:
- [1_Ideation_Phase.md](Document/1_Ideation_Phase.md)
- [2_Requirement_Analysis.md](Document/2_Requirement_Analysis.md)
- [3_Project_Design_Phase.md](Document/3_Project_Design_Phase.md)
- [4_Project_Planning_Phase.md](Document/4_Project_Planning_Phase.md)
- [5_Project_Development_Phase.md](Document/5_Project_Development_Phase.md)
- [6_Project_Documentation.md](Document/6_Project_Documentation.md)
- [7_Project_Demonstration.md](Document/7_Project_Demonstration.md)

## ✅ Requirements
- Python 3.8+
- TensorFlow, Flask, OpenCV, NumPy, Matplotlib, Pillow

## 🚀 Run the App
```bash
cd "Backend Code(Flask)"
python app.py
```
Open your browser to `http://localhost:5000` to access the application.

## 📊 Model Performance
- Accuracy: 96%
- Precision/Recall: High across all classes
- Training Time: Reduced due to transfer learning

## 🤝 Contributing
Feel free to contribute by improving the model, adding features, or enhancing documentation.
