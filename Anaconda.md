# Anaconda

- Anaconda
    
    ```python
    conda update conda
    #若想要進行更新，可以輸入下列命令
    ```
    
    ```python
    
    conda env list
    #輸入下面命令看目前系統已經安裝幾個虛擬環境
    
    ```
    
    ```python
    activate myenv
    #啟動虛擬環境
    
    deactivate
    #關閉虛擬環境，在windows中可使用下列命令
    
    conda remove --name myenv numpy
    #若要刪除虛擬環境中某個package(例如在剛剛建立的虛擬環境myenv中的numpy)
    
    conda env remove --name myenv
    #刪除整個虛擬環境
    ```
    
    ```python
    pip install -r requirements.txt
    ```
    
    ```python
    conda create -n pytorch_gpu pip python=3.7
    #创建一个独立的运行环境。 在这里pytorch_gpu名字可以自定义，同时python=3.7版本
    ```
    
- CUDA安裝教學
    
    [](https://zhuanlan.zhihu.com/p/147154972)
    
    ```bash
    nvidia-smi
    ```
    
    ![Untitled](/Anaconda1/Untitled.png)
    

- Pytorch
    
    ```python
    import torch
    print(torch.__version__)
    ```
    
    Pytorch 漢化教學
    
    [](https://www.bilibili.com/video/BV1qh411U73y?p=1)
    

[FastRCNN](https://www.notion.so/FastRCNN-fd98f856da034015a5bf9949916ff755)

[YOLOv5](https://www.notion.so/YOLOv5-4be032dc752e49c59fea2df9523b8a92)

[YOLOv4](https://www.notion.so/YOLOv4-d9d03591ca324ea89ce46ce24ad3e6f6)

[YOLOv3](https://www.notion.so/YOLOv3-42323d5c9e5c4e9b889756aafe5e1200)

[Keras](https://www.notion.so/Keras-4445598c06764fe2b9f0d308a9085e61)

[labelimg](https://www.notion.so/labelimg-c69ada0651bf4ddfb7d2411610b0934c)
