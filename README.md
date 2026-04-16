AI Virtual Try-On System

An interactive AI-powered Virtual Try-On web application that enables users to visualize clothing on a digital interface in real time. This project combines a modern React (TypeScript)-based frontend with a scalable architecture designed for integration with computer vision and pose estimation models.

The system provides an intuitive user experience for browsing products and simulating a virtual fitting environment, where garments can be dynamically aligned based on body structure using techniques such as scaling, rotation, and translation. It is built with a modular component-based design, ensuring flexibility, maintainability, and seamless extension into a full AI-driven try-on solution.

This project serves as a foundation for developing advanced virtual fitting systems by integrating real-time webcam input, landmark detection, and image rendering techniques, making it highly relevant for applications in e-commerce, fashion technology, and augmented reality.


System Architecture

The system consists of the following modules:

Input Acquisition
Preprocessing
Pose Estimation
Feature Extraction
Garment Alignment
Rendering
Output Display



https://github.com/user-attachments/assets/c6c7974f-4957-44f7-919f-12be93d87312





Features
🎥 Real-time webcam-based try-on
🧍 Human pose detection using key body landmarks
👕 Dynamic garment alignment (scaling, rotation, translation)
🎨 Realistic rendering with alpha blending and masking
⚡ Fast and efficient real-time performance
🖥️ Works on standard systems (no high-end GPU required)

Performance Evaluation

The system is evaluated based on:

Alignment Accuracy → Proper garment fitting
Real-Time Processing → Low latency
Visual Realism → Smooth and natural appearance
Robustness → Works under different lighting and movement conditions

```sh
# Clone the repository
git clone https://github.com/your-username/virtual-try-on.git

# Navigate to project folder
cd virtual-try-on

# Install dependencies
pip install -r requirements.txt

# Run the application
python app.py 


