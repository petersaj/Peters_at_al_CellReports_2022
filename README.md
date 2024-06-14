[![DOI](https://zenodo.org/badge/531614084.svg)](https://zenodo.org/badge/latestdoi/531614084)

Code used to produce figures in "Visuomotor learning promotes visually evoked activity in the medial prefrontal cortex", Peters et al., Cell Reports 2022.

The data loaded by this code is available for download at: https://osf.io/2wh5v/

The full codebase used in this paper (and possible dependencies) are in: https://github.com/petersaj/AP_scripts_cortexlab

Included files: 
- AP_operant_learning_figures_published - produces all figures 
- AP_load_trials_operant - called by figure code (loads and normalizes data) 
- AP_operant_learning_preprocessing - all preprocessing code used to produce data files from raw data 
- operant_grab_trial_data - called by preprocessing script (executes common preprocessing)
- operant_muscimol_injection_experiments - create database of muscimol injections

Note on paths when running this code with data from OSF: two files (`U_master` and `wf_roi`) can be downloaded from OSF, but their locations are hard-coded in the code. In order to load these, the user will have to change the paths to where these files are stored locally.

Any questions or issues I can address via Github issue
