# Jupyter Notebook

## Installation

```bash
# use conda
conda install -c conda-forge notebook
# use pip
pip install notebook
```

## Basic Usage

```bash
# normal run to view with local browser
jupyter notebook

# run on remote server
# Replace <PORT> with your selected port number
jupyter notebook --no-browser --port=<PORT>
```

## Set Environment Variables

> To set an env variable in a jupyter notebook, just use a `%` magic commands, either `%env` or `%set_env`, e.g., `%env MY_VAR=MY_VALUE` or `%env MY_VAR MY_VALUE`. \(Use `%env` by itself to print out current environmental variables.\)

## Reference

\[1\] [https://docs.anaconda.com/anaconda/user-guide/tasks/remote-jupyter-notebook/](https://docs.anaconda.com/anaconda/user-guide/tasks/remote-jupyter-notebook/)

\[2\] [https://jupyter.org/install](https://jupyter.org/install)

\[3\] [https://stackoverflow.com/questions/37890898/how-to-set-env-variable-in-jupyter-notebook](https://stackoverflow.com/questions/37890898/how-to-set-env-variable-in-jupyter-notebook)
