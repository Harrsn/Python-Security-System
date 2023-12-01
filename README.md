# Python Security System

This repository presents a Python security system leveraging OpenCV and a simple person detection model for capturing and storing videos. It features the following:

- Detection of Individuals
- Video Storage (Google Cloud Object Storage)
- Text Notifications
- System Arming & Disarming
- Activity Logs

## Installation

Before you begin, ensure that you have the following components installed:

- Python 3.9+
- Node.js
- ffmpeg

Install the Python dependencies by executing the command `pip install -r requirements.txt` from the root directory.

Next, navigate to the 'frontend' directory (`cd frontend`) and install Node.js dependencies with `npm install`.

## Running The Backend

To launch the backend, execute the `main.py` file by running `cd backend && python main.py`.

## Running The Frontend

To start the frontend, run `npm start` from `/frontend`.
