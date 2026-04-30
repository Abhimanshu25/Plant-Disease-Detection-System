🌱 Plant Disease Detection System

A Deep Learning-based web application that detects plant diseases from leaf images and provides their causes and treatments using AI.

📌 Overview

The Plant Disease Detection System is designed to assist farmers, researchers, and agricultural experts in identifying plant diseases quickly and accurately. By uploading a leaf image, users can get instant predictions along with disease details, helping in timely treatment and improved crop yield.

🚀 Features
🌿 Detects 40+ plant diseases
📷 Upload plant leaf images easily
🧠 Uses CNN (Convolutional Neural Network) model
💊 Provides cause and cure of diseases
🌐 Simple and user-friendly web interface
⚡ Fast and accurate predictions

🛠️ Tech Stack
Technology	Usage
Python	Core programming language
Flask	Backend framework
TensorFlow/Keras	Deep learning model
HTML/CSS	Frontend interface

📂 Project Structure
Plant-Disease-Detection/
│
├── app.py                      # Flask backend
├── models/                    # Trained model (.keras file)
├── plant_disease.json         # Disease info (cause & cure)
├── templates/                 # HTML files
├── uploadimages/              # Uploaded images
├── static/                    # CSS/JS (if any)
└── README.md                  # Project documentation

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/Abhimansu25/plant-disease-detection.git
cd plant-disease-detection
1️⃣ Install Dependencies
pip install -r requirements.txt
2️⃣ Download the Model

Download the pre-trained model from the link below and place it inside the models folder:
👉 https://drive.google.com/file/d/1Ond7UzrNOfdAXWedjlZr2sDXYU6MRBuj/view
Then make sure your app.py contains:

model = tf.keras.models.load_model("models/plant_disease_model_pwp.keras")
3️⃣ Run the Application
python app.py
4️⃣ Open in Browser
http://127.0.0.1:5000/

🧠 How It Works
User uploads a plant leaf image
Image is resized and converted into an array
CNN model processes the image
Model predicts the disease class

System displays:
🌿 Disease Name
🦠 Cause
💊 Cure
🌿 Supported Plants & Diseases

Includes diseases from:
Apple 🍎
Tomato 🍅
Potato 🥔
Corn 🌽
Grape 🍇
Strawberry 🍓
And more...

📸 Sample Output
Disease: Tomato Leaf Mold
Cause: Fungal infection
Cure: Apply fungicides and ensure proper ventilation
ring
Educational AI/ML projects
