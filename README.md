# Docs related to Contextual DB
Contextual DB Schema definition file (db_schema_definitions/db_schema_definitions.xlsx)

**Units and definitions align where possible with MIxS v5.0 (https://gensc.org/mixs/)**

**Version history**

**3.1.2**

**Change summary**

- Fixed error with schema sheet version number
    - Schema sheet version number for release 3.1.1 was not updated (Released as 3.1.0). Updated to reflect current version.

**3.1.1**

**Change summary**

- Fixed error in `rubidium_meth` dType

**3.1.0**

**Change summary**

- Fields added to database schema:
    - `cast_id`
    - `rosette_position`
    - `synonyms`
- Added definitions to `Field_Definition` 

**3.0.1**

**Change summary**
- Added: `Air [ENVO_00002005]` and associated definition to `controlled_vocab_0`

**3.0.0**

**Change summary**
- Added `README` sheet
     - Outlines the contents of the workbook
     - Defines version control terms
     - Defines sentery values used in the database
- Renamed version `x.x.x` sheet to `Schema_x.x.x` (e.g., Schema_3.0.0)
- Renamed `Control_vocab` sheet to `Control_Vocab`
    - Modified `Control_Vocab` sheet layout
- Fields added to database schema:
    - `bleaching_meth`
    - `fouling_meth`
    - `grazing_meth`
    - `grazing_number_meth`
    - `host_abundance_mean_meth`
    - `host_abundance_meth`
    - `host_abundance_seaweed_mean_meth`
    - `host_length_meth`
    - `vegetation_dom_grasses_meth`
    - `vegetation_dom_shrubs_meth`
    - `vegetation_dom_trees_meth`
    - `vegetation_total_cover_meth`

- Field name changes:
    - `gravel_percent_meth` changed to `gravel_meth`
    - `length` changed to `host_length`
    - `tot_depth_water_meth` changed to `tot_depth_water_col_meth`
    - `tot_n_meth` changed to `tot_nitro_meth`

- Definition additions and modifications
- Fixed typographical errors

**2.0.2**

**Change summary**
 - Fixed typographical errors

**2.0.1**

**Change summary**
- Added `Control_vocab` sheet
        - Outlines the controlled vocabulary and its source
- Fixed typographical errors

**2.0.0**
    
Initial commit of contextual DB schema
- sheet name = `x.x.x` <version number> (e.g., 2.0.0). Containing the following information:
    - `Field`: Contextual metadata field
    - `dType`: Datatype used in the database schema
    - `AM_enviro`: Internal reference to distinguish common, terrestrial or non terrestrial metadata fields
    - `Units_Definition`: Long format definition of the units for the field
    - `Units`: Abbreviated units as they appear on the AM portal
    - `Control_Vocab`: Controlled vocabulary associated with the field
    - `Field_Definition`: Provides a definition for the field and where applicable its source

## Tagging version for a release

Version: x.y.z (e.g. 2.1.3)

where 
x.y (2.1) represents version of the database 
z (3) represents revision version of the definition file
