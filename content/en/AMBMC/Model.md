---
title: "Model"
linkTitle: "Model"
weight: 2
type: docs
description: >
  15μm average mouse models in Waxholm space from 16.4T 30μm images

---


Digital MRI atlases serve to integrate data from differing modalities, stereotaxic localisation, automatic region identification, automated segmentation and direct comparisons between individuals. While paper atlases can provide exquisite detail of delineated structures, they are typically based upon an individual subject's histology and as such make it difficult to identify structures in novel subjects in an automated fashion. Improvements in field and gradient strength has led to enhanced resolution and the number of segmented regions in MRI atlases. Arguably, the best current atlas is that of Dorr et al in 20083, acquired at 7T with a final resolution of 32um and 62 segmented structures. The data in this MRI atlas was acquired at 16.4T and created using a specific adaptation of a nonlinear averaging technique that resulted in a final resolution of 15μm and is thus approaching histological clarity.

## Method
Eighteen animals were perfused and fixed with 4% paraformaldehyde and 0.1% Magnevist®. Brains were extracted and incubated in 0.1% Magnevist/PB for 4 days, placed in Fomblin and imaged on a 16.4T (89mm) Bruker micro-imaging system using a 15 mm SAW coil (M2M Imaging, USA). MRI data were acquired using a 3D gradient echo sequence with TR/TE/FA= 50ms/12ms/30°, 82 KHz spectral bandwidth, and 8 excitations with an acquisition time of 5h 15mins to produce T1/T2*-weighted images at 30µm3 isotropic resolution. A complete protocol can be downloaded [here <i class="fas fa-external-link-alt"></i>](https://imaging.org.au/uploads/AMBMC/AMBMC_mouse_brain_protocol.pdf).

## Download
The model is available in both nonsymmetric and symmetric versions. Note that all the segmentations that are released as defined on the symmetric model for the purposes of model based segmentation. For most intents and purposes you should use the symmetric version of the model, we have included the nonsymmetric version for people who are interested in left-right average differences. If you plan to do volume comparisons of structures left/right via model based segmentation you should be fitting to a symmetric model to avoid left/right bias.

- ambmc-c57bl6-model-symmet_v0.8 [ [mnc <i class="fas fa-download"></i>](https://imaging.org.au/uploads/AMBMC/ambmc-c57bl6-model-symmet_v0.8-mnc.tar.gz) | [nii <i class="fas fa-download"></i>](https://imaging.org.au/uploads/AMBMC/ambmc-c57bl6-model-symmet_v0.8-nii.tar.gz) ]
- ambmc-c57bl6-model-nonsym_v0.8 [ [mnc <i class="fas fa-download"></i>](https://imaging.org.au/uploads/AMBMC/ambmc-c57bl6-model-nonsym_v0.8-mnc.tar.gz) | [nii <i class="fas fa-download"></i>](https://imaging.org.au/uploads/AMBMC/ambmc-c57bl6-model-nonsym_v0.8-nii.tar.gz) ]

[TissueStack online viewer <i class="fas fa-external-link-alt"></i>](http://www.tissuestack.org/desktop.html?ds=2&plane=y&x=0.054&y=0.061&z=0.01&zoom=75)

## References
Please reference use of the model as such

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

There is a pdf copy of the above poster here: [Model Poster <i class="fas fa-external-link-alt"></i>](https://imaging.org.au/uploads/AMBMC/ismrm2012_1077.pdf)

## Preview
![model-image.png](../model-image.png)