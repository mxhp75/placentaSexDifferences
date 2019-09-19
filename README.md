# placentaSexDifferences
Extended methods to be read in conjunction with my Florey Post Graduate Research Conference poster #53

##Hypothesis

Given the regulatory role that miRNAs have on gene expression and the molecular changes that occur across early gestation, in particular the purported introduction of oxygenated maternal blood between approximately 8-12 weeks’ gestation, we expect to observe differential miRNA expression between placenta from  10 weeks’ gestation and > 10 weeks’ gestation. Further, given the different growth strategies employed by the female and male bearing pregnancy, we hypothesise that these differences are not identical between the placenta of each fetal sex.

##Methods

To characterise the miRNA profile across early gestation in human placenta, Illumina high-throughput sequencing was performed on miRNA libraries from chorionic villous samples from 96 singleton pregnancies after elective termination (44 female and 52 male bearing pregnancies).

Using a multiple regression (1) we performed differential miRNA expression to compare groups (≤ 10 wks’ and > 10 wks’) directly. This however risks the loss of true biological signal if male and female bearing pregnancies are responding differently throughout early gestation. Using a  model with an interaction term (2) allowed for comparison between groups within each fetal sex achieving the aim of treating the two sexes separately, but comparing the ≤ 10 wks’ and > 10 wks’ groups without sub-setting the total counts matrix and loosing important statistical information.
