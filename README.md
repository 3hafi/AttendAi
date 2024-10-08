# AttendAi
AttendAi is an intelligent attendance management system that leverages computer vision and facial recognition technology to automate the process of recording attendance.

Machine Learning is Fun! Part 4: [Article]([https://medium.com/@ageitgey/machine-learning-is-fun-part-4-modern-face-recognition-with-deep-learning-c3cffc121d78])



##
## Key Features:
- Real-time facial recognition using webcam input
- Automated attendance logging to CSV file
- Support for multiple individuals
- Low-latency processing for instant recognition

## Technologies and Technical Aspects:
- Programming Language: Python 3.x
- Computer Vision: OpenCV (cv2)
- Facial Recognition: face_recognition library (based on dlib)
- Numerical Computing: NumPy
- File I/O: Built-in Python libraries (os, datetime)
- Image Processing: 
  - Color space conversion (BGR to RGB)
  - Image resizing for performance optimization
- Face Detection: HOG (Histogram of Oriented Gradients) method
- Face Encoding: 128-dimensional face embeddings
- Face Matching: Linear SVM classifier
- Data Storage: CSV file for attendance records
- Real-time Video Capture: OpenCV VideoCapture
- GUI: OpenCV imshow for real-time video display

## Performance Metrics:
- Recognition Speed: <1 second per frame
- Accuracy: Up to 99.38% on LFW dataset
- Scalability: Supports unlimited number of registered faces

## Implementation Details:
- Dynamic loading of known faces from image directory
- Multithreaded processing for improved performance
- Attendance logging with timestamp for each recognized individual
- User-friendly visual interface with bounding boxes and name labels

This project demonstrates proficiency in computer vision, machine learning integration, and real-world application development using Python.
