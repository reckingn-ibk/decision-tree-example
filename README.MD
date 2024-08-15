
This quick-start guide is intended for users who don't have experience with Python.  
If you know how to install Python and the required packages, you can skip this. 
You can find the requirements and package versions in `decision_tree_prime_numbers-requirements.txt`.

The following contains the minimum required steps for getting started with Jupyter notebooks in Visual Studio Code at the time of this guide's creation. 
There are of course many other ways to achieve the same result. This guide is targeted specifically to run the notebook `decision_tree_prime_numbers.ipynb`.  
More detailed (and always up to date) guides can be found here: 
* Using Python in VS Code: https://code.visualstudio.com/docs/python/python-tutorial#__install-a-python-interpreter
* Working with Jupyter notebooks in VS Code: https://code.visualstudio.com/docs/datascience/jupyter-notebooks

# Quick-start guide

## Install Python
Install Python from https://www.python.org/downloads/  
Be mindful of compatibility issues. The Jupyter notebook in this repository was tested with Python 3.9.7.  

## Install VS Code
Install VS Code from https://code.visualstudio.com/

Open VS Code  

Install the Python and Jupyter Extensions from the Extensions Marketplace (in the side bar on the left side of VS Code).  

## Run the Jupyter notebook in VS Code
Click `File` > `Open folder` (in the top menu bar of VS Code) and select the folder with the Jupyter notebook `decision_tree_prime_numbers.ipynb`.  
Select the Jupter notebook in the Explorer (in the side bar on the left side of VS Code).

### Create a virtual enviroment
Click `Select Kernel` (on the top right of the notebook in VS Code, see https://code.visualstudio.com/docs/datascience/jupyter-notebooks#_create-or-open-a-jupyter-notebook for a screenshot).  
A Pop-up will open at top of the notebook.

Select `Python Environments...`  

Select `Create Python Environment`  

Select `Venv`  

Select your Python installation. The Juypter notebook has been tested with Python 3.9.7.  

VS Code will create the subfolder `.venv` in your folder.

### Install the packages needed to run the notebook 
Click `Terminal` > `New Terminal` (in the top menu bar of VS Code)  
A terminal will open at the bottom of VS Code.

Open the Command Prompt by clicking the downwards arrow `⌄` (next to the `+`) on the right side of the terminal, then selecting `Command Prompt` (on Windows)  
You should now see the line `(.venv) "PATH OF YOUR FOLDER"` in the terminal

Run the following commands in the terminal:  
`pip install -U scikit-learn`  
`pip install -U matplotlib`  
`pip install pandas`  

This will install the packages in the virtual environment.

### Run the notebook
Now you can run the Jupyter notbook with `Run all` (click the two arrows displayed at the top of the Juypter notebook).  
This resource shows how to use Jupyter Notebooks: https://code.visualstudio.com/docs/datascience/jupyter-notebooks#_run-multiple-code-cells
