# Labview-project
Object Detection Using LabVIEW and Pattern Matching

This project implements a real-time object detection and recognition system using LabVIEW and NI Vision Development Module. It captures live video through a USB webcam, performs image preprocessing, and uses template matching (normalized cross-correlation) to detect known objects in the frame.
🔧 Features

    🎥 Real-time object detection via webcam input

    🧠 Pattern matching using normalized cross-correlation

    🖱️ User interface built on LabVIEW Front Panel

    🎯 Displays object location, coordinates, and match overlays

    📸 Supports grayscale and RGB image processing

    🔁 Continuous image stream processing using While Loop

    🚦 Stop control for safe termination

    🔍 Match result includes position (x, y) and orientation angle

⚙️ Methodology

    Image Acquisition

        Webcam captures live frames using IMAQdx

        Template image is preset and stored

    Image Processing

        Optional grayscale conversion for faster matching

        Pattern matching using cross-correlation compares the live image to the template

    Result Extraction

        Position (X, Y), match score, and angle are extracted

        Bounding box is drawn on the matched region

    Display and Control

        Final image is shown with overlay

        Loop runs continuously until the user stops it

🧪 Applications

    Industrial component sorting

    Quality control systems

    Shape-based object detection

    Educational and prototype development in machine vision

🔍 Future Scope

    Integration with machine learning models (CNN/SVM)

    Enhanced lighting adaptation using histogram equalization

    Object sorting with Arduino-controlled servo motors

    Color-based filtering using HSL space

