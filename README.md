# google_api
Python Class to connect and read Google Worksheet

## First Step
Configure your project and create OAuth 2.0 Client on https://console.cloud.google.com/

Reference: https://developers.google.com/sheets/api/quickstart/python

## Install Requirements
```
    pip install -r requirements.txt
```

## Set Variables
Alter SAMPLE_SPREADSHEET_ID and SAMPLE_RANGE_NAME based on your worksheet

## Example
```
sheet = GoogleSheeet(SAMPLE_SPREADSHEET_ID, SAMPLE_RANGE_NAME, "A1:D10")
df = sheet.to_dataframe()
```