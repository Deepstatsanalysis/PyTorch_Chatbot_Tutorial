# PyTorch Chatbot Tutorial

Note: This code has been adapted from https://pytorch.org/tutorials/beginner/chatbot_tutorial.html. We will demonstrate more details and observe the output step by step to have a deeper understanding.

I was watching freeCodeCamp course on building chatbots: [https://youtu.be/CNuI8OWsppg](https://youtu.be/CNuI8OWsppg). I wanted to find the 
notebooks and play with the code myself, but unfortunately, I was not able to find the notebooks. So, I decided to write the notebook myself completely based on the contents of the video. It has been written to be as close as possible to the video.

### How to run the model
This repository contains three notebooks and one .zip file. zip file contains [Cornell Movie-Dialogs Corpus](https://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html), the dataset we are using to build a chatbot. First you need to unzip this data in the current directoty.

1_beginner_guide.ipynb is a completely beginner guide for whom are not familiar with PyTorch. It contains basic command and operations such as how to create a tensor, slicing and reshaping the tensor, and how to do basic operations such as adding two different tensors. It is suitable for who are not familiar at all with PyTorch.

2_Chatbot_Data_Processing contains the preprocessing steps to prepare the datasets and change it to have the suitable format. The output of this notebook is "formatted_movie_lines.txt", which is used for building chatbot.

3_Chatbot_Building_Model consists of the core elements for bulding chatbot. Fisrt, some processing steps that process the input data. Then, you can find the code for creating emcoder and decoder. 

So, you should follow this steps with order:
1. Unzip the data file and put it in the current directory.
2. Run 1_beginner_guide.ipynb if you are not familiar with PyTorch.
3. Run 2_Chatbot_Data_Processing. It creates the ""formatted_movie_lines.txt".
4. Run 3_Chatbot_Building_Model in order to build and train the chatbot.
