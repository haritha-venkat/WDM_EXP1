# EX: 01 CREATION OF EMPLOYEE, WEATHER DATASET IN WEKA DATA MINING AND ANALYSIS TOOL AND PERFORM PREPROCESSING
## DATE : 20-02-2025
```
# Name: HARITHA SHREE.V
# Reg No: 212222230046
```

## AIM: 
To Create Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform preprocessing.
## PROCEDURE: 
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Employee Table.

```
--------------
EMPLOYEE DATA
---------------
@relation employee
@attribute name {x, y, z, a, b}
@attribute id numeric
@attribute salary {low, medium, high}
@attribute exp numeric
@attribute gender {male, female}
@attribute phone numeric

@data
x, 101, low, 2, male, 250311
y, 102, high, 3 female, 251665
z, 103, medium, 1, male, 240238
a, 104, low, 5, female, 200200
b, 105, high, 2, male, 240240

--------------
WEATHER DATA
---------------
@relation weather
@attribute outlook {sunny, rainy, overcast}
@attribute temperature numeric 
@attribute humidity numeric
@attribute windy {true, false} 
@attribute play {yes, no}

@data sunny, 85.0, 85.0, false, no 
overcast, 80.0, 90.0, true, no 
sunny, 83.0, 86.0, false, yes 
rainy, 70.0, 86.0, false, yes 
rainy, 68.0, 80.0, false, yes 
rainy, 65.0, 70.0, true, no 
overcast, 64.0, 65.0, false, yes 
sunny, 72.0, 95.0, true, no 
sunny, 69.0, 70.0, false, yes 
rainy, 75.0, 80.0, false, yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows employee table on weka.

## OUTPUT:
### EMPLOYEE DATA:
![EXP 1A](https://github.com/Mounesh07/WDM_EXP1/assets/118343401/b5c95e85-7fef-4a9f-a9cc-47dbde625704)
### WEATHER DATA:
![EXP 1B](https://github.com/Mounesh07/WDM_EXP1/assets/118343401/fb1f91ce-95e4-42fa-b669-a83e855492c7)

## PROCEDURE:
### 1) ADD -> Pre-Processing Technique:
1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Add.
9) A new window is opened.
10) In that we enter attribute index, type, data format, nominal label values for Climate.
11) Click on OK.
12) Press the Apply button, then a new attribute is added to the Weather Table.
13) Save the file.
14) Click on the Edit button, it shows a new Weather Table on Weka.

## OUTPUT:
### EMPLOYEE DATA:
![EXP 1D ADD](https://github.com/Mounesh07/WDM_EXP1/assets/118343401/6891efe0-1003-4308-af9c-7e2a2f7e60a3)
### WEATHER DATA:
![EXP 1C ADD](https://github.com/Mounesh07/WDM_EXP1/assets/118343401/adc4b6c0-b53c-4e37-a7ee-2bf17497f18d)

### 2) REMOVE -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Remove.
9) Select the attributes windy, play to Remove.
10) Click Remove button and then Save.
11) Click on the Edit button, it shows a new Weather Table on Weka.

## OUTPUT:
### EMPLOYEE DATA:
![EXP 1D REMOVE](https://github.com/Mounesh07/WDM_EXP1/assets/118343401/66eeec6a-de31-496b-89b7-0b3c22d4f183)
### WEATHER DATA:
![EXP 1C REMOVE](https://github.com/Mounesh07/WDM_EXP1/assets/118343401/66194e59-ba4e-42d6-b838-4a787b16cf55)

### 3) NORMALIZE -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Normalize.
9) Select the attributes temparature, humidity to Normalize.
10) Click on Apply button and then Save.
11) Click on the Edit button, it shows a new Weather Table with normalized values on Weka.

## OUTPUT:
### EMPLOYEE DATA:
![EXP 1D NORMALIZE](https://github.com/Mounesh07/WDM_EXP1/assets/118343401/c45839f1-bb13-467d-bae0-c9358261ba62)
### WEATHER DATA:
![image](https://github.com/Mounesh07/WDM_EXP1/assets/118343401/3a84afb7-40fe-4004-ae05-34355dab0eb5)

## RESULT: 
Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
