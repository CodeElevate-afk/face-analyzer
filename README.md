# 👤 AI Skin + Face Analyzer (Development Version)

> A Google Colab-ready AI project to analyze facial age, emotion, and skin conditions (e.g., pimples or dullness) using real-time webcam input. Designed for future mobile/web deployment.

---

## 🚧 Status: In Development

This project is currently in **development mode**. The current focus is on improving face detection accuracy, skin spot classification, and integrating AI-based personalized skincare advice.

---

## 🔍 Features (Current Version)

* 📷 Capture photo via **webcam input** (Google Colab + JavaScript)
* 🤖 Detect **age** and **emotion** using DeepFace
* 🧴 Detect **pimples or skin scars** via OpenCV thresholding
* 💡 Generate **AI-based skincare advice** using logic-based reasoning
* 📈 Visualize skin issues on the face image

---

## 📦 Setup (Google Colab)

1. Open Google Colab: [https://colab.research.google.com/](https://colab.research.google.com/)
2. Upload the `ai_skin_face_analyzer.ipynb` or copy-paste the code.
3. Run all cells in order.
4. Use webcam to capture face image.

---

## 📁 File Structure

```bash
├── ai_skin_face_analyzer.ipynb    # Main notebook (capture, analysis, advice)
├── cropped_face.jpg               # Saved cropped face image
├── captured_face.jpg              # Original captured image
└── README.md                      # Project overview (this file)
```

---

## 🛠️ Tech Stack

* Python 3
* OpenCV
* DeepFace (Keras backend)
* Matplotlib
* Google Colab + JavaScript (for webcam)

---

## 🚀 Planned Features

* Real-time pimple detection using YOLOv5 or MobileNet
* Skin tone analysis (glow/dull/dry)
* Dermatologist-trained advice classifier
* Export model to Android/iOS
* Multi-face detection and individual analysis

---

## 🙋‍♂️ How to Contribute

We welcome contributions from the community:

* Fork the repo
* Clone locally
* Submit a PR with improvements (face detection, dataset integration, etc.)

---

## 📄 License

MIT License

---

## 💬 Contact

Author: Rishab Roy
Project Maintainer: Open for collaboration

---

> ⭐ Star this repo if you find it helpful. Stay tuned for the production-ready version!
