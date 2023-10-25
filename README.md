
# Surface Defect Detection

**Table of Contents**
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Getting Started](#getting-started)
- [Features](#features)
- [Example Use Cases](#example-use-cases)
- [Screenshots](#screenshots)
- [Requirements](#requirements)
- [Dataset](#dataset)
- [Lessons Learned](#lessons-learned)


**Introduction**

Surface Steel Defect Detection is a computer vision project aimed at automating the identification and classification of common defects in steel surfaces. Leveraging state-of-the-art object detection techniques, particularly the YOLO (You Only Look Once) model, the project can accurately detect six types of surface defects: Craze, Patches, Scratches, Rolled-in Surface, Pitted Surface, and more. The model has been trained on a dataset of over 5,000 images, employing data augmentation to enhance its performance. This system can identify defects in real-time from images or video streams, providing an accuracy rate of approximately 70%. Additionally, an Arduino signal light is integrated to indicate defect presence, offering a practical solution for quality control in steel manufacturing.



## Project Overview

The primary goal of this project is to provide a robust and automated solution for detecting defects in steel surfaces. By adopting YOLO, a state-of-the-art object detection model, this project can identify various defects in real-time from images or video streams. The dataset used for training the model is sourced from Northeastern University (NEU) and contains over 5,000 images. Data augmentation techniques, such as rotation, scaling, and flipping, were applied to enrich the dataset and enhance the model's accuracy.
## Getting Started

Before you begin, ensure you have the following prerequisites:

- Python and Jupyter Notebook installed on your computer.
- The Arduino IDE installed to upload code to your Arduino board.
- An Arduino board (e.g., Arduino Uno) and a USB connection.
- A compatible camera or webcam for image capture.
## Features

The Surface Steel Defect Detection project offers the following features:

- Utilizes the YOLO model for accurate defect detection.
- Detects six common steel surface defects: Craze, Patches, Scratches, Rolled-in Surface, and Pitted Surface.
- Achieves an accuracy rate of approximately 70%.
- Real-time defect detection from images or video streams.
- Integration with Arduino for signaling when a defect is detected.


## Example Use Cases

To get started with this project, you can run the application with the following command:

Follow the on-screen instructions to start the defect detection process. The YOLO model will automatically identify defects in real time on captured images or video streams. If a defect is detected, an Arduino-operated signal light will activate, indicating the presence of a defect.

```bash
python main.py
```


## Screenshots

![App Screenshot](https://drive.google.com/file/d/1cz681dnPzfwVEQa2OfafQCipY8NWxHLt/view?usp=sharing)
![App Screenshot](https://drive.google.com/file/d/1rP3WPcHGkE48v2Bh-LvRkXK0q1jQaUT0/view?usp=sharing)



## Requirements

Before using this system, ensure you have the following prerequisites:

- Python 3.6+
- OpenCV
- YOLO model
- Arduino for signal light integration
## Dataset

The dataset used for training this model is obtained from Northeastern University (NEU) and contains images of six common steel surface defects: Craze, Patches, Scratches, Rolled-in Surface, Pitted Surface. The dataset includes over 5,000 images that were utilized to train the YOLO model.
## Lessons Learned

What did you learn while building this project? What challenges did you face and how did you overcome them?

Data Augmentation Is Crucial: Data augmentation significantly improved the model's performance. Techniques like rotation, flipping, and adding noise helped the model generalize better, especially on limited datasets.

Robust Dataset Selection: Selecting a diverse dataset is vital for detecting a wide range of defects. The NEU dataset, with its six defect types, was instrumental in achieving comprehensive defect identification.

YOLO for Real-time Detection: YOLO's speed and accuracy make it an ideal choice for real-time defect detection. It allows for quick identification and can be integrated with hardware interfaces like Arduino.

Accuracy vs. Speed Trade-off: Achieving high accuracy often comes at the cost of speed. Striking the right balance between accuracy and real-time detection is essential, depending on specific project requirements.

Interfacing with Hardware: Integrating the system with Arduino for signal lights or other hardware interfaces enhances its practicality in industrial settings.

Continuous Improvement: Machine learning models need ongoing refinement and adaptation to maintain their effectiveness as new data becomes available.

Open Source Community: Leveraging open-source tools and resources is invaluable for developing cost-effective solutions.

Domain Expertise Matters: Understanding the domain and the types of defects you're working with is crucial for model training and validation.

