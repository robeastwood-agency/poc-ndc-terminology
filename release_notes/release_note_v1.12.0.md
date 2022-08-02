# NCTIS Data Components CodeSystem release notes

## version 1.12.0 (31 Mar 2022)

The changes include:

## New concepts
The following new concepts were introduced:

code  | display  | synonyms
------------- | ------------- | -------------
`100.32039`  | Disease Screening Program Participation Record  | 
`100.32040`  | National Cancer Screening Program Participation View  | 
`100.32041`  | National Bowel Cancer Screening Program Participation Record  | 
`100.32042`  | National Cervical Cancer Screening Program Participation Record  | 
`100.32043`  | National Breast Cancer Screening Program Participation Record  | 
`101.32046`  | Health Program Information  | 
`101.32047`  | Disease Screening Program Information  |  Population Based Health Screening Program Information

## Concepts
The following existing concepts were updated:
* none

## Bug fixes
The generic rendering issue has been fixed, which includes: 
-	Correct rendering of the different versions on the search page, with the latest being in green (see https://www.healthterminologies.gov.au/access/fhir-terminology-resources/code-systems/?ui:filter=nctis%20data%20components)
-	The rendering of the concepts in the Code System excerpt table now shows correct content for the different versions (compared to only showing the concepts in the latest version for all versions).
-	Values in the definition column in the Code System excerpt table now show correct content (ie no longer empty for a handful nor showing old content)
