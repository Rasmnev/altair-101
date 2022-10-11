# altair-101

## Setup

First create a viratual environment 

**Conda**
```shell
conda create -n altair-101
conda activate altair-101
```

**venv**

```shell
python  -m venv ./venv
source .venv/bin/activate
```

and install requirements.
```shell
pip install -r requirements.txt
```
 **(Optional)** if you don't have jupyter, install it
```shell
pip install jupyterlab
```

Create ipykernal for your created environment.

```shell
python -m ipykernel install --user --name altair-101 --display-name "altair-101"
``` 

## Start jupyter to run the notebook 
```shell
jupyter notebook
```
