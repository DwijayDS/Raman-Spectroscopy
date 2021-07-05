# Raman-Spectroscopy

### Data Preprocessing
  1. Smoothning:
    * Moving average filter
    * Savitzky Golay Filter
  2. Dimentionality Reduction (Only for certain models) (PCA)
  3. Dervative spectroscopy

### Models

  1. Decision Tree
  2. Random Forest
  3. SVM - RBF
  4. Logistic Regression
  5. MLP
  6. CNN
  7. MLP based AE (skip connections)
  8. CNN based AE (skip Connections)
  
### Data Augmentation (CNN, VAE)

  1. shifting waveforms randomly
  2. Introduction of additive gaussian noise
  3. Linear combination of spectra belonging to same material (Coefficients chosen randomly)
 
 ### References 
 
  1. Deep Convolutional neural network for Raman Spectrum recognition : https://arxiv.org/pdf/1708.09022.pdf
  2. DeepCID : https://pubs.rsc.org/en/content/articlehtml/2019/an/c8an02212g
  3. Savitzky-Golay Filter : http://www.statistics4u.com/fundstat_eng/cc_filter_savgolay.html
  4. Moving average Filter : http://www.statistics4u.com/fundstat_eng/cc_moving_average.html
  5. Derivative Spectroscopy : https://www.whoi.edu/cms/files/derivative_spectroscopy_59633940_175744.pdf


