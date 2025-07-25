# Sagebook Installer

This repository contains the setup instructions and dependencies for the Sagebook project.

## Setup Instructions

### TL;DR:
1. Clone this repo
2. Install conda, activate conda env
3. `pip install -r requirements.txt` or just `pip install sage-agent`

### 0. Clone Repository (Optional)

If you don't already have this repository locally, clone it:

```bash
git clone https://github.com/AlpineX-Labs/sagebook-installer.git
cd sagebook-installer
```

### 1. Install Package Management (Conda)

We recommend using conda for package management. Follow the installation guide for macOS:

- **Installation Guide**: https://docs.conda.io/projects/conda/en/stable/user-guide/install/macos.html

### 2. Create and Activate Environment

Create a new conda environment with Python 3.12:

```bash
conda create --name sagebook python=3.12
```

Activate the environment:

```bash
conda activate sagebook
```

### 3. Install Dependencies
Install the required packages using the requirements file:

```bash
pip install -r requirements.txt
```

### ADVANCED (Your Own Package Management)

You can use your own Python environment if you prefer, but you **must** install the `sage-agent` package from [PyPI](https://pypi.org/project/sage-agent/):
```bash
pip install sage-agent
```

### Note:
You can edit this requirements files or just simply pip install other packages in your `sagebook` env

## Required Folders

This project requires the following folders to exist:
- `data/` - For storing data files
- `templates/` - For storing template files

These folders are included in the repository, but if you want to start from a different folder, you should create these, as needed.

## Usage

After completing the setup, you can start JupyterLab, in the folder where you want to work 

```bash
jupyter lab
```

Make sure the `sagebook` environment is activated before running any notebooks. 