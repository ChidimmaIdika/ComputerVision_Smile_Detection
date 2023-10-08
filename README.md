# ComputerVision_Smile_Detection

![image](https://github.com/ChidimmaIdika/ComputerVision_Smile_Detection/assets/137975543/e9632848-cfbc-472b-b68f-a3fbed7cf50b)

## Face, Eye, and Smile Detection using OpenCV

## Table of Contents
1. [Overview](#overview)
2. [Prerequisites](#prerequisites)
3. [How to Use](#how-to-use)
4. [Implementation Details](#implementation-details)
5. [Sample Output](#sample-output)
6. [License](#license)
7. [Acknowledgments](#acknowledgments)
8. [Author](#author)
9. [Contact](#contact)

## Overview
This project demonstrates real-time face, eye, and smile detection using Python and the OpenCV library.   
I leveraged Haar-cascade classifiers to detect faces, eyes, and smiles in a webcam feed and draw rectangles around them.

## Prerequisites
Before running the code, ensure you have the following dependencies installed:

- Python (>=3.6)
- OpenCV (4.8.1.78 or higher)
- NumPy (>=1.17.3)
   
You can install OpenCV and NumPy using pip:   
!pip install opencv-python   
!pip install numpy

## How to Use
1. Clone this repository:   
git clone https://github.com/ChidimmaIdika/ComputerVision_Smile_Detection.git
cd face-eye-smile-detection
2. Run the face_eye_smile_detection.py script:   
   python face_eye_smile_detection.py
3. Press the 'q' key to exit the webcam feed.

## Implementation Details
The key components of this project are as follows:   
- I used Haar-cascade classifiers provided by OpenCV to detect frontal faces, eyes, and smiles.
- The detect function takes the grayscale image and the original frame and returns the frame with rectangles drawn around detected faces, eyes, and smiles.

## Sample Output
![image](https://github.com/ChidimmaIdika/ComputerVision_Smile_Detection/assets/137975543/0258fb47-b28d-4d32-86ed-07e960b63b38)

## License
This project is licensed under the MIT License.

## Acknowledgments
- [OpenCV](https://github.com/opencv/opencv/tree/4.x/data/haarcascades) for providing the Haar-cascade classifiers.
- [10Alytics](https://github.com/10Alytics)

## Author
[Chidimma Idika](https://github.com/ChidimmaIdika)

## Contact
For any inquiries or suggestions, please [send me an email](chidimmaidika@gmail.com).

