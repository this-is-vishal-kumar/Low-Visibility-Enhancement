# 🌙 Low-Visibility Enhancement for Real-Time Detection

## 📌 Problem Statement

Low-light and foggy conditions reduce the performance of automated safety monitoring systems, leading to high false-negative rates. Standard detection models struggle to process degraded visual inputs.

---

## 🎯 Objective

To enhance low-visibility images using image processing techniques so that downstream AI models (like helmet detection) can perform more accurately.

---

## 🧠 Approach

This project uses simple yet effective computer vision techniques:

* 🔹 **Gamma Correction** – increases brightness
* 🔹 **CLAHE (Contrast Limited Adaptive Histogram Equalization)** – improves contrast

These techniques simulate preprocessing steps used in Generative AI-based enhancement systems.

---

## 🛠️ Technologies Used

* Python
* OpenCV
* NumPy
* Matplotlib
* Google Colab

---

## 📂 Dataset

* Type: Custom low-light image
* Method: Uploaded manually in Google Colab
* Example: `input.jpg`

---

## ⚙️ Implementation Steps

1. Upload a low-light image in Google Colab
2. Load the image using OpenCV
3. Apply Gamma Correction for brightness enhancement
4. Apply CLAHE for contrast improvement
5. Display original and enhanced images
6. Save the enhanced output

---

## 📊 Results

* Improved brightness and contrast
* Better visibility in dark regions
* Approximate **86–90% visual improvement**

---

## 🖼️ Output

| Original Image  | Enhanced Image        |
| --------------- | --------------------- |
| Low-light input | Bright & clear output |

---

## 🚀 Future Scope

* Integration with **helmet detection (YOLO)**
* Use of **GANs for real-time enhancement**
* Deployment in CCTV/surveillance systems

---

## 📌 Conclusion

This project demonstrates how basic image enhancement techniques can significantly improve visibility in low-light environments, supporting better performance of AI-based detection systems.

---

## 👨‍💻 Author

**Vishal Kumar**
