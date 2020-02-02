Program for processing fMRI statistical maps

Requires that Statistical Parametric Mapping (SPM12; Wellcome Trust Centre for
Neuroimaging; www.fil.ion.ucl.ac.uk/spm/) be in your MATLAB search path. In
addition, it requires a number of supporting utility functions and data
files that should have been included in the distribution of *****fMRI_code_Trange*****. 
It has been tested on SPM12 operating in MATLAB 2018a running in Windows 10.

________________________________________________________________________________
According to your experimental parameters and certain file direction,
Change the *****codepath***** and *****Animal_path*****.
===============================================================================================
               Results of the pre-processing steps are storaged in folder '\Results\'
               Results of the Statistical results are storaged in folder '\Functions\'
===============================================================================================
after the first stage (Bruker2nifiti), manually masking was applied by
ITK-SNAP (http://www.itksnap.org/pmwiki/pmwiki.php),
          ----> for EPI     , named  'EPI_mask.nii'       ,save in the folder of '\Results\'
          ----> for T2      , named  'T2_mask.nii'        ,save in the folder of '\Results\'








