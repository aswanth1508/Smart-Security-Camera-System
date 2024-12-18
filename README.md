# Smart-Security-Camera-System

The Smart Security Camera System is a Python-based application that leverages computer vision and cutting-edge technologies to enhance home security. It identifies unrecognized individuals in the camera's view, sends instant alerts to the owner, and offers seamless video streaming. Key features include facial recognition, real-time alert notifications via Twilio, and dynamic audio feedback.

Features
Real-time Video Streaming: Streams live feed from an IP webcam or a laptop’s built-in camera.
Facial Recognition: Identifies known faces and flags unrecognized persons.
Alert System: Instantly notifies the owner via Twilio SMS when unrecognized individuals are detected.
Audio Feedback: Plays sounds based on camera exposure levels.
Video Recording: Allows users to start and stop video recording, with videos saved locally.


Requirements
Python 3.6 or newer


Libraries:
OpenCV (cv2)
face_recognition
Twilio API (twilio.rest)
NumPy
sounddevice
geopy
I

Installation

Clone the Repository:
Install Dependencies:
             pip install -r requirements.txt
Configure Settings:
Twilio API Credentials: Update account_sid, auth_token, twilio_phone_number, and owner_phone_number in the script.
IP Webcam URL: Replace the default ip_webcam_url with your IP webcam’s URL if applicable.


Run the Application:
python smart_security_camera.py

Usage
The system continuously monitors video feeds, detects unrecognized faces, and sends alerts to the owner via SMS.


Keyboard Shortcuts:
Press 'q' to quit the application.
Press 's' to start/stop video recording. Videos are saved as output_video.mp4.

Contributing

We welcome contributions! If you encounter issues, have feature suggestions, or wish to enhance the system, feel free to open issues or submit pull requests.

Contact

For inquiries or support, please contact Kishan Jai Soorya N at kishanjaisoorya16@gmail.com.
