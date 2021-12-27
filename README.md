# ecg12

The objective of this work is to implement algorithm that can, based only on the clinical data provided, automatically identify the cardiac abnormality or abnormalities present in each 12-lead ECG recording.

The analysis was carried out according to the main steps involved in the ECG signal processing stage: data acquisition, pre-processing, feature extraction and classification.

To perform heart disease multilabel classification, two different deep learning approaches were considered:
- ECG signal features with MLP: several time and frequency domain features were extracted to be fed into a simple dense neural network.
- - 1D-CNN as feature extractor: a one-dimensional convolution neural network was used to extract spatial and temporal dependencies along the ECG segments containing the 12 leads.
