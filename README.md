# Cross-validation & Simple Linear Regression (234)

## Project overview

* Objective: To develop a predictive linear model using simple linear regression that is capable of estimating salaries within a company based on a given dataset
* Project instructions: [here](http://syllabus.africacode.net/projects/data-science-specific/cross-validation-and-simple-linear-regression/
)
 
## Prerequisites

- Python 3.x
- Jupyter Notebook

## Installation and Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/Thxbiso-DS/simple-linear-regression-and-cross-validation.git
    ```

2. Navigate to the directory:
    ```bash 
    cd simple-linear-regression-and-cross-validation/
    ```

3. Create a virtual environment with a name of your choice or the given name:
   ```bash
   python -m venv linreg-env
   ```

4. Activate your environment:
   - On Windows:
    ```powershell 
    .\linreg-env\Scripts\activate
    ```
   - On macOS/Linux:
    ```bash
    source linreg-env/bin/activate
    ```
5. Install Jupyter in your virtual environment:
    ```bash
    pip install jupyter notebook
    ```
6. Next is to install the kernel for the notebook to run on:
   ```bash
    ipython kernel install --user --name=linear_regression_kernel 
   ```
7. Install dependencies:
    ```bash 
    pip install -r requirements.txt
    ``````
    
8. Start jupyter notebook:
    ```bash
    jupyter notebook
    ```

9.  Navigate to http://localhost:8888 in your web browser.

## Use

1. Open the Jupyter Notebook file (`linear_regression_and_cross_validation.ipynb`).
   
2. Under kernels select `linear_regression_kernel `

3. Under run choose choose the option to run all cell.
4. Once you are done, you can close the the browser and enter `deactivate` on your command line 

## Author 
Thabiso Mokgete  
* s.mokgete@gmail.com

## License 
Copyright © 2023 [Thabiso Mokgete](https://github.com/Thxbiso-DS).<br />
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)