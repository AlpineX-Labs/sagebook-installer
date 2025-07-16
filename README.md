# Sagebook Installer

This repository contains the setup instructions and dependencies for the Sagebook project.

## Setup Instructions

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

### Note:
You can edit this requirements files or just simply pip install other packages in your `sagebook` env

## Usage

After completing the setup, you can start JupyterLab:

```bash
jupyter lab
```

Make sure the `sagebook` environment is activated before running any notebooks. 