# Real-Time Traffic Sign Detection using Phone Camera

This program uses a traffic sign classification model pre-trained by Teachable Machine with dataset from Kaggle to detect and classify traffic signs in real-time using your phone's cam.

## Prerequisites

- Python 3.x
- OpenCV library
- Camo
- Phone's camera

## Installation

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/jungboixitinh/2024_AI-Vision.git
    cd Project 2
    ```

2. **Install Required Libraries:**

    Ensure you have `opencv-python` installed. You can install it using pip:

    ```bash
    pip install tensorflow
    pip install keras
    pip install opencv-python
    ```

## Usage

1. **Run the Script:**

    ```bash
    python trafficsign.py
    ```

    This will start your cam and display a window showing the video feed with rectangles drawn around detected faces.

2. **Quit the Application:**

    Press the `q` key to quit the application and close the webcam feed.

## Dataset

    The pre-trained traffic sign classification model uses dataset from: 
    https://www.kaggle.com/datasets/seebicb/traffic-signs-classification
