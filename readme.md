# Face Mask Detection

This project aims to detect whether a person is wearing a face mask or not using computer vision techniques and deep learning. The code uses a pre-trained model to classify faces into two classes: "Mask" and "No Mask". It utilizes OpenCV for face detection and TensorFlow/Keras for model inference.

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/tanishq0421/FaceMask_detection_AI.git

2. Navigate to the project directory:
    ````shell
    cd face-mask-detection
    
3. Install the required dependencies:
    ````shell
    pip install -r requirements.txt

4. Run the main script:
    ````shell
    python face_mask_detection.py

(i)This will launch the face mask detection application. It will use the default video source (video.mp4) for detection. You can modify the script to use a different video source or even a live webcam feed if desired.

(ii)The application will display the video feed with bounding boxes around detected faces and labels indicating whether the person is wearing a mask or not.

(iii)Press the 'q' key to quit the application.

