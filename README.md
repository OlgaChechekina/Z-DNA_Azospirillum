# Caulobacter

Alphaproteobacteria, Caulobacter использовались в анализе.

[Ссылка на colab](https://colab.research.google.com/drive/1_5P72lwLC4ZLEUQdjOeQWWKfvtPD_CWY?usp=sharing)

# ОБщая информация
Анализируемые организмы: *Caulobacter flavus*, *Caulobacter henricii*, *Caulobacter mirabilis*, *Caulobacter rhizosphaerae*, *Caulobacter segnis*

# общая таблица

| Species  |  Genes number | Genome coverage | Genome length | Genome_plasmid length | Number of sequences |
|---|--|--|---|--|---|
| C_flavus |	5236.00	| 89.71	| 5659202.00	| 5659202.00 |	1.00 |
| C_henricii |	3693.00	| 89.84	| 3864204.00	| 3957288.00 |	2.00 |
| C_mirabilis |	4385.00	| 91.59 |	4577265.00	| 4577265.00 |	1.00 |
| C_rhizosphaera |	5288.00 |	89.44| 	5732418.00 |	5963910.00 |	2.00 |
| C_segnis |	4411.00 |	90.65 |	4655467.00 |	4655467.00 |	1.00 |



**Гистограмы ZH-Score**
|   |   |
|---|---|
| ![](./histograms/C_flavus.png) | ![](./histograms/C_henricii.png)  |
|  ![](./histograms/C_mirabilis.png) | ![](./histograms/C_rhizosphaera.png)  |
| ![](./histograms/C_segnis.png)  |  |

**homologuous clusters**

![](./histograms/clusters.png)
number of clusters: 4644


# Число участков Z-DNA и их длина

| Species  |  C_flavus	| C_henricii |	C_mirabilis |	C_rhizosphaera	| C_segnis |
|---|--|--|---|--|---|
| Number of Z-DNA regions| 81688	| 31202 |	53558	| 66835	| 73335 | 
| Z-DNA length  | 322820	| 126852	| 214626 |	269193	| 276327 |


*визуализация Z-DNA в промоторах*
|   |   |
|---|---|
| ![](./visualization/Cluster1.png) | ![](./visualization/Cluster2.png)  |
|  ![](./visualization/Cluster3.png) | ![](./visualization/Cluster4.png)  |
| ![](./visualization/Cluster5.png)  | ![](./visualization/Cluster6.png)   |
| ![](./visualization/Cluster7.png)  | ![](./visualization/Cluster8.png)   |


## Multiple protein alignment
Files are in the folder *aligment*, one of alignements is provided here

<details>
<summary>Cluster 1 alignment</summary>

```
WP_042880284.1      MLTVRAARADDLGAIVKLERYCFPPEVAFGRSRWHYLLNQAKGRTLLLQDEKAQVMGYVS
WP_041206513.1      MLTVRAARTDDLGAIVKLERYCFPPEVAFGRSRWHYLLSHARGRTLLLLDEKAQLMGYLS
WP_042651955.1      MLTLRAARTDDLGAIVKLERYCFPPEVAFGRSRWHYLLTQAKGRTLLLLDDKAQLMGYLS
WP_226014131.1      MLTVRAARTDDLGAIVKLERYCFPPEVAFGRSRWHYLLTQAKGRTLLVLDQQEQLMGYLC
WP_024946079.1      MLTVRAARTDDLGAIVKLERYCFPPEVAFGRSRWHYLLTHAKGRTLLVLDQQEQLMGYLC
                    ***:****:*****************************.:*:*****: *:: *:***:.

WP_042880284.1      VLEHKGWDRLIIQTLAIRWTVRRQGWARRLLEQVIREGREAGWGAIRLEVADANPEARTL
WP_041206513.1      VLEHRGWNRLIIQTLAIRWTVRRQGWARRLLEQVIREGREAGWGAIRLEVADANPEAQTL
WP_042651955.1      VLEHRGWDRLVIQTLAIRWTVRRQGWARRMLEQVIQEGRQAGWGAIRLEVADANPEAQTL
WP_226014131.1      LLEHRGWDRLIIQTLAIRWTIRRQGWARRLLEQVVREGKEAGWGAIRLEVGDANEEAQAL
WP_024946079.1      LLEHRGWDRLIIQTLAIRWTIRRQGWARRLLEQVIQEGKEAGWGAIRLEVGDANEEAQAL
                    :***:**:**:*********:********:****::**::**********.*** **::*

WP_042880284.1      YQGLGFRPGVRLPDYYGPGQHAHRLVLALGDERQEPS--
WP_041206513.1      YHGLGFRPRLRLPDYYGPGQHAHRLVLALKQA-------
WP_042651955.1      YQRLGFRPRLRLPDYYGPGLHAHRLVLPLGSGEQGLA--
WP_226014131.1      YRGLGFRPRQKLLDYYGHGQHAHRLVLKLAGERREEERG
WP_024946079.1      YRELGFRPRQKLPDYYGHGQHAHRLVLALKQA-------
                    *: *****  :* **** * ******* *          

```
 
</details>

# Предсказание G-квадруплексов

## Number of quadruplex regions and quadruplex length

| Species  |  A_caviae	| A_dhakensis |	A_encheleia	| A_hydrophila | A_media |
|---|--|--|---|--|---|
| Number of quadruplex regions | 3919	| 2998 |	3149 |	2815 |	3302 | 
| Quadruplex length  | 121057 |	91507 |	96600 |	85445 |	101636 |


**aaa distribution**
|   |   |
|---|---|
| ![](./histograms/A_caviae_quadruplex.png) | ![](./histograms/A_dhakensis_quadruplex.png)  |
| ![](./histograms/A_encheleia_quadruplex.png) | ![](./histograms/A_hydrophila_quadruplex.png)  |
| ![](./histograms/A_media_quadruplex.png)  |  |


**Quadruplexes visualization**
|   |   |
|---|---|
| ![](./visualization/quadruplexes/cluster1.png) | ![](./visualization/quadruplexes/cluster2.png)  |
|  ![](./visualization/quadruplexes/cluster3.png) | ![](./visualization/quadruplexes/cluster4.png)  |
| ![](./visualization/quadruplexes/cluster5.png)  | ![](./visualization/quadruplexes/cluster6.png)   |
| ![](./visualization/quadruplexes/cluster7.png)  | ![](./visualization/quadruplexes/cluster8.png)   |

R-scripts used for the analysis can be gained via:
<details>
<summary>pqsfinder</summary>

```
!wget https://raw.githubusercontent.com/narek01/hse22_project/main/pqsfinder.r
  
```
  
<details>
<summary>configure</summary>
  
```
  
!wget https://raw.githubusercontent.com/narek01/hse22_project/main/configure.r

```
<details>

