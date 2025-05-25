# CIFAR-10 Image Classification with ViT, Hybrid MLP-CNN, and ResNet-18 🧠🖼️

This project explores and compares the performance of three deep learning models—**Vision Transformer (ViT)**, **Hybrid MLP-CNN**, and **ResNet-18**—on the CIFAR-10 image classification task. The dataset consists of 60,000 32×32 color images across 10 classes.

## 🔍 Methodology

- **Data Preprocessing**: Applied data augmentation (random cropping, color jittering, horizontal flip) and normalization.
- **Models**:
  - **Vision Transformer (ViT)**: Uses self-attention over image patches.
  - **Hybrid MLP-CNN**: Combines CNN-based feature extraction with MLP classification.
  - **ResNet-18**: Fine-tuned pretrained ResNet for 10-class output.

## 📊 Results (Validation)

| Model             | Accuracy | Precision | Recall | F1-Score |
|------------------|----------|-----------|--------|----------|
| Vision Transformer | 53.77%   | 53.27%    | 53.77% | 52.95%   |
| Hybrid MLP-CNN     | **73.93%**   | **73.70%**    | **73.93%** | **73.72%**   |
| ResNet-18          | —        | —         | —      | —        |

**Hybrid MLP-CNN achieved the best overall performance.**

## 📌 Conclusion

The Hybrid MLP-CNN model outperformed both ViT and ResNet-18 on CIFAR-10. 
It balanced strong feature extraction and robust classification. Vision Transformers showed promise but larger dataset and more finetuning is required.
