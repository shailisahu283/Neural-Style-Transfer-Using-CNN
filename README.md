# 🎨 Neural Style Transfer Using CNN 🧠🖼️

Welcome to the **Neural Style Transfer** project! This repository showcases a powerful computer vision technique using Convolutional Neural Networks (CNNs) to transform a content image with the artistic style of another image. The implementation uses TensorFlow and a pre-trained model from TensorFlow Hub to stylize images in real time.

---

## 📋 Table of Contents

* Project Description
* Requirements
* Week 1 Overview
* Week 2 Overview
* Week 3 Overview
* How to Run the Project
* Output Example
* License

---

## 📝 Project Description

This project implements Neural Style Transfer using a model trained on millions of images to extract content and style features. By leveraging deep layers of VGG19 and style/content loss functions, it stylizes one image (content) using the artistic elements of another (style). Applications include creative design, photo enhancement, and real-time art filters.

The model can be run on local machines or Google Colab, and produces fast, high-quality results without retraining.

---

## 🧠 Key Features

* **Fast Arbitrary Image Stylization** using TensorFlow Hub.
* **Content/Style Feature Extraction** using VGG19 CNN layers.
* **No Retraining Required** – supports any content and style image pair.
* **Easily Extendable** – batch processing, UI integration, or app deployment.

---

## 🧰 Requirements

To run this project, you’ll need:

* Python 3
* TensorFlow
* TensorFlow Hub
* NumPy
* Pillow (PIL)
* Matplotlib
* Google Colab (optional, for cloud execution)

Install dependencies:

```bash
pip install -r requirements.txt
```

**requirements.txt**

```
tensorflow
tensorflow-hub
numpy
pillow
matplotlib
```

---

## 📅 Week 1 Overview

**What was done:**

* Loaded and preprocessed content and style images 🖼️
* Loaded a pre-trained style transfer model from TensorFlow Hub ⚙️
* Implemented image resizing, normalization, and formatting

**Goals:**

* Understand neural style transfer pipeline
* Setup image transformation functions

---

## 🗓️ Week 2: Stylization Execution & Enhancements

**Improvements:**

* Stylized image generation with various content/style pairs
* Added matplotlib-based visualization of input and result images
* Optimized image tensor conversion pipeline

---

## 📈 Week 3: Output Saving & Experimentation

**Enhancements:**

* Saved stylized images automatically to output folder
* Batch stylization supported by looping over multiple content images
* Refactored notebook structure for modular reuse

---

## ⚙️ How to Run the Project

1. Clone the repo:

```bash
git clone https://github.com/yourname/neural-style-transfer-cnn.git
```

2. Upload your content/style images to the appropriate folders:

```
content/
style/
```

3. Run the notebook:

```bash
notebooks/fast_style_transfer.ipynb
```

4. Output image will be saved in:

```
output/
```

---

## 🖼️ Output Example

```
output/
├── stylized_output.jpg   # Final stylized image
```

Example visual: Left - Content | Middle - Style | Right - Stylized Result 🎨

To improve this section, include sample images:

* 📷 Realistic photo (e.g., portrait, cityscape)
* 🖌️ Artistic image (Van Gogh, Picasso, etc.)
* 🎨 Stylized result image

---

## 📝 License

This project is open-source under the MIT License.

---

## 🤖 Contributions

Pull requests, ideas, and issues are welcome. Help expand it with better models, mobile support, or deployment tools!

---

## 👤 Author

Your Shaili Sahu Here
✉️ Email: [shailisahu283@gmail.com](shailisahu283@gmail.com)
