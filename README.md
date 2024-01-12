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

### Up to this point, it is the same as DeSRA.

---------------------------------
##3 3. Download or clone artifact_detection.py
move artifact_detection.py mmsegmentation/demo

    git clone https://github.com/201210302/DeSRA_execution/tree/main/mmsegmentation/demo/artifact_detection.py
    move artifact_detection.py mmsegmentation/demo

If you encounter the directory error about SSIM_MSE_GAN_threshold.txt
###  4. move SSIM_MSE_GAN_threshold.txt mmsegmentation/demo

    move SSIM_MSE_GAN_threshold.txt mmsegmentation/demo 
    move segformer_mit-b5_640x640_160k_ade20k.py mmsegmentation\configs\segformer
    
### 5. Make the checkpoints folder in mmsegmentation and download [segformer_mit-b5_640x640_160k_ade20k_20220617_203542-940a6bd8.pth](https://github.com/open-mmlab/mmsegmentation/blob/c685fe6767c4cadf6b051983ca6208f1b9d1ccb8/configs/segformer/README.md?plain=1%23L49) in checkpoints

    # mmsegmentation/checkpoints/segformer_mit-b5_640x640_160k_ade20k_20220617_203542-940a6bd8.pth
    mkdir checkpoints 
When you download the file by following the link, the file name is slightly different, so change the file name: segformer_mit-b5_640x640_160k_ade20k_20220617_203542-940a6bd8.pth



