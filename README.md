
# Face based attendance system using python and openCV

This project is an automated attendance management system using face recognition. 
It detects and recognizes faces using a webcam and records attendance automatically.
## Features
- Real-time face detection using OpenCV
- Automatic attendance marking
- Student dataset creation and training
- Attendance records stored in CSV format

## Technologies Used
- Python
- OpenCV
- NumPy
- Machine Learning
- Haar Cascade Classifier

## Project Structure
- TrainingImage/ → stores student face images
- TrainingImageLabel/ → trained model files
- StudentDetails/ → student information
- Attendance/ → attendance records

## How to Run
1. Install required libraries
pip install -r requirements.txt

2. Capture student images
python takeImage.py

3. Train the model
python trainImage.py

4. Start attendance system
python automaticAttendance.py
