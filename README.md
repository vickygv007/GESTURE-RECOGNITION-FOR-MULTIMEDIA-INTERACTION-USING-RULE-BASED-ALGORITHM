# ✋ Gesture Recognition for Multimedia Interaction Using Rule-Based Algorithm

This project is an advanced rule-based gesture recognition system that allows users to control various multimedia and desktop functions using just hand gestures captured through a webcam. Built using Python, OpenCV, and MediaPipe, this project replaces traditional input devices with intuitive, touchless control methods—without the need for complex machine learning models.

---

## 🎯 Features

- ✅ Real-time hand gesture recognition
- 🎚️ Volume control using hand movements
- 💡 Brightness control (via gesture-based system calls)
- 🎮 Virtual drawing / air writing
- 🖱️ Virtual mouse – cursor movement, click, drag
- 📊 PowerPoint presentation control – next/previous slide
- 🖼️ Front-end interface for user interaction and feedback
- 🔄 Gesture-based app switching and multimedia control

---

## 🛠️ Tech Stack

- **Programming Language:** Python
- **Libraries:** OpenCV, MediaPipe, PyAutoGUI, NumPy, Tkinter/PyQt (for front-end)
- **OS:** Windows/Linux (best with Windows for full feature support)
- **IDE:** VS Code / PyCharm

---

## 📂 Folder Structure


---

## 🚀 How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/gesture-recognition-rule-based.git
   cd gesture-recognition-rule-based
pip install -r requirements.txt
python main.py

✋ How It Works
The webcam captures live video input.

Hand gestures are detected using MediaPipe or OpenCV.

Predefined rule-based conditions identify gestures:

✋ Open palm – Play/Pause

✊ Fist – Stop

👉 Swipe right – Next slide

👈 Swipe left – Previous slide

✌️ Two fingers – Activate mouse mode

🖐️ Five fingers – Activate drawing mode

Actions are executed using libraries like PyAutoGUI and OS-level commands.

📦 Requirements
Python 3.7 or above

OpenCV

MediaPipe

NumPy

PyAutoGUI

Tkinter (or PyQt5 for advanced GUI)

ScreenBrightnessControl (for brightness on Windows)

You can install all dependencies via:

bash
Copy code
pip install -r requirements.txt
📌 Use Cases
Touchless multimedia control

Presentations and lectures

Home automation interfaces

Smart classrooms and digital boards

Public kiosks (hygienic, no touch needed)

⚠️ Limitations
Works best under good lighting

Needs consistent hand visibility within webcam frame

Some features OS-dependent (like brightness control)

📝 License
This project is open-source and available under the MIT License.

🙋‍♂️ Author
Vigneshwaran G
B.Tech IT | Developer & Designer
📧 vickyvmh3@gmail.com
🔗 GitHub Profile

📢 Contributions
Pull requests are welcome! If you have suggestions or want to improve the system, feel free to fork and contribute.
