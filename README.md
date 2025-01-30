# SDO/AIA and Solar Orbiter/EUI alignment mini-workshop

(Presented Feburary 21st at [SDO 2025 Science Workshop](https://sdo2025.sdo-workshops.org/))

---

In order to follow along with this tutorial locally, we'll need to clone this repository (download the files) and activate a conda environment (install the necessary packages).

These steps assume you already have conda installed (if you don't, follow the conda installation guide [here](https://docs.conda.io/projects/conda/en/stable/user-guide/install/index.html#)).


### Cloning this repository
First, we need to copy this github repository on to your computer. To do this, open your terminal and type:

```
git clone https://github.com/aylaweitz/SDO-EUI-mini-workshop.git
```
** If this doesn't work, you can download this repository as a zip file! Click on green code button on the top right hand side and then click download zip.

<br>

Move into this repository. Run the following line in your terminal:
```
cd SDO-EUI-mini-workshop
```


### Creating a conda envrionment
The python packages required to run this workshop notebook are listed in the `env.yml` file in this repository. To create an environment with these packages installed, in terminal type:
```
conda env create -f env.yml
```
This will then create a new conda environment called `SDO_EUI_workshop_env` (this name is listed in the `env.yml` file).


To activate the environment we just created, run the following:
```
conda activate SDO_EUI_workshop_env
```


### Starting Jupyter Notebook
Inside the environment we just activated, type:
```
jupyter notebook
```
This should open a jupyter notebook homepage where you can access all this repository's notebook in your default browser.
