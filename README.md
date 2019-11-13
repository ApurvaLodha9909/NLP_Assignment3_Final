==========================================================================================

         Introduction to Natural Laguage Processing Assignment 3
 
==========================================================================================

1. In this assignment, I Perform:

  
  - implement the arc-standard algorithm from Incrementality in Deterministic Dependency Parsing(2004, Nivre)

  From A Fast and Accurate Dependency Parser using Neural Networks(2014, Danqi and Manning) 
  - implement feature extraction
  - implement the neural network architecture including activation function
  - implement loss function

 

2. This package contains several files:

  - data.py: 
    This file is the main script for training dependency parser.

  - model.py
    The dependency tree class file.

  - ParsingSystem.py
    This file contains the class for a transition-based parsing framework for dependency parsing.

  - Configuration.py
    The configuration class file.

  - constants.py
    This file contains all hyper parameters.

  - Util.py
    This file contains functions for reading and writing CONLL file. 

  - data/
    train.conll - train set, labeld
    dev.conll - dev set, labeld
    test.conll - test set, *unlabeled*


3. I Performed the task for :
  1. Implement the arc-standard algorithm in ParsingSystem.py
  2. Implement feature extraction in data.py: getFeatures(...)
  3. Implement neural network architecture including activation function: forward_pass(...)
  4. Implement loss function and calculate loss value: in DependencyParserModel.build_graph(...)
  5. Try different number of hidden layers
  6. Try different non-linear activation functions
  7. Train a parser with Fixed embeddings -- by setting trainable=False in tf.Variable


