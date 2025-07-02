# 🦺 PPE Detection in Construction Sites

This project demonstrates a computer vision system for detecting and tracking **Personal Protective Equipment (PPE)** — such as helmets and safety vests — in construction site footage. It aims to improve **workplace safety monitoring** using AI.

> ✅ Real-time detection and tracking  
> 🎥 Includes video demos (`.mp4`)  
> 🖥️ GUI-based interface with `UI.py`  

---

## 📂 Demo Videos

| Type | Preview |
|------|--------|
| PPE Detection | 🎥 [`DEMO_Detect.mp4`](./DEMO_Detect.mp4) |
| PPE Inspection | 🎥 [`DEMO_PPE_Inspection.mp4`](./DEMO_PPE_Inspection.mp4) |
| Tracking Demo | 🎥 [`DEMO_Tracking_15s.mp4`](./DEMO_Tracking_15s.mp4) |

You can download and play these locally to see the detection system in action.

---

## 🛠️ How It Works

- **`Detection.py`**: Core object detection logic (helmet, vest, person, etc.)
- **`UI.py`**: User interface with real-time video input and overlay
- **`Tracking_State.csv`**: Stores tracking output or inspection states
- **`NoteBook.ipynb`**: Contains experiment/test notebook
- **Model Weights**: (You may need to provide or link pretrained weights here)

---

## 🚀 Getting Started

### 1. Install Dependencies
```bash
pip install opencv-python torch torchvision numpy
