# MOOD_BASED_MUSIC_RECOMMENDER
Mood based music recommender based on emotion detection using opencv

✅ Real-Time Emotion-Based Music Recommender

🎯 Key Modifications

To make the project easier, more accurate, and usable:

✔ Use DeepFace for emotion detection

It’s far more accurate than training your own CNN and works in real-time.

✔ Use local music folders instead of Spotify API

(You can add Spotify later if you want.)

✔ Build a simple UI with Streamlit (optional)

But basic version works in terminal.

✔ Clean code structure

emotion_detector.py

music_player.py

main.py



---

🚀 Implementation (Beginner Friendly Version)

Below is a complete working Python code (single file version).
You only need:

pip install opencv-python deepface pygame


---

📌 STEP 1: Create Mood-wise Music Folders

Inside your project folder create directories:

music/
 ├── happy/
 ├── sad/
 ├── angry/
 ├── neutral/

Put 2–3 MP3 songs in each.
---

📌 STEP 2: Full Working Code

#CODE

🎯 How It Works

1️⃣ Webcam opens → you press Q to capture

2️⃣ DeepFace predicts emotion → prints it

3️⃣ Pygame plays a random song based on mood


---

💡 Optional Add-Ons to Improve the Project

Choose any of these — easy extensions:

🌟 1. Show emotion on screen (emoji overlay)

🌟 2. Add GUI using Streamlit (“Capture Emotion” button)

🌟 3. Control music (next/pause/volume)

🌟 4. Add Spotify API support

🌟 5. Save daily mood history + mood analytics graph


---


