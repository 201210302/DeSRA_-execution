# DeSRA_execution

## 🔧 Dependencies and Installation
- python 3.10.2
- torch 2.0.1+cu117
- mmseg version 1.2.2
- mmcv  2.0.0

## 1. Install mmsegmentation

    git clone https://github.com/open-mmlab/mmsegmentation.git
    cd mmsegmentation
    pip install -r requirements.txt

## 2. Install DeSRA

    git clone https://github.com/TencentARC/DeSRA
    cd DeSRA
    move scripts/* mmsegmentation/demo (you need to modify the path)

## Up to this point, it is the same as DeSRA.

---------------------------------
## 3. Download or clone artifact_detection.py
move artifact_detection.py mmsegmentation/demo

    git clone https://github.com/201210302/DeSRA_execution/tree/main/mmsegmentation/demo/artifact_detection.py
    move artifact_detection.py mmsegmentation/demo

## Then you may encounter the directory error about SSIM_MSE_GAN_threshold.txt
## move SSIM_MSE_GAN_threshold.txt mmsegmentation/demo

    move SSIM_MSE_GAN_threshold.txt mmsegmentation/demo 
    
## 
