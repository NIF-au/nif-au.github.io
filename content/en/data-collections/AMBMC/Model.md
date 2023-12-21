---
title: "Model"
linkTitle: "Model"
weight: 2
type: docs
hide_summary: true
description: >
  15μm average mouse models in Waxholm space from 16.4T 30μm images
---

Digital MRI atlases serve to integrate data from differing modalities, stereotaxic localisation, automatic region identification, automated segmentation and direct comparisons between individuals. While paper atlases can provide exquisite detail of delineated structures, they are typically based upon an individual subject's histology and as such make it difficult to identify structures in novel subjects in an automated fashion. Improvements in field and gradient strength has led to enhanced resolution and the number of segmented regions in MRI atlases. Arguably, the best current atlas is that of Dorr et al in 20083, acquired at 7T with a final resolution of 32um and 62 segmented structures. The data in this MRI atlas was acquired at 16.4T and created using a specific adaptation of a nonlinear averaging technique that resulted in a final resolution of 15μm and is thus approaching histological clarity.

Method linked [here <i class="fas fa-external-link-alt"></i>](/AMBMC/#method)

## Downloads

The model is available in both nonsymmetric and symmetric versions. Note that all the segmentations that are released as defined on the symmetric model for the purposes of model based segmentation. For most intents and purposes you should use the symmetric version of the model, we have included the nonsymmetric version for people who are interested in left-right average differences. If you plan to do volume comparisons of structures left/right via model based segmentation you should be fitting to a symmetric model to avoid left/right bias.

Download the data in MINC or NiFTI format here.

### Symmetric
ambmc-c57bl6-model-symmet_v0.8 [ [mnc <i class="fas fa-download"></i>](/uploads/AMBMC/ambmc-c57bl6-model-symmet_v0.8-mnc.tar.gz) | [nii <i class="fas fa-download"></i>](/uploads/AMBMC/ambmc-c57bl6-model-symmet_v0.8-nii.tar.gz) ]

### Non-symmetric
ambmc-c57bl6-model-nonsym_v0.8 [ [mnc <i class="fas fa-download"></i>](/uploads/AMBMC/ambmc-c57bl6-model-nonsym_v0.8-mnc.tar.gz) | [nii <i class="fas fa-download"></i>](/uploads/AMBMC/ambmc-c57bl6-model-nonsym_v0.8-nii.tar.gz) ]

## References
Please reference use of the model as such:

{{% pageinfo %}}
Janke AL, Ullmann JF. (2015) Robust methods to create ex vivo minimum deformation atlases for 
brain mapping. Methods. 2015 Feb;73:18-26. doi: 10.1016/j.ymeth.2015.01.005
{{% /pageinfo %}}

{{% pageinfo %}}
Janke AL, Ullmann J, Kurniawan N, Paxinos G, Keller M, Yang Z, Richards K, Egan G, Petrou S, 
Galloway G, Reutens D. (2012) 15μm average mouse models in Waxholm space from 16.4T 
30μm images. In 20th Annual ISMRM Scientific Meeting and Exhibition, Melbourne, Australia.
{{% /pageinfo %}}

We would also appreciate authours acknowledging the NHMRC as such:

{{% pageinfo %}}
c57bl/6j model funded by National Health and Medical Research Council Enabling Grant 436673.
{{% /pageinfo %}}

There is a pdf copy of the above poster here: [Model Poster <i class="fas fa-external-link-alt"></i>](/uploads/AMBMC/ismrm2012_1077.pdf)

## Preview

The data can be viewed on the [TissueStack online viewer <i class="fas fa-external-link-alt"></i>](http://www.tissuestack.org/desktop.html?ds=2&plane=y&x=0.054&y=0.061&z=0.01&zoom=75)

![model-image.png](../model-image.png)

