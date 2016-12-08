# Deep-Learing Neural Network 
###Framework for a deep learning network to play Boxes &amp; Dots. NN Framework created to be easily adaptable for any use though.
##Objective: Create an AI capable of beating minmax algorithms and most people in a 3 x 3 Boxes and Dots game.

#Strategy: 
  1) Start with 2 x 2 board
  2) Create minmax algorithms for training 
      - Experiment with # of layers and nodes 
      - Have DLN replicate minmax algorithm
  3) Play real people 
      - Learn from lost games
      - Surpass minmax algorithm by differentiate between
        "#" of winning futures vs probabilty of a winning future occuring 
      - Introduce randomness 
  4) Scale to 3 x 3
      - Repeat steps 2 - 3
      

Current Progress:
- Boxes & Dots game created                                                 11/24
- Basic AI w/ single hidden layer                                           11/26
- Attempt to train AI through mutation                                      11/27
- Backpropagation working                                                   11/28
- Framework for Deep Learning AI                                            12/5
- Training data storage, interalized data transfer                          12/6
#- Trainer created, training for data working, started collecting            12/8



#Areas of Research Interest:
- Optimization of Gradient Descent by decreasing alpha on cost function and/or theta bounces
	Note: Start with first layer deeper layers weights not stable 
	Conclusion: This is already a thing - Momentum and Nesterov accelerated gradient, 		disappointing this was exactly what I was thinking :'(.
	See: http://sebastianruder.com/optimizing-gradient-descent/index.html#gradientdescentoptimizationalgorithms
	Will attempt a modified version to improve one scenario 

- Reinforced Learning. Will start Udacity class during winter break. 
