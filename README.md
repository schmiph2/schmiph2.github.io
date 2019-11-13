This website provides a list of my repos.

# Repos

## pysepm - Speech Enhancement Measures Implemented in Python
[pysepm](https://github.com/schmiph2/pysepm) is a collection of several objective speech enhancement measures for performance evaluation analysed in Philipos C. Loizou's great Speech Enhancement Book. The Python implementations are checked with the MATLAB implementations from the additional material of the book. Additional measures will be added soon. 

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
