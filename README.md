# Driver Drowsiness Detection System

## Overview

This project is a real-time Driver Drowsiness Detection System developed using OpenCV and MediaPipe Face Mesh. The system monitors the driver's eye status using Eye Aspect Ratio (EAR) and generates alerts when drowsiness is detected.

## Features

- Real-time webcam monitoring
- Face landmark detection using MediaPipe Face Mesh
- Eye Aspect Ratio (EAR) calculation
- Drowsiness detection
- Voice alert generation
- CSV-based event logging
- Real-time driver status display

## Technologies Used

- Python
- OpenCV
- MediaPipe
- NumPy
- SciPy
- Pandas
- pyttsx3

## Workflow

1. Capture video from webcam.
2. Detect facial landmarks using MediaPipe Face Mesh.
3. Extract eye landmarks.
4. Calculate Eye Aspect Ratio (EAR).
5. Detect prolonged eye closure.
6. Generate voice alert.
7. Store alert event in CSV file.

## Future Enhancements

- Mobile deployment
- SMS alerts
- Cloud monitoring
- Integration with vehicle systems

## Author

Ashik Kumar
