The files created as part of Stolzberg et al, 2017 J Comp Neuro are included here.

File descriptions:
CatT1avg.nii - Nonlinear average of 8 cat brains using DARTEL.  Voxels are scaled between 0 and 1.
CATLAS.nii – Cerebral (left and right hemispheres) and select subcortical regions (bilateral; added since original manuscript) with integers identifying the brain region at each voxel.
CATLAS.txt – Region labels.  Each row of the text file is one region corresponding to voxel values in CATLAS.nii.  L = left hemisphere; R = right hemisphere; B = bilateral.
TPM.nii – Tissue probability maps.  This file is a 4 dimensional NIfTI where the fourth dimension contains: 1. grey matter, 2. white matter, 3. cerebrospinal fluid, and 4. non-brain 

The ‘SlicerFiles’ subdirectory contains files for use with 3D Slicer (https://www.slicer.org/).  If 3D Slicer is installed, double click the file ‘CatCorticalAtlas.mrml’.  Perform the following steps if the brain model appears distorted:
1.	Select ‘Volume Rendering’ from the modules drop-down menu located on the toolbar.
2.	Select ‘TPM GM’ volume from the drop-down menu.
3.	Expand the ‘Advanced’ panel and select the ‘Techniques’ tab.  Change the ‘Quality Control’ setting to ‘Maximum Quality’

Please direct questions to Daniel.Stolzberg@gmail.com

