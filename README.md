This repository follows the tutorial of this [Gitlab](https://gitlab.com/ecostat/imaginecology/-/tree/master/projects/classifierWithKeras/) made by Gaspard Dussert & Vincent Miele  (CNRS/LBBE).


It is recommended to use a virtual environment to avoid conflicts with other projects, using venv or conda. Venv won't be explained here, but you can find more information [here](https://docs.python.org/3/library/venv.html).

If you don't have anaconda, you can either install the lightweigth version [miniconda](https://docs.conda.io/en/latest/miniconda.html) or install the full version [anaconda](https://www.anaconda.com/download). 

You can create a virtual environment with the following command with an anaconda/miniconda prompt:
```python
conda create -n myenv pip
```

Then, you can activate your virtual environment with the following command:
```python
conda activate myenv
```

You can move to the directory of the project with the following command:
```python
cd path/to/directory
```

And finally, you can install the required packages with the following command while in the right directory:
```python
pip install -r requirements.txt 
```

If you want to run the notebook, write the following command while being in the right directory, it will open a jupyter notebook in your browser:

```python
jupyter lab
```

