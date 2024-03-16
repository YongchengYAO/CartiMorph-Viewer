# Step-by-step Instructions

## Graphical User Interface

An example output of the `Capture & Save App Screen` function in CMV.

![CMV-UI-example](instructions.assets/CMV-UI-example.pdf)

## I. Select case

CartiMorph Toolbox saves the quantification results into the `Results` folder with 1 subfolder for each project.  Folders are organized as follows.

```python
# [Results] folder from CartiMorph Toolbox
# ├── [CartiMorph Toolbox folder]
#     ├── Results
#         ├── Task<ID>_<task-name> // <--- "Result Folder" for CMV
#							├── [case-name]
#									├── CartilageSubregion
#									├── CartilageSubregion_Figure // figure files
#									├── Image
#									├── MorphologicalQuantification // quantificaiton files
#											├── [case-name]_MorphQuant.csv // csv files
#									├── Surface
#									├── Surface_Figure // figure files
#									├── SurfaceNormal
#									├── SurfaceNormal_Figure // figure files
#									├── ThicknessMap
#									├── ThicknessMap_Figure // figure files
#									├── ThicknessMap
```

You should choose the `Task<ID>_<task-name>` folder as `Result Folder`. Then you can choose a case from the drop list.

## II. Visualization Options

Configure you options and press `Update Figures and Tables`.

## III. Save UI screenshot

Press `Capture & Save App Screen`.



[<<< Back to the main document](https://github.com/YongchengYAO/CartiMorph-Viewer/tree/main)
