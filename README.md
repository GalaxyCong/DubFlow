<p align="center">
  <img src="assets/EmoDubber_Logo.png" width="30%" />
</p>
<div align="center">
  <h3 class="papername"> 
    EmoDubber: Towards High Quality and Emotion Controllable Movie Dubbing </h3>
</div>


[![python](https://img.shields.io/badge/Python-3.10-blue)](https://github.com/GalaxyCong/DubFlow)
[![arXiv](https://img.shields.io/badge/arXiv-2406.06937-b31b1b.svg?logo=arXiv)](https://arxiv.org/pdf/2412.08988)
[![code](https://img.shields.io/badge/Github-Code-keygen.svg?logo=github)](https://github.com/GalaxyCong/DubFlow)
[![demo](https://img.shields.io/badge/GitHub-Demo%20page-orange.svg)](https://galaxycong.github.io/EmoDub/)



# 

# Environment
1. Python >= 3.10
2. Clone this repository:
```bash
git clone https://github.com/GalaxyCong/DubFlow.git
cd DubFlow
```
3. Install python requirements: 
```bash
pip install -r requirements.txt
```

# Dataset

- Chem dataset
- GRID dataset
- V2C-Animation dataset 


# Training (Flow Matching)

First training:
```bash
python train_flow.py --config_path ./Configs/config.yml
```

# Inference (Flow-based User Emotion Controlling)
```bash
python Inference_Wav_Setting1.py --config_path ./Configs/config.yml
```

```bash
python Inference_Wav_Setting2.py --config_path ./Configs/config.yml
```

```bash
python Inference_Wav_Setting3.py --config_path ./Configs/config.yml
```

# Our Checkpoints

Baidu Drive, Google Drive

# License

Code: MIT License


# Citing

If you find our work useful, please consider citing:
```BibTeX
@article{cong2024emodubber,
  title={EmoDubber: Towards High Quality and Emotion Controllable Movie Dubbing},
  author={Cong, Gaoxiang and Pan, Jiadong and Li, Liang and Qi, Yuankai and Peng, Yuxin and Hengel, Anton van den and Yang, Jian and Huang, Qingming},
  journal={arXiv preprint arXiv:2412.08988},
  year={2024}
}
```


