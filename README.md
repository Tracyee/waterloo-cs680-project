There are in total 8 jupyter notebooks included for this project, each of which trains a particular model on a particular version of the dataset.

The dataset and model can be inferred from their names: ss2 denotes the SST-2 (binary) version of the Stanford Sentiment Treebank, ss5 denotes the SST-5 version (fine-grained); cnn denotes the TextCNN implementation, cnn-non-static denotes the TextCNN with trainable word embeddings, lstm denotes a bidirectional LSTM model with embedding, and bert denotes Bidirectional  Encoder  Representations  from  Transformers.

If you want to run the notebooks and reproduce the result, you need to install some essentially dependencies. You can create a conda environment with the given yml file by running conda env create -f sentiment.yml. Most importantly, you should install pyTorch and fastNLP.


Disclaimer:
1. The models are trained with 1 NVIDIA 1080Ti GPU with 10G memory. You may run into memory issuses if you are using a less powerful training environment.
2. Due to limited amount of time, the code has not been refractored and is not well modularized. 


