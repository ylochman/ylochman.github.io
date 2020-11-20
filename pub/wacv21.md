---
layout: subpage
title: Minimal Solvers for Single-View Lens-Distorted Camera Auto-Calibration
description: (bibtex) Minimal Solvers for Single-View Lens-Distorted Camera Auto-Calibration
---

Y. Lochman, O. Dobosevych, R. Hryniv, J. Pritts 

*Winter Conference on Applications of Computer Vision, 2021 (Oral)*

[arxiv][wacv21-arxiv] · [code][autocalib]

### Abstract
This paper proposes minimal solvers that use combinations of imaged translational symmetries and parallel scene lines to jointly estimate lens undistortion with either affine rectification or focal length and absolute orientation. We use constraints provided by orthogonal scene planes to recover the focal length. We show that solvers using feature combinations can recover more accurate calibrations than solvers using only one feature type on scenes that have a balance of lines and texture. We also show that the proposed solvers are complementary and can be used together in a RANSAC-based estimator to improve auto-calibration accuracy. State-of-the-art performance is demonstrated on a standard dataset of lens-distorted urban images.


### Citing
```tex
@InProceedings{Lochman-WACV21,
    title     = {Minimal Solvers for Single-View Lens-Distorted Camera Auto-Calibration},
    author    = {Lochman, Yaroslava and Dobosevych, Oles and Hryniv, Rostyslav and Pritts, James},
    booktitle = {Proceedings of the IEEE Winter Conference on Applications of Computer Vision},
    year      = {2021},
}
```

[wacv21-arxiv]: https://arxiv.org/abs/2011.08988
[autocalib]: https://github.com/ucuapps/single-view-autocalib