# Neural-Network
A neural network is a method in artificial intelligence that teaches computers to process data in a way that is inspired by the human brain. It is a type of machine learning process, called deep learning, that uses interconnected nodes or neurons in a layered structure that resembles the human brain. It creates an adaptive system that computers use to learn from their mistakes and improve continuously. Thus, artificial neural networks attempt to solve complicated problems, like summarizing documents or recognizing faces, with greater accuracy.

A step-by-step training guide for your Neural Network

1.Randomly initialize the weights to small numbers close to 0 (but not 0).

2.Input the first observation. One feature per input node.

3.Forward-Propagation. From left to right the neurons are activated and the output value is produced.

4.Compare output value to actual value. Measure the difference between the two; the generated error.

5.From right to left the generated error is back-propagated and the weights adjusted accordingly. The learning rate of the Network is dependent on how much you adjust the weights.

6.Repeat steps 1-5 and either adjust the weights after each observation (Reinforcement learning), or after a batch of observations (Batch learning).

7.When the whole training set passes through the Neural Network, that makes an epoch. Redo more epochs.
