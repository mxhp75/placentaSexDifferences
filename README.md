# placentaSexDifferences
Extended methods to be read in conjunction with my Florey Post Graduate Research Conference poster #53

## Introduction

The human placenta is a complex, rapidly developing, and highly regulated transient organ shared between two genetically unique individuals. It is responsible for the supply of nutrients from the mother to the developing fetus, production of hormones, gas exchange, and the elimation of wastes from the fetus.

Placental development involves processes such as cell-cell adhesion, differentiation, angiogenesis, proliferation, and the migration and invasion of placental cells, all regulated (at least in part) by small non-coding RNAs known as microRNA (miRNA). miRNAs are short ~22 nt long non-coding RNAs that perform post-transcritptional regulation of mRNA transcripts in the cytoplasm by either target transcript degradation or repression.

Many pregnancy complications are the result of placental insufficiency, induced by aberrant placental development or function. Male bearing pregnancies employ different growth strategies to female bearing pregnancies, and are more likely to result in pregnancy complications. Understanding normal placental development can give us insight into pregnancy health, and the potential development development of pregnancy complications.

## Hypothesis

Given the regulatory role that miRNAs have on gene expression and the molecular changes that occur across early gestation, in particular the purported introduction of oxygenated maternal blood between approximately 8-12 weeks’ gestation, we expect to observe differential miRNA expression between placenta from <= 10 weeks’ gestation and > 10 weeks’ gestation. Further, given the different growth strategies employed by the female and male bearing pregnancy, we hypothesise that these differences are not identical between the placenta of each fetal sex.

## Methods

To characterise the miRNA profile across early gestation in human placenta, Illumina high-throughput sequencing was performed on miRNA libraries from chorionic villous samples from 96 singleton pregnancies after elective termination (44 female and 52 male bearing pregnancies).

Using a multiple regression (1) we performed differential miRNA expression to compare groups (≤ 10 wks’ and > 10 wks’) directly. This however risks the loss of true biological signal if male and female bearing pregnancies are responding differently throughout early gestation. Using a  model with an interaction term (2) allowed for comparison between groups within each fetal sex achieving the aim of treating the two sexes separately, but comparing the ≤ 10 wks’ and > 10 wks’ groups without sub-setting the total counts matrix and loosing important statistical information.

(1)                𝒚=𝜷<sub>0</sub> +𝜷<sub>1</sub> 𝒙<sub>1</sub>+ 𝜷<sub>2</sub> 𝒙_𝟐+ 𝜺  

(2)                𝒚=𝜷<sub>0</sub>+𝜷<sub>1</sub> 𝒙<sub>1</sub>+𝜷<sub>2</sub> 𝒙<sub>2</sub>+𝜷<sub>3</sub> 𝒙<sub>1</sub>  × 𝒙<sub>2</sub>+ 𝜺  

