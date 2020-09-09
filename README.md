# SquamataAeroRad

**Squamata** is the largest order of reptiles, comprising lizards, snakes and amphisbaenians (worm lizards), which are collectively known as squamates or scaled reptiles.

**SquamataAeroRad** is a Jupyter notebook used to create metadata files for USGS Aeroradiometric data releases to ScienceBase.

*"Birthing the tail that feeds it..."* 

![Squamata - birthing the tale that feeds it](https://github.com/pbrown-usgs/SquamataAssemblyAMT/blob/master/SquamataLemniscateOuroboros.png)

#### Visit https://github.com/pbrown-usgs/SquamataAeroMag/blob/master/SquamataAeroRadEntityAndAttributeArchive.ipynb for Entity and Attribute code from previous Airborne radiometric surveys

This module performs the following operations:
- Create list of data directories.
- Identify files accompanying data release.
- Create file listing for metadata XML markup.
- Identify and load Aeromagnetic *.CSV data file.
- Create file list of data release files
- Create User Editable Keywords Listing
- Create entity and attribute XML markup for all files being released.
- Poplulate metadata template
- Validate metadata; create error log; create HTML and FGDC Text versions of the metadata. (In development - use https://mrdata.usgs.gov/validation/ for validation in the interim)

Known issues needing repair:
- Add items here...

## Future development plans for SquamataSB

- Create all child metadata files from first example created in previous steps. 
- Batch upload files to ScienceBase.
- Batch remove files from ScienceBase. 
- Change ScienceBase parameters such as citation information, add orcid ids, add USGS CMS tags, etc. 

### Instructions
- Create a template xml format that contains boilerplate text common to all childeren in a data release.  Be sure this template contains the approriate curly bracket tags, {SquamataTagExample} used to populate the template using SquamataAeromag.

### To execute a function/command select a cell and Hold-Shift + Press-Enter

**The 'r' signifies a string literal. Use for paths.**

Metadata wizard:  Advanced, Open In a jupyter Notebook?
Metadata Wizard 2.o from ScienceBase

v1.0: Read csv File into pandas
v1.1: Create Array of csv column headers, assign header array of channel descriptions and units, create entity and attribute text for csv file
v1.2 Create file listing, create editable keywords text
v1.3 Creat entity and attributes for files other than CSV
v1.4 Populate metadata template
v1.5 Populate variables with boilerplate text, create file lists, write to metadata template.
v1.6 and 1.7 - Add Raw Up and Down spec file EandA
v1.8 Add Std Order
