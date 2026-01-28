# Object Detection on NVIDIA Jetson AGX Xavier using YOLOv5


This repository provides a step-by-step guide for running YOLOv5-based object detection on the NVIDIA Jetson AGX Xavier.

The JetPack installation process is omitted for brevity.

## **System**
- OS: Ubuntu 20.04 LTS
- Hardware: NVIDIA Jetson AGX Xavier
- CUDA: 11.4
- Python: 3.8
- PyTorch: 1.12.0 (NVIDIA Jetson build)
- TorchVision: 0.12.0


## **Environment Setup**
```shell
python3 -m pip install --upgrade pip  
pip3 install -U PyYAML
pip3 install tqdm 
pip3 install cython 
pip3 install -U numpy
pip3 install cycler kiwisolver pyparsing python-dateutil matplotlib  
pip3 install scipy pillow
```

## **Install PyTorch**
The following steps install the official NVIDIA PyTorch build compatible with JetPack 5.x on Jetson AGX Xavier.
More details can be found [here](https://forums.developer.nvidia.com/t/pytorch-for-jetson/72048).

<img width="1958" height="511" alt="image" src="https://github.com/user-attachments/assets/23b18ffa-5555-4285-9ed2-53d8c401f30c" />

<img width="1964" height="517" alt="image" src="https://github.com/user-attachments/assets/b17ff7da-073a-48cf-b8cc-9b8396a9f6e4" />

```shell
wget https://nvidia.box.com/shared/static/p57jwntv436lfrd78inwl7iml6p13fzh.whl -O torch-1.12.0-cp38-cp38-linux_aarch64.whl
pip3 install torch-1.12.0-cp38-cp38-linux_aarch64.whl  
pip3 install typing-extensions==3.10.0.2  
```

