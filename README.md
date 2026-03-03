# Software Evolution Practical Session: Bots and Contributor Roles in GitHub Projects

This repository contains the Jupyter Notebook for the Software Evolution practical session on bot detection and contributor role analysis in GitHub projects.

## Overview

The goal of this practical session is to analyse the activity of bots and humans in two open‑source projects from the NumFocus ecosystem. Using the RABBIT bot detection tool and a role‑assignment model, you will classify contributors, compare behavioural patterns and draw conclusions about automation in software development.

## Contents

- `Bots-Template.ipynb` : The main Jupyter Notebook containing all instructions, code cells and questions.
- `data/` : Directory with student‑specific datasets (Project‑Events, Contributor‑Events, Project‑Activities).
- `roles.py` : Python module for assigning contributor roles based on activity sequences.

## Setup Instructions

1. **Clone the repository** and navigate into it.
2. **Create and activate a Python virtual environment** (Python 3.8 or later recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate      # On Windows: venv\Scripts\activate
   ```
3. **Install JupyterLab**:
   ```bash
   pip install jupyterlab
   ```
4. **Launch JupyterLab** and open `Bots-Template.ipynb`:
   ```bash
   jupyter lab
   ```
5. Follow the instructions in the notebook. All required Python packages (seaborn, scipy, rabbit-ng, etc.) are installed automatically when you run the first code cell.

**Note:** Your assigned folder number must be set in the notebook’s first section. The dataset is already provided in the `data/` directory.