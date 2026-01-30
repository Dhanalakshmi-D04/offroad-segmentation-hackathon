\# Offroad Semantic Segmentation (Hackathon Submission)



\## Overview

This repository contains the training and testing pipeline for the Offroad Semantic Segmentation challenge.



\- Backbone: DINOv2 (ViT-S/14)

\- Task: Multi-class semantic segmentation

\- Evaluation Metric: Mean IoU on test images



\## Folder Structure

segmentation\_project/

├── train\_segmentation.py

├── test\_segmentation.py

├── segmentation\_head.pth

├── predictions/

│ ├── evaluation\_metrics.txt

│ ├── per\_class\_metrics.png

│ └── comparisons/

└── README.md





\## How to Run



\### 1. Install dependencies

```bash

pip install -r requirements.txt



\#train



python train\_segmentation.py



\#Test



python test\_segmentation.py



Results



Mean IoU achieved on test images: 0.2239





Save and close.



---



\# 🚀 STEP 4: Create `requirements.txt`



```powershell

notepad requirements.txt

torch

torchvision

numpy

opencv-python

matplotlib

tqdm

Pillow



