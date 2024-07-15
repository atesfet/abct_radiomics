# abct_radiomics
Parallelized Intensity and Volume Quantification of Abdominal CT

#Requires FSL
https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/FslInstallation

NOTE: PHI SAFE-RUNS ON ANONYMYZED PATIENT IDENTIFIER
The updated scripts will be under /dataNAS/people/atesfet/IV.

Modify the output directory and segmentation index as needed.

For optimal runtime, use multiple cpu cores (40 in this example)
to extract the intensity and volume metrics. Note that the processed
patients are linearly scaled by the number of cores allocated.
