🛡️ Face Mask & Social Distancing Detection
📌 Overview
This is a real-time Face Mask Detection & Social Distancing Monitoring system that uses Deep Learning and OpenCV to identify whether people are wearing masks and maintaining a safe distance. It provides visual alerts and audio warnings to ensure compliance with COVID-19 safety guidelines.

⚡ Features
✅ Real-Time Face Mask Detection – Detects whether a person is wearing a mask.
✅ Social Distancing Monitoring – Measures the distance between people and flags violations.
✅ Sound Alert for No Mask 🚨 – Plays an alarm if a person without a mask is detected.
✅ Custom Visual Alerts 🎨 –

Green Bounding Box 🟩 – If a mask is worn.
Red Bounding Box 🟥 – If no mask is worn.
Yellow Highlight for Social Distancing Violation 🟨.
✅ Multiple Face Detection – Works even when multiple people are in the frame.
✅ Live Camera Feed – Works in real-time using a webcam.

🔧 Tech Stack
Python
OpenCV – For real-time face detection and distance measurement.
TensorFlow/Keras – To train a deep learning model for mask classification.
NumPy – For data processing.
Haar Cascade – For detecting faces in the video feed.

📂 Dataset
The dataset consists of images of people with and without masks and is stored in:
📂 data
with_mask/
without_mask/
🚀 How It Works
1️⃣ The camera captures real-time video.
2️⃣ Faces are detected using OpenCV’s Haar Cascade Classifier.
3️⃣ The trained CNN model classifies each face as:

"Mask" ✅
"No Mask" ❌ (Triggers a sound alert)
4️⃣ The system measures the distance between detected faces using Euclidean distance.
5️⃣ If two people are standing too close, the bounding box turns yellow 🟨.
6️⃣ The results are displayed with labels and bounding boxes.
🔹 Press ‘Q’ to exit the program.

📸 Sample Output
Face Mask Detection Example:
🟩 Green – Mask detected
🟥 Red – No Mask (with sound alert)

Social Distancing Detection Example:
🟨 Yellow – Social distancing violation
