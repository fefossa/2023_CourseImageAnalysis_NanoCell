# Image-based profiling course in Portuguese (2023/2024)

- Contains materials, documentation, and slides used in the **2023/2024 Bioimage Analysis Course** for NanoCell Interactions Lab.

- This course is recorded in Portuguese, and the materials are available in English.

- All materials were prepared and presented by [fefossa](https://github.com/fefossa).

## Aims

Our aim is to provide a detailed material on how to plan, organize, and perform a bioimage analysis protocol using CellProfiler [1] for segmentation and feature extraction, pycytominer [2] for profiling, and Python for data visualization and interpretation. 

## Materials

For each day of the course, we will provide the written documentation, slides, and recording (in Portuguese).

ATTENTION: Videos are in Portuguese (`PT`). Slides and most materials in English (`EN`).

Most notebooks and scripts used for this course is available at [scripts_notebooks_fossa repo](https://github.com/broadinstitute/scripts_notebooks_fossa). To learn how to use this repository properly for your analysis, watch this tutorial on [how to create a submodule of a GitHub repository in PT](https://youtu.be/ncPi6rW4p-U).

## Topics

1. Folders and file naming for bioimage analysis

    1.1 Practicing: shell and bash basic commands

2. Using Cellpose to train your own model

    2.1 Installing and using Cellpose human-on-a-loop [Video in PT](https://youtu.be/iaMhFuzBcys)
    
    2.2 Using RunCellpose (Cellpose + CellProfiler integration). [Video in EN](https://www.youtube.com/watch?v=8RGvnADDSkg&pp=ygUqY2VudGVyIGZvciBvcGVuIGJpb2ltYWdlIGFuYWx5c2lzIG1vcnBoZXVz)
    

3. Installing CellProfiler with RunCellpose

    [Install CellProfiler+RunCellpose on Windows in PT](https://youtu.be/Gn_S_rH3NLs)

4. Generate Metadata

    4.1 Presentation about metadata in bioimage analysis in PT [here](https://youtu.be/xPL6zivk-BU) and [Q&A](https://www.youtube.com/watch?v=Tj27YWdKscc)

    4.2 Using the Load Data Generator and Layout to CSV apps [demonstration](https://www.youtube.com/watch?v=CcuvvJKur-k) and [Q&A](https://youtu.be/jct80vOhdEo)

    4.3 Using CellProfiler LoadData module [here](https://youtu.be/fLYUx2-7l6s)

5. Assay development and Analysis with CellProfiler

    5.1 Assaydev pipeline

    5.2 Analysis pipeline

    - Practicing: CellProfiler

6. Profiling using Pycytominer

    6.1 What's profiling?

    6.2 Profiling evaluation using mean Average Precision 

    6.3 Practicing: Create environment & Jupyter notebooks

7. Batch correction with PyCombat

    [Batch effect and plate layout design in PT](https://youtu.be/9EltUX3mTJI)

8. Visualizing and interpreting profiling data 

    [Morpheus part 1 in EN](https://www.youtube.com/watch?v=0nkYDeekhtQ&t=40s&pp=ygUqY2VudGVyIGZvciBvcGVuIGJpb2ltYWdlIGFuYWx5c2lzIG1vcnBoZXVz) and [Morpheus part 2 in EN](https://www.youtube.com/watch?v=r9mN6MsxUb0&t=2s&pp=ygUqY2VudGVyIGZvciBvcGVuIGJpb2ltYWdlIGFuYWx5c2lzIG1vcnBoZXVz)

    [Morpheus part 1 in PT](https://youtu.be/skHutBRaKAk) and [Morpheus part 2 in PT](https://youtu.be/OCq3hmofmLg) 

    Visualize single-cells notebook https://youtu.be/55uu1YcmtH0 

7. Machine learning 

    Videos explaining the ideas and mathematics behind machine learning are freely provided by [StatQuest in EN](https://www.youtube.com/@statquest)
    
    A basic explanation of [Machine Learning in PT](https://youtu.be/TgYjdJiW5O0) is also available.
    
    Notebooks for feature importance using Random Forest, Linear Regression, and T-test


EXTRAS

- Using CellProfiler Analyst for Quality Control analysis: [see video in PT](https://youtu.be/kqxsO4nEHKA)


### References

[1] Carpenter, A.E., Jones, T.R., Lamprecht, M.R. et al. CellProfiler: image analysis software for identifying and quantifying cell phenotypes. Genome Biol 7, R100 (2006). https://doi.org/10.1186/gb-2006-7-10-r100

[2] Way, G., Chandrasekaran, S. N., Bornholdt, M., Fleming, S., Tsang, H., Adeboye, A., Cimini, B., Weisbart, E., Ryder, P., Stirling, D., Jamali, N., Carpenter, A., & Singh, S. Pycytominer: Python package for processing image-based profiling data (Version 0.3.0) [Computer software]. https://github.com/cytomining/pycytominer

[3] PyCombat
