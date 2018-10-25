# Deep Learning and Natural Language Processing 

## Embedding 
A comparision of word embeddings
- objects: pretrained word2vec and self-trained starspace
- task: given 1 problem in stackoverflow, sort the candidate problems by their similarities
- metric: Hit@k
- conclusion: supervised learning is much better than unsupervised learning under one specific scenario

## KerasNotes
Some practices using keras
- Aotoencoder: dimensionality reduction by deep learning(unsupervised learning)
- classifier: use DNN to classify MNIST
- CNN: use CNN to classify MNIST
- LSTM: use LSTM to classify MNIST
- regressor: use DNN to predict one function
- RNN: use RNN to classify MNIST
  
## MultilabelClassification
Use bag of words model and tf-idf model to do a multi-label classify task, tried some algorithms: svm, ridge and lr

## Seq2seq
Use bi-LSTM to match + and - by end-to-end training
- task: given string "1-5", predict the result string "-4"
- description: establish the dictionary with words: "^#&1234567890+-", encode every input and output, train them on a Bi-LSTM model
- loss function and optimizer: mse and adam


## Tensorflow notes
MNIST practice(tensorflow is to hard, droped, turn to keras and pytorch)

## PyTorch
To be continued