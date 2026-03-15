# Conda and Python Commands Guide

This guide covers essential Conda environment management, package installation, and Python commands for data science and machine learning projects.

## Conda Environment Management

### Creating a New Environment

Create a new conda environment with a specific Python version:

```bash
conda create -n myenv python=3.10
```

Create an environment in a specific directory:

```bash
conda create -p /path/to/venv python=3.10
```

### Activating and Deactivating Environments

Activate an environment:

```bash
conda activate myenv
```

Deactivate the current environment:

```bash
conda deactivate
```

### Listing Environments

List all available conda environments:

```bash
conda env list
```

## Package Management with Conda

### Installing Packages

Install packages using conda:

```bash
conda install numpy pandas scikit-learn matplotlib
```

### Listing Installed Packages

View all installed packages in the current environment:

```bash
conda list
```

### Updating Packages

Update a specific package:

```bash
conda update package_name
```

Update all packages:

```bash
conda update --all
```

### Removing Packages

Remove a package:

```bash
conda remove package_name
```

### Searching for Packages

Search for available packages:

```bash
conda search package_name
```

## Python Commands

### Check Python Version

Check the Python version:

```bash
python --version
```

### Running Python Scripts

Execute a Python script:

```bash
python script.py
```

### Interactive Python Session

Start an interactive Python session:

```bash
python
```

## Pip Package Management

### Installing Packages with Pip

Install packages using pip:

```bash
pip install package_name
```

Install from requirements file:

```bash
pip install -r requirements.txt
```

### Listing Pip Packages

List installed pip packages:

```bash
pip list
```

### Freeze Requirements

Save current environment packages to requirements.txt:

```bash
pip freeze > requirements.txt
```

## Jupyter Notebook Commands

### Installing Jupyter and Kernel

Install Jupyter Notebook:

```bash
pip install jupyter
```

Install IPython kernel for notebooks:

```bash
pip install ipykernel
```

### Running Jupyter Notebook

Start Jupyter Notebook server:

```bash
jupyter notebook
```

### Converting Notebooks

Convert notebook to Python script:

```bash
jupyter nbconvert --to script notebook.ipynb
```

Convert to HTML:

```bash
jupyter nbconvert --to html notebook.ipynb
```

## Additional Useful Commands

### Conda Info

Get information about conda installation:

```bash
conda info
```

### Clean Conda Cache

Clean conda cache to free up space:

```bash
conda clean --all
```

### Export Environment

Export environment to YAML file:

```bash
conda env export > environment.yml
```

### Create Environment from YAML

Create environment from YAML file:

```bash
conda env create -f environment.yml
```
