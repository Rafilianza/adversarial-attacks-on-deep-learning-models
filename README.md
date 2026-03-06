## Overview
This repository contains the `Adversarial Attack.ipynb` notebook, which explores the vulnerability of deep learning image classification models to adversarial attacks. The project specifically targets a model trained on the **German Traffic Sign Recognition Benchmark (GTSRB)**, demonstrating how subtle, imperceptible perturbations added to traffic sign images can successfully deceive a computer vision system.

## Model Used
Resnet 18

## Adversarial Method Used
PGD Attacks

##  Attack Results

<div align="center">

### 🟢 Before
<img src="assets/limit_200.png" width="250" alt="Original Traffic Sign">  
<br>
<b>Accuracy: 71%</b> <br> <i>(Correctly classified)</i>

<br><hr><br>

### 🔴 After
<img src="assets/limit_200.png" width="250" alt="Adversarial Traffic Sign"> &nbsp;&nbsp; ➡️ &nbsp;&nbsp; <img src="assets/limit_100.png" width="250" alt="100 km/h Sign">
<br>
<b>Predicted as 100 km/h Speed Limit 99% of the time</b> <br> <i>(Actually a 20 km/h sign)</i>

</div>
