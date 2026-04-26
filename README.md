# Deep Learning Based Skin Disease Classification

This project implements a clinical decision support system for dermatological diagnosis using Transfer Learning with **MobileNet** architectures.

## 🚀 Highlights
- **Architecture:** MobileNet V1, V2, and V3 comparison.
- **Accuracy:** Achieved **71% validation accuracy** with MobileNet_V1.
- **Dataset:** 10 different skin disease categories.
- **Optimization:** Implemented `tf.data` API for optimized GPU performance (Dual NVIDIA Tesla T4).

## 📊 Performance Comparison
| Model | Accuracy | Loss |
|-------|----------|------|
| MobileNet_V1 | **%71** | **0.80** |
| MobileNet_V2 | %65 | 0.92 |
| MobileNet_V3 | %35 | 1.82 |

## 🧪 Real-World Inference Result
The model successfully identified a "Melanocytic Nevi" with a confidence score.
![Inference Result](images/teshis_gorseli.png)

## 🛠️ Tech Stack
- Python, TensorFlow, Keras
- Kaggle (Training), Google Colab (Testing)
- Matplotlib (Visualization)

- ## 📦 Trained Models
Due to file size limits on GitHub, all trained models are hosted on Google Drive. 
You can access and download them from the link below:

[Click here to access Trained Models Folder](https://drive.google.com/drive/folders/1SnRYbHE_cqNf_AiEvEM2B1ioLCM8VD1Q?usp=sharing)
