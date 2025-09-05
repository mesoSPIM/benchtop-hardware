![Benchtop V2](https://github.com/mesoSPIM/benchtop-hardware/blob/main/Benchtop-2024(default-version)/CAD-model-Inventor/mesoSPIM/renderings/overview/benchtop-mesoSPIM_latest.png)

# Benchtop mesoSPIM hardware documentation

## Who is the mesoSPIM project for?
* You are looking for a versatile imaging platform for cleared tissue that can be tailored to your needs.
* Research groups and imaging facilities with experience in building and supporting custom microscopes.

## What are ideal imaging applications for a mesoSPIM?
* screening of large numbers of cleared samples
* imaging of cell populations or other structures (blood vessels, plaques, denrites, even axons) in whole cleared organs.

## Why Benchtop mesoSPIM?
Being able to move the microscope from one lab to another, bring it to workshops, and send it to collaborators greatly increases its accessibility for biologists. Lab space is often a scarce asset, and having a compact microscope on the bench gives many advantages compared to bringing your samples to a large instrument in a dedicated room. 

## Key differences to mesoSPIM-v5
![mesoSPIM versions comparison](images/mesoSPIM-comparison.png)


Benchtop mesoSPIM has smaller size, lower cost, higher image quality, and easier assembly than [previous version (V5)](https://github.com/mesoSPIM/mesoSPIM-hardware-documentation). 

| 					| **mesoSPIM v.5** | **Benchtop mesoSPIM** |
|----------|----------|--------------------|
|**Optical resolution, axial**| 5 $\mu m$ | 3.3 $\mu m$  | 
|**Optical resolution, lateral**| 2.7 $\mu m$ (at zoom 4x) | 2.0 $\mu m$ (1.5 - 2.6 $\mu m$ depending on the objective) | 
|**Magnification range**| 0.63x - 6.3x | 0.9x - 20x | 
| **Detection objectives** 	|  Variable magnification (via motorized zoom)  | Fixed-magnification (manual exchange) |
| **Camera sensor FOV (diagonal)** | 19 mm |  25 mm |
| **Pixel size** | 6.5 $\mu m$  | 4.25 $\mu m$  | 
| **Pixels/image** | 4 MP | 15 MP |
| **Footprint** | 1 $m^2$ |  0.25 $m^2$ |
| **Mobile** |  no | yes |
| **Approximate cost, EUR** | 162k | 95k | 

The cost estimate does not include PC workstation and a screen. V.5 costs include 4 laser lines (405, 488, 561, 638 nm) and optical table. Benchtop price includes the three most popular laser lines (488, 561, 638 nm) and 2x, 5x, 10x objectives. 

The number of custom parts in Benchtop is greatly reduced. 

The acquisition software remains the same, compatible with both versions of the microscope. 

## Build your own Benchtop
Our project is free and open-source, allowing anyone to build their own microscope. The [BT-mesoSPIM wiki](https://github.com/mesoSPIM/benchtop-hardware/wiki) will guide you how to build, setup, and use the BT-mesoSPIM system.

## Upgrade your existing v.4-5 mesoSPIM
(currently in beta) We also offer parts list and instructions for upgrading the detection optics of your existing mesoSPIM (v.4 and 5), so it can achieve the same resolution and image quality as the current Benchtop. See parts list and instructions for [mesoSPIM upgrade](https://github.com/mesoSPIM/benchtop-hardware/tree/main/v4-5-upgrade-2023).

# User guides
Introductory training of a new user typically takes 2 hours, ideally with a couple of follow-up sessions to make sure software parameters are set up correctly by the user. Our microscopy facility ZMB (Univerity of Zurich) has detailed guides on [mesoSPIM start-up, setting up, and acquisition](https://zmb.dozuki.com/c/Lightsheet_microscopy#Section_MesoSPIM).

## Citation
If you use any parts of this work for your project, please cite us:

Vladimirov, N., Voigt, F.F., Naert, T. et al. Benchtop mesoSPIM: a next-generation open-source light-sheet microscope for cleared samples. [Nat Commun 15, 2679 (2024).](https://doi.org/10.1038/s41467-024-46770-2)

## Discussion
Since August 2025 we joined the vibrant [image.cs forum](https://forum.image.sc/tag/mesospim)

[![Static Badge](https://img.shields.io/badge/user_forum-image.sc-blue)](https://forum.image.sc/tag/mesospim)

