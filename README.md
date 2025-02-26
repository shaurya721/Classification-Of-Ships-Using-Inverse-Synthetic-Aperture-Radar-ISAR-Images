# Classification-Of-Ships-Using-Inverse-Synthetic-Aperture-Radar-ISAR-Images
Developed an ISAR image classification model using fuzzy logic and deep learning, achieving 89.23% accuracy. Integrated YOLOv4, Faster R-CNN, and ANSYS SpaceClaim R2 for high-precision object detection and benchmarking.


# Ship Classification and Detection using ISAR Images

## Introduction
This project focuses on the development of an efficient and precise ship classification and detection system using Inverse Synthetic Aperture Radar (ISAR) images. The system integrates deep learning, computer vision, and fuzzy logic techniques to enhance accuracy and reliability in maritime surveillance and security applications.

## Features
- **ISAR Image Processing**: Generated ISAR images from STL files with varied azimuth, yaw, pitch, and roll angles.
- **Deep Learning-based Classification**: Developed a convolutional neural network (CNN) for ship classification using transfer learning with models like VGG-16.
- **Object Detection**: Implemented YOLOv4, RCNN, and Faster R-CNN for detecting ship features.
- **Fuzzy Logic Integration**: Designed a fuzzy inference system to enhance classification accuracy and handle uncertain data.
- **Dataset Creation**: Built a structured ISAR image database using MATLAB and ANSYS SpaceClaim R2.

## Technologies Used
- **Deep Learning**: CNN (VGG-16, ResNet), Transfer Learning
- **Computer Vision**: OpenCV, TensorFlow, YOLOv4, RCNN, Faster R-CNN
- **Fuzzy Logic**: MATLAB/Python Fuzzy Inference System
- **Radar Imaging**: ISAR Image Simulation using MATLAB and ANSYS
- **Programming Languages**: Python, MATLAB

## Project Workflow
1. **ISAR Image Generation**: Convert STL files into binary files and generate ISAR images at different orientations.
2. **Dataset Preparation**: Organize ISAR images into training and validation datasets.
3. **Neural Network Training**: Train a modified VGG-16 CNN for ship classification.
4. **Object Detection**: Implement YOLOv4, RCNN, and Faster R-CNN to identify ship features.
5. **Fuzzy Logic Classification**: Utilize extracted features to classify ships based on fuzzy logic rules.
6. **Performance Evaluation**: Validate results using accuracy-loss graphs and confusion matrices.

## Results
- Achieved **89.23% classification accuracy** using CNN and fuzzy logic.
- Improved accuracy by **12%** by integrating real-world ISAR data with fuzzy logic models.
- Successfully classified ships into **10 categories with 16 ship types**.

## Installation & Usage
### Prerequisites
- MATLAB (for ISAR image generation and fuzzy logic)
- Python 3.x
- TensorFlow & Keras
- OpenCV
- ANSYS SpaceClaim R2 (for 3D ship modeling)

### Steps to Run
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/ship-detection
   cd ship-detection
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Generate ISAR images using MATLAB scripts.
4. Train CNN models using the Python script:
   ```sh
   python train_model.py
   ```
5. Run object detection:
   ```sh
   python detect_ships.py
   ```
6. Apply fuzzy logic classification in MATLAB or Python.

## Dataset
- Contains ISAR images of 16 ship types across 10 categories.
- Includes ISAR feature extraction and classification results.
- Labeled data created using MATLAB’s Image Labeler tool.

## Contributors
- Shaurya
- DROO Scientist-E Dr. Dyana A.

## License
This project is licensed under the MIT License.

## Acknowledgments
- Deep learning and computer vision research communities.
- MATLAB and TensorFlow documentation.
- ANSYS SpaceClaim R2 for 3D ship modeling support.

---
For more details, refer to the full project documentation.
