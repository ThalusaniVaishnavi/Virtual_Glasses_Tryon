# Virtual Try-On Glasses
Welcome to the Virtual Try-On Glasses Project!
A real-time application that lets you virtually try on glasses using your webcam, powered by **Python** and **OpenCV**.
## Features
-  Real-time detection of face and eyes using Haar Cascades.
-  Automatic scaling & positioning of glasses based on eye coordinates.
-  Support for multiple glasses styles (PNG images with transparency).
-  Lightweight and easy to run - no heavy dependencies.
## Technologies Used
- Python: Main programming language for the application.
- OpenCV (cv2): Handles image processing, webcam video capture, and Haar Cascade face/eye detection.
- NumPy: Used for pixel-level image manipulation and mathematical operations.
- Haar Cascade Classifiers: Pre-trained XML models (haarcascade_frontalface_alt.xml and haarcascade_eye.xml) for detecting faces and eyes.
- PNG Images with Transparency: Used for the glasses overlays, allowing seamless blending on the face. 
## Setup Instructions
1. Clone the repository
```
git clone <link>
```
2. Install Dependencies
```
pip install opencv-python numpy
```
3. Run Application
```
python glass_virtual_tryon.py
```
## Usage
1. Run the application
2. Allow webcam access
Your default webcam will turn on automatically. Make sure you are in a well-lit environment for better detection.
3. Position your face
Look directly at the camera.
Keep your face inside the frame so the system can detect both eyes.
4. Try on the glasses
The selected glasses image will appear on your face in real-time.
You can swap out the PNG image in glass_image/ to try different styles.
5. Exit the application
Press the Q key to quit.
## Credits
This project was originally created by **thangnch** as [MiAI_Glasses_Tryon](https://github.com/thangnch/MiAI_Glasses_Tryon).  

This version builds upon the original work with translated English comments, improved documentation, and a redesigned README for better clarity and usability.


