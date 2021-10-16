# tensorflow-examples
Collection of examples to learn tensorflow

## Prerequisties
- ubuntu 21.x (Preferable)
- python 3.9
- conda
- git

## Setup
### Install conda
Install MiniConda by from [here](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html)
Download the Installer script for your environment.
For Ubuntu:
```shell
$ chmod +x Miniconda3-py39_4.10.3-Linux-x86_64.sh
$ ./Miniconda3-py39_4.10.3-Linux-x86_64.sh
```

### Create and Activate environment 
```shell
$ conda create --name mldev python=3.9
$ conda activate mldev
$ pip install -r requirements.txt
```

## Run
```shell
$ jupyter-lab
```