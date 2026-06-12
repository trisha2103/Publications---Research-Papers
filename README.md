<div align="center">

# 🦴 Publications — Research Papers

### Deep Learning for Medical Image Analysis

[![Author](https://img.shields.io/badge/Author-Trisha%20Veronica%20M.%20Y.-blueviolet?style=for-the-badge)](https://github.com/trisha2103)
[![Domain](https://img.shields.io/badge/Domain-Medical%20AI%20%7C%20Deep%20Learning-blue?style=for-the-badge)](#)
[![Papers](https://img.shields.io/badge/Publications-2-green?style=for-the-badge)](#publications)
[![Institution](https://img.shields.io/badge/Institution-Saveetha%20University-orange?style=for-the-badge)](#)

---

> *Harnessing the power of deep learning to automate and improve bone fracture detection — bringing AI-assisted diagnostics closer to clinical reality.*

</div>

---

## 👩‍💻 About the Researcher

**Trisha Veronica M. Y.** was a researcher in the Department of Computer Science and Engineering at Saveetha University, India, specializing in **medical image analysis** and **deep learning**. Her work focuses on building and benchmarking state-of-the-art neural network architectures to support early and accurate diagnosis of bone fractures from X-ray imagery. Now she graduated doing Masters in Business Analytics from University Of Massachusetts Boston.

---

## 📚 Publications

### 📄 Paper 1 — XceptionNet vs CNN for Bone Fracture Detection

<table>
<tr>
<td><b>Title</b></td>
<td>Detection of Bone Fractures in Upper Extremities Using XceptionNet and Comparing the Accuracy with Convolutional Neural Network</td>
</tr>
<tr>
<td><b>Authors</b></td>
<td>Trisha Veronica M. Y. &amp; P. V. Pramila</td>
</tr>
<tr>
<td><b>Published In</b></td>
<td>Proceedings of the 1st International Conference on AI for Internet of Things (AI4IoT 2023)</td>
</tr>
<tr>
<td><b>Publisher</b></td>
<td>SCITEPRESS – Science and Technology Publications</td>
</tr>
<tr>
<td><b>DOI</b></td>
<td><a href="https://doi.org/10.5220/0012772300003739">10.5220/0012772300003739</a></td>
</tr>
<tr>
<td><b>Pages</b></td>
<td>360–366</td>
</tr>
<tr>
<td><b>License</b></td>
<td>CC BY-NC-ND 4.0</td>
</tr>
</table>

#### 🔬 Research Overview

This study evaluates a **novel XceptionNet deep learning model** against **Convolutional Neural Networks (CNN)** for classifying bone fractures in X-ray images of upper extremity regions (hands, wrists, forearms).

#### 📊 Key Results

| Model | Accuracy | Precision | F1-Score | Sensitivity | Specificity |
|-------|----------|-----------|----------|-------------|-------------|
| **XceptionNet** | **88.74%** | 88.45% | 89.68% | 90.94% | 87.86% |
| CNN | 72.50% | 88.82% | 89.11% | 89.40% | 89.73% |

> ✅ XceptionNet outperformed CNN in classification accuracy by **~16%** with statistical significance at **p < 0.001** (Independent Samples T-test, 95% CI).

#### 🗃️ Dataset

- **Source:** Kaggle — [Bone Fracture Detection Using X-Rays](https://www.kaggle.com/vuppalaadithyasairam/bone-fracture-detection-using-xrays)
- **Total Images:** 9,463 X-ray images (181 MB)
- **Train Set:** 8,987 images | **Validation Set:** 633 images
- **Classes:** Fractured / Not-Fractured

---

### 📄 Paper 2 — VGG-19 vs CNN for Bone Fracture Detection

<table>
<tr>
<td><b>Title</b></td>
<td>Detection of Bone Fracture in Upper Extremities Using Visual Geometric Group-19 and Compare the Accuracy with CNN</td>
</tr>
<tr>
<td><b>Authors</b></td>
<td>M. Y. T. Veronica, P. V. Pramila, K. Divya, S. K. Selvaperumal, D. Venu</td>
</tr>
<tr>
<td><b>Published In</b></td>
<td>AIP Conference Proceedings, Vol. 3161, Issue 1</td>
</tr>
<tr>
<td><b>Publisher</b></td>
<td>AIP Publishing</td>
</tr>
<tr>
<td><b>DOI</b></td>
<td><a href="https://doi.org/10.1063/5.0229450">10.1063/5.0229450</a></td>
</tr>
<tr>
<td><b>Article No.</b></td>
<td>020186</td>
</tr>
<tr>
<td><b>Published</b></td>
<td>August 2024</td>
</tr>
</table>

#### 🔬 Research Overview

This study investigates the **VGG-19 (Visual Geometric Group-19)** architecture — a deep 19-layer network renowned for its structured depth — and benchmarks it against a standard **CNN** for bone fracture detection in upper extremity X-rays.

#### 🧠 Why VGG-19?

VGG-19's deep, uniform architecture of small (3×3) convolutional filters is highly effective at capturing fine-grained spatial features in medical X-ray images, making it particularly suited for distinguishing subtle fracture patterns that simpler CNNs may miss.

---

## 🧬 Research Theme & Significance

```
Medical Imaging  →  Deep Learning Models  →  Fracture Classification  →  Clinical Decision Support
```

Bone fractures affect millions globally, yet radiological diagnosis is constrained by radiologist availability — with nearly **7.5× more scans** produced annually than there are radiologists to read them. This research directly addresses that gap by applying **Computer-Aided Diagnosis (CAD)** through state-of-the-art deep learning, enabling:

- ⚡ **Faster diagnosis** in emergency and clinical settings
- 🎯 **Higher accuracy** compared to traditional CNN baselines
- 🏥 **Scalable AI support** for resource-constrained healthcare environments
- 🔍 **Early fracture detection** to prevent downstream complications

---

## 🛠️ Technologies Used

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white)
![SPSS](https://img.shields.io/badge/IBM%20SPSS-052FAD?style=flat-square&logo=ibm&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white)

---

## 🏛️ Model Architectures

### XceptionNet
> Developed by Google, XceptionNet uses **Depthwise Separable Convolutions** to decouple channel-wise and spatial feature learning — achieving higher representational efficiency than standard convolutions.

### VGG-19
> A 19-layer deep network by Oxford's Visual Geometry Group, known for its simplicity and power. Uses uniform 3×3 filters throughout, making it effective for extracting hierarchical visual features from medical scans.

### CNN (Baseline)
> A standard Convolutional Neural Network used as the performance baseline in both studies.

---

## 📈 Model Comparison Summary

| Study | Best Model | Accuracy | Baseline (CNN) | Improvement |
|-------|-----------|----------|----------------|-------------|
| AI4IoT 2023 | XceptionNet | 88.74% | 72.50% | +16.24% |
| AIP 2024 | VGG-19 | TBD | Baseline | Significant |

---

## 📂 Repository Structure

```
Publications---Research-Papers/
│
├── Paper_1_XceptionNet/
│   ├── xceptionnet_model.py       # XceptionNet architecture & training
│   ├── cnn_baseline.py            # CNN baseline model
│   ├── evaluate.py                # Metrics: accuracy, precision, F1
│   └── results/                   # Confusion matrices, accuracy plots
│
├── Paper_2_VGG19/
│   ├── vgg19_model.py             # VGG-19 architecture & training
│   ├── cnn_baseline.py            # CNN baseline model
│   ├── evaluate.py                # Metrics evaluation
│   └── results/                   # Plots and performance tables
│
├── datasets/
│   └── README_dataset.md          # Dataset download instructions (Kaggle)
│
├── LICENSE
└── README.md
```

---

## 🔗 Citation

If you find this work useful, please cite:

```bibtex
@inproceedings{veronica2023xceptionnet,
  title     = {Detection of Bone Fractures in Upper Extremities Using XceptionNet 
               and Comparing the Accuracy with Convolutional Neural Network},
  author    = {Trisha Veronica, M. Y. and Pramila, P. V.},
  booktitle = {Proceedings of the 1st International Conference on AI for IoT (AI4IoT)},
  pages     = {360--366},
  year      = {2023},
  publisher = {SCITEPRESS},
  doi       = {10.5220/0012772300003739}
}

@article{veronica2024vgg19,
  title   = {Detection of Bone Fracture in Upper Extremities Using Visual 
             Geometric Group-19 and Compare the Accuracy with CNN},
  author  = {Veronica, M. Y. T. and Pramila, P. V. and Divya, K. 
             and Selvaperumal, S. K. and Venu, D.},
  journal = {AIP Conference Proceedings},
  volume  = {3161},
  number  = {1},
  pages   = {020186},
  year    = {2024},
  publisher = {AIP Publishing},
  doi     = {10.1063/5.0229450}
}
```

---

## 📬 Contact

**Trisha Veronica M. Y.**
Masters in Business Analytics with Big Data
University of Massachusetts Boston
Bachelors in Computer Science and Engineering
Saveetha University, India
🔗 GitHub: [@trisha2103](https://github.com/trisha2103)

---

<div align="center">

*"Bridging the gap between artificial intelligence and accessible healthcare — one X-ray at a time."*

⭐ If this research helped you, consider starring the repository!

</div>
