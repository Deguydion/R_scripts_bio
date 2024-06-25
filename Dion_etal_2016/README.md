## Data collection and analysis for plasticity in pheromone porduction
## From Dion E, Monteiro A, Yew JY. Phenotypic plasticity in sex pheromone production in Bicyclus anynana butterflies. Sci Rep. 2016;6:39002.
## https://www.nature.com/articles/srep39002

### Data collection
The butterflies were anesthetized with CO2 and the wings cut with fine scissors at their base on the thorax. 
Both forewings and both hindwings were placed for 30 minutes in glass vials containing 500 μL of hexane with 10 μg.mL−1 of methyl stearate as an internal standard. 
Componenet quantification was carried out on a GCMS QP2010 system and a Shimadzu Gas-Chromatography-QQQ Mass Spectrometer equipped with a DB-5 column.
Relative amounts for each MSP were calculated by normalizing the area under each MSP peak to the area of the peak corresponding to the spiked standard.

### Statistical analyzes
Amounts of MSP were analyzed with a one-way multivariate analysis of variance (MANOVA), followed by univariate ANOVA to explore the effect on each MSP independently.
A Bonferroni correction was applied to adjust for multiple pairwise comparisons. 
Two different GCMS instruments were used for the quantification of MSPs. 
However, because this factor could not be added as random factor in the MANOVA, data obtained from each instrument were analyzed separately.
Hotelling-Lawley’s Trace, Pillai’s Trace, Roy’s Largest Root, and Wilk’s Lambda were all computed, but because the statistical outcome was similar for all of them only Pillai’s Trace was reported here. 
To ensure normality and homoscedasticity, MSP amounts were square-root transformed and ratios were inverse-transformed. 
Normality within group was checked with the Shapiro-Wilk test and homoscedasticity with Levene’s test. 
Multivariate normality was assessed using Mardia’s multivariate normality test and chi-square quantile-quantile plots. 
Multivariate outlier detection was done based on robust Mahalanobis distance. 

All analyses were carried out using the R language and environment for statistical graphics and computing, and associated packages (MVN v.4.0 and car). 
Strength of shift in MSP amounts was calculated as standardized mean differences. 
We used Hedges’ g, which is a standardized effect size expressed in units of standard deviation66. 
R package compute.es was used to calculate Hedges’ g and its bootstrapped 95% confidence interval for the difference between DS-17 and DS-27, and between WS-27 and WS-17 (for effect of adult temperatures), and between WS-27 and DS-27, and WS-17 and DS-17 (for effect of developmental temperatures). 
For qPCR analysis, once agreement between technical replicates was obtained, differences in relative expression of pheromone biosynthetic genes were tested for significance with a Pair Wise Fixed Reallocation Randomization Test in the Relative Expression Software Tool (REST, 2009; http://rest.gene-quantification.info/)68. 
5000 randomizations were done. 
DART, pheromone mass and ratio graphs were built with OriginPro 9.1.0.
