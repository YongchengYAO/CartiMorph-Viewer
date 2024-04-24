# CartiMorph Viewer

<div style="text-align:center"> <img src="README.assets/aboutCMV.png"  style="zoom:100%;" /> </div>

## Release

- [v1.0.2](https://github.com/YongchengYAO/CartiMorph-Viewer/releases/tag/v1.0.2):
  - [CartiMorphViewer-linux-standalone-v1.0.2.install](https://github.com/YongchengYAO/CartiMorph-Viewer/releases/download/v1.0.2/CartiMorphViewer-linux-standalone-v1.0.2.install)
  - [CartiMorphViewer-macOS-standalone-v1.0.2.install.app.zip](https://github.com/YongchengYAO/CartiMorph-Viewer/releases/download/v1.0.2/CartiMorphViewer-macOS-standalone-v1.0.2.install.app.zip)

## Introduction

**CartiMorph Viewer (CMV)** is part of the [**CartiMorph Toolbox (CMT)**](https://github.com/YongchengYAO/CartiMorph-Toolbox) and the [**CartiMorph**](https://github.com/YongchengYAO/CartiMorph) project. It was originally a component of the CartiMorph Toolbox, designed for visualizing some intermediate and final results from CMT. Thus you need the `Results` folder from CMT. As part of CMT, the CMV can be launched directly from the UI of CMT once all computation tasks are finished. Considering the scenario where users may wish to share their results generated by CMT with collaborators, we provide this **standalone version of CMV** to help with data sharing. 

## Installation

```bash
chmod u+x CartiMorphViewer-linux-standalone-v1.0.2.install
./CartiMorphViewer-linux-standalone-v1.0.2.install
```

Check the [post-installation instructions page](https://github.com/YongchengYAO/CartiMorph-Viewer/blob/main/Documents/post_installation_linux.md) for setting environment variables and aliases, and solving library conflicts.

## Features

- support Linux (tested on Ubuntu 22.04.2 LTS ) and macOS (tested on Sonoma 14.4)
- visualisation
  - reconstructed cartilage surface
  - pseudo healthy cartilage surface
  - surface normal
  - cartilage subregions
  - cartilage thickness map
  - MR image and subregional masks 
  - quantitative results for cartilage morphometrics

## Example Results from CMT

Try CMV with our example results from the CMT. Just unzip the file and select the top-level folder in CMV.

## Step-by-step Instructions

<div style="text-align:center"> <img src="README.assets/fig_report_sample.png"  style="zoom:100%;" /> </div>

For detailed instructions, please go to [this page](https://github.com/YongchengYAO/CartiMorph-Viewer/blob/main/Documents/instructions.md).

## Citation

If you use the toolkit, please cite the CartiMorph paper.

```
@article{yao2024cartimorph,
  title={CartiMorph: A framework for automated knee articular cartilage morphometrics},
  author={Yao, Yongcheng and Zhong, Junru and Zhang, Liping and Khan, Sheheryar and Chen, Weitian},
  journal={Medical Image Analysis},
  volume={91},
  pages={103035},
  year={2024},
  publisher={Elsevier}
}
```





