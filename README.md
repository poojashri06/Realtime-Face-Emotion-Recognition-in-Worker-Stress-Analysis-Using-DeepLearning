# Realtime-Face-Emotion-Recognition-in-Worker-Stress-Analysis-Using-DeepLearning

😊 Facial Emotion Recognition System

A real-time Facial Emotion Recognition (FER) system built using Convolutional Neural Networks (CNN) and OpenCV, capable of detecting human emotions through webcam input.

🚀 Features

🎯 Detects 7 emotions:

Happy 😄

Sad 😢

Angry 😠

Surprise 😲

Fear 😨

Neutral 😐

Disgust 🤢

📷 Real-time face detection using webcam

🧠 Deep Learning-based emotion classification

⚡ Fast and responsive predictions

💻 Easy to run locally

🛠️ Tech Stack

Python 🐍

TensorFlow / Keras

OpenCV

NumPy

Matplotlib / Seaborn (for evaluation)

📂 Project Structure

FER-Project/
│
├── Face.h5                     # Trained CNN model

├── haarcascade_frontalface_default.xml

├── app.py / main.py            # Real-time detection script

├── train.py                    # Model training code (optional)

├── dataset/                    # Training & testing data

├── emotion_heatmap.png         # Confusion matrix

└── README.md

⚙️ Installation

1️⃣ Clone the repository

git clone https://github.com/your-username/fer-project.git

cd fer-project

2️⃣ Install dependencies

pip install -r requirements.txt

3️⃣ Run the project

python main.py

🧠 Model Details

Architecture: Convolutional Neural Network (CNN)

Input Shape: (96, 96, 3) (RGB images)

Output: 7 emotion classes

Loss Function: Categorical Crossentropy

Optimizer: Adam

📊 Results

The model successfully classifies facial expressions into seven categories:
Happy, Sad, Angry, Surprise, Fear, Neutral, Disgust

Achieves good accuracy on validation data
Performs well in real-time webcam detection
Works best under:
Normal lighting
Frontal face position
⚠️ Limitations
Performance drops in low lighting
Struggles with side faces
Sensitive to occlusions (mask, glasses, etc.)
🔮 Future Improvements
Improve accuracy using transfer learning (VGG16 / ResNet)
Add emotion confidence score
Deploy as a web application (Flask / Streamlit)
Mobile app integration
📸 Demo

(Add screenshots or GIF here)

🧑‍💻 Author

Poojashri K

GitHub: https://github.com/poojashri06

📌 Note

Make sure your webcam is enabled and dependencies are installed correctly before running the project.
