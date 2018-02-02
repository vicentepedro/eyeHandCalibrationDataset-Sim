# eyeHandCalibrationDataset-Sim
This is a dataset that can be used to test eye-hand calibration on the iCub humanoid robot. 
The images were recorded in a realistic (visually) iCub simulation.

## Description of the Dataset Folder

The dataset was recorded during a babbling movement of the right arm and it is composed with:

- left and right images 
- head encoders
- right arm encoders
- artificial angular offsets on the right arm .([-10.0   -10.0   6.0 -7.0    -1.0    -20.0   7.0]º)


## Description of the Results Folder

The results are the output on the present dataset running the **code** on the GitHub repository:

https://github.com/vicentepedro/Online-Body-Schema-Adaptation

The outputs are:

- the canonical hand pose projection in the left camera generated using the arm encoders values (which have an artificial angular offset)
- the corrected hand pose projection in the left camera generated using the arm encoders and the estimated angular offsets
- the estimated angular offsets in each time step 

## Using the dataset

The YARP dataplayer ([here](http://www.yarp.it/yarpdataplayer.html)) can be used to reproduce the dataset in a synchronized way.
