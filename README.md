 AI Deepfake Detection System

![Deepfake Detection Banner](assets/banner.png)

An AI-powered Streamlit application for **deepfake detection** in videos and live webcam streams using a **Vision Transformer (ViT)** model. This system analyzes faces frame-by-frame and provides real-time predictions with confidence scores.

---

  About The Project

Deepfakes are becoming increasingly realistic and pose serious risks in areas like **online interviews, identity verification, and digital media trust**.

This project provides a **real-time detection system** that:
- Identifies manipulated (deepfake) faces
- Works on both uploaded videos and live webcam feed
- Gives clear visual and statistical feedback

---

  Features

-  **Video Detection**
  - Upload MP4, AVI, MOV files
  - Frame-by-frame analysis
  - Bounding boxes with predictions

-  **Live Webcam Detection**
  - Real-time face detection
  - Instant classification (Real / Fake)
  - Confidence scores

-  **AI Model**
  - Vision Transformer (ViT)
  - Fine-tuned for deepfake classification

-  **Analytics Dashboard**
  - Majority voting system
  - Detection summary
  - Confidence metrics

-  **Modern UI**
  - Built with Streamlit
  - Clean layout with custom styling

---

 Tech Stack

- **Frontend/UI**: Streamlit  
- **Backend**: Python  
- **Computer Vision**: OpenCV  
- **Deep Learning**: PyTorch, Hugging Face Transformers  
- **Model**: Vision Transformer (ViT)  

---

 Installation

 1️ Clone the Repository

```bash
git clone https://github.com/your-username/deepfake-detection-system.git
cd deepfake-detection-system
