# SkeletonGaussian: Editable 4D Generation through Gaussian Skeletonization

<div align="center">

[![arXiv](https://img.shields.io/badge/arXiv-2602.04271-b31b1b.svg)](https://arxiv.org/abs/2602.04271)
[![Project Page](https://img.shields.io/badge/Project-Page-green)](https://wusar.github.io/projects/skeletongaussian/)
[![Video](https://img.shields.io/badge/Video-YouTube-red)](https://wusar.github.io/projects/skeletongaussian/)

**Lifan Wu**, Ruijie Zhu, Yubo Ai, Tianzhu Zhang

**University of Science and Technology of China (USTC)**

**AAAI 2026** / **Computational Visual Media (CVM) 2026**

</div>

---

## 📢 News

*   **[2026-02-05]** Paper is available on [arXiv](https://arxiv.org/abs/2602.04271).
*   **[2026-02-05]** SkeletonGaussian is accepted to **AAAI 2026** and recommended to **CVMJ**! 🎉
*   **[Coming Soon]** Code and pretrained weights will be released soon. Please star this repo for updates! 🌟

---

## 💡 Abstract

4D generation has made remarkable progress in synthesizing dynamic 3D objects from input text, images, or videos. However, existing methods often represent motion as an implicit deformation field, which limits direct control and editability.

To address this, we propose **SkeletonGaussian**, a novel framework for generating editable, dynamic 3D Gaussians from monocular video input. Our approach introduces a hierarchical, articulated representation that decomposes motion into sparse, rigid motion explicitly driven by a skeleton and fine-grained, non-rigid motion. Concretely, we extract a robust skeleton and drive rigid motion via linear blend skinning, followed by a hexplane-based refinement for non-rigid deformations—enhancing interpretability and editability.

Experimental results show that SkeletonGaussian surpasses existing methods in generation quality while enabling intuitive motion editing, establishing a new paradigm for editable 4D generation.

![Teaser](assets/teaser.png)

---

## 🗓️ Roadmap

- [ ] Release inference code
- [ ] Release pretrained models
- [ ] Release training scripts
- [ ] Gradio Demo

---

## 🔗 Citation

If you find this work useful for your research, please consider citing our paper:

```bibtex
@inproceedings{wu2026skeletongaussian,
  title={SkeletonGaussian: Editable 4D Generation through Gaussian Skeletonization},
  author={Wu, Lifan and Zhu, Ruijie and Ai, Yubo and Zhang, Tianzhu},
  booktitle={AAAI},
  year={2026}
}
```
