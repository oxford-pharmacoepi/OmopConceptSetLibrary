# OmopConceptSets

## Description
This repository contains concept sets from previously published research using the OMOP CDM. A corresponding app is here: https://dpa-pde-oxford.shinyapps.io/OmopConceptSetLibrary/ 

## File overview

├── README.md  
├── conceptSets  
│   ├── cardiacArrythmia01  
│   │   ├── cardiacArrythmia01.json  
│   │   ├── README  
│   ├── celiacArteryThrombosis01  
│   │   ├── celiacArteryThrombosis01.json  
│   │   ├── README  
[...]

Note, each directory within conceptSets will contain one (and only one) json of a conept set and an associated README file, which contains a structured description.

## Contributing concept sets
To add concept sets from a published studied please add them to a new branch and open a pull request. Please follow the same conventions as are currently being followed: lower camel case for names (with the same name used for the folder and the .json file), the json to be an ATLAS compliant concept set, and the README.md file to follow the same structure and formatting as existing ones (with the following headings: Description, Development, Databases used, Reference, and Change log). For the reference, please provide it in bibTex format. To allow for multiple concept sets for the same clinical idea, we start with 01 and then increment from there onwards.  

## Recommended usage
To add ... Building cohorts.... Cohort diagnostics... etc
