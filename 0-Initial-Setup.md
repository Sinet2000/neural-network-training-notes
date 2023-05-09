### !WARNING!. To setup environments you can use both python venv or minicoda. There are provided isntructions only for anaconda.
--

## 1. Setup virtual env
`conda config --add channels conda-forge`

## 2. Create env  (For Older Neural Networks, like SSD or Faster R-CNN)
`conda create --prefix ./b-conda-env python=3.7.12`

## 3. Activate environment 
`conda activate ./b-conda-env`

# Setup Environment to run commands in the Jupyter Notebooks (VScode)
1. Install Jupyter Notebook extensions in VSCode
2. Install IPykernel : `conda install ipykernel` !NOTE!. You must restart conda env, using commands `conda deactivate` && `conda activate ./b-conda-env`