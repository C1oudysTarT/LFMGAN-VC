# LFMGAN-VC

Inspired by work such as StarGANv2-VC, LFMGAN-VC is a non-parallel voice conversion model that can synthesize audio with anti-detection capability.

## Model environment and dataset

1. We listed the LFMGAN-VC conda environment as environment.yml. So you can simply build the conda environment with the following command:
```bash
   conda env create -f environment.yml
```
1. Download and extract the [VCTK dataset](https://datashare.ed.ac.uk/handle/10283/3443) and use VCTK.ipynb to prepare the data (downsample to 24 kHz etc.). 



## Training

1. For quick start, you can just
```bash
python train.py
```
2. For more detailed training, you can change /Configs/config.yml .

## Inference

Use inference.ipynb in ./Demo to inference.


## References
- [yl4579/StarGANv2-VC](https://github.com/yl4579/StarGANv2-VC)
- [clovaai/stargan-v2](https://github.com/clovaai/stargan-v2)

