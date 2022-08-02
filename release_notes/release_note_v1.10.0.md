# NCTIS Data Components CodeSystem release notes

## version 1.10.0 (31 Dec 2021)

permalink: https://www.healthterminologies.gov.au/integration/R4/fhir/CodeSystem/nctis-data-components-1.10.0

The changes include:

## New concepts
The following new concepts were introduced:

code  | display  | synonyms
------------- | ------------- | -------------
`100.32038`  | COVID-19 View  | COVID-19 Dashboard
`101.32041`  | Administered Immunisations  | COVID-19 Administered Immunisations


## Concept updates
The following existing concepts were updated:

code  | display changes  | definition changes   | synonym changes 
------------- | ------------- | ------------- | -------------
`101.16638`  | (existing display value `Immunisations` is unchanged) |  | synonym `COVID-19 Vaccinations` has been added
`101.17039`  | (existing display value `Australian Immunisation Register Entries` is unchanged) |  |  added synonyms `Australian Immunisation Register Immunisations` and `Australian Immunisation Register Vaccinations`
`101.20018`  | (existing display value `Pathology` is unchanged) |  | synonym `Recent COVID-19 Tests` has been added
`101.32030`  | (existing display value `Pathology` is unchanged) |  | added synonyms `Vaccination Recommendations` and `COVID-19 Next Immunisations Due`
`103.32033`  | existing display value `CDA Repository Information` is replaced with `Repository Identifier` | existing definition value `CDA Repository Information` is replaced with `Repository Identifier` | synonym `CDA Repository Information` has been added
`100.32034`  | existing display value `Immunisation Consolidated View` is replaced with `Immunisation View` | existing definition value `Immunisation Consolidated View` is replaced with `Immunisation View` | synonym `Immunisation Consolidated View` has been added
`101.32035`  | existing display value `Immunisations Sorted by Date` is replaced with `Immunisations Ordered by Date` | existing definition value `Immunisations Sorted by Date` is replaced with `Immunisations Ordered by Date` | synonym `Immunisations Sorted by Date` has been added


## Bug fixes
These concepts had the following fixes:

code  | fix
------------- | ------------- 
`101.32036`  | the erroneous hyphen was removed from the concept display and definition values; now both are `Immunisations AIR`
`101.32037`  | the erroneous hyphen was removed from the concept display and definition values; now both are `Immunisations MHR and AIR` 
