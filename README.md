# 📈 Time Series Dataset
A comprehensive time-series dataset survey.

These datasets are classified based on the following tasks.
- [📈 Time Series Dataset](#-time-series-dataset)
  - [Time Series Forecasting](#time-series-forecasting)
  - [Time Series Classification](#time-series-classification)
  - [Anomaly Detection](#anomaly-detection)
  - [Others](#others)


## Update
- [2022-04-24] **TS-Data v1.0 is released!** We support the most used datasets in the previous time series papers.


## Features
- [ ] More descriptions and configurations.
- [ ] Add the user guide and data loaders.

## Time Series Forecasting 
|   Dataset   |                                                                    Download Link                                                                     | Domain    | Used Papers                                                    |
| :---------: | :--------------------------------------------------------------------------------------------------------------------------------------------------: | --------- | -------------------------------------------------------------- |
|   Traffic   |                              https://github.com/mbohlkeschneider/gluon-ts/blob/mv_release/datasets/traffic_nips.tar.gz                               | Traffic   | [1], [2], [3], [4], [5], [6], [7], [8], [9], [10], [11]        |
| Electricity |                                      https://www.kaggle.com/datasets/uciml/electric-power-consumption-data-set                                       | Energy    | [2], [3], [4], [5], [12], [6], [7], [8], [9], [10], [13], [14] |
|    Wiki     |                            https://github.com/mbohlkeschneider/gluon-ts/blob/mv_release/datasets/wiki-rolling_nips.tar.gz                            | Others    | [4], [7], [8], [15], [16], [10]                                |
|    Solar    |                                                   https://www.nrel.gov/grid/solar-power-data.html                                                    | Energy    | [2], [3], [4], [12], [6], [7], [8], [10], [11]                 |
|    Taxi     |                                            https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page                                             | Traffic   | [4], [10]                                                      |
|    PEMS     | From UCI Repo: https://archive.ics.uci.edu/ml/datasets/PEMS-SF ; From California Department of Transportation PEMS website: http://pems.dot.ca.gov/  | Traffic   | [2], [13], [17]                                                |
|   BikeNYC   |                                    https://www.kaggle.com/datasets/akkithetechie/new-york-city-bike-share-dataset                                    | Traffic   | [13]                                                           |
|     M5      | Homepage: https://mofc.unic.ac.cy/m5-competition/ ; Official download link: https://drive.google.com/drive/folders/1D6EWdVSaOtrP1LEFh1REjI3vej6iUS_4 | Sales     | [2], [16]                                                      |
|  Rossmann   |                                          https://www.kaggle.com/datasets/pratyushakar/rossmann-store-sales                                           | Sales     | [16]                                                           |
|     M4      |                                            https://github.com/M4Competition/M4-methods/raw/master/Dataset                                            | Sales     | [2], [3]                                                       |
|  exchange   |                           https://github.com/mbohlkeschneider/gluon-ts/blob/mv_release/datasets/exchange_rate_nips.tar.gz                            | Financial | [2], [4], [6], [7], [8], [11]                                  |
|    Labor    |                      https://www.abs.gov.au/statistics/labour/employment-and-unemployment/labour-force-australia/latest-release                      | Others    | [15]                                                           |
|   Tourism   |                                              https://robjhyndman.com/publications/hierarchical-tourism/                                              | Others    | [15]                                                           |
|    wind     |                                          https://www.kaggle.com/sohier/30-years-of-european-wind-generation                                          | Energy    | [3]                                                            |

> [1] Ada RNN
> 
> [2] Adjusting for Autocorrelated Errors in Neural Networks for Time Series
> 
> [3] Adversarial Sparse Transformer for Time Series Forecasting
> 
> [4] Autoregressive Denoising Diffusion Models for Multivariate Probabilistic Time Series Forecasting
> 
> [5] Block Hankel Tensor ARIMA for Multiple Short Time Series Forecasting
> 
> [6] Connecting the Dots: Multivariate Time Series Forecasting with Graph Neural Networks
> 
> [7] Deep Explicit Duration Switching Models for Time Series
> 
> [8] Deep Rao-Blackwellised Particle Filters for Time Series Forecasting
> 
> [9] Probabilistic Time Series Forecasting with Structured Shape and Temporal Diversity
> 
> [10] Probabilistic Transformer for Time Series Analysis
> 
> [11] Tensorized LSTM with Adaptive Shared Memory for Learning Trends in Multivariate Time Series 
> 
> [12] Conformal prediction interval for dynamic time-series
> 
> [13] ST-Norm: Spatial and Temporal Normalization for Multi-variate Time Series Forecasting
> 
> [14] Topological Attention for Time Series Forecasting
> 
> [15] End-to-End Learning of Coherent Probabilistic Forecasts for Hierarchical Time Series
> 
> [16] MixSeq: Connecting Macroscopic Time Series Forecasting with Microscopic Time Series Data
> 
> [17] Z-GCNETs: Time Zigzags at Graph Convolutional Networks for Time Series Forecasting


## Time Series Classification 
|   Dataset    |                                                                                                                                         Download Link                                                                                                                                          |  Domain    | Used Papers                              |
| :----------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | --------------- | ---------------------------------------- |
|   UCR/UEA    |                                                                                                                     https://www.cs.ucr.edu/~eamonn/time_series_data_2018/                                                                                                                      | Hybrid          | [18], [19], [20], [21], [22], [23], [24] |
|    PM2.5     | Xuan Liang, Tao Zou, Bin Guo, Shuo Li, Haozhe Zhang, Shuyi Zhang, Hui Huang, and Song Xi Chen. 2015. Assessing Beijing’s PM2. 5 pollution: severity, weather impact, APEC and winter heating. Proceedings of the Royal Society A: Mathematical, Physical and Engineering Sciences 471, 2182 (2 | Environment     | [25]                                     |
|   Seizure    |                                                                                                                       https://archive.physionet.org/pn3/challenge/2012/                                                                                                                        | Bio-electricity | [25]                                     |
| UCI activity |                                                                                                      https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones                                                                                                      | Bio-electricity | [1], [26], [27]                          | Classification, Imputation |

> [18] Active Model Selection for Positive Unlabeled Time Series Classification
> 
> [19] Joint-Label Learning by Dual Augmentation for Time Series Classification
> 
> [20] Learnable Dynamic Temporal Pooling for Time Series Classification
> 
> [21] MINIROCKET
> 
> [22] Multilevel Wavelet Decomposition Network for Interpretable Time Series Analysis
> 
> [23] TapNet: Multivariate Time Series Classification with Attentional Prototypical Network
> 
> [24] Time2Graph: Revisiting Time Series Modeling with Dynamic Shapelets
> 
> [25] Explainable Multivariate Time Series Classification: A Deep Neural Network Which Learns To Attend To Important Variables As Well As Informative Time Intervals
> 
> [26] Correlative Channel-Aware Fusion for Multi-View Time Series Classification
> 
> [27] Generative Semi-supervised Learning for Multivariate Time Series Imputation

## Anomaly Detection

|           Dataset            |                                                                                                                                       Download Link                                                                                                                                       | Domain      | Used Papers                              |
| :--------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | ----------- | ---------------------------------------- |
|             SWaT             |                                                                                                         https://drive.google.com/drive/folders/1ABZKdclka3e2NXBSxS9z2YF59p7g2Y5I                                                                                                          | Environment | [28], [29], [30], [31], [32]             |
|             WADI             |                                                                                                         https://drive.google.com/drive/folders/11XWMQruwxFvlVEiqNgZ1mxVw-c-5xSmR                                                                                                          | Environment | [28], [29], [31], [32]                   |
|         Power-demand         |                                                                                                                                                                                                                                                                                           | Energy      | [33]                                     |
|            Yahoo             |                                                                                                                            https://webscope.sandbox.yahoo.com/                                                                                                                            | Others      | [33]                                     |
| SMD (server machine dataset) | Ya Su, Youjian Zhao, Chenhao Niu, Rong Liu, Wei Sun, and Dan Pei. 2019. Robust Anomaly Detection for Multivariate Time Series through Stochastic Recurrent Neural Network. In Proceedings of the 25th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining. 2828–2837 | Others      | [29], [30], [32]                         |
|             SMAP             |                                                                                                                        https://nsidc.org/data/smap/smap-data.html                                                                                                                         | Environment | [32]                                     |
|          MIMIC-III           |                                                                                                                        https://physionet.org/content/mimiciii/1.4/                                                                                                                        | Medical     | [34], [35], [36], [37], [38], [39], [40] |

> [28] Graph Neural Network-Based Anomaly Detection in Multivariate Time Series
> 
> [29] Multivariate Time Series Anomaly Detection and Interpretation using Hierarchical Inter-Metric and Temporal Embedding
> 
> [30] Practical Approach to Asynchronous Multivariate Time Series Anomaly Detection and Localization
> 
> [31] Time Series Anomaly Detection for Cyber-physical Systems via Neural System Identification and Bayesian Filtering
> 
> [32] USAD : UnSupervised Anomaly Detection on Multivariate Time Series
> 
> [33] Time Series Anomaly Detection with Multiresolution Ensemble Decoding
> 
> [34] DATA-GRU: Dual-Attention Time-Aware Gated Recurrent Unit for Irregular Multivariate Time Series
> 
> [35] Dynamic Gaussian Mixture based Deep Generative Model
> 
> [36] Event Outlier Detection in Continuous Time
> 
> [37] Explaining Time Series Predictions with Dynamic Masks
> 
> [38] Learning from Irregularly-Sampled Time Series: A Missing Data Perspective
> 
> [39] Set Functions for Time Series
> 
> [40] Time Series Deconfounder: Estimating Treatment Effects over Time in the Presence of Hidden Confounders

## Others

|   Dataset    |                    Download Link                    | Domain | Used Papers            | Task                   |
| :----------: | :-------------------------------------------------: | ------ | ---------------------- | ---------------------- |
| KDD-CUP 2018 |         https://www.kdd.org/kdd2018/kdd-cup         |        | [35], [27]             | Imputation             |
| Air Quality  | https://box.nju.edu.cn/f/2239259e06dd4f4cbf64/?dl=1 |        | [1], [2], [41]         | Imputation, Regression |
|  PhysioNet   |                                                     |        | [41], [27], [42], [39] | Imputation, prediction |

> [41] CSDI: Conditional Score-based Diffusion Models for Probabilistic Time Series Imputation
> 
> [42] Joint Modeling of Local and Global Temporal Dynamics for Multivariate Time Series Forecasting with Missing Values
