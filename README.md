# Action Detection and Tracking with YOLOv8 + DeepSORT

This project performs **object detection and tracking** on CCTV footage using YOLOv8 and DeepSORT. It supports both image and video processing, and includes visualization and evaluation metrics (MOTA, IDF1).

## 📁 Folder Structure

train/
├── Normal/
├── Peaking/
├── Sneaking/
└── Stealing/

markdown
Copy
Edit

## 🚀 Features

- ✅ YOLOv8-based object detection
- 🎯 DeepSORT tracking
- 📉 Frame-wise object count plots
- 🧪 MOTA & IDF1 evaluation using `motmetrics`
- 📸 Visual outputs saved for both images and videos

## 🛠️ Setup

```bash
pip install -r requirements.txt
🧪 Run Tracking on Images

python track_images.py
🎥 Run Tracking on Video

python track_video.py
🤝 Contributing
Fork this repo

Create a branch: git checkout -b feature/your-feature

Commit and push: git commit -am "Add feature" → git push origin feature/your-feature

Open a pull request

📄 License
MIT License



