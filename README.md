# MatIR

MatIR: A Hybrid Mamba-Transformer Image Restoration Model
## Features
- Combining **Mamba** (efficient long-distance modeling) and **Transformer** (strong contextual learning capability).
- Suitable for image restoration tasks such as super-resolution, denoising, and deblurring.
- Provides training and testing scripts and supports custom datasets.
# download code
git clone https://github.com/weijuan7275/MatIR.git
cd MatIR
conda create --name <env> --file requirements.txt
conda activate <env>
## Citation

If you find the code helpful in your resarch or work, please cite the following paper(s).
```
@article{wen2025matir,
  title={MatIR: A Hybrid Mamba-Transformer Image Restoration Model},
  author={Wen, Juan and Hou, Weiyan and Van Gool, Luc and Timofte, Radu},
  journal={arXiv preprint arXiv:2501.18401},
  year={2025}
}
```

## Acknowledgement
The codes are based on [BasicSR](https://github.com/xinntao/BasicSR),
[Restormer](https://github.com/swz30/Restormer)and
[VMamba](https://github.com/MzeroMiko/VMamba) 
Please also follow their licenses. Thanks for their awesome works.
