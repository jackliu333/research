# Research Proposal
Anomaly detection, or change point detection, has been a popular research topic in recent years. Most statistical methods uses adaptive forecasting as baseline model based on certain window size, and classifies the new data point as anomalous if it deviates from baseline prediction by some threshold. The choice of window size and threshold thus affect the quality of the anomaly detection model, and should change based on domain and time period. To avoid such continuous parameter tuning, we introduce reinforcement learning to consistently learn the optimal policy on parameter tuning and anomaly detection. In addition, we employ group sparse lasso for anomaly estimation, which enables us to find the location of the anomaly with statistical significance.
