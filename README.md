# Fitness Counter using Pose Estimation

## Overview

This project utilizes OpenCV and MediaPipe to track and count bicep curls and push-ups in a workout video. It calculates the angle of the elbow joint, displays the number of repetitions, visualizes the progress with a bar indicator, and shows real-time FPS.

## Features

- Pose Detection: Detects and tracks key landmarks on the body.

- Angle Calculation: Measures the elbow angle to determine curl motion.

- Repetition Counter: Tracks completed curls based on angle changes.

- Visual Feedback: Displays a progress bar and real-time repetition count.

- FPS Display: Shows the frames per second (FPS) for performance monitoring.

## Usage

- Place your workout video in the Videos folder.

- Update the video path in the script

- Run the script

- Press 1 to exit the video window.

## Key Code Components

- Angle Calculation: Tracks the elbow joint using keypoints.

- Progress Bar: Visualizes curl progress from 0% to 100%.

- Counter Logic: Increases count based on arm curl direction.

- FPS Display: Monitors and displays real-time performance.

## Future Improvements

- Add support for real-time webcam tracking.

- Enhance accuracy with additional pose refinement.

- Include more workout types.
