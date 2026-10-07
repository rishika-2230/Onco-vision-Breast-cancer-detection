# 🩺 OncoVision — Breast Cancer Detection Project

<p align="center">
  <b>Deep Learning–Based Breast Cancer Image Classification with an Interactive Streamlit Application</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python">
  <img src="https://img.shields.io/badge/Deep%20Learning-CNN-orange">
  <img src="https://img.shields.io/badge/Model-ResNet50-red">
  <img src="https://img.shields.io/badge/Framework-TensorFlow%20%7C%20Keras-orange">
  <img src="https://img.shields.io/badge/App-Streamlit-red?logo=streamlit">
</p>

---

## 📌 Project Overview

**OncoVision** is a deep-learning-based breast cancer image classification project designed to demonstrate an end-to-end machine learning workflow — from medical image preprocessing and model development to prediction and interactive application deployment.

The project uses a **Convolutional Neural Network (CNN)** architecture with **ResNet50-based transfer learning** to learn visual patterns from breast cancer image data.

A **Streamlit web application** provides a simple interface where an image can be uploaded and processed by the trained model to generate a classification result.

> **Important:** OncoVision is an educational and portfolio project. It is not a medical diagnostic system and should not be used for clinical decision-making.

---

## 🎥 Application Demo

<p align="center">
  <img src="breast_cancer_streamlit_demo.gif" alt="OncoVision Streamlit Breast Cancer Detection Demo" width="850">
</p>

The application workflow is designed to be straightforward:

**Upload Image → Image Preprocessing → CNN/ResNet50 Model → Prediction → Result Display**

---

## 🎯 Project Objective

The objective of this project was to build an end-to-end computer vision pipeline capable of:

- Processing breast cancer image data
- Preparing images for deep-learning-based classification
- Applying CNN-based feature learning
- Using **ResNet50 transfer learning** for image classification
- Generating predictions from unseen input images
- Providing model results through an interactive **Streamlit interface**
- Demonstrating how a trained machine-learning model can be converted into a usable application

---

## 🧠 Machine Learning Approach

### Convolutional Neural Networks

CNNs are particularly suitable for image classification because they can automatically learn spatial and visual features directly from image data.

Rather than manually defining image characteristics, convolutional layers learn increasingly complex representations during training.

### ResNet50

The project incorporates **ResNet50**, a deep residual neural network architecture, as part of the image-classification pipeline.

Transfer learning allows knowledge learned from a large-scale image dataset to be reused for a more specialized classification problem.

This approach helps create a stronger feature extraction pipeline without requiring a deep neural network to be trained entirely from scratch.

---

## 🔄 End-to-End ML Pipeline

```text
Breast Cancer Image Dataset
          │
          ▼
Data Loading & Inspection
          │
          ▼
Image Preprocessing
          │
          ▼
Training / Validation Preparation
          │
          ▼
Data Augmentation
          │
          ▼
CNN + ResNet50 Transfer Learning
          │
          ▼
Model Training
          │
          ▼
Model Evaluation
          │
          ▼
Trained Classification Model
          │
          ▼
Streamlit Application
          │
          ▼
Image Upload
          │
          ▼
Preprocessing & Inference
          │
          ▼
Prediction Result
```

---

## 🛠️ Technology Stack

| Area | Technology |
|---|---|
| Programming | Python |
| Deep Learning | CNN |
| Transfer Learning | ResNet50 |
| ML Framework | TensorFlow / Keras |
| Data Processing | NumPy |
| Image Processing | Python image-processing libraries |
| Model Evaluation | Classification metrics |
| Application | Streamlit |
| Version Control | Git & GitHub |

---

## 🔬 Project Workflow

### 1. Data Preparation

The breast cancer image dataset was loaded and inspected before model development.

The preparation stage focused on organizing the image data into a format suitable for the deep-learning pipeline.

### 2. Image Preprocessing

Images were transformed into a consistent format before being passed to the model.

The preprocessing pipeline prepares raw image input for CNN-based feature extraction and prediction.

