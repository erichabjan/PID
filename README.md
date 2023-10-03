# PID
In this project I test the effectiveness of machine learning techniques to identify particles in the GlueX detector at Jefferson Laboratory. I train the DNN model on smeared monte carlo data that will be extrapolated on to real detector outputs. 

**PID_init.ipynb** In this notebook my initial DNN model is trained on detector data in the 0 GeV - 1 GeV regime.

**2D_Spectrum_sandbox.ipynb** In this notebook I plot data from both the low energy (0 GeV - 1 GeV) and the high energy (1 GeV - 12 GeV) regimes. I plot the change in energy per unit distance in different chambers of the detector versus the momentum of the particle. This gives intuition as to how the particle is being identified in the manual particle identification process. 
