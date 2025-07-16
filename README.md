# 😷 Face Mask Classifier

[![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)](https://www.python.org/)
[![Deep Learning](https://img.shields.io/badge/Deep%20Learning-CNN-green)]()
[![Flask](https://img.shields.io/badge/Flask-API-lightgrey?logo=flask)](https://flask.palletsprojects.com/)
[![License](https://img.shields.io/badge/License-MIT-purple.svg)](LICENSE)

A Deep Learning-powered web application that detects whether a person is wearing a face mask or not from uploaded images. Built with TensorFlow and Keras, and deployed using Flask.

---

## 📌 Project Highlights

- 🧠 Built a CNN model using TensorFlow/Keras to classify images as *With Mask* or *Without Mask*  
- 🖼️ Preprocessed over 7,500 images: resized, normalized, and converted them to RGB  
- ✂️ Split dataset into training and testing sets to optimize generalization  
- 📈 Achieved **92.46%** accuracy on test data  
- 📊 Visualized training/validation performance using loss and accuracy curves  
- 🌐 Deployed the model using Flask with a user-friendly interface for real-time image classification  

---

## 🔧 Tech Stack

- **Language:** Python  
- **Libraries:** TensorFlow, Keras, OpenCV, NumPy, Matplotlib  
- **Modeling:** Convolutional Neural Network (CNN)  
- **Deployment:** Flask (Web API)  
- **Tools:** Jupyter Notebook, Google Colab, VS Code  

---

## 📁 Folder Structure

`face-mask-classification/` →  
`├── static/uploads/` – Uploaded images directory  
`├── templates/` – HTML templates for Flask frontend  
`├── model/` – Trained CNN model file (`mask_detector.model`)  
`├── app.py` – Flask backend for image prediction  
`├── mask_classifier.ipynb` – Model training & evaluation notebook  
`├── requirements.txt` – Project dependencies  
`├── .gitignore` – Ignored files  
`├── LICENSE` – License file  
`└── README.md` – You're here!

---

## 🚀 Run the Project Locally

```bash
# 1. Clone the repository
git clone https://github.com/ayush4628/face-mask-classification.git
cd face-mask-classification
```

# 2. Set up virtual environment (optional)
```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

# 3. Install dependencies
```bash
pip install -r requirements.txt
```

# 4. Run the Flask app
```bash
python app.py
```

# 5. Open in browser
Visit: http://localhost:5000/  
Upload an image to check if the person is wearing a mask.

## 🧪 Sample Input
Upload an image file (JPEG/PNG) of a person’s face through the web interface.  

## ✅ Sample Output
- With Mask  
- Without Mask  

The app displays the predicted category directly on the webpage after uploading the image.  

## 📓 Notebook Insights
- Explore the Jupyter notebook mask_classifier.ipynb for:  
- Data preprocessing and augmentation  
- CNN model creation and tuning  
- Accuracy and loss graph plotting  
- Model saving and loading

## 🌟 Future Improvements
📹 Add support for real-time webcam detection  
📦 Package model as a REST API or Docker container  
📱 Build a mobile-friendly frontend with Streamlit or React  
🧠 Improve model robustness using data augmentation  

## 📜 License
This project is licensed under the [MIT License](LICENSE). See the LICENSE file for details.  

## 🙏 Acknowledgments
- Kaggle & Open Source Face Mask Datasets  
- TensorFlow and Keras Documentation  
- Flask Community

## 📬 Contact
📧 Email: [kushwahasatak@gmail.com](mailto:kushwahasatak@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/ayush4628)
