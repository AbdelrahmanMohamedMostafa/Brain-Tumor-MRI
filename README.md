# Brain-Tumor-MRI
# 🧠 MRI Tumor Detection System

A deep learning–based web application for detecting brain tumors from MRI images.
The system classifies MRI scans into four categories and displays the prediction result with a confidence score using a trained CNN model and a Flask web interface.

---

## 📌 Features
- Upload MRI images through a web interface
- Automatic tumor classification using a trained deep learning model
- Supports multiclass classification:
  - Glioma
  - Meningioma
  - Pituitary Tumor
  - No Tumor
- Displays prediction confidence
- Shows the uploaded MRI image with the result
- Simple and clean UI using Bootstrap

---

## 🧠 Model Details
- Model Type: Convolutional Neural Network (CNN)
- Framework: TensorFlow / Keras
- Input Size: 128 × 128 RGB images
- Output: Softmax probabilities for 4 classes

---

## 🛠️ Technologies Used
- Python
- Flask (Backend)
- TensorFlow / Keras (Deep Learning)
- NumPy
- HTML + Bootstrap (Frontend)

---

## 📁 Project Structure
Brain-Tumor-MRI/
├── src/                        
│   ├── data/                  
│   ├── models/               
│   │   └── model.h5            
│   ├── notebooks/              
│   │   └── notebook.ipynb
│   ├── templates/              
│   │   └── index.html         
│   ├── uploads/                
│   ├── .gitignore              
│   ├── main.py                 
│   └── requirement.txt        
├── venv/                      
├── .gitignore                  
└── README.md                   


---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/AbdelrahmanMohamedMostafa/Brain-Tumor-MRI.git
cd Brain-Tumor-MRI


### 2️⃣ Create a virtual environment
python -m venv venv

### 3️⃣ Activate the virtual environment
venv\Scripts\activate

### 4️⃣ Install dependencies
pip install -r requirements.txt

### ▶️ Run the Application
python main.py

Then open your browser and go to:
http://127.0.0.1:5000/

📸 How It Works

User uploads an MRI image
Image is preprocessed and normalized
CNN model predicts the tumor type
Result and confidence score are displayed
Uploaded image is shown on the page


👤 Author
Abdelrahman Mohamed