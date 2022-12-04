<img width="1100" src="https://user-images.githubusercontent.com/8450091/205450952-2c23a413-cdf0-4412-9d24-6a4ef08e3d78.png">

| Anime Style | Interactive Colorization |
| ----------- | -------------------------|
| <img width="500" src="https://user-images.githubusercontent.com/8450091/205465788-86902f1a-0953-4f3b-8c7a-4d4f2dc25713.jpg"> | <img width="500" src="https://user-images.githubusercontent.com/8450091/205465819-58834a02-a437-4b47-93c8-ff3f3fc0672b.png"> |

| Portrait Mode | Grayscale Background |
|---------------| -------------------- |
| <img width="500" src="https://user-images.githubusercontent.com/8450091/205465880-b9549d26-aaf7-46dc-967f-d79148ac1f03.jpg"> | <img width="500" src="https://user-images.githubusercontent.com/8450091/205465881-fb1a61c7-734c-4c7d-b11c-edb14bf2deaa.jpg"> |

| Super-Resolution |
| ---------------- |
| <img width="1100" src="https://user-images.githubusercontent.com/8450091/205465965-6dc7cb45-d69d-4cd5-a7b0-f14f824a1227.jpg"> |

| White Balance Correction |
| -------------------------|
| <img width="1100" src="https://user-images.githubusercontent.com/8450091/205467129-64a3fad4-c4c6-4578-ba07-16e79dd94bd3.jpg"> |

### Quick Start

Install dependencies using pip. If you have a CUDA-enabled device, install the appropriate version of [CUDA](https://developer.nvidia.com/cuda-downloads) and [PyTorch](https://pytorch.org/).

```console
foo:bar$ pip install -r requirements.txt
```

Download the pretrained models by running the included download script:

```console
foo:bar$ python download_models.py
```

Start the editor by running:

```console
foo:bar$ python src/main.py
```

### Generate requirements.txt

```
pipreqs --force --encoding=utf-8-sig .
```
