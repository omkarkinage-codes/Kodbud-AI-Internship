
# Task 2: Face Detection App

## Description
A Computer Vision application that detects human faces in images (supporting .webp format) and draws bounding boxes around them. 

## How it Works
1. **Grayscale Conversion:** Images are converted to grayscale to improve detection speed and accuracy.
2. **Haar Cascade Classifier:** Uses a pre-trained model to identify facial features. 
3. **Multi-Scale Detection:** The `detectMultiScale` function handles faces at different distances from the camera.
4. **Parameter Tuning:** - `scaleFactor=1.1`: Allows detection of faces of various sizes.
   - `minNeighbors=5`: Ensures high-quality detection by requiring multiple overlapping "votes."

## Project Files
* `Face_Detection.ipynb`: The main notebook containing the detection logic.
* `img.webp`, `img2.webp`, `img3.webp`: Sample images used for testing.

## Results
The model successfully identifies multiple faces across different image formats with minimal false positives.
