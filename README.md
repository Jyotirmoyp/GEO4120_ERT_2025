# GEO4120_ERT_2025

This data set will be used for GEO4120 Near Surface geophysics course's ERT module. 

# Instructions for Installing Conda and Associated Packages

## 1. Conda Installation

Conda installation for windows, linux or mac is given in details here: https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html

Miniconda will take less space in the system and ideally it should work. But if you have enough space, better install anaconda. 

Once installed, type in your terminal 

$ conda --version


if it prints conda 23.0.0 or more, it should be fine. 

## 2. pyGIMLi installation

Once conda is intalled, pyGIMLi can be installed. All the instructions are given here: https://www.pygimli.org/installation.html

Phython interface: 

Spyder or jupyterlab can be installed in the same environment as instructed by the page. 


## 3. Preferred way of installation (in linux/mac terminal)

$ conda create -n pg -c gimli -c conda-forge "pygimli>=1.5.0"
$ conda activate pg
(pg)$ conda install -c conda-forge spyder

Users may choose to install nothing and can work in google colab. 

## 4. Google colab

in the google colab notebook just type: 
!pip install pygimli tetgen

For detailed instruction, follow: https://www.pygimli.org/installation.html




