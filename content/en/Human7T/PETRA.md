---
title: "PETRA"
linkTitle: "PETRA"
weight: 5
type: docs
description: >
  PETRA average 7T model
---

View online and download the model in MINC or NiFTI format here:

## PETRA average 7T model
petraModel_L11_asym-mincanon_v0.8 [ [View model online <i class="fas fa-external-link-alt"></i>](http://tissuestack.org/desktop.html?ds=43&plane=z&x=27.25&y=-11.75&z=33&zoom=7) | [mnc <i class="fas fa-download"></i>](/uploads/Human7T/petraModel_L11_asym-mincanon_v0.8.mnc) | [nii <i class="fas fa-download"></i>](/uploads/Human7T/petraModel_L11_asym-mincanon_v0.8.nii) ]

## Acquisition and processing details
28 participants (21-34 years of age, 26.5 years on average, 14 males) on a 7 T whole-body research scanner (Siemens Healthcare, Erlangen, Germany), with maximum gradient strength of 70 mT/m and a slew rate of 200 mT/m/s. A 7 T Tx/32 channel Rx head array (Nova Medical, Wilmington, MA, USA) was used for radio frequency transmission and signal reception. We acquired data using a prototype ultra-short-TE sequence PETRA (Grodzki DM, Jakob PM, Heismann B. Ultrashort echo time imaging using pointwise encoding time reduction with radial acquisition (PETRA). Magn. Reson. Med. 2012;67:510–518. doi: 10.1002/mrm.23017.): TR = 1.99 ms, TE = 0.07 ms, flip angle = 2°, FOV = 288x288x288 mm3, matrix = 288x288x288 (1 mm isometric voxels), no GRAPPA, TA = 2 min. The volgenmodel pipeline was used to construct a minimum deformation model.First, the initial model was generated based on one individual dataset blurred using a kernel size of 4 mm to remove individual features. Then all original input images were aligned via a 12 parameter affine transformation and a normalized cross correlation objective function. The original input datasets were then resampled to the model space and transformed using a concatenation of the inverse transformation from model to participant space and the average transform. Finally, the next model stage was computed by using a robust averaging process of the resampled data, including only data within two standard deviations of the existing mean. After the affine transformation, non-linear fitting was used with incrementally decreasing step and smoothing kernel sizes.
