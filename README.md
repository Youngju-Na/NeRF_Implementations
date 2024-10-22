# NeRF_Implementations

[Neural Radiance Fields (NeRF)](https://www.matthewtancik.com/nerf) is a method for synthesizing novel views from 2D images.
This repository is to reproduce nerf models only for educational purpose.
All models are from their official implementations and cited in each directory.

NeRF from scratch implementations are heavily brought from [NeRF tutorial](https://towardsdatascience.com/its-nerf-from-nothing-build-a-vanilla-nerf-with-pytorch-7846e4c45666) which I highly recommend to visit.

## Installation
```
git clone https://github.com/YoungjuNa-KR/NeRF_Implementations.git
cd NeRF_Implementations
pip install -r requirements.txt
```

### environments details & Dependencies
- GPU: RTX3090
- CUDA: 11.3
- cudnn: 8.05
- Python 3.8
- Pytorch 1.11
- matplotlib
- numpy
- imageio
- imageio-ffmpeg
- configargparse

### Data Preprocessing
Understanding the data preprocessing pipeline is important in reproducing models, especially NeRF because it requires understanding camera models. I recommend following the hyper-nerf data preprocessing pipeline to grasp the procedure.

### Pretrained Models
[blender_lego_200000_iters](https://drive.google.com/file/d/1XhhzBb1bZOlRmFNtF93419jQPRfsFq-F/view?usp=sharing)

### available (brought from offical implementations)
- mip-nerf [github](https://github.com/google/mipnerf.git)
- pixel-nerf [github](https://github.com/sxyu/pixel-nerf.git)
- hypernerf [github](https://github.com/google/hypernerf.git)
- 
### Upcoming updates
- RegNeRF [github](https://github.com/google-research/google-research/tree/master/regnerf)
- MVSNeRF [github](https://github.com/apchenstu/mvsnerf)

### Jupyter Guides
Jupyter guides follow the PyTorch implementations of models below from scratch.
(Data Processing, Model, train/test, visualizations)
- NeRF
- D-NeRF
- NeRFACE
- PixelNeRF (TBU)
- RegNeRF(TBU)

![image](https://user-images.githubusercontent.com/45136186/195795464-dc809f8d-bf7f-40a5-b108-b847364e4be5.png)
