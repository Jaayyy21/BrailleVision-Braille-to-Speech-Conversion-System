# BrailleVision 🔡🔊 — Braille to Speech Conversion System

A real-time Braille recognition and text-to-speech system built using deep learning.
Designed to improve accessibility for visually impaired users by converting Braille
characters into spoken audio in English and Tamil.

## 🚀 Features
- Real-time Braille character detection using YOLOv12 and Faster R-CNN
- 98% classification accuracy on test data
- Multilingual speech output — English and Tamil (via gTTS)
- Trained on a custom dataset of 3,000+ annotated Braille samples from Kaggle

## 🧠 Models Used
- **YOLOv12** — real-time object detection
- **Faster R-CNN** — high-accuracy Braille classification
- Dataset sourced and preprocessed from Kaggle

## 🛠️ Tech Stack
- Python
- YOLOv12, Faster R-CNN
- PyTorch
- gTTS (Google Text-to-Speech)
- Google Translate API
- NumPy, Pandas

## 📁 Project Structure
```
├── Yolo.ipynb                  # YOLOv12 training, inference & TTS pipeline
├── Untitled.ipynb              # Faster R-CNN experiments
├── braille_data.yaml           # Dataset configuration
├── training_runs/              # Training results and metrics
├── test_images/                # Sample test images
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
pip install ultralytics torch torchvision gtts googletrans==4.0.0rc1
```
3. Open `Yolo.ipynb` in Jupyter and run the cells
> ⚠️ Requires an active internet connection for Google Translate and gTTS

## 👥 Team
Built by a team of 3 as part of a project at VIT Chennai (2025)

## 📌 Note
Model weights and dataset are not included due to file size.
Dataset available on Kaggle — contact for access.
