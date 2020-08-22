# STERP-Denoising

STERP-Denoising is a MATLAB application for Single-Trial Event-Related Potentials denoising using non-conventional methods. It implements a generator of simulated data sets with an additive EEG activity as noise. The tool allows denoising of simulated and real data using different automatic adaptive filtering models and provides statistical analysis to ensure generality of the results. It could serve as a comparison tool for future studies dealing with ST-ERP denoising and be of broad use to the computational and cognitive neuroscience communities.

Prerequisites
---------------

STERP-Denoising is implemented as a MATLAB Application and has been tested on computers running Windows 7 and 10 (but should run on macOS and Linux distributions) using MATLAB version from R2018b.

Installation
----------------

1. Download the installation file [here](https://github.com/Mamoud26/ST-ERP-Den/blob/master/ERP_Toolbox.mlappinstall)

2. On the APPS tab of MATLAB, click the Install App button.

3. Browse to the containing folder and select the file.

Or just double click on the installation file and choose Install. 

The STERP-Denoising appears alongside MATLAB toolbox apps in the apps gallery.
Users do not need to manage the MATLAB search path or other installation details.

# Quickstart guides and examples
-------------------------------

Steps for Simulation
--------------------

A. On the Simulation tab:
-------------------------
1. Set the number of trials and number of samples per trial.
2. Set the level of added EEG background in dB.
3. Set the range of latency variation.
4. Choose one of the five waveforms.
5. Save the two generated data sets using the Save Data button. (optional)

<img src="https://github.com/Mamoud26/ST-ERP-Den/blob/master/Simulation1.png" width="470">

B. On the Denoising tab:
------------------------
1. Choose the Simulation data.
2. Click the Load button to load the data.
3. Choose the methods to be used for denoising the data.
4. Click the Filter button to process the data.
5. Set the parameters of each method in their respective subtabs.
6. Save the denoised data sets. (optional)
7. Load the data denoised externally. (optional)
8. Export the figure of the noisy and denoised data using the Save Figures button. (optional)

<img src="https://github.com/Mamoud26/ST-ERP-Den/blob/master/Simulation1.png" width="470"> <img src="https://github.com/Mamoud26/ST-ERP-Den/blob/master/Simulation1.png" width="470">

C. On the Evaluation tab:
-------------------------
1. Click the Evaluate button to plot the curves of the SNR and the MSE.
2. Export the figure of the curves using the Save Figure button. (optional)

<img src="https://github.com/Mamoud26/ST-ERP-Den/blob/master/Simulation1.png" width="470"> 

D. On the Statistical Analysis tab:
-----------------------------------
1. Choose the significance level alpha.
2. Choose the post hoc test.
3. Click the respective button to analyse the SNR or the MSE.
4. Export the figure of the statistical analysis using the Save Figure button. (optional)

<img src="https://github.com/Mamoud26/ST-ERP-Den/blob/master/Simulation1.png" width="470">

Steps for Real data
-------------------

A. On the Denoising tab:
------------------------
1. Choose the Real data.
2. Click the Load button to load the data.
3. Choose the methods to be used for denoising the data.
4. Click the Filter button to process the data.
5. Set the parameters of each method in their respective subtabs.
6. Save the denoised data sets. (optional)
7. Load the data denoised externally. (optional)
8. Export the figure of the noisy and denoised data using the Save Figures button. (optional)

<img src="https://github.com/Mamoud26/ST-ERP-Den/blob/master/Simulation1.png" width="470">

B. On the Evaluation tab:
-------------------------
1. Click the Evaluate button to plot the bars of the SNR estimations.
2. Export the figure using the Save Figure button. (optional)

<img src="https://github.com/Mamoud26/ST-ERP-Den/blob/master/Simulation1.png" width="470">

C. On the Statistical Analysis tab:
-----------------------------------
1. Choose the significance level alpha.
2. Choose the post hoc test.
3. Click the button to analyse the SNRcorr.
4. Export the figure of the statistical analysis using the Save Figure button. (optional)

<img src="https://github.com/Mamoud26/ST-ERP-Den/blob/master/Simulation1.png" width="470"> 

Find our quick start guides for many applications in the [Documentation](https://youtu.be/xKG8v_MYl_s).

<img src="https://github.com/Mamoud26/ST-ERP-Den/blob/master/Table1.png" width="470"> 


Bug Reports and Further Assistance
----------------------------------

Please submit questions or bug reports via the GitHub repository [issues page](https://github.com/Mamoud26/ST-ERP-Den/issues).


License
-------

Copyright 2020 Mohamed Amine Boudiaf, boudiafmohamedamine@hotmail.fr, University Badji Mokhtar Annaba.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
