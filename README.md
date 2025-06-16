# WP2 - Python package requirements 

This repo documents Python packages requested as part of the Pharos WP2 [tech stack V1](https://emckclac.sharepoint.com/:x:/r/sites/MT-RMI-PAI/Shared%20Documents/Tech/Work_packages/WP2_ML_user_stories/Pharos_Tech_Stack_V1.xlsx?d=wafdd41c98a654218808e5afb852fdccf&csf=1&web=1&e=bSieSU).
The package versions in `requirements.txt` are compatible with each other for installation in the same Python virtual environment.
Practical usage of these packages has not yet been tested, however.

## Usage

This `requirements.txt` has been tested using Python 3.12.10. 
Python 3.13 is not supported, as Tensorflow is not yet available for Python 3.13.
To install these packages, first create a new Python virtual environment:

```
python -m venv .venv
```

Then activate the environment and install the require packages using `pip`:

```
source .venv/bin/activate
pip install -r requirements.txt
```
