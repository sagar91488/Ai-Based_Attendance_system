🎯 AI-Based Attendance System using Face Recognition
This project is a real-time attendance system that uses face recognition through a webcam. It detects and recognizes faces, then marks attendance automatically with date, time, and a saved image of the person.

📌 Features
Live face detection and recognition

Automatic attendance marking

Saves name, date, time, and face image

Exports attendance to both CSV and Excel formats

Simple GUI to start/stop attendance

🛠️ Technologies Used
Python – Main programming language

OpenCV – For webcam and image processing

face_recognition – For detecting and recognizing faces

dlib – For face encoding

NumPy – For numerical tasks

pandas – To save attendance in CSV and convert to Excel

Tkinter – To build the user interface

Pillow (PIL) – For image handling in GUI

🧠 How It Works
Face Encoding

Loads known faces from the dataset/ folder

Each person has a folder with their images

GUI Interface

Built with Tkinter

Start and Stop buttons control attendance

Real-Time Face Detection

Uses webcam to detect and compare faces

Matches faces with the known dataset

Attendance Marking

If a face matches, attendance is recorded

Saves the name, time, and face image

Save to File

Attendance data is saved in a .csv file

Also automatically converted to .xlsx Excel format

Images saved in a separate folder

📁 Output
CSV file: Attendance_YYYY-MM-DD_HH-MM.csv

Excel file: Attendance_YYYY-MM-DD_HH-MM.xlsx

Face images saved with timestamp

Each file includes name, time, and image path

📌 Use Case
A simple and practical tool for schools, colleges, or companies to track attendance automatically using face recognition. 
