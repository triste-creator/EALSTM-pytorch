# EALSTM-pytorch
# Introduction
  This is a model by long-short-time-model.We propose a new method based on short and long term memory networks for the task of predicting national carbon emissions data in the People's Republic of China,in this model,  we make use of Empirical Mode Decomposition and SelfAttention. In the area of Carbon prediction, this is a new method and none using it. Not only our model is using of the Carbon prediction,but also accuracy close to 2.6% 
# Construction
My article by RNN neutrul network, the model's construcrtion as follows:
![RNN](https://github.com/triste-creator/EALSTM-pytorch/blob/triste-creator-patch-1/RNN%E7%BB%93%E6%9E%84.png)
The following is the LSTM network structure based on the evolution of RNN networks:
![LSTM][(https://github.com/triste-creator/EALSTM-pytorch/blob/triste-creator-patch-1/%E6%9C%AA%E5%91%BD%E5%90%8D%E6%96%87%E4%BB%B6%20(1).png))
The SelfAttention structure is as follows:
![SelfAttention](https://github.com/triste-creator/EALSTM-pytorch/blob/triste-creator-patch-1/%E6%B3%A8%E6%84%8F%E5%8A%9B.png)
Based on LSTM and EMD, combined with self-attention mechanism, the EALSTM network structure proposed in this project is as follows:
![EALSTM](https://github.com/triste-creator/EALSTM-pytorch/blob/triste-creator-patch-1/%E6%9C%AA%E5%91%BD%E5%90%8D%E6%96%87%E4%BB%B6%20(1).png)
# Expermenting
EMD decomposes the final effect
![EMD1-4](https://github.com/triste-creator/EALSTM-pytorch/blob/triste-creator-patch-1/%E5%8E%9F%E7%A5%9EEMD2.png)
![EMD5-8](https://github.com/triste-creator/EALSTM-pytorch/blob/triste-creator-patch-1/%E5%8E%9F%E7%A5%9EEMD2.png)
Train:
The loss function curve is as follows:
![MSE Loss Fuction](https://github.com/triste-creator/EALSTM-pytorch/blob/triste-creator-patch-1/MSE%E6%9B%B2%E7%BA%BF.png)
Test:
EMD:
![EMD Prediction 1-4](https://github.com/triste-creator/EALSTM-pytorch/blob/triste-creator-patch-1/EMD1.png)
![EMD Prediction 5-8](https://github.com/triste-creator/EALSTM-pytorch/blob/triste-creator-patch-1/EMD1.png)
The result of the model on the test set is as follows:
![Test Data](https://github.com/triste-creator/EALSTM-pytorch/blob/triste-creator-patch-1/%E9%A2%84%E6%B5%8B%E7%BA%BF%E6%80%A7%E5%9B%BE.png)
The effect of the model on the evaluation index:
![Evaluation](https://github.com/triste-creator/EALSTM-pytorch/blob/triste-creator-patch-1/1.png)
# Conclusion
  In this paper, LSTM network is used for data prediction and analysis, and self-attention mechanism is introduced into the network to improve the model's feature learning of long-term series data, and good results are obtained in the national daily carbon emission data prediction.
