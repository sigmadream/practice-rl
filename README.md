# Practice RL

## 환경 설정

- `Ubuntu` >= 22.04.1
- `Python` <= 3.10.x
- `CUDA` <= 11.8

## PIP 관련 업데이트

```shell
(venv) $ python.exe -m pip install --upgrade { pip setuptools wheel }
```

## Python 패키지 설치
- for PyTorch

```
(venv) $ pip3 install torch torchvision torchaudio
(venv) $ pip3 install seaborn
(venv) $ pip3 install tensorboard
(venv) $ pip3 install "gymnasium[all]"
``

- for Tensorflow
```
(venv) $ pip3 install tensorflow
(venv) $ pip3 install keras-tqdm
(venv) $ pip3 install seaborn
(venv) $ pip3 install "gymnasium[all]"
``