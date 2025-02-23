# Multi-class Segmentation of Structural Damage and Pathological Manifestations Using YOLOv8 and Segment Anything Model

*Reference:* AUTCON_106037  
*Authors:* Paulo Alberto Sampaio Santos, Michele Tereza Marques Carvalho  
*DOI:* https://doi.org/10.1016/j.autcon.2025.106037

Postgraduate Program in Structural Engineering and Construction, Department of Civil and Environmental Engineering, University of Brasilia (UnB), Building SG–12 1st Floor, Campus Universitário Darcy Ribeiro, Brasília, 70910-900, Federal District, Brazil

------------------------------------------------------------
## Hello👋 
This is a repository for *Automation in Construction* made available for research purposes. Please, when using it, cite the model correctly as shown below:

```
Santos, Paulo Alberto Sampaio, and Michele Tereza Marques Carvalho. "Multi-class segmentation of structural damage
and pathological manifestations using YOLOv8 and Segment Anything Model." Automation in Construction 172 (2025): 106037.
```

------------------------------------------------------------
## Abstract

![drywall capture](https://github.com/pauloengcsantos/multiclass-damage-segmentation/blob/main/graphical_abstract.png)

------------------------------------------------------------
## Datasets

| **Version**        | **Size** | **Version** | **Image Count** | **Link**              |
|--------------------|---------|------------|----------------|----------------------|
| dataset_v1  | 432 MB  | v1.0       | 7,926          | [Download](https://drive.google.com/drive/folders/1gjxBYemlojSyqGeAyQIyXuhpE5KNoKQV?usp=drive_link)        |
| dataset_v2 | 9.03 GB  | v2.0       | 41,132          | [Download](https://drive.google.com/drive/folders/1-O_IPpdkCAXnPFY5q52oz2f9P1BTJL_L?usp=drive_link)        |

------------------------------------------------------------
## Models

| **Version**        | **Size** | **Version** | **Image Count** | **Link**              |
|--------------------|---------|------------|----------------|----------------------|
| dataset_v1  | 432 MB  | v1.0       | 7,926          | [Download](https://drive.google.com/drive/folders/1gjxBYemlojSyqGeAyQIyXuhpE5KNoKQV?usp=drive_link)        |
| dataset_v2 | 9.03 GB  | v2.0       | 41,132          | [Download](https://drive.google.com/drive/folders/1-O_IPpdkCAXnPFY5q52oz2f9P1BTJL_L?usp=drive_link)        |


Performance
<p align="center">
  <img src="https://github.com/pauloengcsantos/multiclass-damage-segmentation/blob/main/performance_mAP50-models.png" alt="Descrição da Imagem 1" width="45%"/>
  <img src="https://github.com/pauloengcsantos/multiclass-damage-segmentation/blob/main/performance_mAP50-models.png" alt="Descrição da Imagem 2" width="45%"/>
</p>
Overview of post-processing annotations. (a) Histogram of annotation count per image, showing a 114.5% increase in dataset annotations by separating previously grouped damages into distinct bounding boxes. (b) Damages were previously spread across the image, making it difficult for the model to focus. (c) Bounding box annotations are now individually centered in the image, providing a focused training bias.

------------------------------------------------------------
![drywall capture](http://peccft.unb.br/images/logo-pecc.png)

