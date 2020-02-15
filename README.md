# Cats-vs-Dogs
Follow along the jupyter notebook to learn basic programming in tensorflow and tesorboard.
## Downloading Dataset
https://www.microsoft.com/en-ca/download/details.aspx?id=54765
## About Model
<img src="model.png?raw=true" width="200">

## Setup
Clone the repository
```
  git clone https://github.com/GopiKishan14/Cats-vs-Dogs.git
```
Opening notebook on local host:
```
  cd Cats-vs-Dogs
  jupyter-notebook
```
`Futher comments are given in notebooks to help out.`

### Pre-processing Dataset
Open [*Dataset-Builder.ipynb*](https://github.com/GopiKishan14/Cats-vs-Dogs/blob/master/Dataset-Builder.ipynb)

### Training Model :-

Open [*model.ipynb*](https://github.com/GopiKishan14/Cats-vs-Dogs/blob/master/Model.ipynb)

#### Performance and Evaluation 
```
Models trained on partial datset and the partial pre-processed datset
is provided.
```

[*Saved Model*](https://github.com/GopiKishan14/Cats-vs-Dogs/tree/master/Saved_models)


[*Built Dataset*](https://github.com/GopiKishan14/Cats-vs-Dogs/tree/master/Built_Dataset)

#### Running Tensorboard :-
Check versions :- 
```
from tensorboard import version; 
print(version.VERSION)
```
```
import tensorflow as tf; 
print(tf.__version__)
```
Running log_dir in tensorboard :-
```
tensorboard --logdir = logs/
```
#### [*Batch_acc*]

<img src="https://github.com/GopiKishan14/Cats-vs-Dogs/blob/master/batch_acc%20.svg" width="400">




#### [*Batch loss*]

<img src="https://github.com/GopiKishan14/Cats-vs-Dogs/blob/master/batch_loss%20.svg" width="400">

### Predicting :-

Open [*predict.ipynb*](https://github.com/GopiKishan14/Cats-vs-Dogs/blob/master/predict.ipynb)

## Installing Dependencies :

[*To install tensorflow*]
Refer to this [link](https://www.tensorflow.org/install/pip)

Or , on Linux for CPU-only (no GPU)
```
  pip install -U pip
  pip install tensorflow
```
[*To install anaconda-navigator*](https://anaconda.org/anaconda/anaconda-navigator)

``
conda install -c anaconda anaconda-navigator
``

[*To install tensorboard*](https://anaconda.org/conda-forge/tensorboard)

``
conda install -c conda-forge tensorboard 
``

Or through pip :-

``
pip install tensorboard
pip show tensorboard
``


[*To install opencv*](https://pypi.org/project/opencv-python/):-

```
  pip install opencv-python
```

```
  python 3.x
  Numpy
  scipy
  matplotlib
```
## About Dataset
Asirra (Animal Species Image Recognition for Restricting Access) is a HIP that works by asking users to identify photographs of cats and dogs. This task is difficult for computers, but studies have shown that people can accomplish it quickly and accurately. Asirra is unique because of its partnership with Petfinder.com, the world's largest site devoted to finding homes for homeless pets. They've provided Microsoft Research with over three million images of cats and dogs, manually classified by people at thousands of animal shelters across the United States. Kaggle is fortunate to offer a subset of this data for fun and research. For more information, see https://www.kaggle.com/c/dogs-vs-cats.

## Contributing
If you wish to contribute, feel free to open a PR
Peace out!
