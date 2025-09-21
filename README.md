
# Flask Face & Eye Detection

A simple Flask web application that streams live webcam video with **real-time face and eye detection** using OpenCV.

## Features

* Live webcam streaming in a browser.
* Real-time face detection using Haar cascades.
* Real-time eye detection within detected faces.
* Responsive and easy-to-use interface.


## Requirements

* Python 3.7+
* Flask
* OpenCV (opencv-python)

Install the dependencies using:

```bash
pip install flask opencv-python
```

---

## Project Structure

```
.
├── face.py
├── static             # Main Flask application
    └── css
    └── script
├── templates/
│   └── face.html      # HTML template for video streaming
├── Haarcascades/
│   ├── haarcascade_frontalface_default.xml
│   └── haarcascade_eye.xml
└── README.md
```


## How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/flask-face-eye-detection.git
cd flask-face-eye-detection
```

2. Make sure the Haarcascade XML files are in the correct folder (`Haarcascades/`).

3. Run the Flask app:

```bash
python app.py
```

4. Open your browser and go to:

```
http://127.0.0.1:5000/
```

You should see your live webcam feed with face and eye detection.


