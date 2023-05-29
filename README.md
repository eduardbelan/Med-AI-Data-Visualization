# Med-AI & Data Visualization Project

## Project Sequence

### Step 0: Importing the Required Libraries
Import the necessary libraries required for data manipulation, visualization, and machine learning.

### Step I: Data Preparation and Exploration
1. Convert Data into pandas DataFrame:
   - The provided data is loaded into a pandas DataFrame for easy manipulation and analysis.

2. View Data:
   - The loaded data is explored by examining the structure and contents of the DataFrame.
   - This step helps in understanding the available data and identifying any necessary data cleaning or preprocessing steps.

3. Prep Data for Visualization:
   - Data preprocessing steps are performed to ensure the data is in a suitable format for visualization.
   - This may include handling missing values or transforming data types.

### Step II: Data Visualization
- Histogram Visualization:
   - The data is visualized using a histogram to analyze the distribution of variables.
   - Two approaches are demonstrated: using the simple `.plot` method and the more detailed `Object-Oriented` method.

- Scatter Plot Visualization:
   - The connection between variables (Cholesterol & Heart Disease, Max Heart Rate & Heart Disease) is visualized using scatter plots.

### Step III: Data Preparation for Machine Learning
- Data Adjustment for Machine Learning:
   - The data is preprocessed and adjusted to prepare it for training a machine learning algorithm.

- Splitting Data into Training and Test Datasets:
   - The data is divided into separate training and test datasets to evaluate the performance of the machine learning model.

- Training and Testing an Ensemble Algorithm:
   - An ensemble algorithm from scikit-learn is trained and tested using the preprocessed data.

## Data
The project uses a CSV-file containing anonymized patient data.
The dataset contains various attributes related to patient health, including cholesterol levels, max heart rate, and the presence of heart disease. The dataset is used for data exploration, visualization, and training a machine learning model to predict heart disease.

This project serves as an example of how to analyze and visualize medical data. It also demonstrates the process of preparing the data for machine learning tasks. The code and visualizations provided in the project can be used as a starting point for further analysis and development in the field of healthcare and data science.

Please note that this is a brief summary of the project. Detailed steps, code, and further explanations can be found in the project files.

## Tool Time
The following libraries and tools are used in this project:
```python
# for data manipulation and analysis
import pandas as pd
# for numerical operations on data
import numpy as np
# for visualizations
import matplotlib.pyplot as plt
# for training and testing machine learning models
import sklearn
```

The Project Environment was made with Miniconda. For more information on how to use Miniconda and how to set up a working environment, [visit the Miniconda Website.](https://docs.conda.io/en/latest/miniconda.html)
```bash
# Setup Project Environment with Miniconda

# 1. Open a command prompt or terminal window.

# 2. Create a project directory where you store all the data related to this project.

# 3. Inside the project directory, set up the developer environment with the desired tools using Miniconda:
conda create --prefix ./env pandas numpy matplotlib scikit-learn jupyter
# - The above command tells conda to create a folder called "env" (short for environment) within the project directory.
# - Conda will install all the specified tools into the env directory.

# 4. To start your environment using the Miniconda Terminal:

# - On Windows:
cd Your-Project-Directory
conda activate ./env
# - Note: Use forward slashes (`/`) instead of backslashes (`\`) in the environment activation command on Windows.

# - On macOS/Linux:
cd Your-Project-Directory
conda activate ./env

# 5. The developer environment should be active, and you can start a Jupyter Notebook by typing:
jupyter notebook
```