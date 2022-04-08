# 📈 Time Series Dataset
A comprehensive time-series dataset survey.

These datasets are classified based on the following tasks.
- [📈 Time Series Dataset](#-time-series-dataset)
  - [](#)
  - [Time Series Forecasting](#time-series-forecasting)
  - [Time Series Classification](#time-series-classification)
  - [Anomaly Detection](#anomaly-detection)
  - [Others](#others)



## 


## Time Series Forecasting 
|                Dataset                | Year  |                           Download Link                            | Domain | Used Papers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| :-----------------------------------: | :---: | :----------------------------------------------------------------: | ------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|                traffic                |       |                                                                    |        | Ada RNN, Adjusting for Autocorrelated Errors in Neural Networks for Time Series, Adversarial Sparse Transformer for Time Series Forecasting, Autoregressive Denoising Diffusion Models for Multivariate Probabilistic Time Series Forecasting, Block Hankel Tensor ARIMA for Multiple Short Time Series Forecasting, Connecting the Dots: Multivariate Time Series Forecasting with Graph Neural Networks, Deep Explicit Duration Switching Models for Time Series, Deep Rao-Blackwellised Particle Filters for Time Series Forecasting, Probabilistic Time Series Forecasting with Structured Shape and Temporal Diversity, Probabilistic Transformer for Time Series Analysis, Tensorized LSTM with Adaptive Shared Memory for Learning Trends in Multivariate Time Series                                                                                           |
|              electricity              |       |                                                                    |        | Adjusting for Autocorrelated Errors in Neural Networks for Time Series, Adversarial Sparse Transformer for Time Series Forecasting, Autoregressive Denoising Diffusion Models for Multivariate Probabilistic Time Series Forecasting, Block Hankel Tensor ARIMA for Multiple Short Time Series Forecasting, Conformal prediction interval for dynamic time-series, Connecting the Dots: Multivariate Time Series Forecasting with Graph Neural Networks, Deep Explicit Duration Switching Models for Time Series, Deep Rao-Blackwellised Particle Filters for Time Series Forecasting, Probabilistic Time Series Forecasting with Structured Shape and Temporal Diversity, Probabilistic Transformer for Time Series Analysis, ST-Norm: Spatial and Temporal Normalization for Multi-variate Time Series Forecasting, Topological Attention for Time Series Forecastin |
|                 wiki                  |       |                                                                    |        | Autoregressive Denoising Diffusion Models for Multivariate Probabilistic Time Series Forecasting, Deep Explicit Duration Switching Models for Time Series, Deep Rao-Blackwellised Particle Filters for Time Series Forecasting, End-to-End Learning of Coherent Probabilistic Forecasts for Hierarchical Time Series, MixSeq: Connecting Macroscopic Time Series Forecasting with Microscopic Time Series Data, Probabilistic Transformer for Time Series Analysis                                                                                                                                                                                                                                                                                                                                                                                                     |
|                 solar                 |       |                                                                    |        | Adjusting for Autocorrelated Errors in Neural Networks for Time Series, Adversarial Sparse Transformer for Time Series Forecasting, Autoregressive Denoising Diffusion Models for Multivariate Probabilistic Time Series Forecasting, Conformal prediction interval for dynamic time-series, Connecting the Dots: Multivariate Time Series Forecasting with Graph Neural Networks, Deep Explicit Duration Switching Models for Time Series, Deep Rao-Blackwellised Particle Filters for Time Series Forecasting, Probabilistic Transformer for Time Series Analysis, Tensorized LSTM with Adaptive Shared Memory for Learning Trends in Multivariate Time Series                                                                                                                                                                                                       |
|                 taxi                  |       |                                                                    |        | Autoregressive Denoising Diffusion Models for Multivariate Probabilistic Time Series Forecasting, Probabilistic Transformer for Time Series Analysis                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|                 PEMS                  |       |                                                                    |        | Adjusting for Autocorrelated Errors in Neural Networks for Time Series, ST-Norm: Spatial and Temporal Normalization for Multi-variate Time Series Forecasting, Z-GCNETs: Time Zigzags at Graph Convolutional Networks for Time Series Forecasting                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|                BikeNYC                |       |                                                                    |        | ST-Norm: Spatial and Temporal Normalization for Multi-variate Time Series Forecasting                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|                  M5                   |       |                                                                    |        | Adjusting for Autocorrelated Errors in Neural Networks for Time Series, MixSeq: Connecting Macroscopic Time Series Forecasting with Microscopic Time Series Data                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
|               Rossmann                |       |                                                                    |        | MixSeq: Connecting Macroscopic Time Series Forecasting with Microscopic Time Series Data                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|                  M4                   |       |                                                                    |        | Adjusting for Autocorrelated Errors in Neural Networks for Time Series, Adversarial Sparse Transformer for Time Series Forecasting                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|               exchange                |       |                                                                    |        | Adjusting for Autocorrelated Errors in Neural Networks for Time Series, Autoregressive Denoising Diffusion Models for Multivariate Probabilistic Time Series Forecasting, Connecting the Dots: Multivariate Time Series Forecasting with Graph Neural Networks, Deep Explicit Duration Switching Models for Time Series, Deep Rao-Blackwellised Particle Filters for Time Series Forecasting, Tensorized LSTM with Adaptive Shared Memory for Learning Trends in Multivariate Time Series                                                                                                                                                                                                                                                                                                                                                                              |
|                 parts                 |       |                                                                    |        | Topological Attention for Time Series Forecastin                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
|                 Labor                 |       |               Australian Bureau of Statistics, 2020)               |        | End-to-End Learning of Coherent Probabilistic Forecasts for Hierarchical Time Series                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|                Tourism                |       |               m (Tourism Australia, Canberra, 2005)                |        | End-to-End Learning of Coherent Probabilistic Forecasts for Hierarchical Time Series                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|                 wind                  |       | https://www.kaggle.com/sohier/30-years-of-european-wind-generation |        | Adversarial Sparse Transformer for Time Series Forecasting                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |



## Time Series Classification 
|                      Dataset                       |   Year   |                                                                                                                                                              Download Link                                                                                                                                                               | Domain         | Used Papers                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| :------------------------------------------------: | :------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|                      UCR/UEA                       |          |                                                                                                                                                                                                                                                                                                                                          |                | Active Model Selection for Positive Unlabeled Time Series Classification, Joint-Label Learning by Dual Augmentation for Time Series Classification, Learnable Dynamic Temporal Pooling for Time Series Classification, MINIROCKET, Multilevel Wavelet Decomposition Network for Interpretable Time Series Analysis, TapNet: Multivariate Time Series Classification with Attentional Prototypical Network, Time2Graph: Revisiting Time Series Modeling with Dynamic Shapelets |
|                       PM2.5                        |          |                      Xuan Liang, Tao Zou, Bin Guo, Shuo Li, Haozhe Zhang, Shuyi Zhang, Hui Huang, and Song Xi Chen. 2015. Assessing Beijing’s PM2. 5 pollution: severity, weather impact, APEC and winter heating. Proceedings of the Royal Society A: Mathematical, Physical and Engineering Sciences 471, 2182 (2                      |                | Explainable Multivariate Time Series Classification: A Deep Neural Network Which Learns To Aend To Important Variables As Well As Informative Time Intervals                                                                                                                                                                                                                                                                                                                 |
|                      Seizure                       |          | Ary L Goldberger, Luis AN Amaral, Leon Glass, Jeffrey M Hausdorff, Plamen Ch Ivanov, Roger G Mark, Joseph E Mietus, George B Moody, Chung-Kang Peng, and H Eugene Stanley. 2000. PhysioBank, PhysioToolkit, and PhysioNet: components of a new research resource for complex physiologic signals. circulation 101, 23 (2000), e215–e220. |                | Explainable Multivariate Time Series Classification: A Deep Neural Network Which Learns To Aend To Important Variables As Well As Informative Time Intervals                                                                                                                                                                                                                                                                                                                 |
|                    UCI activity                    | AAAI2021 |                                                                                                                                                                                                                                                                                                                                          |                | Ada RNN, Correlative Channel-Aware Fusion for Multi-View Time Series Classification, Generative Semi-supervised Learning for Multivariate Time Series Imputation                                                                                                                                                                                                                                                                                                              | Classification, Imputation |



## Anomaly Detection

| Dataset | Year  | Download Link | Domain | Used Papers |
| :-----: | :---: | :-----------: | ------ | ----------- |
|SWaT                                                     |          |                                                                                                                                                                                                                                                                                                                                        |                          |Graph Neural Network-Based Anomaly Detection in Multivariate Time Series, Multivariate Time Series Anomaly Detection and Interpretation using Hierarchical Inter-Metric and Temporal Embedding, Practical Approach to Asynchronous Multivariate Time Series Anomaly Detection and Localization, Time Series Anomaly Detection for Cyber-physical Systems via Neural System Identification and Bayesian Filtering, USAD : UnSupervised Anomaly Detection on Multivariate Time Series                                                                                                                                                                                                                                                                                                                                                                                   |
|WADI                                                     |          |                                                                                                                                                                                                                                                                                                                                        |                          |Graph Neural Network-Based Anomaly Detection in Multivariate Time Series, Multivariate Time Series Anomaly Detection and Interpretation using Hierarchical Inter-Metric and Temporal Embedding, Time Series Anomaly Detection for Cyber-physical Systems via Neural System Identification and Bayesian Filtering, USAD : UnSupervised Anomaly Detection on Multivariate Time Series                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|Power-demand                                             |          |                                                                                                                                                                                                                                                                                                                                        |                          |Time Series Anomaly Detection with Multiresolution Ensemble Decoding                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|Yahoo                                                    |          |                                                                                                                                                                                                                                                                                                                                        |                          |Time Series Anomaly Detection with Multiresolution Ensemble Decoding                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|SMD (server machine dataset)                             |          |Ya Su, Youjian Zhao, Chenhao Niu, Rong Liu, Wei Sun, and Dan Pei. 2019. Robust Anomaly Detection for Multivariate Time Series through Stochastic Recurrent Neural Network. In Proceedings of the 25th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining. 2828–2837                                               |                          |Multivariate Time Series Anomaly Detection and Interpretation using Hierarchical Inter-Metric and Temporal Embedding, Practical Approach to Asynchronous Multivariate Time Series Anomaly Detection and Localization, USAD : UnSupervised Anomaly Detection on Multivariate Time Series                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|SMAP                                                     |          |                                                                                                                                                                                                                                                                                                                                        |                          |USAD : UnSupervised Anomaly Detection on Multivariate Time Series                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|MIMIC-III                                                |          |                                                                                                                                                                                                                                                                                                                                        |                          |DATA-GRU: Dual-Attention Time-Aware Gated Recurrent Unit for Irregular Multivariate Time Series, Dynamic Gaussian Mixture based Deep Generative Model, Event Outlier Detection in Continuous Time, Explaining Time Series Predictions with Dynamic Masks, Learning from Irregularly-Sampled Time Series: A Missing Data Perspective, Set Functions for Time Series, Time Series Deconfounder: Estimating Treatment Effects over Time in the Presence of Hidden Confounders                                                                                                                                                                                                                                                                                                                                                                                            |

## Others

|            Dataset             | Year  |                    Download Link                    | Domain                        | Used Papers                                                                                                                                                                                                                                                                                                            | Task                   |
| :----------------------------: | :---: | :-------------------------------------------------: | ----------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------- |
|            KDD-CUP             |       |                                                     |                               | Dynamic Gaussian Mixture based Deep Generative Model, Generative Semi-supervised Learning for Multivariate Time Series Imputation                                                                                                                                                                                      | Imputation             |
|          Air Quality           |       | https://box.nju.edu.cn/f/2239259e06dd4f4cbf64/?dl=1 |                               | Ada RNN, Adjusting for Autocorrelated Errors in Neural Networks for Time Series, CSDI: Conditional Score-based Diffusion Models for Probabilistic Time Series Imputation                                                                                                                                               | Imputation, Regression |
|           PhysioNet            |       |                                                     | 存在missing value的prediction | CSDI: Conditional Score-based Diffusion Models for Probabilistic Time Series Imputation, Generative Semi-supervised Learning for Multivariate Time Series Imputation, Joint Modeling of Local and Global Temporal Dynamics for Multivariate Time Series Forecasting with Missing Values, Set Functions for Time Series | Imputation, prediction |
