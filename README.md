# Face Recognition System using Python

A simple face recognition desktop application built using **Python**, **OpenCV (cv2)**, **face_recognition**, and **Tkinter**. This tool allows users to upload an image and detect or recognize faces using pre-trained models and inbuilt functions.

## Technologies Used

- Python 3.x
- OpenCV (cv2)
- face_recognition
- Tkinter (GUI)
- File dialogs and event handling

## Features

- GUI interface with buttons, labels, and file explorer
- Upload image from system using file dialog
- Recognize faces and mark them on the image
- Uses inbuilt face detection and recognition functions from the `face_recognition` library
- Displays output on the same GUI window

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/face-recognition-app.git
   cd face-recognition-app
````

2. Install dependencies:

   ```bash
   pip install opencv-python face_recognition
   ```

3. Run the Python script:

   ```bash
   python face_recognition_gui.py
   ```

4. Use the GUI to upload an image and perform recognition.

## Folder Structure

```
/face-recognition-app
├── face_recognition_gui.py
├── known_faces/             # Optional folder to store known face encodings
└── README.md
```

## Notes

* Make sure your system supports image display and webcam (if extended for live capture).
* For better accuracy, use clear frontal images.

## License

This project is open-source and available under the [MIT License](LICENSE).

---

Built with Python's power and a touch of AI!

```

---

Let me know if you need a demo GIF, sample face images folder structure, or error handling additions.
```
