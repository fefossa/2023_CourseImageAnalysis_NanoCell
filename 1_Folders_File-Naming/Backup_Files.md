# Backing up files in Google Drive (UNICAMP)

- Having an Unicamp gmail account, you have access to unlimited space in Google Drive (GD). 

- My suggestion is to backup the image files and workspace files at GD periodically, so you never lose your data.

- In the Google Drive lab's folder "Compartilhar" > "Templates" > "BioImageAnalysis_Pastas_Template" > "Template_Vazio", you'll have a template of folders organization that you can copy to your personal GD, and from there alter depending on your data/name of your projects.

## Suggestion on how to keep your backup up to date: `images` and `workspace`

- First, make sure you have `Google Drive` installed in your PC. You can select the `Stream Files` option or `Mirror files`, depending on the memory space you have available.

- All the folders I'm discussing next will live inside your `Google Drive` from Unicamp.

- Make sure to share your project folders with your advisor, so they have access to the data even after you leave.

1. You can create one folder for each `<project_specific>` inside your top level folder `<project>`: `<project_specific1>`, `<project_specific2>`, as the project evolves.

    1.1 `<project_specific>` will be a part of the bigger project, and will come to you naturally as the project happens. 

    **Example**: Working with the Live Cell Painting `<project>`, I have specific projects that I labeled based on the experiment I had to perform: `DILI` for drugs related to liver toxicity, `AgNP_Viability` for a dose-response curve using AgNP, and so on. 

2. As images are being acquired you should check that the cells are ok, the images are in focus and not saturated, and the experiment falls in the quality control check. If that's the case, you can upload the plate containing the images inside the `<project_specific>` folder.

    **Tip**: For images acquired on Cytation 5, the folder's name pattern is usually "220526_084043_Plate_1", having the `date` first, and then random numbers. Copy this folder with the plate name inside the `<project_specific>` main folder. 

3. As you go through the project, and achieve the number of replicates you need (usually 3 times), you'll proceed to start the image analysis. That's when you'll populate your `workspace` folders. If you followed the last steps, everything will be backed up to Google Drive automatically. 


## `analysis` folder

The `analysis` folder will contain the notebooks and figures used to analyze your data. 

This one will live inside a GitHub repository associated with your project, so all the updates and history will be easier to manage using the `version control` of GitHub.

**Instructions** TBD




