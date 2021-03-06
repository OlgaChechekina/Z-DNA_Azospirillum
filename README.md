# Caulobacter

Alphaproteobacteria, Caulobacter использовались в анализе.

[Ссылка на colab](https://colab.research.google.com/drive/1_5P72lwLC4ZLEUQdjOeQWWKfvtPD_CWY?usp=sharing)

# Общая информация
Анализируемые организмы: *Caulobacter flavus*, *Caulobacter henricii*, *Caulobacter mirabilis*, *Caulobacter rhizosphaerae*, *Caulobacter segnis*

# Общая таблица

| Species  |  Genes number | Genome coverage | Genome length | Genome_plasmid length | Number of sequences |
|---|--|--|---|--|---|
| C_flavus |	5236.00	| 89.71	| 5659202.00	| 5659202.00 |	1.00 |
| C_henricii |	3693.00	| 89.84	| 3864204.00	| 3957288.00 |	2.00 |
| C_mirabilis |	4385.00	| 91.59 |	4577265.00	| 4577265.00 |	1.00 |
| C_rhizosphaera |	5288.00 |	89.44| 	5732418.00 |	5963910.00 |	2.00 |
| C_segnis |	4411.00 |	90.65 |	4655467.00 |	4655467.00 |	1.00 |

Прочая статистика: https://docs.google.com/spreadsheets/d/1KQDy0_MQZVYTKdX1ksnddA-_FehDP3LllVt7rxA_fwM/edit?usp=sharing


**Гистограмы ZH-Score**
|   |   |
|---|---|
| ![](./histograms/C_flavus.png) | ![](./histograms/C_henricii.png)  |
|  ![](./histograms/C_mirabilis.png) | ![](./histograms/C_rhizosphaera.png)  |
| ![](./histograms/C_segnis.png)  |  |

**Кластеры**

![](./histograms/clusters.png)

Число кластеров: 4644


# Число участков Z-DNA и их длина

| Species  |  C_flavus	| C_henricii |	C_mirabilis |	C_rhizosphaera	| C_segnis |
|---|--|--|---|--|---|
| Number of Z-DNA regions| 81688	| 31202 |	53558	| 66835	| 73335 | 
| Z-DNA length  | 322820	| 126852	| 214626 |	269193	| 276327 |


*визуализация Z-DNA в промоторах*
|   |   |
|---|---|
| ![](./visualization/Cluster_1.png) | ![](./visualization/Cluster_2.png)  |
|  ![](./visualization/Cluster_3.png) | ![](./visualization/Cluster_4.png)  |
| ![](./visualization/Cluster_5.png)  | ![](./visualization/Cluster_6.png)   |
| ![](./visualization/Cluster_7.png)  | ![](./visualization/Cluster_8.png)   |


## Множественное выравнивание белков 
Файлы выравниваний находятся в папке *aligment*, пример приведен ниже

<details>
<summary>Cluster 1 alignment</summary>

```

WP_101712774.1      MDDAAGGLQATMRAMGQAAREGARALRLATPAQRTAALTAIAAAIRADAPAILGANARDL
WP_163233626.1      MDDAGMSLQATMTAMGQAARHGASALRVATPAQRTAALQAMAAAIRADAPAILAANARDL
WP_099620472.1      MDDGAVSLQATMTAMGQAAREGARALRLSTPEQRTAAIRAMAQAIRDDAQAILAANQRDQ
WP_062149973.1      MDDAGVSLQAKMIAMGEAARAGARALRLASAEQRTTALQAMAKAIREDAAPILAANARDI
WP_013077445.1      MDDAGVSLQATMADMGRTAREGARALRLATPEQRTAAIRAMAAEIRKAAPAILAANAQDL
                    ***.. .***.*  **.:** ** ***:::. ***:*: *:*  **  * .**.** :* 

WP_101712774.1      EKAGANGLTPPMIERLMLNEARLEGVAAGVEAVAAIPDPLGVETARWTRPNGLDIARVRT
WP_163233626.1      DKAGAGGLTAPMVERLMLNAERLEGVAAGLEAVAAIPDPLGVETARWTRPNGLDIARVRT
WP_099620472.1      AAARDAGLAAPMIDRMMLDAGRLEGVAQGVEAVAGIPDPLGVETARWTRPNGLDIARVRT
WP_062149973.1      AQAKANGLSGPMLDRLLLDEARLEAMAAGVEVVAALADPLGVATARWTRPNGLDIARVRT
WP_013077445.1      SRAEANGVSGPMLDRLALDEKRLEGVAAGVEAVAEIADPLGVATSRWTRPNGLDISRVRT
                      *   *:: **::*: *:  ***.:* *:*.** :.***** *:**********:****

WP_101712774.1      PIGVIAMIYESRPNVTADAAALTLRSGNAVILRGGSECIESNLAIHAAVVKGLTAAGLPH
WP_163233626.1      PIGVIAMIFESRPNVTADAAALCVRSGNAVILRGGSECLQSNLAIHAAIAKGLKAAGIST
WP_099620472.1      PIGVIAIIYESRPNVTADAAALCVRSGNAAILRGGSECIRTNQALHAAVAKGLTAAGLPA
WP_062149973.1      PIGVIAMIYESRPNVTADAAALCVRSGNAVILRGGSECLASSLAIHAAIVRGLKAAGLPA
WP_013077445.1      PIGVIAMIYESRPNVTADAAALCVRSGNAVILRGGSECIASNLAIHTAIERGLETAGLPA
                    ******:*:************* :*****.********: :. *:*:*: :** :**:. 

WP_101712774.1      QVVQMVRTTDRAAVGAILSGLDRSIDLIIPRGGKSLVARVQAEARAPVLGHLEGLNHVFV
WP_163233626.1      DAVQIVRTPDRDAVGAILSGLDRTIDLIIPRGGKSLVARVQQEARVAVLGHLEGLNHVFV
WP_099620472.1      ACVQVVKTSDRAAVGHILSGLDRTIDLIIPRGGKSLVARVQAEARAPVLGHLEGLNHVYV
WP_062149973.1      SAVQAVGTADRAAVGHILAGLNRAVDLIIPRGGKSLVARVQAEARAPVLGHLEGLNHVFV
WP_013077445.1      SAVQAVKTPDRAAVGMILQGLDRSIDLIIPRGGKSLVARVQAEARAPVLGHLEGLNHVFV
                      ** * *.** *** ** **:*::**************** ***..***********:*

WP_101712774.1      HEAADLKKAADIVLNAKMRRVSVCGSAETLLIDRAAAGKLLPPIADVLIKAGCEIRGDAA
WP_163233626.1      HAAADPRKAVDIVLNAKMRRVSVCGAAETLLVDRAAASRLLPPIADALIKAGCELRGDGP
WP_099620472.1      DAEADVAKARDIVLNAKMRRVSVCGAAETLLVDAKAAERLLPPVADALIRAGCELRGDAR
WP_062149973.1      HAAADPRKAVEIALNAKMRRVSVCGSAETLLVDRAVADRLLPLLADALIKAGCELRGDAA
WP_013077445.1      HAAADPKKAVDIVVNAKLRRVSVCGSAETLLVDKVAAETLLPPIAQALLVAGCELRGDAA
                    .  **  ** :*.:***:*******:*****:*  .*  *** :*:.*: ****:***. 

WP_101712774.1      ARAIEPELKAAAVEDWTTEYLAPIIAVAVVDGVEGAAQHIATYGSGHTDAIVTEDAAAAE
WP_163233626.1      SRAIEPTMKPAIEADWSTEYLAPTISVAVVDGVEGAAAHIAAYGSGHTDAILTEDAAAAE
WP_099620472.1      ARAIEPTMAAATIEDWTTEYLAPTIAVAVVDGVEGAAAHIASYGSGHTDAIVTENAATAE
WP_062149973.1      ALVIEPTMKKAQEADWSTEYLAPILSVAVVDGVAGAAAHIARYGSGHTDAIVTEDAAAAE
WP_013077445.1      ARAIVPAMKAATTEDWTTEYLAAILAVAVVDGVEGAAAHIAAFGSGHTDAIVTEDEAAAE
                    : .* * :  *   **:*****. ::******* *** *** :********:**: *:**

WP_101712774.1      RFVSQVDSAIVLVNASTQFADGGEFGFGAEIGIATDKLHARGPVGAEQLTTFKYVVRGTG
WP_163233626.1      RFVALVDSAIVLVNASTQFADGGEFGFGAEIGIATDKLHARGPVGAEQLTTFKYVVRGTG
WP_099620472.1      RFTALVDSAIVLINASTQFADGGEFGFGAEIGIATDKLHARGPVGAEQLTTFKYVVRGTG
WP_062149973.1      AFAAEVDSAIVLINASTQFADGGEFGFGAEIGIATDKLHARGPVGAEQLTTFKYVVRGTG
WP_013077445.1      TFVAAVDSAIVLVNASTQFADGGEFGFGAEIGIATDKLHARGPVGAEQLTTFKYVVRGTG
                     *.: *******:***********************************************

WP_101712774.1      QTRP
WP_163233626.1      QTRP
WP_099620472.1      QTRP
WP_062149973.1      QTRP
WP_013077445.1      QTRP
                    ****

```
 
</details>

# Предсказание G-квадруплексов

## Число участков G-квадруплексов и их длины
| Species  |  C_flavus |	C_henricii |	C_mirabilis |	C_rhizosphaera |	C_segnis |
|---|--|--|---|--|---|
| Number of quadruplex regions | 4639	| 2938	| 3049	| 5038	| 2879 | 
| Quadruplex length  | 132289 |	87637	| 89031	| 145818	| 82928 |


**Quadruplexes score**
|   |   |
|---|---|
| ![](./histograms/C_flavus_quadruplex.png) | ![](./histograms/C_henricii_quadruplex.png)  |
| ![](./histograms/C_mirabilis_quadruplex.png) | ![](./histograms/C_rhizosphaera_quadruplex.png)  |
| ![](./histograms/C_segnis_quadruplex.png)  |  |


**Визуалиация квадруплексов**
|   |   |
|---|---|
| ![](./visualization/Cluster_1_quadruplex.png) | ![](./visualization/Cluster_2_quadruplex.png)  |
|  ![](./visualization/Cluster_3_quadruplex.png) | ![](./visualization/Cluster_4_quadruplex.png)  |
| ![](./visualization/Cluster_5_quadruplex.png)  | ![](./visualization/Cluster_6_quadruplex.png)   |
| ![](./visualization/Cluster_7_quadruplex.png)  | ![](./visualization/Cluster_8_quadruplex.png)   |


