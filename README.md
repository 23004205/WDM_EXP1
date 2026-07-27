### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 27-07-2026
### AIM: 
  To Create Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform preprocessing
### PROCEDURE: 
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Employee Table.

```
--------------
Employee Data
---------------
@relation employee
@attribute name {SAI,aparna,sanjay,regins,tata}
@attribute id numeric
@attribute salary {low,medium,high}
@attribute exp numeric
@attribute gender {male,female}
@attribute phone numeric
@data
SAI,2,low,2,male,250311
aparna,102,high,3,female,251665
sanjay,103,medium,1,male,240238
regins,104,low,5,female,200200
tata,105,high,2,male,240240

--------------
Weather Data
---------------
@relation weather
@attribute outlook {sunny,rainy,overcast}
@attribute temparature numeric
@attribute humidity numeric
@attribute windy {true,false}
@attribute play {yes,no}
@data
sunny,85.0,85.0,false,no
overcast,80.0,90.0,true,no
sunny,83.0,86.0,false,yes
rainy,70.0,86.0,false,yes
rainy,68.0,80.0,false,yes
rainy,65.0,70.0,true,no
overcast,64.0,65.0,false,yes
sunny,72.0,95.0,true,no
sunny,69.0,70.0,false,yes
rainy,75.0,80.0,false,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows employee table on weka.

### OUTPUT:
## EMPLOYEE DATA

<img width="1232" height="737" alt="image" src="https://github.com/user-attachments/assets/47c49bfa-6b2a-407b-b7fe-bc806ad847d1" />

## WEAHER DATA

<img width="844" height="504" alt="image" src="https://github.com/user-attachments/assets/3d32b014-72c4-4a27-9bda-57a1a5b51d86" />


### PREPROCESSING
### Procedure:
#### 1) Add -> Pre-Processing Technique:
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

### OUTPUT:

## EMPLOYEE DATA

<img width="1223" height="738" alt="image" src="https://github.com/user-attachments/assets/39cf9b20-5f84-4b64-a80c-57a6adcbd416" />

## WEAHER DATA

<img width="835" height="509" alt="image" src="https://github.com/user-attachments/assets/1baafd57-aa3a-44b8-ae8b-de39c1726d6a" />


### 2) Remove -> Pre-Processing Technique:

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

### OUTPUT:

## EMPLOYEE DATA

<img width="1227" height="737" alt="image" src="https://github.com/user-attachments/assets/5cd4ca01-77da-4468-b5b7-d517100a6239" />

## WEAHER DATA

<img width="834" height="503" alt="image" src="https://github.com/user-attachments/assets/d9e02999-c4ee-438a-a9a3-ddb71699912d" />



### Normalize -> Pre-Processing Technique:

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

### OUTPUT:

## EMPLOYEE DATA

<img width="1234" height="740" alt="image" src="https://github.com/user-attachments/assets/c75a3647-df66-47bc-b710-c0a9642e6507" />

## WEAHER DATA

<img width="836" height="496" alt="image" src="https://github.com/user-attachments/assets/5c9551c0-939c-4758-87e9-4231fa540c7c" />


### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
