# Face Recognition-Based Smart Attendance System with Real-Time Web Integration Using Machine Learning

## Overview
This project implements a real-time attendance system using face recognition. Built with Python, OpenCV, and the K-Nearest Neighbors (KNN) algorithm, it records attendance and displays it on a web interface using Streamlit.

## Features
- **Real-Time Face Recognition:** Utilizes OpenCV for capturing and recognizing faces in real-time.
- **Machine Learning:** Employs the KNN algorithm for accurate face recognition.
- **Attendance Recording:** Stores attendance data in a CSV file.
- **Web Integration:** Displays attendance data through a user-friendly web interface using Streamlit.

## Project Description
The Face Recognition-Based Smart Attendance System is designed to automate the process of recording attendance. The system captures images from a webcam, identifies individuals using the KNN algorithm, and marks their attendance. The attendance data is stored in a CSV file and is accessible via a web application built with Streamlit for real-time visualization and monitoring.

### Components
1. **Face Detection and Recognition:**
   - Utilizes OpenCV for image capturing and preprocessing.
   - Uses the KNN algorithm for face recognition.
   
2. **Attendance Management:**
   - Records attendance in a CSV file with timestamp and name.

3. **Web Interface:**
   - Streamlit is used to create an interactive and real-time web interface.
   - Displays the attendance data in a tabular format with additional features for data visualization.

## Setup and Installation
1. **Clone the Repository:**
   ```bash
git clone git@github.com:adarshakumar395/Face-Recognition-Based-Smart-Attendance-System-with-Real-Time-Web-Integration-Using-Machine-Learning.git
cd face-recognition-attendance-system

2. **Install Dependencies:**
Ensure you have Python 3.6+ installed. Then, install the required packages using pip:
pip install -r requirements.txt
python -m pip install --upgrade pip  

4. **Run The Application**
   1. python add_faces.py   #for adding the faces
   2. python test.py     # for taking attendence
   3. press 'o' for capture the attendance
   4. streamlit run app.py #for runnig the streamlit web application for displaying attendance

## Usage
**1.Capture Training Data:**
Run the script to capture images of individuals and label them for training the KNN model.

**2.Train the Model:**
Use the captured images to train the KNN model for face recognition.

**3.Start Attendance System:**
Execute the main script to start the face recognition-based attendance system.

**Monitor Attendance:**
Use the Streamlit web app to view and manage attendance records in real-time.

**Contributing**
Contributions are welcome! Please feel free to submit a Pull Request.

## Acknowledgements ##
-**OpenCV:** For providing powerful computer vision tools.
-**Streamlit:** For enabling the creation of a real-time web interface.
-**KNN Algorithm:** For reliable and efficient face recognition.

## Contact ##
For any inquiries or feedback, please contact https://www.linkedin.com/in/adarsha-kumar-13a94223b/ .
