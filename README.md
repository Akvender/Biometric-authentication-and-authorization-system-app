# Biometric authentication and authorization system

School competition project (team, 2024): a desktop app that signs users in with a password **and** a face check.

## What it does
- Registration: username, password (hashed with bcrypt) and a face photo from the webcam, stored in SQLite.
- Login: password check, then live face verification against the stored photo (DeepFace).
- Face detection with OpenCV Haar cascades (`pliki haar/`).
- GUI in Tkinter / CustomTkinter.

## Stack
Python, OpenCV, DeepFace, bcrypt, SQLite, Tkinter/CustomTkinter.

## Run
```bash
cd programy
python main.py
```
`main.py` installs its dependencies with pip on start (opencv-python, numpy, customtkinter, bcrypt, deepface). A webcam is required.

## Status
School project from 2024, kept as a record. Not maintained.
