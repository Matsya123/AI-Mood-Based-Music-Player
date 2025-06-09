# 🎵 AI-Mood-Based-Music-Player

A smart AI-based music player that detects a user’s facial emotion via webcam in real-time and automatically recommends mood-matching music. It uses YOLOv8 for face detection, a CNN model for emotion recognition (FER-2013), and plays music via Python using a Flask GUI.

---

## 🧠 Features

- Real-time emotion detection (Happy, Sad, Angry, Neutral, Surprise)
- Face detection using YOLOv8 and Haar Cascades
- Emotion prediction using trained FER CNN model
- Auto music recommendation from static folders
- Flask-based web interface with TailwindCSS UI
- Music playback with play/pause/stop support via Pygame

---

## 🛠 Technologies Used

| Technology       | Purpose                              |
|------------------|--------------------------------------|
| Python           | Core language                        |
| OpenCV           | Webcam + face detection              |
| YOLOv8           | Real-time face detection             |
| TensorFlow/Keras | Emotion recognition model            |
| Pygame           | Music playback                       |
| Flask            | Backend web server                   |
| HTML + Tailwind  | UI for displaying emotion + songs    |

---

## 🧪 System Architecture

1. **Webcam** captures face → YOLO detects face.
2. **FER CNN Model** predicts emotion from cropped grayscale face.
3. **Flask Backend** fetches matching song list from emotion dictionary.
4. **Web UI** displays detected emotion and music recommendations.
5. **Pygame** plays the selected audio file.



---



