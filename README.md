# ChemRegressionNeuralNet

This project codes and trains an feedforward neural network to predict the ground state energies of molecules given their Coulomb matrices as input. This neural network uses optimisation techniques such as batch-normalisation and Adam, and uses Dropout as a regularisation technique.

The dataset being used is from a research paper that looked at machine learning for this same regression task, and contains ground state energies of 16,242 molecules calculated by quantum mechanical simulations.

The research paper can be found at: https://arxiv.org/pdf/1609.07124.pdf

The dataset is a csv file and can be found at http://bit.ly/2xjPpc4

The model trained vastly outperforms those in the research paper, with a root-mean-square error of 3.708, compared with the boosted regression tree and neural net used in the paper (36.63 and 58.39 respectively).
