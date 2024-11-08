# Global Deforestation Project

<div id="Deforestation_image", align="center">

  <img src="Deforestation_image.jpg" width="700" height="500" alt=""/>

</div>


## Table of Content

* [1. Project Description](#project-description)
* [2. Datasets](#dataset)
* [3. Packages](#packages)
* [4. Environment](#environment)
* [5. Team Members](#team-members)


## 1. Project Description <a class="anchor" id="project-description"></a>

This project explores global deforestation, which is gradual or rapid removal of trees and vegetation, and conducts a thorough data analysis procedure on a dataset with the global forest area in square km. The main concern is the trend of this phenomena on a global scale between the years 1990 and 2021. Consequently, highlighting factors that contribute to the rate of deforestation or afforestation (increase in forest area) such as region and income levels. The key objectives explored are as follows:
* To perform exploratory data analysis of the global deforestation dataset.
* To analyse the change in global forest area from 1990 and 2021, identifying trends of deforestation or afforestation for each country.
* To identify countries, regions and income levels that have the largest decrease and increase in forest area between 1990 and 2021.
* To determine the relationship between income status and rate of deforestation.
* To determine the relationship between various regions and rate of deforestation.

The folowing structure is used for data analysis sequentially:
1. Importing packages
2. Data loading
3. Data cleaning
4. Exploratory Data Analysis (EDA)
5. Conclusion and insights


## 2. Datasets <a class="anchor" id="dataset"></a>

The raw dataset used in the project can be located [here] (https://github.com/LaudRam/Python_Final_Projec_ExploreAI/forest_area_km.csv). It consists of 34 coloumns and 259 rows, and has the follwing features:
* <b>Country_name</b>: list of country names, regions, and income statuses, with each element (country, region, income status) appearing as a distinct entry.
* <b>Country_code</b>: A three letter code that distinctively represents a country.
* <b>1990</b>: total forest area in squared kilometers.
    <p> .</p>
    <p> .</p>
    <p> .</p>
* <b>2021</b> : total forest area in squared kilometers.

## 3. Packages <a class="anchor" id="packages"></a>


The following packages and libraries are essential for analysis and achieving the outlined objectives:

+ `numpy (2.0.1)`
+ `pandas (2.2.2)`
+ `seaborn (0.13.2)`
+ `matplotlib (3.9.2)`


## 4.Enivironment <a class="anchor" id="environment"></a>

The project made use of a virtual environment to ensure all dependencies are isolated. This can be set up in Anaconda, which is a open source software comprising of Jupyter Notebooks and supports Python language amongst other tools. The steps to achieve this using conda interface are detailed below.

###  Setting up environment

Firstly ensure that conda is installed and this can be done by running the command below on your command prompt or terminal. If it is installed correctly, a version numeber will be retrieved. 
```bash
conda -V
```
The next step is to create a named environment. Replace <environment_name> with your desired name for the enivironment.
```bash
conda create --name <environment_name>
```
Then activate the environment.
```bash
conda activate <environment_name>
```

### Installing packages in the environment

It is paramount that the libraries are installed on your enivironment before importing. Use the the package manager and requirements.txt file to install required libraries as demonstrated below.

```bash
conda install pip #Installs package manager

pip install -r requirements.txt #installs necessary packages encased in requirements.txt
```

### Cloning Git repository

To clone the repository to a local machine, type the following command. Ensure to replace <link_to_git_repository> with the actual URL of the repository. 

`git clone <link_to_git_repository>`


## 5.Team Members <a class="anchor" id="team-members"></a>

These are the authors of this project, along with their emails for communication.

| Name                                                                                        |  Email              
|---------------------------------------------------------------------------------------------|--------------------             
| [Nthabiseng Mokhachane](https://github.com/NthabisengM95)                                                                    | nthabisengmokhachane95@gmail.com
| [Laudicia Ramasenya](https://github.com/LaudRam)                                                                      | laudiciaramasenya@gmail.com
| [Musa Khuzwayo](https://github.com/MusaKhuzwayo)                                                                           | musakhuzwayomedia@gmail.com
| [Obakeng Motalane](https://github.com/lensitaliks)                                                                        | lensitaliks@gmail.com
| [Khumbelo Dowelani](https://github.com/dowelani)                                                                       | dowelanikhumbelo@gmail.com

# Image Reference

1. Curley, J. (2018). How Does Deforestation Affect The Air? [online] Sciencing. Available at: https://www.sciencing.com/deforestation-affect-air-10632/[Accessed 6 Nov. 2024].
