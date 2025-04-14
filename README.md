# NYCU_CV2025_Spring_HW2  
StudentID : 110550065  
Name : 尤茂為  

## Introduction  
In this task, we aim to perform digit recognition on a dataset consisting RGB images where each image contains multiple digits. The objective is twofold : (1) Detect each digit in the image by outputting bounding boxes and class labels. (2) Use the results from Task 1 (pred.json) as input to predict the whole number. My approach leverages the state-of-the-art object detection framework Faster R-CNN, which contains ResNeXt50_32x4d as backbone.  

## How to Install  
```sh
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
pip install tqdm
pip install matplotlib  
```

## Performance Snapshot  

