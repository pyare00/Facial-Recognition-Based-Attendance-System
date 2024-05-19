**Facial Recognition Based Attendance System**

This project implements a facial recognition-based attendance system using Machine Learning (ML) and Deep Learning techniques. 
The system captures and recognizes faces to mark attendance automatically, leveraging Python, OpenCV, and a pre-trained face recognition model. 
The graphical user interface (GUI) is built using Tkinter.
This project is Data Specific i.e will not accept new registration yet.
If you add new faces it would require changes in Main.py

Table of Contents
Features
Requirements
Installation
Usage
Model Training
Data Preparation
File Structure
Credits

Features
Face Detection and Recognition: Detect and recognize faces in real-time.
Attendance Marking: Automatically marks attendance based on recognized faces.
User-friendly GUI: Simple and intuitive interface built with Tkinter.
Database Integration: Stores attendance records in a CSV file.

Requirements
Python 3.6+
OpenCV
numpy
pandas
PIL (Pillow)
Tkinter (usually comes pre-installed with Python)


Installation
Clone the repository:

bash
Copy code
git clone https://github.com/pyare00/Facial-Recognition-Based-Attendance-System.git
cd facial-recognition-attendance-system




Install the required packages:

Copy code
pip install requirement

**Usage**
Run the application:
python main.py


Interact with the GUI:

Recognize faces and mark attendance.
View attendance records.
Model Training
The facial recognition system uses a pre-trained model provided by the face_recognition library, which is based on deep learning techniques. No additional training is required for face recognition. However, you need to register faces for each individual to build the face database.

Registering Faces
Capture images of the faces you want to mark attendance by pressing escape button as it is set.


Data Preparation
Face Images: Collect clear images of each individual for accurate recognition.
Attendance Records: Attendance data is stored in a database file, which is updated automatically.


File Structure
  Maintain the file structure as it is uploaded here.
  "whereever you put this folder structure make change in Main.py line 167 [ path=Path("Write the path of "Project" folder)]"

Credits
This project utilizes the ML model SVM and various libraries for face detection and recognition. 
Acknowledgements to the creators and maintainers of these resources.
