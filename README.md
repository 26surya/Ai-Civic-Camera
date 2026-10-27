# Ai-Civic-Camera
AI Civic Camera: software-based littering detection using YOLOv8 and OpenCV on a standard Wi-Fi IP camera. It tracks objects across frames, saves a timestamped video clip and image of each confirmed incident, and shows them on a web dashboard.
AI Civic Camera

AI Civic Camera is a software-driven system that automatically detects littering in public areas using an ordinary Wi-Fi IP camera, with no special hardware. It was built as a Community Engagement Project at Ghanshyamdas Saraf College of Arts & Commerce.

Features
Real-time detection of garbage-throwing events using YOLOv8 and OpenCV
Tracking across frames to tell a person holding an object from one discarding it, which reduces false alarms
Saves a short video clip, an image and a timestamp for each confirmed incident
Web dashboard where authorities can review and manage incident records
Incident data stored in an SQLite database
Privacy-conscious design: no facial recognition and no matching against external databases
Tech Stack

Python, YOLOv8 (Ultralytics), OpenCV, Flask/FastAPI, SQLite, HTML/CSS/JavaScript

Team

Suraj Ramdas Vishwakarma, Alex Cyril Britto, Arpit Rakesh Yadav
