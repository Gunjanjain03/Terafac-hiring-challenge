# Terafac-hiring-challenge
# Terafac ML Hiring Challenge
Gunjan Jain

## Problem
Image classification on CIFAR-10 using a multi-level evaluation framework.

## Dataset
- CIFAR-10 (60,000 images, 10 classes)
- Split: 80% Train / 10% Validation / 10% Test

## Tools & Frameworks
- Python
- PyTorch
- Google Colab (GPU)
- torchvision, sklearn, matplotlib

---

## Levels Completed

### Level 1 – Baseline Model
- Model: ResNet18 (pretrained)
- Test Accuracy: **91.72%**

### Level 2 – Intermediate Techniques
- Added data augmentation (RandomCrop, Flip, ColorJitter)
- Accuracy improved to: **92.66%**
- Performed ablation study (baseline vs augmented)

### Level 3 – Advanced Analysis
- Confusion Matrix
- Per-class accuracy analysis
- Grad-CAM visualization for interpretability

### Level 4 – Advanced Technique (TTA)
- Implemented Test-Time Augmentation (horizontal flip + averaging)
- Accuracy improved to: **93.38%**

---

