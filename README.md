### Creating a virtual environment
```
conda create -p venv python==3.8
```
### Activating the virtual environment 
```
cond activate venv/
```
### Installing requirements.txt
```
pip install -r requirements.txt
```
### Create setup.py
```
Helps in converting project into package which includes version author
```
### egg-info file we generate after defining setup.py
```
The .egg-info file contains a number of metadata fields, including the following:
Name: The name of the Python package.
Version: The version of the Python package.
Description: A short description of the Python package.
Author: The author of the Python package.
Author-email: The email address of the author of the Python package.
License: The license under which the Python package is distributed.
Url: The URL of the Python package's homepage.
```
### Running setup.py
```
python setup.py install
```
### Model Lifecycle
```
EDA-->Feature Engineering-->Model Training-->Model Deployment
```
```
Data Cleaning --> Data Ingestion --> Data Transformation --> Model Training --> Model Evaluation --> Deployment
```
