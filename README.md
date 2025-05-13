# Enhancing CNNs and LSTMs with Attention for Time Series Classification

UNI: as7629 

This project was run in google colab. It assumes the entire UCR dataset is downloaded as .tsv files and is located in 'drive/MyDrive/UCRArchive_2018/UCRArchive_2018'

# Introduction

Recurrent Neural Networks (RNNs) and Convolutional Neural Networks (CNNs) are fundamental building blocks for ML models of time series datasets. When comparing different models for time series data, the UCR time series archive is often used to provide a variety of time series datasets for comparison. Therefore, to compare the utility of RNNs vs CNNs for time series classification, a separate RNN and CNN can be trained and compared on each of the UCR datasets. While the UCR archive is frequently used to evaluate time series classification models, most experiments emphasize traditional ML techniques that rely on feature-based approaches, rather than deep learning [1,2]. The experiments that do utilize deep learning techniques focus on advanced architectures such as Multi-scale CNN and Time Le-Net, as opposed to basic architecture of “vanilla” CNNs or LSTMs [2]. Therefore, the current experiment elucidates the differences between these two basic architectures for time series classification tasks. Additionally, each of these architectures are augmented with attention mechanisms to determine how they affect each basic architecture. This experiment also explores whether it is appropriate to add attention mechanisms before or after the typical feature extraction done with LSTMs or CNNs. Lastly, a similar analysis across the UCR datasets will consider if attention mechanisms were especially beneficial for certain dataset types. 
