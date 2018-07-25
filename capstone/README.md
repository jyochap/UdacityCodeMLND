# Machine Learning Engineer Nanodegree

## Project: Clustering of Medicare 2014 Part D Opioid claims to identify over prescribing providers

**Source Data and other important links**

- Source of the 2014 medicare file. The following file contains 24121660 records which is huge, so will be pulling only the claims that have been submitted for an opioid drug

https://data.cms.gov/Medicare-Part-D/Medicare-Provider-Utilization-and-Payment-Data-201/465c-49pb

- Following is the pdf detailing about the columns in the dataset
https://data.cms.gov/api/views/465c-49pb/files/0931bfc7-1069-4437-961b-e3f43e26ac33?download=true&filename=Part_D_Prescriber_PUF_Methodology_2017-05-25.pdf

- Following is the list of drug classification, generic and branded names that are considered as Opioids. I have taken 2014 data
https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/Medicare-Provider-Charge-Data/Downloads/OpioidDrugList.zip

- OIG exclusion list, list of providers identified as fradulent. Now please keep in mind that this exclusion list is for all types of frauds/misdiagnosis/malpractices not just Opioid over prescription. Goal is identify the list of providers who shall be further investigated. The list of providers should consist all of the providers from the list for which ever state we are doing clustering.
https://oig.hhs.gov/exclusions/exclusions_list.asp
https://oig.hhs.gov/exclusions/downloadables/UPDATED.csv


**Software**

- Python 2.0
- supplemental code visuals.py, source is from udacity customer_segments project
- used Unix grep commands to get data pertaining to state of AL
