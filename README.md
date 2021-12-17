Install miniconda :

```wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh -O ~/miniconda.sh```

```bash ~/miniconda.sh -b -p $HOME/miniconda```

```conda activate```

```conda init``` or ```conda init zsh``` (for zsh shell)

Install ipython & jupyter :

```conda install ipython jupyter```

and the dependencies :

```conda install -c conda-forge numpy```

```conda install -c conda-forge opencv```

```conda install -c conda-forge matplotlib```

Launch the notebook :

```jupyter```

```jupyter notebook```