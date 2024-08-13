
This quick-start guide is intended for users who don't have experience with Python.  
If you know how to install Python and the required packages, you can skip this. 
You can find the requirements and package versions in `decision_tree_prime_numbers-requirements.txt`.

The following contains the most minimum required steps for getting started with Jupyter notebooks in Visual Studio Code at the time of this guide's creation. 
There are of course many other ways to achieve the same result.  
More detailed (and always up to date) guides can be found here: 
* Using Python in VS Code: https://code.visualstudio.com/docs/python/python-tutorial#__install-a-python-interpreter
* Working with Jupyter notebooks in VS Code: https://code.visualstudio.com/docs/datascience/jupyter-notebooks

# Quick-start guide

## Install Python
Install Python from https://www.python.org/downloads/  
Be mindful of compatibility issues. The Jupyter notebook in this repository was tested with Python 3.9.7.  

## Install VS Code
Install Visual Studio Code from https://code.visualstudio.com/

Open VS Code  

Install the Python and Jupyter Extensions from the Extensions Marketplace (in the side bar on the left side of VS Code).  


## Run the Jupyter notebook in VS Code
Click `File` > `Open folder` (in the top menu bar) and select the folder with the Jupyter notebook `decision_tree_prime_numbers.ipynb`.  
Select the Jupter notebook in the Explorer (in the side bar on the left side of VS Code).

Click `Select Kernel` (on the top right in VS Code).

### Create a virtual enviroment
Select `Python Environments...`  

Select `Create Python Environment`  

Select `Venv`  

Select your Python installation. The Juypter notebook has been tested with Python 3.9.7.  

VS Code will create the subfolder `.venv` in your folder.

### Install the packages
Click `Terminal` > `New Terminal` (in the top menu bar)  
A terminal will open at the bottom of VS Code.

Open the Command Prompt (downwards arrow next to the + on the right side of the terminal, then select `Command Prompt`)  

Run the following commands in the Console:  
`pip install -U scikit-learn`  
`pip install -U matplotlib`  
`pip install pandas`  

This will install the packages in the virtual environment.

### Run the notebook
Now you can run the Jupyter notbook with `Run all` (the two arrows displayed above the Juypter notebook).
