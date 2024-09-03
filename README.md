# Face Detection Using Mediapipe

## Project Overview

The "Face Detection Using Mediapipe" project demonstrates how to implement face detection in both images and live video streams using Google's Mediapipe library, combined with OpenCV for handling image and video processing. The project is designed to accurately detect faces in real-time, offering a versatile solution for various applications, including security systems, user interaction, and more.

## Key Features

- **Dual Mode Detection:** Supports face detection in both static images and live video feeds.
- **Real-Time Processing:** Optimized for real-time face detection, ensuring minimal latency and high accuracy.
- **Mediapipe Integration:** Utilizes Mediapipe's state-of-the-art face detection technology, which provides reliable and efficient detection.

## How It Works

### Image Face Detection

1. **Load an Image:** The system reads an image from a specified file path.
2. **Convert to RGB:** The image is converted from BGR (default OpenCV format) to RGB, which is required by Mediapipe.
3. **Face Detection:** The Mediapipe Face Detection model processes the image, identifying any faces present.
4. **Bounding Box Creation:** For each detected face, a bounding box is drawn around the face.
5. **Save Cropped Faces:** The detected faces are cropped and saved as separate image files.

### Video Face Detection

1. **Capture Video Stream:** The system captures video from a connected camera or a video file.
2. **Convert to RGB:** Each video frame is converted from BGR to RGB.
3. **Face Detection:** The Mediapipe Face Detection model processes each frame in real-time, detecting faces.
4. **Draw Bounding Boxes:** A bounding box is drawn around each detected face in the video stream.
5. **Display the Video:** The processed video with detected faces is displayed in real-time.

## Code Description

### Libraries Used

- **OpenCV:** Used for handling image and video capture, processing, and display.
- **Mediapipe:** Provides the face detection model and necessary processing functions.
- **NumPy:** Used for array operations and handling the bounding box calculations.

### Main Code

The project consists of two parts:
1. **Face Detection in Images:** The script reads an image, detects faces, and saves the cropped face images.
2. **Face Detection in Video:** The script captures live video, detects faces in real-time, and displays the video with bounding boxes around detected faces.

### Installation

To run this project, you need to have Python installed with the following dependencies:
```bash
pip install opencv-python mediapipe numpy
```

### Usage

1. **For Image Detection:**
   - Set the image path in the script.
   - Run the script to detect and save faces in the image.

2. **For Video Detection:**
   - Run the script In Note Book to start detecting faces in the live video feed.


### Results

- **Image Detection:** Faces detected in images are saved as new image files with bounding boxes.
- **Video Detection:** Faces detected in video streams are displayed with bounding boxes around them in real-time.

## Conclusion

The "Face Detection Using Mediapipe" project is a robust solution for real-time face detection in both static images and live video streams. By leveraging the power of Mediapipe and OpenCV, this project is suitable for various applications, including security, user interaction, and more.

Feel free to reach out if
