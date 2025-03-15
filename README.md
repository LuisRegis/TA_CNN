# TA_CNN

TA-CNN is a two-arm one-dimensional convolutional model that classifies an alcoholic beverage (rum) in the presence of five different concentrations of dopant (isopropyl alcohol) and undoped rum. This network is fed features extracted by linear (PCA) and nonlinear (TSNE) dimensionality reduction techniques from images of interferograms captured with a common-path interferometer (DACPI). The change in optical path between a dopant-contaminated sample and a dopant-uncontaminated sample is reflected in changes in the fringe patterns of the interferogram related to the difference in refractive indices of the samples. 

In TACNN-Folds.ipynb you can see the workbook developed in the Python language, which details the selected libraries, the functions and classes developed, and the results achieved. 

The data files of labels, categorical labels and vector matrices extracted from the interferograms with PCA and TSNE are found in the DataInterferogram folder, in CSV files. It is recommended to download them and attach them to the cloud storage unit, since the notebook developed for its execution refers to paths of said unit associated with the Anfrition account that executes it.

The Interferograms folder, contained in DataInterferogram, contains three samples (the original set is protected by intellectual property rights as it is part of a research project) of the interferograms of the different dopant concentration classes. These images show the vectors obtained with PCA and TSNE, which are shown in the workbook.
