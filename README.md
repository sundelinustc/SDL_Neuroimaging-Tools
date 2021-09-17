# SDL_Neuroimaging-Tools

## Aims
The aim of this project is to share a set of Python, R, and Matlab scripts to facilitate neuroimaging data analyses and results display. 

I made these scripts based on easily available toolboxes and packages of the most popular scientific programming language.

## Motivations
The motivation of this project is that some excellent softwares for neuroimaging processing, analyses and display were developped in some special platforms, such as FSL and FreeSurfer in Unix/Linux. However, not all of the researchers want to deeply divie into these softwares and platforms -- that's too time- and energy-consuming. Some neuroimaging researchers just want to analyze and show the outputs of these softwares in an easier way.

## List of scripts
### To plot neuroimaging data on brain
SDL_FreeSurfer_Display_demo.mlx (Matlab Live)
--- Display a series colorful surface plots.

### Machine Learning based on neuroimaging data
SDL_ML_Pipeline_01.ipynb (Jupyter Notebook)
--- Classfy patients and controls based on resting-state functional connectivity.

### QC Neuroimages
SDL_QC_pngs.ipynb (Jupyter Notebook)
--- Use nilearn package to generate the snapshots (.png files) of target image(s) for the ease of review.
