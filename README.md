 Vehicle Number Plate Detection System
🔍 Overview
This project is an AI-powered vehicle number plate detection system using OpenCV, Tesseract OCR, and Firebase. It captures real-time video from a webcam or an ESP32-CAM stream, detects number plates, extracts text, and validates it against a Firebase database.

✨ Features
Real-Time Detection: Uses OpenCV and edge detection to locate number plates in video streams.
OCR for Text Extraction: Utilizes Tesseract OCR to extract and validate number plate text.
Firebase Integration: Stores and retrieves vehicle details, allowing registration and monitoring.
ESP32-CAM Support: Can process video streams from an ESP32-CAM for remote detection.
User-Friendly Interface: Provides a command-line menu for easy interaction.
🛠️ Technologies Used
Python
OpenCV (Computer Vision)
Tesseract OCR (Text Recognition)
Firebase Realtime Database (Data Storage)
ESP32-CAM (Optional Video Source)
📌 How It Works
Vehicle Registration: Users can register vehicles by entering details like owner name, type, model, and color.
Detection Mode: The system captures a video frame, detects a number plate, extracts the text, and checks if it's registered.
Logging to Firebase: If registered, details are fetched from Firebase; otherwise, the vehicle is marked as "Unregistered."
🚀 Getting Started
🔧 Prerequisites
Ensure you have the following installed:

Python 3.x
OpenCV (pip install opencv-python)
Pytesseract (pip install pytesseract)
Firebase Admin SDK (pip install firebase-admin)
🛠 Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/vehicle-number-plate-detection.git  
cd vehicle-number-plate-detection
Configure Firebase:

Add your Firebase credentials JSON file (serviceAccount.json).
Set your Firebase database URL in the script.
Run the application:

bash
Copy
Edit
python main.py  
🖥️ Usage
Register a Vehicle: Start the system and enter vehicle details.
Detect Vehicles: Scan plates in real time and check if they are registered.
📝 Future Enhancements
Improve OCR accuracy with deep learning models.
Add a web-based interface for better usability.
Implement SMS/email notifications for unregistered vehicles.
🤝 Contributing
Pull requests are welcome! Feel free to open issues for feature requests or bug reports.

📜 License
MIT License.

