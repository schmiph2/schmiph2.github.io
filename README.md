# Welcome to schmiph2

## Repos

### pyespm - Speech Enhancement Measures Implemented in Python
[pyespm](https://github.com/schmiph2/pyespm) is a collection of different objective speech enhancement measures for performance evaluation.
### Implemented Objetive Speech Intelligibility Measures
+ Segmental Signal-to-Noise Ratio (SNRseg)
+ Frequency-weighted Segmental SNR (fwSNRseg)
+ Log-likelihood Ratio (LLR)
+ Weighted Spectral Slope (WSS)
+ Perceptual Evaluation of Speech Quality (PESQ)
+ Composite Objective Speech Quality (composite)

### Implemented Objetive Speech Intelligibility Measures
+ Short-time objective intelligibility (STOI)

### Installation using pip
The setup.py is not finished yet. You have to install the dependencies by hand.

First install Cython (Required for python-pesq):
```
pip3 install Cython
```
Then install python-pesq and pystoi:
```
pip3 install https://github.com/schmiph2/python-pesq/archive/master.zip
pip3 install https://github.com/schmiph2/pystoi/archive/master.zip
```
Finally install pysepm:
```
pip3 install https://github.com/schmiph2/pysepm/archive/master.zip
```
