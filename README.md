# Cifar-10 Image Classification using Autoencoder as Classifier

This project report is for fulfilling the assignment  from Ridge-i. In this project, I attempt to  make an autoencoder and then use it as a classifier to detect classes  for Cifar-10

## Getting Started
Install all the dependencies and this experiment works well using python 3.7

```
$ pip install -r requirements.txt
```
## Training
Simply run this script. This will  start  the  training.
```
$ python main.py
```
## Approaches
There are three types of methods. Adding augmentation or not. Adding noise  or not. Adding  skip connection or  not.

In order to change  these, open utils/config.py and change variables  from the followings.

```
        self.use_skip_conn = True
        self.add_noise = True
        self.augmentation = False
        self.train_encoder = True
```


## Report
You  can see the report  from this link: [link](https://github.com/RaihanUllIslam/ridge-i_assignment/blob/main/Autoencoder%20as%20Classifier%20on%20Cifar-10%20Dataset.pdf) 