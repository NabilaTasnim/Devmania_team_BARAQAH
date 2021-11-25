# Devmania_team_BARAQAH
Abstract


The brain computer interface (BCI) depends on the effective analysis of different aspects of neural activities associated with different cognitive, behavioral or emotional states such as attention, memory, mood, etc. to generate equivalent commands that can be utilized for various external control. Among different brain signal generating mechanisms, the event-related potential P300 is known as a valuable tool for assessing cognitive function, in particular for the treatment of autism spectrum disorder (ASD). In this case, rehabilitation progress of joint-attention which is the ability in sharing attention between interactive social partner with third external elements as objects or events can be monitored by setting up an experimental environment. In this project, a machine learning based scheme is developed to automatically detect the target objects by analyzing the continuous wavelet transform (CWT) of electroencephalogram (EEG) signals recorded as the P300 event-related potential (ERP) of ASD patients. The effects of various frequency bands and left, right and whole portion of the brain are observed. A dimension reduction of the feature vector is performed using L1-based feature selection approach and finally ensembled classifier is used. The dataset used is BCIAUT P-300 which possesses imbalanced class with a ratio of 1: 8. So, to handle this, SMOTE augmentation is employed. Apart from the detection accuracy, a trend in detection performance over the time for various sessions of a particular person is also investigated. From this extensive experimentation on a large publicly available BCI ASD dataset, it is found that selection of proper frequency band and proper portion of brain, a very satisfactory detection performance can be achieved.

Dataset


https://www.medicon2019.org/scientific-challenge/#sci_datasets

Algorithms used:

1) Pre-processing: P300 Signal Extraction and Noise Suppression
2) Reduction of Dimension of Data Space
3) Feature Extraction
4) Data Augmentation
5) Classification: Voting Ensemble
    
