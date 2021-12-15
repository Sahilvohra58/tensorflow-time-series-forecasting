**Bit Predict Time series**


- Bitcoin price prediction using N-BEATS (Neural Basis Expansion Analysis for Interpretable Time Series 
Forecasting) algorithm. 

- The algorithm consisted of 120 dense layers with each layer of 512 neurons. 

- The model used residual connection for overcoming problems of vanishing gradient and overfit.

- Designed a series of 10 deep learning experiments for improving results and forecasting horizon.  

- Also made the use of ensemble learning method by combining 5 deep learning models. 

- Introduced outliers on purpose to evaluate the effects of on training and overall model testing



This project will follow the following experiment procedure:

| Model Number | Model Type | Horizon size | Window size | Extra data |
| ----- | ----- | ----- | ----- | ----- |
| 0 | Naïve model (baseline) | NA | NA | NA |
| 1 | Dense model | 1 | 7 | NA |
| 2 | Same as 1 | 1 | 30 | NA | 
| 3 | Same as 1 | 7 | 30 | NA |
| 4 | Conv1D | 1 | 7 | NA |
| 5 | LSTM | 1 | 7 | NA |
| 6 | Same as 1 (but with multivariate data) | 1 | 7 | Block reward size |
| 7 | [N-BEATs Algorithm](https://arxiv.org/pdf/1905.10437.pdf) | 1 | 7 | NA |
| 8 | Ensemble (multiple models optimized on different loss functions) | 1 | 7 | NA | 
| 9 | Future prediction model (model to predict future values) | 1 | 7 | NA| 
| 10 | Same as 1 (but with turkey 🦃 data introduced) | 1 | 7 | NA |


