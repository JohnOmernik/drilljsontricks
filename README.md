# drilljsontricks
A collection of tricks for parsing JSON in Apache Drill


This repository contains challenges and tricks overcome challenges in parsing text data, specifically JSON in Apache Drill.  


Links for Drill: 
Main Documentation: https://drill.apache.org/docs/

JSON Data Model: (Must Read) https://drill.apache.org/docs/json-data-model/



## Sections

### Settings in Drill for reading JSON files. 

#### SYSTEM/SESSION Level  

store.json.read_numbers_as_double

(DRILLDOC) Reads numbers from JSON files with or without a decimal point as DOUBLE. You need to cast numbers from DOUBLE to other numerical types only if you cannot use the numbers as DOUBLE.

Example Error Messages where addressing this could be your answer:

store.json.all_text_mode

(DRILLDOC) Reads all data from JSON files as VARCHAR. You need to cast numbers from VARCHAR to numerical data types, such as DOUBLE or INTEGER.


### Error Messages with Unclear Resulst

### Wish lists

- A setting that allows files with a bad last reacord to be ignored. I.e. if all records in a file are ok, but the last record is a partial record, could we just ignore that record?

- Others? 



