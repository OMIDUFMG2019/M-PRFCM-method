# Time Series Forecasting Using Parallel Randomized Fuzzy Cognitive Map and Reservoir Computing
This repository contains the code for a novel randomized multiple-input multiple-output (MIMO) FCM-based forecasting technique named M-PRFCM to forecast real-world high-dimensional time series in Internet of Things (IoT) applications. M-PRFCM is a ﬁrst-order forecasting method integrating the concepts of randomized FCMs, Echo State Networks (ESNs), and Kernel Principle Components Analysis (KPCA). The training process of M-PRFCM is accelerated as a result of utilizing the ESN weight initialization trick, which randomly selects weights. The obtained results show the eﬃcacy and validation of the proposed technique in terms of accuracy and parsimony when compared with other existing ML and DL approaches.

## Objectives and contributions
1) The code implements M-PRFCM, a MIMO forecasting model inspired by the R-HFCM technique, to predict high-dimensional multivariate non-stationary time series in IoT applications, such as smart cities and smart buildings.
2) M-PRFCM is a hybrid method combining Kernel PCA, FTS, and R-HFCM.
3) It is the first FCM-based forecasting model to predict multi-output high-dimensional time series, offering faster performance than conventional FCM forecasting models with different structures.
4) It is less complex and more cost-effective than existing deep learning models.
 
## References
Orang, O., Bitencourt, H., de Lima e Silva, P. C., & Guimarães, F. G. (2024). Time Series Forecasting Using Parallel Randomized Fuzzy Cognitive Maps and Reservoir Computing. In Emerging Trends and Applications in Artificial Intelligence (pp. 153-177). DOI: 10.1007/978-3-031-56728-5_5.

## Computational Experiments

To use the R-HFCM model, upload your cleaned and pre-processed dataset, then run the Jupyter Notebook to visualize the results. Before running the model, it is necessary to install the pyFTS library using the command !pip3 install -U git+https://github.com/PYFTS/pyFTS. All computational experiments in this study were implemented using Python 3.6.12 with open-source packages such as Scikit-learn, Pandas, Numpy,Pytorch, Tensorflow and pyFTS.
