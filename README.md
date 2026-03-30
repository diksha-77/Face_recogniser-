# Face Recognition System

This project is a real-time face recognition system built using OpenCV and Python. It detects faces using a Haar Cascade classifier and recognizes them using the LBPH algorithm.

---

## Features

* Detects faces using webcam
* Recognizes known faces
* Displays name on screen
* Shows "UNKNOWN" for unrecognized faces

---

## Technologies Used

* Python
* OpenCV
* NumPy
* Pillow (PIL)
* Machine Learning

---

## Project Structure

```
Face_Recogniser/
│
├── data/                               # Training images
├── classifier.xml                      # Generated after training
├── haarcascade_frontalface_default.xml
├── face_recogniser.ipynb
└── README.md
```

---

## Dataset Format

Store images inside the `data/` folder in this format:

```
name.id.imageNumber.jpg
```

Example:

```
diksha.1.1.jpg
diksha.1.2.jpg
manish.2.1.jpg
```

---

## How to Run

1. Install required libraries:

```
pip install opencv-contrib-python numpy pillow
```

2. Run training code to generate:

```
classifier.xml
```

3. Run the main file to start face recognition.

4. Press **Enter** or **q** to stop the camera.

---

## Notes

* `classifier.xml` is created after training
* Make sure camera access is enabled
* Use `opencv-contrib-python` (required for face module)


