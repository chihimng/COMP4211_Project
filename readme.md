# COMP4211 Project

Ng Chi Him
SID 20420921
chngax@connect.ust.hk

Submission for Kaggle Completition - [TMDB Box Office Prediction](https://www.kaggle.com/c/tmdb-box-office-prediction)


## Usage

To setup and activate the environment, run:

```sh
conda create -n comp4211 python=3.6 anaconda
conda install -n comp4211 -c pytorch pytorch torchvision
conda install -n comp4211 tensorflow tensorboardX
conda active comp4211
```

Then, launch Jupyter Notebook and open files using web ui:

```sh
jupyter notebook
```

Logs generated in the submission is stored in `/logs` and can be viewed by tensorboard:

```sh
tensorboard --logdir ./logs/
```

## Dataset

Dataset obtained from Kaggle (`test.csv` and `train.csv`) should be placed in `./dataset`. Preprecessed data npz is stored here as well.