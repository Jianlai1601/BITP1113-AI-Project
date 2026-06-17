# SafeEntry AI: Real-Time PPE Safety Compliance Monitor

## Overview

SafeEntry AI is a web-based Artificial Intelligence system developed for Universiti Teknikal Malaysia Melaka (UTeM) to monitor Personal Protective Equipment (PPE) compliance in science laboratories. The system uses image classification to determine whether a student is wearing the required PPE before entering the laboratory.

The AI model is trained using Google Teachable Machine and deployed through TensorFlow.js, allowing real-time prediction directly within a web browser.

---

## Problem Statement

Laboratory safety compliance is commonly checked manually by laboratory staff. This approach can be time-consuming, inconsistent, and prone to human error. Students may unintentionally enter laboratory areas without the required safety equipment, increasing the risk of accidents and safety violations.

SafeEntry AI addresses this problem by automating PPE verification using Artificial Intelligence and Computer Vision technologies.

---

## Project Objectives

* Develop an AI-based image classification model for PPE compliance detection.
* Classify students as **Compliant** or **Non-Compliant**.
* Integrate the trained model into a web-based dashboard.
* Provide real-time predictions with confidence scores.
* Support safer laboratory environments through automated monitoring.

---

## System Workflow

1. Student stands in front of the webcam.
2. The system captures an image after scanning.
3. The AI model analyzes the image.
4. The system checks for the presence of:

   * Face Mask
   * Lab Coat
   * Matric Card
5. The model classifies the student as:

   * **Compliant**
   * **Non-Compliant**
6. The result and confidence score are displayed instantly on the dashboard.

---

## Technologies Used

* Google Teachable Machine
* TensorFlow.js
* HTML5
* CSS3
* JavaScript
* GitHub Pages

---

## AI Model

The project uses a Convolutional Neural Network (CNN) model trained with Google Teachable Machine.

### Classes

#### Compliant

Student is wearing:

* Face Mask
* Lab Coat
* Matric Card

#### Non-Compliant

Student is missing one or more required PPE items.

### Dataset Variations

To improve model robustness, images were collected under different conditions:

* Various lighting conditions
* Different camera angles
* Different distances
* Partial occlusions

---

## Features

* Real-time PPE compliance detection
* Webcam-based image capture
* Confidence score visualization
* Compliance statistics tracking
* User-friendly dashboard interface
* Browser-based deployment

---

## Results

Testing demonstrated high confidence scores for PPE compliance classification under normal laboratory conditions.

| Test Case           | Prediction    | Confidence |
| ------------------- | ------------- | ---------- |
| Complete PPE        | Compliant     | 98.7%      |
| Missing Matric Card | Non-Compliant | 96.2%      |
| Missing Face Mask   | Non-Compliant | 94.5%      |

The system successfully performed real-time PPE verification and correctly classified all tested scenarios.

---

## Future Improvements

* Expand the training dataset.
* Improve performance under challenging lighting conditions.
* Integrate with laboratory access control systems.
* Support multi-user detection.
* Implement automatic attendance and logging features.

---

## Project Team

**Group 14**

* Muhammad Najib Bin Mohd Nizam
* Ainnur Humairah Iryna Binti Ahmad Termizi
* Lai Yong Jian
* Ayu Natasha Binti Afainizam

Universiti Teknikal Malaysia Melaka (UTeM)

---

## Live Demo

Project Website:

https://jianlai1601.github.io/BITP1113-AI-Project/

---

## License

This project was developed for academic purposes as part of the BITI1113 Artificial Intelligence course at Universiti Teknikal Malaysia Melaka (UTeM).
