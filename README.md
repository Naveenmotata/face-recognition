

# Face Recognition Project

## Introduction

This project utilizes OpenCV for face detection in real-time using a webcam. It aims to identify faces in the captured video stream and draw rectangles around them.

## Requirements

- Python (>=3.6)
- OpenCV (cv2)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Naveenmotata/Face-recognition.git
   ```

2. Install the required dependencies:

   ```bash
   pip install opencv-python
   ```

3. Download the Haar Cascade file for face detection from [OpenCV GitHub Repository](https://github.com/opencv/opencv/tree/master/data/haarcascades) and save it in the `haarcascades` directory of your project.

## Usage

1. Run the main script:

   ```bash
   python main.py
   ```

2. The script will use your webcam to detect faces in real-time.

3. Press 'g' to exit the program.

## Configuration

- Adjust parameters such as `scaleFactor` and `minNeighbors` in the `detectMultiScale` function for different face detection scenarios.

## Contributing

Feel free to contribute by opening issues, suggesting improvements, or creating pull requests.

## License

This project is licensed under the [MIT License](LICENSE).

---