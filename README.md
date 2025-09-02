# AI-Powered Industrial Quality Control for Package Inspection

## 📌 Project Overview
This project aims to build an **AI-driven quality control system** for industrial packaging lines. The system ensures **product integrity**, detects **physical damages**, and verifies **printed serial numbers** using computer vision and OCR techniques.

The solution combines **image classification** and **text recognition** to automate the inspection process, reducing manual intervention and improving operational efficiency.

---

## ✅ Key Objectives
1. **Multi-View Package Classification**  
   - Train a deep learning model to classify **damaged** vs **intact** packages using images captured from **top view** and **side view**.
   - Detect structural defects, dents, and deformations accurately.

2. **Single-View Package Classification**  
   - Develop a secondary model that performs classification using **only top-view images**.
   - Reduce dependency on multiple cameras and lower computational costs while maintaining accuracy.

3. **OCR for Serial Number Extraction**  
   - Implement an **Optical Character Recognition (OCR)** system to extract and verify **serial numbers** printed on packages.
   - Ensure correct labeling, traceability, and compliance with manufacturing standards.

---

## 🛠️ Tech Stack
- **Programming Language:** Python  
- **Deep Learning Frameworks:** TensorFlow   
- **OCR Engine:** Tesseract OCR / EasyOCR  
- **Image Processing:** Tensorflow , Keras
 

---

## 🔍 Workflow & Architecture
1. **Data Collection:**  
   - Capture package images from top and side views.
   - Label data for **damaged** and **intact** classes.

2. **Model 1:**  
   - Train CNN-based classifier on **multi-view images** for high-accuracy defect detection.

3. **Model 2:**  
   - Train a lightweight CNN on **top-view images only** for faster inference.

4. **OCR Module:**  
   - Apply OCR to extract serial numbers and validate them against the database.

5. **Integration:**  
   - Combine classification and OCR into a unified pipeline for real-time industrial quality control.

---

## 📂 Project Structure
├── data/
│ ├── top_view/
│ ├── side_view/
│ ├── annotations/
├── models/
│ ├── multi_view_classifier.h5
│ ├── top_view_classifier.h5
├── ocr/
│ ├── ocr_extraction.py
├── scripts/
│ ├── train_classifier.py
│ ├── predict.py
├── README.md
└── requirements.txt


---

## 🚀 Real-World Impact
- **Automation:** Reduces manual inspection workload and human error.
- **Speed & Efficiency:** Enables **real-time defect detection** on packaging lines.
- **Accuracy:** Improves defect detection reliability and ensures compliance with quality standards.
- **Traceability:** Serial number verification ensures correct product labeling and inventory tracking.

---

## 📈 Future Enhancements
- Integrate with **edge devices** for on-site processing.
- Deploy as a **web-based dashboard** for monitoring inspection statistics.
- Implement **real-time alerts** for damaged package detection.

---

## 👩‍💻 Author
**Nikita Deshmukh**  
*BSc Data Science | ML AI Enthusiast*  


