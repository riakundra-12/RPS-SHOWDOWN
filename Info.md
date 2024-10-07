# Rock-Paper-Scissors Game with Hand Gesture Recognition

This project implements a real-time Rock-Paper-Scissors game using hand gesture recognition. It utilizes OpenCV for video processing, cvzone for overlaying images, and the HandTrackingModule from cvzone for detecting hand gestures. The game allows a player to compete against an AI opponent, with scores updated dynamically based on hand gestures recognized.

## Technologies Used

- **OpenCV**: For capturing video frames from the webcam and image processing.
- **cvzone**: Provides functions for overlaying PNG images and integrating with OpenCV.
- **HandTrackingModule from cvzone**: Used for detecting and tracking hand gestures in real-time.
- **Python Libraries**: Random for generating AI moves, Time for managing game timing.

## Features

- **Hand Gesture Recognition**: Detects and recognizes gestures (rock, paper, scissors) based on the number of fingers extended using the HandTrackingModule.
- **Real-time Interaction**: Allows the player to make moves by displaying recognized gestures on-screen.
- **AI Opponent Logic**: Generates random moves for the AI opponent and determines the winner based on classic game rules.
- **Score Tracking**: Updates and displays scores in real-time during gameplay.
- **User Interface**: Utilizes overlay images and text on the background image to provide visual feedback to the user.
