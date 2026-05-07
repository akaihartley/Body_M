# BodyM CNN 

This project is for EE240
Group 20
Alexander Hartly and Harshaan Sall

This dir should contain data from BodyM and a jupyter notebook 'Body_M.ipynb'

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) for installs.

```bash
pip install opencv-python numpy scipy tensorflow pandas scikit-learn
```
To download data from AWS include boto3
```bash
pip install boto3
```
## Steps

Skip section 'Data from AWS' if data is extracted from zip file.
Begin running code from 'Data processing' if wanting to run just the CNN.
models are saved after running. load from save dir.

for model without images, set 'usee_images=False'.

## README FORMAT

The format for this README.txt was taken from [Make a README](https://www.makeareadme.com/)