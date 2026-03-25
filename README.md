🎯 Face Recognition Based Automated Attendance System
📌 Overview

This project is a Face Recognition Based Automated Attendance System developed using Python, OpenCV, and machine learning techniques. It detects and recognizes faces in real-time through a webcam and automatically marks attendance.

The system eliminates manual attendance, reduces proxy chances, and improves accuracy and efficiency.

🚀 Features
👤 Real-time face detection using webcam
🧠 Face recognition using LBPH algorithm
📝 Automatic attendance marking with date & time
📂 Stores attendance in CSV format
➕ Register new faces easily
🔄 Retrain model with new data
🖥️ User-friendly GUI using Tkinter

🛠️ Technologies Used
Python 3.x
OpenCV
NumPy
Dlib
face_recognition library
Tkinter (GUI)
PIL (Image Processing)

💻 System Requirements
Hardware
Laptop/Desktop
Webcam
Minimum 4GB RAM
Software
Python 3.x

Required libraries (see installation below)
⚙️ Installation
Clone the repository:
git clone https://github.com/your-username/face-attendance-system.git
cd face-attendance-system
Install dependencies:
pip install opencv-python numpy face-recognition dlib pillow

▶️ How to Run
python main.py

📸 How It Works
Register a new face by entering a name
System captures multiple face samples
Train the model
Start attendance mode
Faces are detected and recognized
Attendance is automatically saved

📁 Project Structure
📦 face-attendance-system
 ┣ 📂 dataset              # Stored face images
 ┣ 📂 attendance_logs      # Attendance CSV files
 ┣ 📜 main.py              # Main application file
 ┣ 📜 trainer.yml          # Trained model
 ┣ 📜 labels.pickle        # Label mapping
 ┗ 📜 README.md
 
📊 Output
Webcam window with:
Face detection box
Name display (if recognized)
"Unknown" for unregistered faces

Attendance log:
Name, Date, Time
Anshika, 2026-03-25, 10:32:15
🎯 Applications
🏫 School/College attendance
🏢 Office attendance systems
🔐 Security & surveillance
📱 Face authentication systems
🔮 Future Enhancements

Improve accuracy using deep learning models
Add database integration
Multi-face recognition support
Cloud-based attendance system
Mobile app integration

📚 References
https://opencv.org
https://pypi.org/project/face-recognition
https://docs.python.org

👩‍💻 Author
ANSHIKA DHYANI
B.TECH CSE
25SCS1003001606
IILM UNIVERSITY , GREATER NOIDA

⭐ Contribute:
Feel free to fork this repo and contribute!

📄 License
This project is for educational purposes.
