# Company-house-data-filtering
This task's objective is to clean up the Company House Data in order to increase data quality and verify the accuracy of customer information. The issues raised by inaccuracies, inconsistencies, and missing data in the client database are the main emphasis of the data cleanup plan.
## Downloading Company House Data File and saving the file locally:
The Company House Data file is downloaded from the provided [URL](https://download.companieshouse.gov.uk/BasicCompanyData-2023-07-01-part7_7.zip). The data file contains customer information for UK businesses and is saved locally.

<img width="749" alt="image" src="https://github.com/parth-7283/Company-house-data-filtering/assets/78414082/0c67bda2-70d9-45f0-9c50-d6d4fe0b6d59">

## Filtering the data :
The company house data is filtered based on the following conditions:

* Company Category is 'Private Limited Company'
* Company Status is 'Active'
* Accounts Category is 'SMALL' or 'MEDIUM'

<img width="752" alt="image" src="https://github.com/parth-7283/Company-house-data-filtering/assets/78414082/55f342c9-11bb-4817-bb75-103f3ecb9edb">

## Saving Filtered Data to CSV File:
The filtered data is saved in CSV format to the 'downloads/output' directory. If the directory doesn't exist, it will be created.

<img width="754" alt="image" src="https://github.com/parth-7283/Company-house-data-filtering/assets/78414082/02ce98e5-6949-45c9-9b25-12e4fec839fd">

## Output:
After running the script, the filtered data will be saved in the 'downloads/output' directory as 'filtered_data.csv'. You can also download the output file from [here](https://github.com/parth-7283/Company-house-data-filtering/blob/main/filtered_data.csv)
