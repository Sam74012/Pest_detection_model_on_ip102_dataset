Pest Detection with EfficientNet-B0 (IP102 Dataset)

This repository contains experiments on pest classification using the IP102 dataset. We fine-tuned a pretrained EfficientNet-B0 model (from Torchvision) to detect and classify 102 different pest species commonly affecting crops.

🔹 Key Features

Dataset: IP102 (large-scale pest dataset with 102 classes).

Model: EfficientNet-B0 pretrained on ImageNet, fine-tuned for pest detection.

Training: 85 epochs, optimized with Adam, learning rate scheduling.

Results: Achieved ~72% validation accuracy with decreasing loss trend.

Visuals: Includes training curves (loss & accuracy).

Comparison: Benchmarked against recent research (Frontiers in Plant Science, 2025).

🔹 Tech Stack

Python, PyTorch, Torchvision

NumPy, Pandas, Matplotlib

Jupyter Notebook / Colab

🔹 References

IP102 Dataset: https://github.com/xpwu95/IP102

Latest Research Benchmark: Frontiers in Plant Science, 2025

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sam74012/Climate_impact_on_crop_production/blob/main/Climate_impact_on_crop_production.ipynb)
