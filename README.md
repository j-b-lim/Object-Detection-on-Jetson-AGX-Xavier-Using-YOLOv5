# Object-Detection-on-Jetson-AGX-Xavier-Using-YOLOv5

This script provides a tutorial on object detection using YOLOv5 on Jetson Xavier.

The JetPack installation process is omitted for brevity.

## **System**
- OS: Ubuntu 20.04 LTS
- Hardware: NVIDIA Jetson AGX Xavier
- CUDA: 11.4
- Python: 3.8
- PyTorch: 1.12.0 (NVIDIA Jetson build, 1.12.0a0+2c916ef.nv22.3)
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
<img width="1958" height="511" alt="image" src="https://github.com/user-attachments/assets/23b18ffa-5555-4285-9ed2-53d8c401f30c" />

<img width="1964" height="517" alt="image" src="https://github.com/user-attachments/assets/b17ff7da-073a-48cf-b8cc-9b8396a9f6e4" />

```shell
wget https://nvidia.box.com/shared/static/p57jwntv436lfrd78inwl7iml6p13fzh.whl -O torch-1.12.0-cp38-cp38-linux_aarch64.whl
pip3 install torch-1.11.0-cp38-cp38-linux_aarch64.whl  
pip3 install typing-extensions==3.10.0.2  
```

