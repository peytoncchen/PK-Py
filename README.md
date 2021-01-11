# Supporting files for pharmacokinetic data modeling and visualization tool
This repo contains the supporting files for the pharmacokinetic data modeling and visualization tool written in HTML, CSS, and JavaScript. 
You can find the code for that app [here](https://github.com/peytoncchen/PK-Visualization). 
You will find 2 main files of interest here:
- ```calc_k.py``` 
- ```pk_example.ipynb```

### calc_k.py
```calc_k.py``` is not meant for user to run. It is simply a place to document and explain the code run in pyodide in the web application. The code cannot and will not run in a standard Python environment. It references many JavaScript related things that normal Python does not support.

### pk_example.ipynb
```pk_example.ipynb``` is meant as an example for the user to run. The code is documented and is meant for the user to customize to their needs. As it stands, it is functioning on my sample dataset and sample inputs inside a Jupyter Notebook.
To run this Jupyter Notebook:
- Requirements
  - Download and install [Python](https://www.python.org) 3.5+
  - Clone the project:
  ```
  git clone https://github.com/peytoncchen/PK-Py
  ```
    - Or: download the source code into a zip file from the green button labelled 'Code'
  - (Optional but highly recommended): Make sure you are in the source code directory and set up a python virtual environment with
  ```
  python3 -m venv NameOfVenv
  ```
  - To activate the virtual environment:
  ```
  source venv/bin/activate
  ```
  - Make sure you are in the source code directory and install all necessary dependencies:
  ```
  pip install numpy pandas scipy matplotlib jupyter
  ```
  or
  ```
  python3 -m pip install numpy pandas scipy matplotlib jupyter
  ```
  - From a terminal in the folder of this project, run the Jupyter Notebook with the following command:
  ```
  jupyter notebook
  ```

## Built With
- Python 3
- Various packages: scipy, numpy, pandas, matplotlib, jupyter

## Feedback/Development
The code for this application is open source and can be downloaded and modified as you wish. 

## Licensing
This application is licensed under the MIT License. See [LICENSE.txt](LICENSE.txt) for more details.

## Developers
- Peyton Chen

## Acknowledgments
- Caitlin Maikawa, Stanford Bioengineering Ph.D.
- Joseph Mann, Stanford Materials Science Ph.D.
- Eric Appel, Assistant Professor of Material Science and Engineering at Stanford University