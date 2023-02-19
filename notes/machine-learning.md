# Machine Learning

## Deep Learning

- based on neural networks 
- *training:* inputs+parameters --> model
- *using*: inputs --> model --> results
- *effectiveness:* predictions+labels --> loss
- hyperparameter - parameters about parameters

### Models

- classification - predicts based on of discrete possibilities
- regression - predicts numeric quantities
- CNN (convolutional neural network)
    - layers of semantic components, lower --> higher
- transfer learning - use model for different task than what it was trained for
- head - part of the model specific to new dataset
- epoch - one pass through the data set
    - can augment image data by randomize resize/crop and distorting over multiple epochs
- image segmentation - model that can cluster parts of an image that belong to the same object class (e.g. pedestrian, stop sign, etc)

### Data

- training set
    - overfitting - model gives accurate results for training data but not new data
- validation set
