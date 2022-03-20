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
    
    ![Untitled](/Anaconda/Untitled.png)
    

- Pytorch
    
    ```python
    import torch
    print(torch.__version__)
    ```
    
    
    [Pytorch 中文教學](https://www.bilibili.com/video/BV1qh411U73y?p=1)
    
