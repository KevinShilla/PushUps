# Push-Up Counter Web App

https://kevinshilla.github.io/PushUps/
This project is a real-time push-up counter that uses your webcam to track your form and count your push-ups. When you complete a proper push-up, the app plays a beep sound and updates your count on the screen.

## Features

- **Real-Time Camera Access:** Requests access to your camera and displays the video feed.
- **Pose Detection:** Uses TensorFlow.js with the MoveNet model to detect your body movements.
- **Push-Up Detection:** Monitors your form and counts a push-up when performed correctly.
- **Audio Feedback:** Plays a beep sound when a push-up is correctly completed.
- **Simple and Lightweight:** Runs directly in modern browsers without needing extra software.

## How It Works

The app uses the MoveNet model from TensorFlow.js to estimate your pose. It calculates key angles (such as the elbow angle) and uses a simple state machine to detect the down and up phases of a push-up.

## Setup and Running Locally

1. **Clone or Download the Repository:**  
   Download this repository or clone it using:
   ```bash
   git clone https://github.com/KevinShilla/PushUps.git
