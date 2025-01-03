# **DeepLOB-PyTorch: LOB Price Prediction**

A PyTorch implementation of the **DeepLOB** model for predicting price movements from limit order book (LOB) data. Based on the paper *"DeepLOB: Deep Convolutional Neural Networks for Limit Order Books"* by Zihao Zhang, Stefan Zohren, and Stephen Roberts.

## Features  
- **Convolutional Layers**: Extract spatial patterns from LOB data.  
- **Inception Modules**: Capture multi-scale temporal dependencies.  
- **LSTM Layer**: Model long-term temporal dynamics.  
- Tested on **ETH/USD LOB and Trade data** from HyperLiquid and Binance.  

## Scripts  
- **DeepLOB-torch.ipynb**: Main implementation of the DeepLOB model in PyTorch.  
- **LSTM-lob.ipynb**: Contains baseline models and an LSTM test model implemented in TensorFlow.  

## Outputs  
- Model predictions  
- Classification report and confusion matrix  
- Saved model weights  

## Acknowledgements  
Inspired by the paper [DeepLOB: Deep Convolutional Neural Networks for Limit Order Books](https://ieeexplore.ieee.org/document/8673598).  

## License  
MIT License.  
