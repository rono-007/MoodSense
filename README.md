<!-- README.md for MoodSense -->

<h1 align="center">🎧 MoodSense: Emotion-Based Music Recommender 🎵</h1>
<img src="https://socialify.git.ci/rono-007/MoodSense/image?custom_description=&description=1&font=Rokkitt&language=1&name=1&owner=1&pattern=Circuit+Board&theme=Light" >


<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue?logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Streamlit-WebApp-orange?logo=streamlit">
  <img src="https://img.shields.io/badge/OpenCV-Face%20Detection-green?logo=opencv">
</p>

<p align="center">
  <em>A real-time emotion recognition and music recommendation system built with deep learning and computer vision.</em>
</p>

---

## 🚀 Features

<ul>
  <li>🎥 <strong>Webcam-based Facial Emotion Detection</strong> using OpenCV</li>
  <li>🧠 <strong>Deep Learning Model</strong> to classify emotions like Happy, Sad, Angry, Neutral, etc.</li>
  <li>🎶 <strong>Music Recommendation</strong> tailored to the detected emotion</li>
  <li>🖥️ <strong>Streamlit Web Interface</strong> – Simple, clean, and interactive</li>
</ul>

---

## 📸 Emotion Categories

<div align="center">
  <code>😊 Happy</code> &nbsp; | &nbsp;
  <code>😔 Sad</code> &nbsp; | &nbsp;
  <code>😡 Angry</code> &nbsp; | &nbsp;
  <code>😐 Neutral</code>
</div>

---

## 📂 Project Structure

```plaintext
MoodSense/
├── app.py                  # Main Streamlit app
├── emotion_model.h5       # Trained deep learning model
├── music/                 # Music files categorized by emotion
├── utils/                 # Helper functions
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation 
```
## 📦 Download Dependencies

To install all required Python packages for this project, you can download the `requirements.txt` file and run:

```bash
pip install -r requirements.txt
```
## 🛠️ Installation Guide

<ol>
  <li><strong>Clone the Repository</strong><br>
  First, clone the repository to your local machine:
  <pre><code>git clone https://github.com/rono-007/MoodSense.git
cd MoodSense</code></pre>
  </li>

  <li><strong>Create a Virtual Environment (optional but recommended)</strong><br>
  Set up and activate a virtual environment:
  <pre><code>python -m venv venv
venv\Scripts\activate   # On Windows
source venv/bin/activate   # On Mac/Linux</code></pre>
  </li>

  <li><strong>Install Required Dependencies</strong><br>
  Use the provided <code>requirements.txt</code> file to install all necessary packages:
  <pre><code>pip install -r requirements.txt</code></pre>
  </li>

  <li><strong>Run the Application</strong><br>
  Launch the Streamlit app:
  <pre><code>streamlit run app.py</code></pre>
  This will open the app in your default web browser.
  </li>
</ol>

👨‍💻 Author
<p align="center"> <strong>Ronojoy Nag</strong><br> <a href="https://github.com/rono-007">GitHub</a> | <a href="https://www.linkedin.com/in/Ranajoy-Nag">LinkedIn</a> </p> ```
