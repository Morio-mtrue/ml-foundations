# ML Foundations

My machine learning training notebooks, gathered in one place. They follow a structured course: Python problem-solving first, then data analysis, then classical machine learning built from scratch with NumPy, then deep learning from first principles through to Keras, TensorFlow and modern computer vision models.

Each folder holds a self-contained Jupyter notebook. Where a notebook needs a small dataset, it sits beside it.

## 1. Python problem-solving

| Notebook | Topic |
| --- | --- |
| [Wheat and chessboard](01-python-problem-solving/wheat-and-chessboard) | Exponential growth with NumPy arrays and plots |
| [Rice doubling](01-python-problem-solving/rice-doubling) | Growth over time and how long it takes to run out |
| [Chestnut bun](01-python-problem-solving/chestnut-bun) | Doubling volume until it covers the solar system |
| [Matrix product](01-python-problem-solving/matrix-product) | Matrix multiplication by hand, by loops and with NumPy |
| [Gradient](01-python-problem-solving/gradient) | Linear and non-linear functions and their gradients |
| [Mt. Fuji descent](01-python-problem-solving/mt-fuji-descent) | Gradient descent intuition on real elevation data |

## 2. Data analysis

| Notebook | Topic |
| --- | --- |
| [Iris EDA](02-data-analysis/iris-eda) | Loading, combining and visualising the Iris dataset |
| [House prices EDA](02-data-analysis/house-prices-eda) | Missing values, distributions and correlations (Kaggle House Prices) |
| [Home credit EDA](02-data-analysis/home-credit-eda) | Exploring credit default risk data (Kaggle Home Credit) |
| [Dummy data](02-data-analysis/dummy-data) | Generating synthetic datasets with NumPy |

## 3. Classical machine learning (from scratch)

| Notebook | Topic |
| --- | --- |
| [Linear regression](03-classical-ml/linear-regression) | Hypothesis function, cost and gradient descent implemented by hand |
| [Logistic regression](03-classical-ml/logistic-regression) | Sigmoid, regularisation and decision boundaries |
| [SVM](03-classical-ml/svm) | Lagrange multipliers and support vector selection |
| [Decision tree](03-classical-ml/decision-tree) | Gini impurity, information gain and tree building |
| [K-means clustering](03-classical-ml/kmeans-clustering) | Centroid initialisation, elbow method, wholesale customer segments |
| [Ensemble learning](03-classical-ml/ensemble-learning) | Blending, bagging and stacking |
| [Iris binary classification](03-classical-ml/iris-binary-classification) | Comparing classifiers with scikit-learn |
| [House price forecasting](03-classical-ml/house-price-forecasting) | Regression models compared on house price data |

## 4. Deep learning

| Notebook | Topic |
| --- | --- |
| [Neural network from scratch](04-deep-learning/neural-network-from-scratch) | Forward and backward propagation in NumPy |
| [Deep neural network](04-deep-learning/deep-neural-network) | Layer classes, initialisers and optimisers |
| [Conv1D from scratch](04-deep-learning/conv1d-from-scratch) | One-dimensional convolution layer implemented by hand |
| [Conv2D from scratch](04-deep-learning/conv2d-from-scratch) | Two-dimensional convolution and pooling layers |
| [TensorFlow](04-deep-learning/tensorflow) | Rebuilding the scratch models in TensorFlow |
| [Keras](04-deep-learning/keras) | Running and adapting the official Keras examples |
| [RNN from scratch](04-deep-learning/rnn-from-scratch) | Recurrent forward propagation by hand |
| [LSTM](04-deep-learning/lstm) | Comparing recurrent layer types in Keras |
| [Seq2Seq](04-deep-learning/seq2seq) | Sequence-to-sequence translation |
| [ResNet and VGG](04-deep-learning/resnet-vgg) | Transfer learning with pretrained CNNs |
| [U-Net](04-deep-learning/u-net) | Image segmentation |
| [Faster R-CNN and YOLOv3](04-deep-learning/faster-rcnn-yolov3) | Object detection |

## Notes

- These are learning notebooks, kept as a record of the ground covered. My applied work is on my [profile](https://github.com/Morio-mtrue).
- The Home Credit dataset (about 166 MB) is not included. Download `application_train.csv` from the Kaggle Home Credit Default Risk competition to rerun that notebook.
