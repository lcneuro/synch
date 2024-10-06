# synchrony in brain regions
This repository contains MATLAB scripts and preprocessed fMRI data employed to create figures and reach conclusions in the following paper:
Metabolism Modulates Network Synchrony in the Aging Brain (https://www.pnas.org/doi/full/10.1073/pnas.2025727118).

---
Directory names within `fmri_data/` and `scripts/` correspond to the respective dataset. See `readme.txt` within `fmri_data/` for more information on the respective dataset. 

To run the MATLAB scripts, 
1. Add all subdirectories of `synchrony/scripts/` to your environment path. 
2. Make sure that the `DIR` variable in `synchrony/scripts/utilts/readin.m` is correctly set. `DIR` corresponds to the path to `synchrony/` from your MATLAB's present working directory. 

Scripts are partitioned based on the dataset they analyze. Further details on which figures in the paper the respective script reproduces can be found in comments at the top of the script.

---
Acknowledgements: initial version of scripts written by Corey Weistuch; Botond Antal preprocessed the fMRI data
