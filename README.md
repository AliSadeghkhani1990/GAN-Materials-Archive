# GAN-Materials-Archive

## A Decade of Generative Adversarial Networks for Porous Material Reconstruction

**Authors:** Ali Sadeghkhani, Brandon Bennett, Masoud Babaei, Arash Rabbani  
**Affiliations:**  
- School of Computer Science, University of Leeds, Leeds, UK  
- School of Chemical Engineering, The University of Manchester, Manchester, UK  

**Corresponding author:** a.rabbani@leeds.ac.uk

---

## About This Repository

This repository provides supplementary data resources accompanying the systematic review paper on GAN-based porous material reconstruction. It contains:

1. **Compiled Excel datasets** — structured summary tables of all 95 reviewed papers, organised by GAN architecture category (Appendix B of the paper)
2. **Curated open-source repository list** — all publicly available implementations identified in the review (Appendix A of the paper)

These resources are intended to support reproducibility, facilitate comparisons, and serve as a reference for researchers working in porous media reconstruction using deep learning.

---

## Repository Structure

```
GAN-Materials-Archive/
│
├── README.md
├── CITATION.cff
└── data/
    ├── 01_Vanilla_GAN.xlsx
    ├── 02_MultiScale_GAN.xlsx
    ├── 03_Conditional_GAN.xlsx
    ├── 04_Attention_Enhanced_GAN.xlsx
    ├── 05_Style_based_GAN.xlsx
    └── 06_Hybrid_Architecture_GAN.xlsx
```

### Excel File Contents
Each file covers the following fields for all reviewed papers in that category:
- Reference & Year
- Loss Function
- Training Image Size & Dimensionality
- Generated Image Size & Dimensionality
- Image Type (Binary / Grayscale / Multi-phase)
- Material Type
- Key Novelties & Innovations
- Evaluation Metrics
- Computational Requirements (GPU, RAM, Training Time)

---

## Open-Source Implementations

Below is a curated list of all publicly available code repositories identified in this review, organised by GAN category.

---

### Vanilla GAN

| Reference | Repository |
|-----------|-----------|
| Mosser L. et al. (2017) | [PorousMediaGan](https://github.com/LukasMosser/PorousMediaGan) |
| Gayon-Lombardo A. et al. (2020) | [pores4thought](https://github.com/agayonlombardo/pores4thought) |
| Coiffier G. et al. (2020) | [diaGAN](https://github.com/randlab/diaGAN) |
| Kench S. et al. (2021) | [SliceGAN](https://github.com/stke9/SliceGAN) |
| Zhang T. et al. (2022) | [IWGAN-GP](https://github.com/vevvve/IWGAN-GP) |
| Zhang T. et al. (2023) | [3DRGAN](https://github.com/Hugsazp/3DRGAN) |
| Amiri H. et al. (2024) | [True2Dto3Drecon](https://github.com/hamediut/True2Dto3Drecon) |
| Zhang Y. et al. (2025) | [porescale](https://github.com/ImperialCollegeLondon/porescale) / [Multi-physics-Network-Model](https://github.com/iPMLab/Multi-physics-Network-Model) |

---

### Multi-Scale GAN

| Reference | Repository |
|-----------|-----------|
| You N. et al. (2021) | [Zenodo](https://doi.org/10.5281/zenodo.4437911) |
| Xia P. et al. (2022) | [MS-GAN](https://github.com/FPXMU/MS-GAN) |
| Zhang T. et al. (2023) | [SASGAN](https://github.com/vevvve/SASGAN) |
| Zhu L. et al. (2024) | [IPWGAN](https://github.com/ImperialCollegeLondon/IPWGAN) |
| Zhao X. et al. (2025) | [CEM3DMG](https://github.com/NBICLAB/CEM3DMG) |
| Ugolkov E. et al. (2025) | [x16-Octree-Based-Super-Resolution](https://github.com/EvgenyUgolkov/x16-Octree-Bassed-Super-Resolution) |

---

### Conditional GAN

| Reference | Repository |
|-----------|-----------|
| Sadeghkhani A. et al. (2025) | [PCP-GAN](https://github.com/AliSadeghkhani1990/PCP-GAN) |

---

### Attention-Enhanced GAN

| Reference | Repository |
|-----------|-----------|
| Zhang T. et al. (2023) | [SASGAN](https://github.com/vevvve/SASGAN) |

---

### Style-based GAN

| Reference | Repository |
|-----------|-----------|
| Fokina D. et al. (2020) | [StyleGAN (NVlabs)](https://github.com/NVlabs/stylegan) |
| Liu M. et al. (2022) | [MultiscaleDRPNet](https://github.com/theanswer003/MultiscaleDRPNet) |
| Cao D. et al. (2022) | [CISGAN](https://github.com/Berthou817/CISGAN) |
| Thakre S. et al. (2023) | [StyleGAN2-ADA-MicrostructureGeneration](https://github.com/vir-k01/StyleGAN2-ADA-MicrostructureGeneration) |

---

### Hybrid Architecture GAN

| Reference | Repository |
|-----------|-----------|
| Chen H. et al. (2020) | [SRCycleGAN](https://github.com/III-SCU/SRCycleGAN) |
| Cao D. et al. (2022) | [CISGAN](https://github.com/Berthou817/CISGAN) |
| Zhang Y. et al. (2025) | [ADA-PGGAN](https://github.com/QUST-SmartData/ADA-PGGAN) |

---

## Citation

If you use the data or resources in this repository, please cite our paper:

```bibtex
@article{Sadeghkhani2025GANReview,
  title   = {A Decade of Generative Adversarial Networks for Porous Material Reconstruction},
  author  = {Sadeghkhani, Ali and Bennett, Brandon and Babaei, Masoud and Rabbani, Arash},
  journal = {[Journal Name]},
  year    = {2025},
  doi     = {[DOI]}
}
```

---

## License

The data compiled in this repository is made available under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). You are free to share and adapt the material for any purpose, provided appropriate credit is given.
