---
title: "TSE"
linkTitle: "TSE"
weight: 4
type: docs
hide_summary: true
description: >
  Turbo Spin Echo average 7T model
---

## Downloads
View online and download the model in MINC or NiFTI format here:

### TSE model in MP2RAGE model space (registered using contrast matching and cross correlation)
tseModelInMP2RAGEspaceCMACC_L15_hippocampus-TSE-7T-sym-mincanon_v0.8 [ [View model online <i class="fas fa-external-link-alt"></i>](http://tissuestack.org/desktop.html?ds=40&plane=y&x=26.775&y=0.903&z=-8.325&zoom=8) | [mnc <i class="fas fa-download"></i>](/uploads/Human7T/tseModelInMP2RAGEspaceCMACC_L15_hippocampus-TSE-7T-sym-mincanon_v0.8.mnc) | [nii <i class="fas fa-download"></i>](/uploads/Human7T/tseModelInMP2RAGEspaceCMACC_L15_hippocampus-TSE-7T-sym-mincanon_v0.8.nii) ]

### TSE model raw
tseModel_L15_hippocampus-TSE-7T-sym-mincanon_v0.8 [ [View model online <i class="fas fa-external-link-alt"></i>](http://tissuestack.org/desktop.html?ds=38&plane=y&x=27.11&y=-0.2&z=0.2&zoom=5) | [mnc <i class="fas fa-download"></i>](/uploads/Human7T/tseModel_L15_hippocampus-TSE-7T-sym-mincanon_v0.8.mnc) | [nii <i class="fas fa-download"></i>](/uploads/Human7T/tseModel_L15_hippocampus-TSE-7T-sym-mincanon_v0.8.nii) ]

## Citing this model:
{{% pageinfo %}}
Bollmann, Steffen, Andrew Janke, Lars Marstaller, David Reutens, Kieran O’Brien, and Markus Barth. “Turbo Spin Echo average 7T model” January 1, 2017. doi:10.14264/uql.2017.267
{{% /pageinfo %}}

[doi:10.14264/uql.2017.267 <i class="fas fa-external-link-alt"></i>](http://dx.doi.org/10.14264/uql.2017.267)

## References describing this model:
{{% pageinfo %}}
Janke AL, O'Brien K, Bollmann S, Kober T, Marstaller L, Barth M. A 7T Human Brain Microstructure Atlas by Minimum Deformation Averaging at 300um. In 24th Annual ISMRM Scientific Meeting and Exhibition, Singapore.
{{% /pageinfo %}}

## Contrast matching algorithm
[https://github.com/CAIsr/cma <i class="fas fa-external-link-alt"></i>](https://github.com/CAIsr/cma)

## Acquisition details
TSE: 26 (13 female, average age 26.8±3.9) individuals were imaged using 3 repetitions of a 2D Turbo Spin Echo (TSE) sequence covering a slab orthogonally to the axis of the hippocampus with a resolution of 0.2x0.2x0.8mm, flip angle 134, TR 10.3s. Before the atlas creation, we averaged the three TSE acquisitions per participant to one dataset to increase SNR and reduce the amount of data to be processed. Then we resampled the TSE data to an isotropic voxel size of 0.4 mm.

## Preview
![tse.png](../tse.png)
