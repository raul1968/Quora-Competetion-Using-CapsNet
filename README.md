# Quora insincere question classification challenge kaggle using capsnet and different embeddings.

## Overview
### This kernel shows the following:
* Usage of bi-directional GRU networks.
* Mechanism for re-sampling of data, as their is a huge imbalance in the number of classes.
* Usage of CapsNet.
* Usage of different embeddings, and how they can be combined together to provide better results.

## Usage
* Download the dataset from kaggle and place them in the same directory as the notebook.
* Specify the path of embeddings in the EMBEDDINGS_FILES list.

## Dependencies
* Keras/ Tensorflow
* sklearn
* Pandas
* Numpy
