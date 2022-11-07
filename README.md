# machine-learning-a-z

Everything ML

## Create and activate virtual environment

```
$ python -m venv venv
$ source venv/bin/activate
$ pip install --upgrade pip

```

## Install python modules

```
$ pip install -r requirements.txt
```

## Add new kernel for virtual environment

```
$ ipython kernel install --user --name=machine-learning-az-kernel
```

## Run jupyter notebook server

```
$ jupyter notebook
```

## Uninstall kernel for virtual environment when done

```
$ jupyter-kernelspec uninstall machine-learning-a-z-kernel
```
