# AssayDev and Analysis

The pipelines used for each step are available [here](https://github.com/broadinstitute/scripts_notebooks_fossa/tree/main/cellprofiler/2023_CourseBioImageAnalysis_pipelines)

1. assaydev.cppipe: CellProfiler pipeline used to flag only one site per well, segment it, and save the outlines from it. The purpose is to make sure the segmentation works across all the plate.

2. analysis.cppipe: CellProfiler pipeline used to segment and extract features from single-cells. Example using LoadData to point where the images are. 

## Materials

1. Presentation about CellProfiler:

- [video in PT](https://youtu.be/dw_MKWUEtIg)

2. How to develop your analysis: segment your objects, and save the outlines for each well in your plate to check segmentation:

- [assay development demonstration in PT](https://youtu.be/yHOkQRKiqF4)

- [Q&A](https://youtu.be/lxlDzyxuMtM)