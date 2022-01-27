![Benchtop V2](images/benchtop-v2.png)

# Benchtop mesoSPIM hardware documentation

## Who is the mesoSPIM project for?
* You are looking for a versatile imaging platform for cleared tissue that can be tailored to your needs.
* Research groups and imaging facilities with experience in building and supporting custom microscopes.

## What are ideal imaging applications for a mesoSPIM?
* screening of large numbers of cleared samples
* visualization and analysis of cell populations or other structures (blood vessels, plaques) in whole cleared organs.

## Why Benchtop mesoSPIM?
Being able to move the microscope from one lab to another, bring it to workshops, and send it to collaborators greatly increases its accessibility for biologists. Lab space is often a scarce asset, and having a compact microscope on the bench gives many advantages compared to bringing your samples to a large instrument in a dedicated room. 

## Key differences to mesoSPIM-v5
![mesoSPIM versions comparison](images/mesoSPIM-comparison.png)


Benchtop mesoSPIM has smaller size, lower cost, higher image quality, and easier assembly than [previous version (V5)](https://github.com/mesoSPIM/mesoSPIM-hardware-documentation). 

The excitation optics (and lightsheet properties) are identical to V5, but with more compact folding. 

The detection path uses exchangeable telecentric lenses (available from various manufactureres), as opposed to one objective with zoom (Olympus PLAPO 1x). Fixed-focus (prime) lenses offer better imaging quality than zoom lenses, just like in consumer DSLR cameras. We tested and characterized off-the-shelf telecentric lenses with various magnifications, suitable for different samples.

Hardware is more compact, the number of parts is greatly reduced. 

The acquisition software remains the same, compatible with both versions of the microscope. Only the config file has to be adjusted.

## Build your own
Our project is free and open-source, allowing anyone to build their own microscope. The [BT-mesoSPIM wiki](https://github.com/mesoSPIM/benchtop-hardware/wiki) will guide you how to build, setup, and use the BT-mesoSPIM system.