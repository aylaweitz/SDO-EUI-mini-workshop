# SDO/AIA and Solar Orbiter/EUI alignment mini-workshop

*Combining Data over Satellites* mini-workshop for [SDO 2025 Science Workshop](https://sdo2025.sdo-workshops.org/)

---

## Run this tutorial externally
If you don't want to deal with the setup, you can run this tutorial online by clicking here &#8594; [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/aylaweitz/SDO-EUI-mini-workshop/HEAD)


## Run this tutorial locally

In order to follow along with this tutorial locally, we'll need to clone this repository (download the files) and activate a conda environment (install the necessary packages).

These steps assume you already have conda installed (if you don't, follow the conda installation guide [here](https://docs.conda.io/projects/conda/en/stable/user-guide/install/index.html#)).


### 1. Cloning this repository
First, we need to copy this github repository on to your computer. To do this, open your terminal and type:

```
git clone https://github.com/aylaweitz/SDO-EUI-mini-workshop.git
```
*You can also just download this repository as a zip file! Click on green code button on the top right hand side and then click download zip.*

<br>

Now navigate into the newly created `SDO-EUI-mini-workshop` repository. Type:
```
cd SDO-EUI-mini-workshop
```


### 2. Creating a conda envrionment
The python packages required to run this workshop notebook are listed in the [`environment.yml`](https://github.com/aylaweitz/SDO-EUI-mini-workshop/blob/main/environment.yml) file in this repository. To create an environment with these packages installed, in terminal type:
```
conda env create -f environment.yml
```
This will then create a new conda environment called `SDO_EUI_workshop` (this name is listed in the `environment.yml` file). It may take a little bit for this to run.


To activate the environment we just created, run the following:
```
conda activate SDO_EUI_workshop
```


### 3. Starting Jupyter Notebook
Inside the environment we just activated, type:
```
jupyter notebook
```
This should open up a window in your default browser. This is a jupyter notebook homepage where you can access and run this repository's tutorial notebook!

---

## Other useful resources
- https://github.com/SolarOrbiterWorkshop/solo8_tutorials/tree/main/EUI_tutorial
