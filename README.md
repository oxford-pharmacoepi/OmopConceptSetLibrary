# OmopConceptSets

## Description
This repository contains concept sets from previously published research using the OMOP CDM. A corresponding app is here: https://dpa-pde-oxford.shinyapps.io/OmopConceptSetLibrary/ 

## File overview

├── README.md  
├── ConditionConceptSets  
│   ├── addisonsDisease01  
│   │   ├── addisonsDisease01.json  
│   │   ├── README  
│   ├── anaphylaxis01  
│   │   ├── anaphylaxis01.json  
│   │   ├── README  
├── MeasurementConceptSets  
│   ├── bmi01  
│   │   ├── bmi01.json  
│   │   ├── README 
[...]

Note, each directory within conceptSets will contain one (and only one) json of a conept set and an associated README file, which contains a structured description. There are currently four groupings of concept sets: 1) condition concept sets, 2) measurement concept sets, 3) medication concept sets, and 4) procedure concept sets. It is important to note that these are not nexessarily directly linked to the OMOP CDM domains. For example, a measurement concept that indicates a positive result (e.g. "Influenza B virus present" [4262075]) may be included in a condition concept set (whereas "Influenza A and B virus antigen assay" [4039357] where a corresponding value is needed to identify a positive result would be expected to apperar in a measurement concept set). 

## Contributing concept sets
To add concept sets from a published study please add them to a new branch and open a pull request. Please follow the same conventions as are currently being followed: lower camel case for names (with the same name used for the folder and the .json file), the json to be an ATLAS compliant concept set, and the README.md file to follow the same structure and formatting as existing ones (with the following headings: Description, Reference, and Change log). For the reference, please provide it in bibTex format. To allow for multiple concept sets for the same clinical idea, we start with 01 and then increment from there onwards.  

## Recommended usage
These concept sets are from previously published peer-reviewed studies. It should be stressed, however, that when resuing them you should re-evaluate them (not least because the vocabularies of the OMOP CDM are updated over time) and consider whether they are appropriate for your study. 
