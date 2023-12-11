# INR (Implicit Neural Representations for Zero-shot super-resolution of DWI)

1. Installation

pip install requirements.txt

2. Data
   
We uploaded one sample anonymized prostate DWI to the following Box folder:
https://uchicago.box.com/s/3ue65qnzxmscc313qsg42d90n556laqz

The data is a 4x4 diffusion matrix, acquired for 4 b-values (0, 150, 1000, 1500) and 4 echo times (57, 70, 150, 200). Each (b, TE) combination has a shape (x,y,z,NEX) where the last index is the number of acquisitions. We make use of the different acquisitions for super-resolution

3. Training and Inference

Jupyter notebook showing the code and outputs for one example patient is given with the repo. 




