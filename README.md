# Masking

```
docker run -it --name <NAME> --gpus '"device=0,1,2,3,4,5,6,7"' -v ~:/work --shm-size=2g  andrewseidl/nvidia-cuda:10.2-devel-ubuntu20.04 bash
```

```
apt update && apt upgrade -y && apt install g++ gcc git neovim make cmake git wget libgl1-mesa-dev curl sudo zip unzip python3-pip -y
```



```
pip install -U pip
pip install numpy==1.20.0 matplotlib 
pip install torch==1.7.1+cpu torchvision==0.8.2+cpu -f https://download.pytorch.org/whl/torch_stable.html

```

```
pip install -e masking
```



サンプルデータ
```
wget https://www.pakutaso.com/shared/img/thumb/nekocatPAR591482434_TP_V.jpg
mv nekocatPAR591482434_TP_V.jpg input.png
```
