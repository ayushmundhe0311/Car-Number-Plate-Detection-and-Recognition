# **Car Number Plate Extraction and Recognition**

## **Project Overview**
This project aims to develop a robust system capable of accurately detecting and recognizing car number plates from images. Leveraging advanced deep learning techniques, the system is designed to achieve high performance and reliability in real-world scenarios.

---

## **Methodology**
1. **Dataset Preparation**:
   - A dataset of 900 car images was collected, each featuring a clearly visible number plate.
   - Bounding box annotations were created in a CSV format, specifying the coordinates of the number plates.
   - A script converted these annotations into individual TXT files, compatible with YOLOv8's training format.
   - The dataset was divided into training and validation sets, organized into appropriate directories for model training.

2. **Number Plate Detection**:
   - YOLOv8, a state-of-the-art object detection model, was trained on the prepared dataset.
   - The trained model was used to detect and localize number plates within input images.
   - Detected number plates were saved for further processing.

3. **Number Plate Recognition**:
   - The EasyOCR library was employed to extract the text from the detected number plates.
   - EasyOCR’s optical character recognition capabilities were utilized to recognize characters and digits accurately.

---

## **Key Technologies and Tools**
- **YOLOv8**: A cutting-edge object detection framework known for its speed and accuracy.
- **EasyOCR**: A powerful library for optical character recognition.
- **Python**: The primary programming language used for implementation.
- **TensorFlow**: A popular deep learning framework utilized for supporting tasks.

---

## **Expected Outcomes**
- A highly accurate system capable of detecting and recognizing car number plates in real-world scenarios.
- Practical applications in traffic management, law enforcement, parking systems, and more.
- Potential for further enhancements and seamless integration with other systems.

---

## **Future Work**
- Improve recognition accuracy in challenging conditions such as low lighting and occlusions.
- Explore the use of Generative Adversarial Networks (GANs) to augment the training dataset for enhanced performance.
- Develop real-time video processing capabilities to extend the system's functionality to dynamic environments.

--- 
