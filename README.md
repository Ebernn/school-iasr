## Setup

Download and extract [Fruits fresh and rotten for classification project dataset](https://www.kaggle.com/sriramr/fruits-fresh-and-rotten-for-classification).

### Install miniconda :

```wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh -O ~/miniconda.sh```

```bash ~/miniconda.sh -b -p $HOME/miniconda```

```conda init``` or ```conda init zsh``` (for zsh shell)

### Install the dependencies :

```conda create -n iasr```

```conda activate iasr```

```conda install ipython jupyter```

```conda install -c conda-forge numpy opencv matplotlib scikit-learn```

(check [this](https://exerror.com/solving-environment-failed-with-initial-frozen-solve-retrying-with-flexible-solve/) if `Solving environment: failed with initial frozen solve. Retrying with flexible solve` throws)

## Launch the notebook :

```conda activate iasr```

```jupyter notebook```
