# AutoEncoders for tabular data examples

This project is based on on the dfencoder library that provides feature rich denoising autoencoders suited for tabular data. Details for installation are provided bellow. 


# Installation
We highly recommend using a virtual environment to install! This software has only been tested using python 3.6.<br><br>
The bare-bones requirements are installed automatically by pip. You may also want to install jupyter and matplotlib to run notebooks and the ipynb logger, but these are not requirements to install.<br><br>
Install using:<br><br>
```
pip install dfencoder
```
<br><br>
Or, you can get the latest version by cloning this repository and installing from the home directory:
<br><br>
```
pip install .
```
<br><br>
# Usage
The [demo notebook](demo_data/demo.ipynb) is available to show some of the features of this library.
Compared to the original project, some more examples have been added

# Running the tests
The `adult.csv` dataset is used in the testing script. Make sure the file (found in the root of this repo) is in the same directory as `test.py` when you run the script.


# Examples in the demo
* Training the DAE to dect
* Demonstrating use of the DAE to detect outliers
* Demonstrating use of DAE to find similar points to a list of provided points in the embedding space 


# Extending and reusing the basic idea from these sources:
https://github.com/AlliedToasters/dfencoder.git


