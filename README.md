# WDYDYA 
This code is used to analyze the new version of the WDYDYA survey from Q1/2020 and onwards. It is written in Python but using Jupyter Lab to run.

## Installation (on Mac)

```bash
$ sudo pip3 install jupyterlab
$ sudo jupyter lab build
```

## Dependencies 

```bash
$ sudo pip3 install pandas 
$ sudo pip3 install openpyxl
```

## Steps
### 1. Download the Typeform data
For each of the 11 languages, download Typeform data for that quarter in XLSX format. Name the files {ISO-CODE}.xlsx like DE.xlsx

### 2. Open the code in Jupyter notebook
Move the code from the “newest” folder to a new folder and put all the xlsx files into it. 

```bash
$ cd /your-new-directory 
$ jupyter-lab .
```

### 3. Run the code and hope for the best 
If Typeform changed the schema of their data or Python has changed good luck! 

### 4. Copy the results to the Google Sheet
https://docs.google.com/spreadsheets/d/1i-KFaVVtraIjp5YcmbzrfYEugahTjEvSbhaxe2mHpCs/edit#gid=1759956839
