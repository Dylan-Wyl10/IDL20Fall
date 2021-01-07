# IDL20Fall

This is the code restore dictionary of the assignments and homework of the course 11-785 Introduction to Deep Learning from Carnegie Mellon University. For each homework, the first part is in the local environment and the other is a practical Kaggle problem. 

Part1 foloder, which is a self-made library based on similar funcitons of PyTorch, is named as MyTorch. For homework1 to homework3, there are three simple neural network model with the applications of this library. 

Part2 includes the a Kaggle competition in each homework. Homework1 Part 2 is a MLP contextual classifier with a Multi-lenth Perceptron Neural Network.  

## Homework1 Part2
-------------- https://www.kaggle.com/c/11-785-fall-20-homework-1-part-2/overview
Frame Level Classification of Speech
In this challenge you will take your knowledge of feedforward neural networks and apply it to a more useful task than recognizing handwritten digits: speech recognition. You are provided a dataset of audio recordings (utterances) and their phoneme state (subphoneme) labels. The data comes from librispeech that are read aloud and labelled using the original text. If you have not encountered speech data before or have not heard of phonemes or spectrograms, we will clarify the problem further.

The training data comprises of:
1. Speech recordings (raw mel spectrogram frames)
2. Frame-level phoneme state labels
The test data comprises of:
1. Speech recordings (raw mel spectrogram frames)
2. Phoneme state labels are not given
Your job is to identify the phoneme state label for each frame in the test data set. It is important to note that utterances are of variable length.

To start the file, run: python3 hw1p2_code/main.py 
To change the model parameters, go to the neuralent.py and going through Class Nnetwork()
After compelete the code, the result and model state files is saved in ./data folder. 

## Homework2 Part2
-------------- 
