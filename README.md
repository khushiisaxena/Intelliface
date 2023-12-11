# Face Recognition Based Attendance System

This project is a face recognition-based attendance system that uses OpenCV and Python. The system utilizes a trained Convolutional Neural Network (ResNet model) for accurate facial feature recognition. Dlib enhances facial landmark detection, while NumPy ensures efficient data manipulation. Attendance records are stored in CSV files for easy management, and OpenCV enables real-time image processing. The system offers a reliable, user-friendly solution for attendance tracking, showcasing its potential to revolutionize traditional methods in educational and corporate settings.

## Installation

1. Clone the repository to your local machine. ``` git clone https://github.com/Arijit1080/Face-Recognition-Based-Attendance-System ```
2. Install the required packages using ```pip install -r requirements.txt```.
3. Download the dlib models from https://drive.google.com/drive/folders/12It2jeNQOxwStBxtagL1vvIJokoz-DL4?usp=sharing and place the data folder inside the repo

## Usage

1. Collect the Faces Dataset by running ``` python get_faces_from_camera_tkinter.py``` .
2. Convert the dataset into ```python features_extraction_to_csv.py```.
3. To take the attendance run ```python attendance_taker.py``` .
4. Check the Database by ```python app.py```.


## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you find any bugs or have any suggestions.


