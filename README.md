# Pro2d Coffeeproject
This project is the code repository of the Pro2d Coffeeproject at FHNW.

#### -- Project Status: [Completed]

## Project Objective
In 2019, the rules and regulations of the World Barista Championship (WBC) have been changed. Now coffee may be prepared with an individually selected water temperature in the range of 90.5 to 96 degrees. This paper investigates the effect of water and coffee temperature on coffee aroma. 
Two experiments were conducted. With three water temperatures (90, 93 and 96 degrees) and with active cooling of the spout or ice cubes directly in the coffee. In both samples, the amount of each molecule in the coffee was determined. For this purpose, the chemical method gas chromatography coupled with mass spectrometry and headspace gas chromatography was used. 
The study showed that volatile molecules were more abundant at lower water and coffee temperatures. Significant differences occurred at water temperatures between 90 and 93 degrees and 90 and 96 degrees. For active coffee cooling, differences between no cooling and active cooling are significant. There are hardly any significance differences between the different cooling amounts and methods.
The project team focused on analyzing relationships between the amount of volatile molecules in coffee based on the four molecular properties (molecular mass, solubility, polarizability and Henry Law constant) as a function of water and coffee temperature.
In tendency, with higher molecular mass, solubility, polarizability and Henry Law constant, the abundance of volatile molecules decreases. The highest coefficient of determination was 0.42. The figures are in the expected direction, but do not show a significant relationship with the molecular properties analyzed.
### Keywords
Coffee, volatile molecules, normalization, regression, extraction, gas chromatography, mass spectrometry.

### Partner
* Zürcher Hochschule für Angewandte Wissenschaften (ZHAW)
* [ZHAW Coffee Institute](https://www.zhaw.ch/de/lsfm/institute-zentren/icbt/analytische-chemie/analytical-technologies/)
* Partner contact: Chahan Yeretzian 

### Methods Used
* Datawrangling
* Explorative Dataanalysis
* Linear Regression
* multiple Linear Regression

### Technologies
* Python
* Pandas
* sklearn
* statsmodels


## Needs of this project

- data exploration/descriptive statistics
- data processing/cleaning
- statistical analytics
- writeup/reporting

## Getting Started
1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept [here](Rohdaten) within this repo.
3. Wrangled Data is being kept [here](Arbeitsdaten) within this repo.
4. Molecular Data is being kept [here](chemical_database) within this repo.
5. Molecular Data aquisition scripts are being kept [here](Scripts/Initial_Dataset/chemical_Code) within this repo.
6. Data processing/transformation/visualisation/analytic for the first dataset (Volatiles) scripts are being kept [here](Scripts/Initial_Dataset)
7. Data processing/transformation/visualisation/analytic for the second dataset (Chilling) scripts are being kept [here](Scripts/Chilling_Compound)
8. Data visualisations for the first dataset (Chilling) scripts are being kept [here](Scripts/Initial_Dataset/plots)

## Installation
    `pip install -r .\requirements.txt`

## Important Files
* [Aquisition and Wrangling of molecular Property Database](Scripts/Initial_Dataset/chemical_Code/chemical_database.py) -> should not be used if no molecules are added.
* [Data Wrangling & Explorative Data analysis & Visualisations &  Regression Models for first Dataset](Scripts/Chilling_Compound/Explorative_Datenanalyse/EDA_Chilling_Comp_HSGC.py) -> shows histograms, density plots and scatter plots of the dataset combined with the molecular properties
* [Data Wrangling & Explorative Data analysis & Visualisations & Regression Models for second Dataset](Scripts/Initial_Dataset/Explorative_Datenanalyse.py) -> scatter plots and 3D scatter plots of the dataset as well as all the results of the multiple linear regression models

