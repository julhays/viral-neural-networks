## Definitions of key terms
* phylodynamics - a field that studies how evolutionary biology, epidemiology, and mathmateical modeling interact to influence population dynamics and shape the branching patterns of viral phylogenetic trees. Phylodynamics provides information about outbreaks such as when and where transmission occurred, how the pathogen spread geographically, and the impact of interventions or population structure on transmission dynamics.
* ordinary differential equation (ODE) - mathematical equation that describe how a function's rate of change relates to its current state for a single independent variable. In this case, an ODEs are used to calculate the probability density of a phylogenetic tree.
* lineage - eevolutionary line of descent of a pathogen inferred from genetic sequence data.
* state - a geographic location, such as a zip code, city, or county.
* node - a computational unit in a neural network that processes data and passes it on to the next layer of the network
* hyperparameters - adjustable parameters in a neural network whose values control how the model learns. Unlike model parameters (e.g., weights and biases), which are learned by the model from the data during training, hyperparameters are external configurations that influence training process and model performance. Some examples include:
  * learning rate - step size for updating model weights during training
  * activation functions - specify the non-linear transformations applied between each layer
  * epochs: the number of complete passes through the training dataset the model learns on
  * number of layers/neurons - defines the architecture of the neural network
* loss - metric that quantifies the error between a model's prediction and the actual solution
* MASCOT - state-of-the-art phylodynamics algorithm used to infer viral transmission history given a phylogenetic tree by solving sets of ordinary differential equations. 
* nnMASCOT - a full scale inplementation of MASCOT that swaps the traditional step-wise ODE solver in MASCOT with a neural network.
* PyTorch - a library in Python used to train and implement deep learning models such as a neural network.
* Weights & Biases (W&B) - an AI developer platform with tools for training, fine-tuning, and evaluating the performace of deep learning models.
