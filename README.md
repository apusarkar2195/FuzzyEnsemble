# [Sugeno Fuzzy Integral Based Ensemble of Deep Learners for Human Activity Recognition Using Sensor Data](https://link.springer.com/article/10.1007/s13748-025-00381-0?utm_source=rct_congratemailt&utm_medium=email&utm_campaign=nonoa_20250626&utm_content=10.1007%2Fs13748-025-00381-0)

This repository contains the code implementation for our research paper:

> **"[Sugeno Fuzzy Integral Based Ensemble of Deep Learners for Human Activity Recognition Using Sensor Data](https://link.springer.com/article/10.1007/s13748-025-00381-0?utm_source=rct_congratemailt&utm_medium=email&utm_campaign=nonoa_20250626&utm_content=10.1007%2Fs13748-025-00381-0)"**

We explore how fuzzy logic-based ensemble methods—specifically the **Sugeno fuzzy integral**—can be leveraged to improve classification performance in Human Activity Recognition (HAR) using sensor data collected from wearable devices such as smartphones and smartwatches.

---

## 🧠 Overview

Human Activity Recognition (HAR) has broad applications in areas such as healthcare monitoring, fitness tracking, and smart environments. This project proposes a deep ensemble learning framework where predictions from three deep learning models are fused using the **Sugeno fuzzy integral**, with the associated fuzzy measures learned through a **genetic algorithm-based optimization** technique.

---

## 🏗️ Model Architecture

We use the following three base classifiers:

- **CNN-LSTM**: For temporal and spatial feature learning.
- **VGG-16-based model**: For deep spatial representation learning.
- **ResNet-18-based model**: For residual feature extraction.

The output probabilities from these models are combined using the **Sugeno fuzzy integral**. Fuzzy measures (i.e., the importance/confidence of each model) are optimized using a **Genetic Algorithm**.

---

## 📊 Results

| Dataset   | Accuracy (%) |
|-----------|---------------|
| WISDM     | 98.28         |
| PAMAP2    | 98.40         |
| MHEALTH   | 99.72         |

---

## Citation
If you use this repository or our work, please cite the following paper:
```bash
@article{mondal2025sugeno,
  title={Sugeno fuzzy integral based ensemble of deep learners for human activity recognition using sensor data},
  author={Mondal, Pushan and Sarkar, Apu and Sarkar, Ram},
  journal={Progress in Artificial Intelligence},
  pages={1--18},
  year={2025},
  publisher={Springer}
}
```
