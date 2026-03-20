# BrailleVision 🔡🔊 — Braille to Speech Conversion System

A real-time Braille recognition and text-to-speech system built using deep learning. 
Designed to improve accessibility for visually impaired users by converting Braille 
characters into spoken audio across multiple languages.

## 🚀 Features
- Real-time Braille character detection using YOLOv12 and Faster R-CNN
- 98% classification accuracy on test data
- Multilingual text-to-speech output
- Trained on a custom dataset of 3,000+ annotated Braille samples

## 🧠 Models Used
- **YOLOv12** — for real-time object detection
- **Faster R-CNN** — for high-accuracy classification
- Dataset sourced and preprocessed from Kaggle

## 🛠️ Tech Stack
- Python
- YOLOv12, Faster R-CNN
- PyTorch
- NumPy, Pandas
- Text-to-Speech (TTS) library

## 📁 Project Structure
```
├── Yolo.ipynb               # YOLOv12 training and inference
├── Untitled.ipynb           # Faster R-CNN experiments  
├── braille_data.yaml        # Dataset configuration
├── training_runs/           # Training results and metrics
├── test_images/             # Sample test images
```

## 📊 Results
| Model | Accuracy |
|-------|----------|
| YOLOv12 | 98% |
| Faster R-CNN | ~96% |

## 🔧 How to Run
1. Clone the repo
```bash
git clone https://github.com/Jaayyy21/BrailleVision-Braille-to-Speech-Conversion-System.git
```
2. Install dependencies
```bash
pip install ultralytics torch torchvision gtts
```
3. Open `Yolo.ipynb` in Jupyter and run the cells

## 👥 Team
Built by a team of 3 as part of final year project at VIT Chennai (2025)

## 📌 Note
Model weights are not included in this repo due to file size. 
Dataset available on Kaggle — contact for details.
