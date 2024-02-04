# AssayDev and Analysis

1. assaydev.cppipe: CellProfiler pipeline used to flag only one site per well, segment it, and save the outlines from it. The purpose is to make sure the segmentation works across all the plate.

2. analysis.cppipe: CellProfiler pipeline used to segment and extract features from single-cells. Example using LoadData to point where the images are. 