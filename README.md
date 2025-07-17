# Face Recognition Attendance System 🎯

A Python-based real-time face recognition attendance system using OpenCV, Streamlit, and face_recognition libraries. This project captures faces through a webcam, recognizes registered users, and logs their attendance with timestamps in a CSV file. The Streamlit dashboard auto-refreshes and displays the live attendance records.

---

## 🚀 Features

- 🎥 Real-time face detection and recognition using webcam
- 📁 Stores attendance in CSV format with time and date
- 🔄 Auto-refresh Streamlit dashboard for live updates
- 📊 Highlights latest attendance in the web UI
- 👤 Easy to add new faces for recognition
- 💡 Built with a virtual environment and modular Python scripts

---

## 🛠️ Tech Stack

- Python 3.11+
- OpenCV
- face_recognition
- Streamlit
- streamlit_autorefresh
- Pandas
- NumPy
- Git

---

## 📂 Project Structure

face_detection_system/
├── Attendence/
│ └── Attendence_<dd-mm-yyyy>.csv
├── data/
│ └── known_faces/
├── aa_faces.py # Face recognition logic
├── test.py # Utility/testing script
├── app.py # Streamlit dashboard
├── background01.png # UI background
├── .venv/ # Virtual environment
└── README.md

yaml
Copy
Edit

---

## 🔧 Installation & Setup

```bash
# Clone the repo
git clone https://github.com/Rahuldilla/Face_recongnition_Attendence_System.git
cd Face_recongnition_Attendence_System

# Create and activate virtual environment (optional but recommended)
python -m venv .venv
.venv\Scripts\activate     # On Windows

# Install dependencies
pip install -r requirements.txt
Note: If requirements.txt is not created yet, use:

bash
Copy
Edit
pip freeze > requirements.txt
🖥️ Running the App
Add known faces in the data/known_faces/ directory.

Start webcam face recognition:

bash
Copy
Edit
python aa_faces.py
Launch Streamlit dashboard:

bash
Copy
Edit
streamlit run Attendence/app.py
📈 Sample Output
Attendance logs saved as:

Copy
Edit
Attendence/Attendence_17-07-2025.csv
Streamlit displays a live data table and auto-refreshes every 2 seconds.

🙋‍♂️ Author
Rahul Dilla
📧 rahuldilla.2003@gmail.com
🌐 GitHub - @Rahuldilla

📜 License
This project is licensed under the MIT License - feel free to use and modify.

⭐️ Show Your Support
If you like this project, give it a ⭐️ on GitHub and feel free to fork it!
