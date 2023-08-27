# analysis folder

This folder contains files related to analysis and interpretation of the profiles:

- Jupyter Notebooks;

- Figures;

- Python scripts;

- Representative images of your cells;

- Small files relevant to the analysis.

## Structure

It depends on the type of analysis you'll be doing, but for bioimage analysis we usually have the following folders:

```
<project>
└──<project_specific>
    ├──batch_correction
    ├──dose_response
    ├──generate_profiles
    ├──individual_features
    ├──profile_evaluation_metrics
    └──representative_cells
```

1. This folder structure will be very dependent on the type of analysis you're doing, and each folder name will be connected to the analysis;

2. What's important here is to keep the `Issues` section of your repository active, with interpretation and discussion of the data when a notebook or a figure is uploaded to your repo.

3. Always add the number of the `Issue` in your commit message (for example, `Generate profiles for DILI #1`), and adding `#1` will make sure that this commit will be referenced in Issue #1. This keeps the data trackable! 

