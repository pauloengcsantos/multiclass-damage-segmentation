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
## Model Performance per Damage Class

| **AI Model**      | **Class**              | **P**    | **R**    | **Inference Speed** |
|------------------|-----------------------|----------|----------|--------------------|
| **YOLOv8l**       | All Classes            | 0.946    | 0.916    | 13.40 ms           |
|                  | Efflorescence          | 0.872    | 0.751    |                    |
|                  | Exposed Reinforcement  | 0.963    | 0.912    |                    |
|                  | Rust Stain             | 0.960    | 0.990    |                    |
|                  | Scaling                | 0.974    | 0.991    |                    |
|                  | Crack                  | 0.962    | 0.920    |                    |
| **YOLOv8l-small** | All Classes            | 0.916    | 0.716    | 6.80 ms            |
|                  | Efflorescence          | 0.866    | 0.643    |                    |
|                  | Exposed Reinforcement  | 0.944    | 0.590    |                    |
|                  | Rust Stain             | 0.874    | 0.856    |                    |
|                  | Scaling                | 0.959    | 0.785    |                    |
|                  | Crack                  | 0.935    | 0.709    |                    |
| **YOLOv8l-medium**| All Classes            | 0.919    | 0.879    | 6.18 ms            |
|                  | Efflorescence          | 0.845    | 0.713    |                    |
|                  | Exposed Reinforcement  | 0.936    | 0.874    |                    |
|                  | Rust Stain             | 0.933    | 0.962    |                    |
|                  | Scaling                | 0.947    | 0.962    |                    |
|                  | Crack                  | 0.935    | 0.882    |                    |
| **YOLOv8l-big**   | All Classes            | 0.940    | 0.895    | 6.20 ms            |
|                  | Efflorescence          | 0.858    | 0.735    |                    |
|                  | Exposed Reinforcement  | 0.954    | 0.878    |                    |
|                  | Rust Stain             | 0.956    | 0.969    |                    |
|                  | Scaling                | 0.981    | 0.996    |                    |
|                  | Crack                  | 0.949    | 0.900    |                    |
| **YOLOv8l-tensorRT** | All Classes         | 0.938    | 0.897    | 3.40 ms            |
|                  | Efflorescence          | 0.877    | 0.730    |                    |
|                  | Exposed Reinforcement  | 0.942    | 0.889    |                    |
|                  | Rust Stain             | 0.967    | 0.963    |                    |
|                  | Scaling                | 0.951    | 0.990    |                    |
|                  | Crack                  | 0.951    | 0.903    |                    |
| **YOLOv9-GELAN**  | All Classes            | 0.799    | 0.773    | 31.60 ms           |
|                  | Efflorescence          | 0.738    | 0.606    |                    |
|                  | Exposed Reinforcement  | 0.803    | 0.765    |                    |
|                  | Rust Stain             | 0.828    | 0.839    |                    |
|                  | Scaling                | 0.812    | 0.876    |                    |
|                  | Crack                  | 0.812    | 0.779    |                    |



Performance
<p align="center">
  <img src="https://github.com/pauloengcsantos/multiclass-damage-segmentation/blob/main/performance_mAP50-models.png" alt="Descrição da Imagem 1" width="45%"/>
  <img src="https://github.com/pauloengcsantos/multiclass-damage-segmentation/blob/main/performance_mAP50-models.png" alt="Descrição da Imagem 2" width="45%"/>
</p>
Overview of post-processing annotations. (a) Histogram of annotation count per image, showing a 114.5% increase in dataset annotations by separating previously grouped damages into distinct bounding boxes. (b) Damages were previously spread across the image, making it difficult for the model to focus. (c) Bounding box annotations are now individually centered in the image, providing a focused training bias.

------------------------------------------------------------
![drywall capture](http://peccft.unb.br/images/logo-pecc.png)

