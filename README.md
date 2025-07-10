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

## 🗂️ Dataset

- Source: [Fruits Fresh and Rotten for Classification – Kaggle](https://www.kaggle.com/datasets/sriramr/fruits-fresh-and-rotten-for-classification?resource=download)


## 🖼️ From Image
Inside `fruit_predictor.py`, uncomment and update the following line:
'predict_from_image("path/to/image.jpg", my_model, device)'

## 🎥 From Webcam
Inside `fruit_predictor.py`, uncomment the webcam line:
'predict_from_camera(my_model, device)'

Press 'q' to quit webcam mode.
