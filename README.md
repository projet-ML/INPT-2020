# INPT-2020
Machine Learning Lab

## Lab setup
### Install Miniconda
#### Download 
Miniconda from https://conda.io/miniconda.html
#### install
$bash Miniconda3-latest-Linux-x86_64.sh

### Create environment
#### Create env
$conda create --name inptlab python=3.6

#### activate env
$source activate inptlab

### Install packages 
(inptlab)$pip3 install --upgrade pip
(inptlab)$pip3 install numpy scipy pandas matplotlib 
(inptlab)$pip3 install scikit-learn
(inptlab)$pip3 install jupyter
(inptlab)$pip install --ignore-installed --upgrade tensorflow 
#### list packages
(inptlab)$ conda list

### Jupyter notebook
#### run jupyter
(inptlab)$ jupyter notebook
#### install package inside a jupyter notebook cell
!pip install numpy
