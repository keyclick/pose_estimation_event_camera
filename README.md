# Pose Estimation with MoveNet (Google Colab Compatible)

This repository contains a portable Jupyter Notebook that demonstrates human pose estimation using the [MoveNet](https://www.tensorflow.org/lite/models/pose_estimation/overview) model via TensorFlow Hub.

## 📌 Features
- Uses **MoveNet SinglePose Lightning** model.
- Allows users to **upload any image** directly in Google Colab.
- Automatically detects and visualizes human body keypoints.
- No setup required — works entirely in the cloud.

---

## 🚀 Run in Google Colab

Click the badge below to open the notebook directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/your-repo/blob/main/pose_estimation_colab.ipynb)

---

## 🖼️ Usage Instructions

1. Open the notebook in [Google Colab](https://colab.research.google.com/).
2. Upload an image when prompted.
3. The notebook will run inference and display detected keypoints.

**Note:** If running outside Colab, update the `image_path` variable manually with the path to your local image.

---

## 📂 File Structure

```
📦 your-repo/
├── pose_estimation_colab.ipynb      # ✅ Main notebook
├── README.md                        # 📘 This file
└── assets/
    └── sample_image.jpg             # (Optional) Sample image
```

---

## 🧠 Model Info

- **Model**: MoveNet SinglePose Lightning
- **Source**: [TF Hub Link](https://tfhub.dev/google/movenet/singlepose/lightning/4)
- **Resolution**: 192x192 input size

---

## 📄 License

MIT License. See [LICENSE](LICENSE) for details.
