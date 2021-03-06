# Проект 2022. Z-ДНК

###### Кличко Никита  

*Подробности анализа см. в гугл колабе* [colab](https://colab.research.google.com/drive/1xVCzMqQgZSB_OGuTJA0xS_GduAuHkgPq?usp=sharing)

# Общая информация  

Для анализа был выбран таксон *Gammaproteobacteria*, род *Xanthomonas*.  
Организмы: *cucurbitae, euroxanthea, hyacinthi, theicola, translucens pv. undulosa* 

# Сводная таблица 

Название вида | Количество хромосом| Количество скаффолдов | Количество плазмид | Общая длина | Количество аннотированных генов | Доля аннотированных генов в геноме (в %) | Количество предсказанных участков Z-dna | Количество участков с Z-score > 500 | Oбщая длина участков с zh-score >500 | 
--- | ---  | --- | --- | --- | --- | --- | --- | --- | ---
cucurbitae | 1 | 0 | 1 | 4615492 | 4013 | 87.4 | 4601253 | 107878 | 1079030 | 
euroxanthea | 1 | 0 | 1 | 4968459 | 4177 | 85.4 | 4923218 | 123357 | 1234600 | 
hyacinthi | 1 | 0 | 1 | 4963026 | 4385 | 86.9 | 4918645 | 138494 | 1369694 | 
theicola | 1 | 0 | 1 | 4785596 | 4541 | 85.6 | 4744641 | 130754 | 1295114 | 
translucens pv. undulosa | 1 | 0 | 2 | 4649333 | 4037 | 85.7 | 4563212 | 128993 | 1276212 | 

# Гистограммы ZH-Score значений  

![](https://github.com/NikitaKlichko/hse22_project/blob/main/imgs/zh-hist-cucurbitae.png) 
![](https://github.com/NikitaKlichko/hse22_project/blob/main/imgs/zh-hist-euroxanthea.png) 
![](https://github.com/NikitaKlichko/hse22_project/blob/main/imgs/zh-hist-hyacinthi.png) 
![](https://github.com/NikitaKlichko/hse22_project/blob/main/imgs/zh-hist-theicola.png) 
![](https://github.com/NikitaKlichko/hse22_project/blob/main/imgs/zh-hist-translucens.png)  

# Визализация нескольких генов, пересеченных с пресказанными Z-DNA 

***Xanthomonas cucurbitae*** 
![](https://github.com/NikitaKlichko/hse22_project/blob/main/imgs/z-cucurbitae.png) 
***Xanthomonas hyacinthi*** 
![](https://github.com/NikitaKlichko/hse22_project/blob/main/imgs/z-hyacinthi.png) 
***Xanthomonas translucens_pv*** 
![](https://github.com/NikitaKlichko/hse22_project/blob/main/imgs/z-translucens.png) 

# Информаиця по получившимся гомологичным кластерам

Количество кластеров: *3991*

![](https://github.com/NikitaKlichko/hse22_project/blob/main/imgs/hist-clast.png) 

Количество кластеров в районе промотера: *42*

# Таблица с информацией по выбранным кластерам 

Выберем 10 кластеров с наибольшим ZH-Score'ом: 

|Clust|# Species|Genes|Alg.-Conn.    |protein_cucurbitae.faa|protein_euroxanthea.faa|protein_hyacinthi.faa|protein_theicola.faa|protein_translucens.faa                           |zh-scores         |mean_zh-score|GeneID_protein_cucurbitae.faa|GeneID_protein_euroxanthea.faa|GeneID_protein_hyacinthi.faa|GeneID_protein_theicola.faa|GeneID_protein_translucens.faa|func_protein_cucurbitae.faa|func_protein_euroxanthea.faa|func_protein_hyacinthi.faa|func_protein_theicola.faa|func_protein_translucens.faa                    |
|-----|---------|-----|--------------|----------------------|-----------------------|---------------------|--------------------|--------------------------------------------------|------------------|-------------|-----------------------------|------------------------------|----------------------------|---------------------------|------------------------------|---------------------------|----------------------------|--------------------------|-------------------------|------------------------------------------------|
|0    |5        |5    |1.0           |WP_064507842.1        |WP_016901574.1         |WP_046980641.1       |WP_128420848.1      |WP_003471869.1                                    |[651.3941, 2057.902, 28780.5, 28780.5, 28780.5]|17810.15922  |EBN15_RS00095                |H7A86_RS00100                 |FZ025_RS07030               |G4Q83_RS17685              |ISN38_RS08195                 |DUF1820 family protein     |DUF1820 family protein      |DUF1820 family protein    |DUF1820 family protein   |DUF1820 family protein                          |
|1    |5        |5    |1.0           |WP_159407721.1        |WP_119131704.1         |WP_046978994.1       |WP_128419959.1      |WP_003467858.1                                    |[8323.257, 1309.834, 138924.1, 505.8732, 28780.5]|35568.71284  |EBN15_RS17825                |H7A86_RS17945                 |FZ025_RS06460               |G4Q83_RS20310              |ISN38_RS07660                 |glycosyltransferase family 2 protein|glycosyltransferase family 2 protein|glycosyltransferase family 2 protein|glycosyltransferase family 2 protein|glycosyltransferase family 2 protein            |
|2    |5        |5    |1.0           |WP_159406934.1        |WP_119132146.1         |WP_104558680.1       |WP_128418663.1      |WP_047324982.1                                    |[2213.593, 198956.2, 2752.447, 2752.447, 2752.447]|41885.4268   |EBN15_RS07550                |H7A86_RS09235                 |FZ025_RS18335               |G4Q83_RS10015              |ISN38_RS19025                 |4-hydroxy-tetrahydrodipicolinate synthase|4-hydroxy-tetrahydrodipicolinate synthase|4-hydroxy-tetrahydrodipicolinate synthase|4-hydroxy-tetrahydrodipicolinate synthase|4-hydroxy-tetrahydrodipicolinate synthase       |
|3    |5        |5    |0.6           |WP_159407733.1        |WP_180707937.1         |WP_046977482.1       |WP_128420444.1      |WP_038236362.1                                    |[908.3955, 27872.66, 138924.1, 708.0171, 138924.1]|61467.45452000001|EBN15_RS17990                |H7A86_RS18115                 |FZ025_RS06640               |G4Q83_RS19775              |ISN38_RS07825                 |transcription termination factor Rho|transcription termination factor Rho|transcription termination factor Rho|transcription termination factor Rho|transcription termination factor Rho            |
|4    |5        |5    |1.0           |WP_208800643.1        |WP_232099329.1         |WP_046978980.1       |WP_128420334.1      |WP_003466919.1                                    |[302785.5, 1202.592, 2555.896, 803.2278, 803.2278]|61630.08872  |EBN15_RS06575                |H7A86_RS08065                 |FZ025_RS06380               |G4Q83_RS20615              |ISN38_RS07595                 |L-fucose:H+ symporter permease|L-fucose:H+ symporter permease|sugar MFS transporter     |sugar MFS transporter    |sugar MFS transporter                           |
|5    |5        |5    |1.0           |WP_159406962.1        |WP_104648646.1         |WP_046980439.1       |WP_128419729.1      |WP_003472164.1                                    |[13713.99, 27872.66, 27872.66, 138924.1, 138924.1]|69461.50200000001|EBN15_RS07955                |H7A86_RS09765                 |FZ025_RS18875               |G4Q83_RS04620              |ISN38_RS00365                 |phosphoglycerate mutase    |phosphoglycerate mutase     |phosphoglycerate mutase   |phosphoglycerate mutase  |hypothetical protein                            |
|6    |5        |5    |1.0           |WP_104603128.1        |WP_119131113.1         |WP_104558755.1       |WP_128418685.1      |WP_206712091.1                                    |[883.5764, 931.1695, 138924.1, 302785.5, 138924.1]|116489.68918000002|EBN15_RS13780                |H7A86_RS15215                 |FZ025_RS02040               |G4Q83_RS08905              |ISN38_RS05165                 |DUF3011 domain-containing protein|DUF3011 domain-containing protein|DUF3011 domain-containing protein|DUF3011 domain-containing protein|DUF3011 domain-containing protein               |
|7    |5        |5    |1.0           |WP_104601725.1        |WP_104582792.1         |WP_104558116.1       |WP_128421855.1      |WP_087960525.1                                    |[1430.8, 941334.2, 1737.612, 1964.835, 1964.835]|189686.4564  |EBN15_RS06770                |H7A86_RS08265                 |FZ025_RS17825               |G4Q83_RS04660              |ISN38_RS18190                 |NAD kinase                 |NAD kinase                  |NAD kinase                |NAD kinase               |NAD kinase                                      |
|8    |5        |5    |1.0           |WP_104604391.1        |WP_016903181.1         |WP_046978138.1       |WP_128419433.1      |WP_003465531.1                                    |[65884.11, 904.32, 941334.2, 198956.2, 29467.88]|247309.342   |EBN15_RS08065                |H7A86_RS09835                 |FZ025_RS18945               |G4Q83_RS04810              |ISN38_RS19120                 |type II toxin-antitoxin system VapC family toxin|type II toxin-antitoxin system VapC family toxin|type II toxin-antitoxin system VapC family toxin|type II toxin-antitoxin system VapC family toxin|type II toxin-antitoxin system VapC family toxin|
|9    |5        |5    |1.0           |WP_029219710.1        |WP_016903166.1         |WP_170874001.1       |WP_185817409.1      |WP_170874001.1                                    |[883.5764, 1202.592, 198956.2, 198956.2, 941334.2]|268266.55368 |EBN15_RS07950                |H7A86_RS09760                 |FZ025_RS18870               |G4Q83_RS04615              |ISN38_RS00360                 |transcription elongation factor GreA|transcription elongation factor GreA|transcription elongation factor GreA|transcription elongation factor GreA|transcription elongation factor GreA            |

# Множественное белковое выравнивание для каждого выбранного кластера 

До и после выравнивания см [alignment](https://github.com/NikitaKlichko/hse22_project/tree/main/alignment)  

Скриншоты самого выраванивания ниже (сдвинем индекс кластеров на один, чтобы первый кластер начинался с единицы): 
![](https://github.com/NikitaKlichko/hse22_project/blob/main/imgs/Cluster1.JPG) 
![](https://github.com/NikitaKlichko/hse22_project/blob/main/imgs/Cluster2.JPG) 
![](https://github.com/NikitaKlichko/hse22_project/blob/main/imgs/Cluster3.JPG) 
![](https://github.com/NikitaKlichko/hse22_project/blob/main/imgs/Cluster4.JPG) 
![](https://github.com/NikitaKlichko/hse22_project/blob/main/imgs/Cluster5.JPG) 
![](https://github.com/NikitaKlichko/hse22_project/blob/main/imgs/Cluster6.JPG) 
![](https://github.com/NikitaKlichko/hse22_project/blob/main/imgs/Cluster7.JPG) 
![](https://github.com/NikitaKlichko/hse22_project/blob/main/imgs/Cluster8.JPG) 
![](https://github.com/NikitaKlichko/hse22_project/blob/main/imgs/Cluster9.JPG) 
![](https://github.com/NikitaKlichko/hse22_project/blob/main/imgs/Cluster10.JPG) 

# Визуализация расположения участков Z-DNA для каждого выбранного кластера 

![](https://github.com/NikitaKlichko/hse22_project/blob/main/imgs/v-clast1.png) 
![](https://github.com/NikitaKlichko/hse22_project/blob/main/imgs/v-clast2.png) 
![](https://github.com/NikitaKlichko/hse22_project/blob/main/imgs/v-clast3.png) 
![](https://github.com/NikitaKlichko/hse22_project/blob/main/imgs/v-clast4.png) 
![](https://github.com/NikitaKlichko/hse22_project/blob/main/imgs/v-clast5.png) 
![](https://github.com/NikitaKlichko/hse22_project/blob/main/imgs/v-clast6.png) 
![](https://github.com/NikitaKlichko/hse22_project/blob/main/imgs/v-clast7.png) 
![](https://github.com/NikitaKlichko/hse22_project/blob/main/imgs/v-clast8.png) 
![](https://github.com/NikitaKlichko/hse22_project/blob/main/imgs/v-clast9.png) 
![](https://github.com/NikitaKlichko/hse22_project/blob/main/imgs/v-clast10.png) 




