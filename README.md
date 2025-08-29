# Handwritten Digit Recognition using Deep Learning (MNIST)

## 📌 Project Overview
This project implements a **Convolutional Neural Network (CNN)** to classify handwritten digits (0–9) from the **MNIST dataset** using **TensorFlow/Keras**.  
The model achieves high accuracy and demonstrates the effectiveness of deep learning in computer vision tasks.

---

## 🚀 Features
- Preprocessing and normalization of handwritten digit images  
- Convolutional Neural Network (CNN) built using TensorFlow/Keras  
- Visualization of training samples and performance graphs  
- Model evaluation with high test accuracy (≈ 98–99%)  
- Ready for deployment with simple integration into web apps (e.g., Streamlit/Flask)  

---

## 📂 Dataset
- **MNIST Dataset**: 70,000 grayscale images of handwritten digits (28x28 pixels)  
  - Training set: 60,000 images  
  - Test set: 10,000 images  

---

## 🔧 Tech Stack
- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  

---

## 📊 Workflow
1. Load MNIST dataset  
2. Preprocess images (reshape + normalize)  
3. Visualize sample digits  
4. Define CNN architecture  
5. Train the model on training data  
6. Evaluate accuracy & visualize results  

![Workflow](https://i.ibb.co/fSRTZMn/deep-learning-workflow.png)

---

## 🧠 Model Architecture
- Convolutional Layers  
- MaxPooling Layers  
- Flatten Layer  
- Dense Fully Connected Layers  
- Softmax Output Layer  

---

## 📈 Results
- Achieved test accuracy: **~98–99%**  
- Loss and accuracy curves show good convergence  
- Model generalizes well on unseen handwritten digits  

---

## ▶️ How to Run
1. Clone this repository  
   ```bash
   git clone https://github.com/your-username/HandWritten_Digit_Recognizer.git
   ```
2. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook or Python script  
   ```bash
   jupyter notebook HandWritten_Digit_Recognizer.ipynb
   ```

---

## 📌 Future Improvements
- Deploy using Streamlit/Flask for real-time digit prediction  
- Experiment with deeper CNN or transfer learning  
- Integrate with mobile apps for handwriting recognition  

---

## 📜 License
This project is licensed under the MIT License.

---
