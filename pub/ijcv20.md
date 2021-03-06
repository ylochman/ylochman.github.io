---
layout: publication
title: Minimal Solvers for Rectifying from Radially-Distorted Scales and Change of Scales
description: (bibtex) Minimal Solvers for Rectifying from Radially-Distorted Scales and Change of Scales
---

[James Pritts][jbpritts], [Zuzana Kukelova][zkukelova], [Viktor Larsson][vlarsson], [Yaroslava Lochman][ylochman], [Ondřej Chum][ochum]

*International Journal of Computer Vision (2020)*

[paper][ijcv20] · [arxiv][ijcv20-arxiv] · [code][repeats]

### Abstract
This paper introduces the first minimal solvers that jointly estimate lens distortion and affine rectification from the image of rigidly-transformed coplanar features. The solvers work on scenes without straight lines and, in general, relax strong assumptions about scene content made by the state of the art. The proposed solvers use the affine invariant that coplanar repeats have the same scale in rectified space. The solvers are separated into two groups that differ by how the equal scale invariant of rectified space is used to place constraints on the lens undistortion and rectification parameters. We demonstrate a principled approach for generating stable minimal solvers by the Gröbner basis method, which is accomplished by sampling feasible monomial bases to maximize numerical stability. Synthetic and real-image experiments confirm that the proposed solvers demonstrate superior robustness to noise compared to the state of the art. Accurate rectifications on imagery taken with narrow to fisheye field-of-view lenses demonstrate the wide applicability of the proposed method. The method is fully automatic.

<img src="../assets/thumbnails/ijcv20.jpg"/>

### Citing
```bibtex
@Article{Pritts-IJCV20,
    title     = {Minimal Solvers for Rectifying from   Radially-Distorted Scales and Change of Scales},
    author    = {Pritts, James and Kukelova, Zuzana and Larsson, Viktor and Lochman, Yaroslava and Chum, Ond{\v{r}}ej},
    journal   = {International Journal of Computer Vision},
    volume    = {128},
    number    = {4},
    pages     = {950--968},
    year      = {2020},
}
```

[ijcv20]: https://link.springer.com/article/10.1007/s11263-019-01216-x
[ijcv20-arxiv]: https://arxiv.org/abs/1907.11539
[repeats]: https://github.com/prittjam/repeats

[jbpritts]: https://scholar.google.com/citations?user=fvTKAEUAAAAJ
[zkukelova]: https://scholar.google.com/citations?user=M4a3VyYAAAAJ
[vlarsson]: https://scholar.google.com/citations?user=vHeD0TYAAAAJ
[ylochman]: https://scholar.google.com/citations?user=9tfA7cMAAAAJ
[ochum]: https://scholar.google.com/citations?user=4T42Ke0AAAAJ