# **🧠 Dermatologist-Level Skin Cancer Classification using Cascaded Deep Learning**

## **📌 Overview**

This project presents a deep learning–based skin lesion classification system designed to assist dermatologists in early detection of melanoma and other skin cancers.

The system combines:

* 🧠 Convolutional Neural Networks (CNN)  
* 🎨 Handcrafted features (Color Moments \+ Texture)  
* 🔁 Cascaded Ensembling Architecture  
* 📱 MobileNet-based deployment model  
* 🌐 Flask-based Web Interface with SQLite Authentication

The proposed approach improves accuracy from **85.3% (baseline CNN)** to **98.3% (Cascaded Ensemble Model)**.

## **🚀 Key Highlights**

* ✅ Implemented Cascaded CNN \+ Handcrafted Feature Fusion  
* ✅ Compared ML models: SVM, Random Forest, Decision Tree, MLP, Voting Classifier  
* ✅ Applied Transfer Learning using VGG16 & MobileNet  
* ✅ Achieved \~88–90% accuracy using MobileNet in 5 epochs  
* ✅ Developed Flask-based Web Application for real-time prediction  
* ✅ Implemented User Authentication using SQLite  
* ✅ Integrated Azure ML for scalable model training

## **🏗 System Architecture**

The model follows a multi-stage pipeline:

1. Image Preprocessing  
2. CNN-based Feature Extraction  
3. Handcrafted Feature Extraction (Color \+ Texture)  
4. Feature Fusion  
5. Cascaded Classification  
6. Web Deployment via Flask

(Refer to `/documents/Report.pdf` for detailed architecture)

## **🛠 Tech Stack**

### **🔹 Machine Learning**

* TensorFlow / Keras  
* Scikit-Learn  
* Transfer Learning (MobileNet, VGG16)  
* CNN, SVM, Random Forest, MLP

### **🔹 Backend**

* Flask  
* SQLite

### **🔹 Cloud & Deployment**

* Azure ML Compute Instance

## **📊 Model Performance**

| Model | Accuracy |
| ----- | ----- |
| Cascaded CNN (Base Paper) | 85.3% |
| Proposed Ensemble Model | 98.3% |
| MobileNet (Extension) | \~88.42% |

## **📸 Application Screens**

* User Signup  
* User Login  
* Image Upload  
* Prediction Result Display

(Screens available in `/app/templates` folder)

## **🧪 Dataset**

The model was trained using dermoscopic skin lesion images including:

* Melanoma  
* Actinic Keratosis  
* Non-Melanoma Skin Cancer

## **📄 Originality**

Turnitin Similarity Index: **9%**  
(Refer to `/documents/Originality_Report.pdf`)

Skin cancer Prediction 9%

## **⚠ Disclaimer**

This project is for research and educational purposes only. It is not a substitute for professional medical diagnosis.

## **👨‍💻 Author**

Sravani Dantuluri  
Master’s of Professional Studies in Data Science

