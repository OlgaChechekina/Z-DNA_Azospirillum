# Caulobacter

Alphaproteobacteria, Caulobacter использовались в анализе.

[Ссылка на colab](https://colab.research.google.com/drive/1_5P72lwLC4ZLEUQdjOeQWWKfvtPD_CWY?usp=sharing)

# General info
Анализируемые организмы: *Caulobacter flavus*, *Caulobacter henricii*, *Caulobacter mirabilis*, *Caulobacter rhizosphaerae*, *Caulobacter segnis*

# overview table

| Species  |  Genes number | Genome coverage | Genome length | Genome_plasmid length | Number of sequences |
|---|--|--|---|--|---|
| C_flavus |	5236.00	| 89.71	| 5659202.00	| 5659202.00 |	1.00 |
| C_henricii |	3693.00	| 89.84	| 3864204.00	| 3957288.00 |	2.00 |
| C_mirabilis |	4385.00	| 91.59 |	4577265.00	| 4577265.00 |	1.00 |
| C_rhizosphaera |	5288.00 |	89.44| 	5732418.00 |	5963910.00 |	2.00 |
| C_segnis |	4411.00 |	90.65 |	4655467.00 |	4655467.00 |	1.00 |


![image](https://user-images.githubusercontent.com/60808830/173884168-0a472a40-c986-4b4b-9c32-9aec366d53da.png)


**ZH-Score histograms**
|   |   |
|---|---|
| ![](./histograms/A_caviae.png) | ![](./histograms/A_dhakensis.png)  |
|  ![](./histograms/A_hydrophila.png) | ![](./histograms/A_encheleia.png)  |
| ![](./histograms/A_media.png)  |  |

**homologuous clusters**

![](./histograms/clusters.png)
number of clusters: 4318


# Number of Z-DNA regions and Z-DNA length

| Species  |  A_caulinodans |	A_oryzae	| A_ramasamyi |	A_thermophilum |	A_thiophilum |
|---|--|--|---|--|---|
| Number of Z-DNA regions| 92178 |	30198 |	30870 |	30321 |	31743 | 
| Z-DNA length  | 359344 |	121602 |	123827 |	122256 |	127340 |



*Z-DNA in promoters visualization*
|   |   |
|---|---|
| ![](./visualization/cluster1.png) | ![](./visualization/cluster2.png)  |
|  ![](./visualization/cluster3.png) | ![](./visualization/cluster4.png)  |
| ![](./visualization/cluster5.png)  | ![](./visualization/cluster6.png)   |
| ![](./visualization/cluster7.png)  | ![](./visualization/cluster8.png)   |


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

