# 100 DAYS OF ML

## Day 0: August 24, 2018
**Today's Progress:**
**1.** Studied Keras from a book: "Deep Learning with Python" by Francois Cholet. 
**2.** Read an article titled 7 steps to learning Keras: https://www.kdnuggets.com/2017/10/seven-steps-deep-learning-keras.html
**3.** Watched a video (from pydata) on Keras: https://www.youtube.com/watch?v=FrkYu2zVUyM 

**Thoughts:**
I am beginning to grasp the function class / Model class. See this documentation for more info: 
https://keras.io/models/about-keras-models/

## Day 1: August 25, 2018
**Today's Progress:**
**1.** Studied Keras from a book: "Deep Learning with Python" by Francois Cholet. Today I finished reading the last chapter.
**2.** Watched the first 30 minutes of a more recent video (from pydata) on Keras: https://www.youtube.com/watch?v=BBIA6Wcu2j4
**3.** Bookmarked a set of keras implementations of Generative Adversarial Networks


**Thoughts:**
Today I learned about the implementation of 'temperature' in a RNN/LSTM. I was pleased to learn that keras functionality is low enough level to accomplish a dynamic temperature. My hope is to reproduce (in keras) the results of this blog:
https://www.mtgsalvation.com/forums/magic-fundamentals/custom-card-creation/612057-generating-magic-cards-using-deep-recurrent-neural?page=32

## Day 2: August 26, 2018
**Today's Progress:**
**1.** Watched the last hour of the same video from yesterday.
**2.** Watched Siraj Raval's video on how to teach AI: https://www.youtube.com/watch?v=tczjZOLVjJM&t=654s


**Thoughts:**
One term stuck out to me that I failed to understand: Batch Normalization. I'm reading this article to amend that: https://towardsdatascience.com/batch-normalization-in-neural-networks-1ac91516821c

## Day 3: August 27, 2018
**Today's Progress:**
**1.** Watched the first sixteen episodes of 'AI Adventures' https://www.youtube.com/watch?v=0uXMgLIlXoE&list=PLIivdWyY5sqJxnwJhe3etaK7utrBiPBQ2&index=17
**2.** Watched two videos by sentdext on Tensorboard and model optimization.
**3.** Printed out and read over the original GAN paper by Ian Goodfellow, Yoshua Bengio, Sherjil Ozair, and others.
**4.** Wrote out some basic vocabulary terms that every beginner should familiarize themselves with. In the next few weeks I will be helping to organize a meetup in San Francisco. I did this work as preperation for a handout I could share with students to make sure everyone is caught up as best as possible

## Day 4: August 28, 2018
**Today's Progress:**
**1.** reread the original GAN paper
**2.** Printed and read the paper 'Improved Techniques for training GANs' https://arxiv.org/pdf/1606.03498.pdf
**3.** tried out the code for the first 5 chapters of "Deep Learning with Python" by Francois Cholet. 

**Thoughts:**
At first when I tried to run some of Francois Cholet's code on Convolutional Neural Nets, I found it estimating each epoch at 5+ hours... so I shut down training and checked the GPU. Of course I'd forgotten to activate the environment in which I have GPU version of tensorflow properly installed (whoops). After activating, each epoch took about ten seconds.

###  Code Snippet for checking if CUDA (GPU) is being used:
#### import tensorflow as tf
#### print("TensorFlow successfully installed.")
#### if tf.test.is_built_with_cuda():
####     print("The installed version of TensorFlow includes GPU support.")
#### else:
####     print("The installed version of TensorFlow does not include GPU support.")
