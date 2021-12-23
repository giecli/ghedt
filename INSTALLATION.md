# Installation

## Install from source
Clone the repository.
```angular2html
git clone https://github.com/j-c-cook/ghedt
```
Recursively update the submodules.
```angular2html
 git submodule update --init --recursive
```
Create environment that GHEDT can be installed to. 
```angular2html
conda create -n ENV python=3.7
```
Activate the environment. 
```angular2html
conda activate ENV
```
Install GHEDT to the environment.
```angular2html
cd ghedt/
pip install .
```
or if the package is zipped. 
```angular2html
pip install ghedt.zip
```