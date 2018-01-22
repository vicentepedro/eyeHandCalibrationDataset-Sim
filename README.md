# eyeHandCalibrationDataset-Sim
A dataset to be used to test eye hand calibration on the iCub. 
The images were recorded in a realistic (visually) iCub simulation.

## Description of the Dataset Folder

The Dataset is composed with:

- left and right images 
- head encoders
- right arm encoders
- artificial angular offsets on the right arm

## Description of the Results Folder

The results are the output on the present dataset running the CODE on the GitHub repository:

https://github.com/vicentepedro/Online-Body-Schema-Adaptation

The outputs are:

- The canonical hand pose projection in the left camera according with the encoders values (which have an offset error)
- The corrected hand pose projection in the left camera according with the corrected angular offsets
- the calculated angular offsets in each time step 
