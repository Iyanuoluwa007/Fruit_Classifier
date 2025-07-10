# 🍎 Fruit Freshness Classifier

This project uses deep learning and computer vision to classify fruit images as **fresh** or **rotten** using transfer learning with VGG16. It also supports real-time predictions from webcam or image input.

---

## 📌 Project Highlights

- Transfer Learning with **VGG16**
- Supports **Apple**, **Banana**, and **Orange**
- Distinguishes between **fresh** and **rotten** states
- Inference from **image files** or **live webcam**
- Built with **PyTorch**, **TorchVision**, and **OpenCV**

---

## 🧠 Model Details

- **Backbone:** `VGG16` (pretrained on ImageNet)
- **Classifier:** Custom fully connected layers
- **Classes:** 6
  - `fresh apple`
  - `fresh banana`
  - `fresh orange`
  - `rotten apple`
  - `rotten banana`
  - `rotten orange`
- **Input Size:** 224x224

