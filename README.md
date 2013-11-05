matlab_speech_features
======================

A set of speech feature extraction functions for ASR and speaker identification written in matlab.
Documentation is available at http://www.practicalcryptography.com/miscellaneous/machine-learning/matlab_speech_features-documentation/

currently implemented:

Feature | Description
--------| -----------
 MFCCs | Mel frequency cepstral coefficients
 LFBE | Log filterbank energies
 SSC | Spectral Subband Centroids
 LPCs | Linear prediction coefficients
 LPCCs | Linear prediction cepstral coefficients
 LSF | line spectral frequencies
 LAR | log area ratios
 RC | reflection coefficients

To be implemented:

- PLP

There are other things I'd like to clean up, e.g. reflection coefficients and log area ratios use MATLABs poly2rc and rc2lar functions,
I would like to implement these myself. Also the function naming is a bit wierd, I'll have to fix it up at some point.
