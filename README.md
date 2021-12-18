# Masking

```
docker run -it --name <NAME> --gpus '"device=0,1,2,3,4,5,6,7"' -v ~:/work --shm-size=2g  andrewseidl/nvidia-cuda:10.2-devel-ubuntu20.04 bash
```



```
pip install -U pip
pip install torch==1.7.1+cpu torchvision==0.8.2+cpu -f https://download.pytorch.org/whl/torch_stable.html
```

```
pip install -e masking
```
