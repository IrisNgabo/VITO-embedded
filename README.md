
# Face and Sign Recognition System

## Overview
This application detects and recognizes customers' faces, ensuring that the face is identified correctly at least 5 times. After successful recognition, it prompts the customer to make an "OK" sign for further verification. Once verified, the customer’s information is added to a database.

## Features
- **Face Detection and Recognition**: Uses a pre-trained LBPH face recognizer and Haar Cascade classifier for face detection.
- **Sign Detection**: Uses a Keras model to recognize hand signs, specifically the "OK" sign.
- **Database Integration**: Stores customer information in an SQLite database after successful verification.

## Requirements
- Python 3.11.2 !important
- OpenCV
- Keras (with TensorFlow backend)
- NumPy
- SQLite3

