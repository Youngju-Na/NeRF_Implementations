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
Understanding data preprocessing pipeline is important in repducing models, especially NeRF, because it requires to understand camera models.
I recommend to follow hypernerf data preprocessing pipeline to grasp the procedure.

### available (brought from offical implementations)
- mip-nerf [github](https://github.com/google/mipnerf.git)
- pixel-nerf [github](https://github.com/sxyu/pixel-nerf.git)
- hypernerf [github](https://github.com/google/hypernerf.git)
- 
### Upcoming updates
- RegNeRF [github](https://github.com/google-research/google-research/tree/master/regnerf)
- MVSNeRF [github](https://github.com/apchenstu/mvsnerf)

### Jupyter Guides
Jupyter guides pytorch implementations from scratch.
(Data Processing, Model, train/test, visualizations)
- NeRF
- D-NeRF (TBU)
- NeRFACE (TBU)
- PixelNeRF (TBU)
- RegNeRF(TBU)
