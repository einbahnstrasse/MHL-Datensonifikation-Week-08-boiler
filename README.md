# MHL-Datensonifikation-Week-08-boiler
Functions, V60 Coffee Brew Data, Jupyter Lab, MIDI

## Steps to Use JupyterLab in a Virtual Environment 

### 1. Download this Repository

Download the `.zip` folder, or clone this repository.

Open a Terminal window and run: 

```
cd /drag/and/drop/path/to/this/repository
```

### 2. Create a Virtual Environment.

Open a terminal and run:

```
bash
Copy code
python3 -m venv myenv
```

This creates an isolated Python environment in a folder named myenv.

Activate the Virtual Environment:

On macOS/Linux:
bash
Copy code
source myenv/bin/activate
On Windows:
cmd
Copy code
myenv\Scripts\activate
Install JupyterLab in the Virtual Environment: Once the environment is active (you'll see (myenv) in the terminal prompt), run:

bash
Copy code
pip install jupyterlab
Install Additional Libraries (Optional): If the notebook requires pandas, numpy, or other libraries, students can install them in the same virtual environment:

bash
Copy code
pip install pandas numpy
Run JupyterLab:

While still in the virtual environment, launch JupyterLab:
bash
Copy code
jupyter lab
This will start JupyterLab, and they can open their .ipynb notebooks.
Deactivate the Virtual Environment: After they finish using JupyterLab, they can deactivate the environment:

bash
Copy code
deactivate
