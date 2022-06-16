# Iba-1-Data
The Iba-1 staining data used in the ACCT validation testing. Imaged microglia in mice with and without immune-and-inflammation-activating conditions brought on by the transgenic expression of the envelope protein gp120 of human immunodeficiency virus-1 (HIV-1). 

In context of ACCT:

[Validation_Hand_Counts](#Validation_Hand_Counts) refers to the manual counts by observers on the validation dataset used in the paper. Ten ROi multipoint selection files from Imagej.

[Validation_data](#Validation_data) refers to the validation data used to check the performance of classifier models. Twenty-three images from wild type and gp120 mice which are grouped in sets of 2 or 3 to repersent 10 fields of view which were counted with the validation hand placed markers.

[experimental_images](#experimental_images) refers to the full dataset of uncounted images that were automatically counted by ACCT. Ninety-seven images from wild type and gp120 mice

[training_fem_Npt3_8bit](#training_fem_Npt3_8bit) refers to the images used for training classifier models in the ACCT paper. Ten images from female wild type and gp120 mice.

[genotype.csv](#genotype.csv) refers to the file that denotes the experimental condition the images belong to in the validation dataset.

[geno_full.csv](#geno_full.csv) refers to the file that denotes the experimental condition the images belong to in the experimental images dataset.


Description of data:

In brief, mice were terminally anesthetized with isoflurane and transcardially perfused with 0.9$\%$ saline. The mouse brains were removed and fixed for 72 hours at 4°C in 4% paraformaldehyde. Brain sections were obtained using a vibratome (Leica VT1000S, Leica Biosystems, Buffalo Grove, IL) and cerebral cortex in 40 µm thick sagittal sections spaced 320 µm apart medial to lateral from brains of 11-14 month-old mice of each genotype. Staining was performed with rabbit anti-ionized calcium-binding adaptor molecule 1 (Iba-1) IgG (1:125; Wako) with secondary antibody Fluorescein isothiocyanate (FITC). For quantification of IBA-1 stained microglia, cell bodies were counted in the cerebral cortex from three fields of view per section. Between 2 and 3 images were collected per field of view to capture as many cells as possible in sufficient focus for identification. Microscopy was performed with a Zeiss 200 M fluorescence deconvolution microscope with a computer-controlled 3D stage and FITC filter. All images were collected using Slidebook software (version 6, Intelligent Imaging Innovations, Inc., Denver, CO). Images were acquired at 10X magnification and pixel resolution 1280x1280 and cropped to 1280x733 pixel area to exclude irregular tissue edges.

For more detail see: 

Singh, H., Ojeda-Juárez, D., Maung, R. et al. A pivotal role for Interferon-α receptor-1 in neuronal injury induced by HIV-1. J Neuroinflammation 17, 226 (2020). https://doi.org/10.1186/s12974-020-01894-2



# Fluocell-Data

The 283 1600x1200 pixel images were taken at 200x magnification of 35 µm thick slices of mouse brain tissue with neurons stained via a monosynaptic retrograde tracer (Cholera Toxin b, CTb). This tracer highlighted only neurons connected to the toxin injection site. 

Description of data:

This dataset contains images with both high and low cell density, as well as varying amounts of noise and artifacts (Supplementary Fig. F2). We also observed that many images contain overlapping or touching cells. The Fluocell dataset presents different challenges when compared to our Iba-1 positive microglia dataset where cells are more evenly distributed and the number of cells per image is more consistent.

for more detail see:

Morelli, R., Clissa, L., Amici, R., Cerri, M., Hitrec, T., Luppi, M., Rinaldi, L., Squarcio, F., & Zoccoli, A. (2021). Automating cell counting in fluorescent microscopy through deep learning with c-ResUnet. Scientific Reports, 11(1), 22920.
https://www.nature.com/articles/s41598-021-01929-5