### 3. Data Augmentation

Image augmentation was incorporated into the training workflow to introduce variation into the training samples and improve the model's ability to generalize.

### 4. CNN-Based Feature Learning

Convolutional neural networks were used to learn relevant visual patterns from the image data.

CNN layers identify increasingly complex visual representations as information moves deeper through the network.

### 5. ResNet50 Transfer Learning

A **ResNet50-based architecture** was used to leverage pretrained visual feature representations.

Transfer learning enables the project to take advantage of previously learned image features while adapting the model to the breast cancer classification task.

### 6. Model Training

The prepared image data was used to train the classification model.

Training involved learning the relationship between image features and their corresponding target classes.

### 7. Model Evaluation

The trained model was evaluated on data outside the training process to assess its classification behavior and generalization.

### 8. Streamlit Deployment

The trained machine-learning workflow was integrated into a **Streamlit application**, transforming the model from an experimental notebook/model into an interactive application.

---

## 💻 Streamlit Application

The Streamlit interface provides a simple workflow for interacting with the trained model.

### User Flow

1. Open the OncoVision application.
2. Upload a supported breast cancer image.
3. The application preprocesses the image.
4. The processed image is passed to the trained CNN/ResNet50 model.
5. The model generates a classification prediction.
6. The result is displayed through the Streamlit interface.

This demonstrates the complete transition from:

**Data → Model → Prediction → User-facing Application**

---

## 🚀 Running the Project Locally

### 1. Clone the Repository

```bash
git clone https://github.com/rishika-2230/Breast_cancer_project_deployment.git
cd Breast_cancer_project_deployment
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

### 3. Activate the Environment

#### Windows

```bash
venv\Scripts\activate
```

#### macOS / Linux

```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Start the Streamlit Application

```bash
streamlit run app.py
```

> If the Streamlit entry file in your repository has a different name, replace `app.py` with the corresponding filename.

---

## 💡 Business & Practical Value

Although this project is intended for educational and portfolio purposes, it demonstrates several skills that transfer directly to real-world analytics and machine-learning workflows:

- Preparing unstructured image data for analysis
- Developing deep-learning classification pipelines
- Applying transfer learning
- Evaluating machine-learning models
- Connecting trained models with user-facing applications
- Translating technical ML workflows into accessible tools
- Deploying analytical solutions rather than limiting them to notebooks

---

## 📊 Skills Demonstrated

**Machine Learning & AI**
- Deep Learning
- Convolutional Neural Networks
- Transfer Learning
- ResNet50
- Image Classification
- Model Training
- Model Evaluation
- Inference

**Programming & Data**
- Python
- NumPy
- Image preprocessing
- Data preparation

**Application Development**
- Streamlit
- Model integration
- Interactive prediction workflow

**Development**
- Git
- GitHub
- Version control
- Project documentation

---

## 🔮 Future Improvements

Potential extensions to OncoVision include:

- Experimenting with additional CNN architectures
- Comparing ResNet50 against alternative transfer-learning models
- Expanding model evaluation and explainability
- Adding confidence/probability visualization
- Adding Grad-CAM or similar visual explanation techniques
- Improving the Streamlit user interface
- Deploying the application through a persistent cloud environment
- Adding automated model and application testing

---

## ⚠️ Medical Disclaimer

**OncoVision is an educational machine-learning project and is not a medical device.**

The predictions generated by this application must **not** be interpreted as medical diagnoses, treatment recommendations, or substitutes for professional medical evaluation.

Breast cancer diagnosis should only be performed by qualified healthcare professionals using clinically validated diagnostic procedures.

---

## 👩‍💻 Author

**Rishika**

Business/Data Analyst with a non-tech background and a tech-curious mindset, learning and building practical solutions using data, Python, SQL, machine learning and AI.

**GitHub:** [rishika-2230](https://github.com/rishika-2230)

---

<p align="center">
  <b>OncoVision</b><br>
  Turning machine learning models into practical, interactive applications.
</p>
