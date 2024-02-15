# **Final Project**
# *Coral Life Forms Detection for Analysis of Climate Change Impact on Coral Biodiversity*
## Overview
![Screenshot 2024-02-15 232329](https://github.com/harrisonhan123/final_project/assets/39963089/9d8815a4-a563-462d-8c36-575be30bd61a)
## Tujuan
Mengklasifikasikan jenis-jenis terumbu karang
## Pengumpulan Data
Kami mengolah data terumbu karang dengan Roboflow.
## Pengolahan Data
Untuk preprocessing data diolah di Roboflow.
Data terumbu karang disediakan oleh Bapak Tri Wahyu dan pengolahan di Roboflow juga dikerjakan oleh beliau.
## Model
Kami mengunakan model pre-trained YOLOv3, YOLOv5, dan YOLOv8 untuk membangun model untuk mendeteksi jenis terumbu karang.
## Pelatihan
### Hyperparameters
 - Epoch: 100
 - Batch Size: 16
 - Image Size: 416x416
 - Learning Rate: lr0 = 0.01, lrf = 0.0001
 - Momentum: 0.937
 - Weight Decay: 0.0005
 - Optimizer: AdamW
## Evaluasi & Hasil
![Screenshot 2024-02-15 232559](https://github.com/harrisonhan123/final_project/assets/39963089/73d50bc1-8987-4627-9742-17863cc331de)

