# Naming files: we must have structure

It's important to keep the name of files machine and human readable, and that plays well with default data ordering.

For most bioimage analysis we will perform, some files will always be similar between projects, and therefore we can keep a pattern for the filenames.

## backend

SQLite and/or CSV files will be named after the `<plate>` name + the extension.

- Example: `2022_05_25_LiveCellPainting_single_cells.sqlite` or `2022_05_25_LiveCellPainting_single_cells.csv`

## load_data_csv 

- `load_csv.csv` that contains the image filename, image path, plate, well, and site. 

- `load_csv_with_illum.csv` for files with all the above plus the illumination correction filename and pathname.

## metadata

- `barcode_platemap.csv` for the map, with the following columns: `Assay_Plate_Barcode` containing the plate name, and `Plate_Map_Name` for the filename that contains the platemap;

- `<platemap_ID.csv>`, `ID` being something meaningful that identifies your layout (can be related to the experiment), or 1, 2, 3 if there's no especial pattern.

## pipelines

The default is to have at least an assay dev and an analysis protocol.

- `assay_dev.cppipe` for the assay dev pipeline;

- `analysis.cppipe` for the analysis pipeline. You can add more details if you have more than one analysis that you're testing, for example `analysis_with_cellpose.cppipe` and `analysis_without_cellpose.cppipe`;

- `illum.cppipe` if you need to calculate an illumination correction pipeline. 

## profiles

Profiles will always have the name of the specific assay plus the details about how the data was treated. 

- `<project_specific>_<AGG>_<NORMALIZATION>_<FEAT-SELECTION>_<BATCH-CORRECTION>.csv`

If you're using our notebooks to generate the profile, then this file naming is the pattern, and you don't have to worry about it.

- Example: `2022_05_25_LiveCellPainting_agg_median_normalized_negcon_feature_select_pycombat.csv`



