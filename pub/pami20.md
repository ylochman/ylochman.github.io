---
layout: publication
title: Minimal Solvers for Rectifying from Radially-Distorted Conjugate Translations
description: (bibtex) Minimal Solvers for Rectifying from Radially-Distorted Conjugate Translations
---

[James Pritts][jbpritts], [Zuzana Kukelova][zkukelova], [Viktor Larsson][vlarsson], [Yaroslava Lochman][ylochman], [Ondřej Chum][ochum]

*Transactions on Pattern Analysis and Machine Intelligence (2020)*

[paper][tpami20] · [arxiv][tpami20-arxiv] · [code][repeats]

### Abstract
This paper introduces minimal solvers that jointly solve for radial lens undistortion and affine-rectification using local features extracted from the image of coplanar translated and reflected scene texture, which is common in man-made environments. The proposed solvers accommodate different types of local features and sampling strategies, and three of the proposed variants require just one feature correspondence. State-of-the-art techniques from algebraic geometry are used to simplify the formulation of the solvers. The generated solvers are stable, small and fast. Synthetic and real-image experiments show that the proposed solvers have superior robustness to noise compared to the state of the art. The solvers are integrated with an automated system for rectifying imaged scene planes from coplanar repeated texture. Accurate rectifications on challenging imagery taken with narrow to wide field-of-view lenses demonstrate the applicability of the proposed solvers.

### Citing
```bibtex
@Article{Pritts-PAMI20,
    title     = {Minimal Solvers for Rectifying from Radially-Distorted Conjugate Translations}, 
    author    = {Pritts, James and Kukelova, Zuzana and Larsson, Viktor and Lochman, Yaroslava and Chum, Ond{\v{r}}ej},
    journal   = {IEEE Transactions on Pattern Analysis and Machine Intelligence},
    year      = {2020},
}
```

[tpami20]: https://ieeexplore.ieee.org/document/9086062
[tpami20-arxiv]: https://arxiv.org/abs/1911.01507
[repeats]: https://github.com/prittjam/repeats

[jbpritts]: https://scholar.google.com/citations?user=fvTKAEUAAAAJ
[zkukelova]: https://scholar.google.com/citations?user=M4a3VyYAAAAJ
[vlarsson]: https://scholar.google.com/citations?user=vHeD0TYAAAAJ
[ylochman]: https://scholar.google.com/citations?user=9tfA7cMAAAAJ
[ochum]: https://scholar.google.com/citations?user=4T42Ke0AAAAJ