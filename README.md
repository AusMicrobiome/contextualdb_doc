# Docs related to Contextual DB
Contextual DB Schema definition file (db_schema_definitions/db_schema_definitions.xlsx)

This excel spreadsheet includes:
- sheet name = <version number> (e.g., 2.0.0). Containing the following information:
    - Field: Contextual metadata field
    - dType: Datatype used in the database schema
    - AM_enviro: Internal reference to distinguish common, terrestrial or non terrestrial metadata fields
    - Units_Definition: Long format definition of the units for the field
    - Units: Abbreviated units as they appear on the AM portal
    - Control_Vocab: Controlled vocabulary associated with the field
    - Field_Definition


- sheet name = Control_vocab. Outlines the controlled vocabulary and its source.

- Units and definitions align where possible with MIxS v5.0 (https://gensc.org/mixs/)

## Tagging version for a release

Version: x.y.z (e.g. 2.1.3)

where 
x.y (2.1) represents version of the database 
z (3) represents revision version of the definition file
