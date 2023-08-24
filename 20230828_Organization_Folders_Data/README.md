# Organizing folders and image data: required structure

Here, we suggest how the folders should be organized when doing an image analysis project. 

Having a fixed structure helps making the data findable, accessible, and reusable. 

An example is:

```
├───<project>
|   └───<project_specific>
|   │   ├───illum
|   │   │   ├───<plate>
|   │   │   ├───<plate>
|   │   │   └───<plate>
|   │   └───images
|   │   │   ├───<plate>
|   │   │   ├───<plate>
|   │   │   └───<plate>
|   ├───workspace
|   │   ├───backend
|   │   │   ├───<project_specific>
|   │   │   │   └───<plate>
|   │   ├───profiles
|   │   │   ├───<project_specific>
|   │   │   │   └───well_profile.csv
|   │   ├───assaydev
|   │   │   ├───<project_specific>
|   │   │   │   └───montage_segmentation.png
|   │   ├───representative_cells
|   │   │   ├───<project_specific>
|   │   │   │   │   └───notebooks
|   │   │   │   │   └───images
|   │   ├───metadata
|   │   │   ├───platemaps
|   │   │   │   ├───<project_specific>
|   │   │   │   │   ├───barcode_platemap.csv
|   │   │   │   │   └───platemap
|   │   ├───cellpose
|   │   │   └───<project_specific>
|   │   │   │   ├───train
|   │   │   │   │   └───models
|   │   │   │   └───test
|   │   ├───model
|   │   │   └───<project_specific>
|   │   └───pipelines
|   │       └───<project_specific>
```

