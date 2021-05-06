# Dimensional Sentiment Analysis Using a Regional CNN-LSTM Model:


- The categorical approach for sentiment analysis focuses on sentiment classification such as binary classification (i.e., positive and negative), and do not provide fine-grained sentiment analysis
- Dimensional sentiment analysis aims to recognize continuous numerical values in multiple dimensions such as the valence-arousal (VA) space
- To achieve this we are using CNN - LSTM architecture which is designed as a regression problem to predict valence space of the given text 
- Dataset used for this project is `Stanford Sentiment Treebank(SST)`
- A convolutional neural network was used to extract local information from a text, while the long short-term memory was used to extract the contextual dependencies of the text
- By combining the advantages of convolutional neural network and long short-term memory, the proposed hybrid CNN-LSTM was able to yield a good results



### Dataset 

- Stanford Sentiment Treebank (https://www.kaggle.com/atulanandjha/stanford-sentiment-treebank-v2-sst2) dataset contains 8,544 training texts, 2,210 test texts, and 1,101 validation texts
- Each text was rated with a single dimension (valence) in the range of (0, 1)
- The word vectors for the words were obtained using GloVe. The dimensionality for word vectors is 100


### Model Architecture

![Model Architecture](https://github.com/LikhithaGaddi/Sentiment_Analysis_using_CNN_LSTM/blob/main/Model_architecture.png)






The project was submitted as a part for the requirement for the fullfilment of course work of Computer Vision in the spring session of IIIT Hyderabad in the year 2021. The project is the joint effort of the collective works of

- Likhitha Gaddi
- B Sindhu
- Devershi Chandra

Under the guidance of Ms. Sireesha Vakada (TA) and Vineet Gandhi (Assistant Professor CVIT, IIITH)
