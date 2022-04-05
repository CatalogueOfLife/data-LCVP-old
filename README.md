# LCVP v1.0.4
This is a COL fork of the original R datapackage of the Leipzig Plant Catalogue. 
It adds a python script to convert the raw data into a valid Catalogue of Life Data Package (ColDP) suitable for ingestion into COL ChecklistBank.
Orders, families and genera are normalised from the raw species list.

LCVP ChecklistBank entry: https://www.checklistbank.org/dataset/2262


# Python Converter Usage

## Requirements
pip install pybtex

## Run ColDP conversion
This makes use of the zipped data and the bibtex citation and references file.
It will generate distinct families in ColDP with references attached.
It then places all the species in those families.
