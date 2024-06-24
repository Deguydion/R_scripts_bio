## The script is the data analysis for the article:
## Gowri V, Dion E, Viswanath A, Piel FM, Monteiro A. Transgenerational inheritance of learned preferences for novel host plant odors in Bicyclus anynana butterflies. Evolution. 2019;73(12):2401-14.
## (Gowri & Dion are co 1st authors)

### Methods:
**Odor choice assay:** 
Odor choice assays were performed at different stages of larval development, from naive emerged to 5th instar. 
Each assay was performed using a Petri dish, on which a central line was drawn, two more lines, equally spaced from the central line, were drawn on either side of it. 
One side of the Petri dish had a small piece of a control leaf coated in ethanol, whereas the other side had a similarly sized leaf coated with one of the essences. 

**Oviposition choice assay:** 
Done on mated adults. The butterflies were given two options with regard to oviposition site: control leaves or odor leaves in a test cage.

### Statistical analysis:
**Testing for an appropriate control treatment**
Changes in proportions of larvae choosing ethanol-coated leaves over noncoated leaves over larval development (day 5, 10, 15, and   20) were analyzed with a two-tailed 
Fisher exact test of independence followed by an adjusted pairwise nominal independence post hoc analysis.

**Testing for larval odor preferences**
We used a chi-squared test of goodness of fit to test if the proportion of larvae choosing the odor leaves over the control leaves was significantly different from random choice (50–50% choice).
The test was done separately for each treatment group, generation, and day. 
A significant deviation from 50% was considered a preference.

**Testing for differences in odor choice over time and among diet treatments**
We tested the effects of caterpillar age (5, 10, 15, and 20 days after hatching), food treatment (odor or control), and their interaction on larval choice 
by fitting a binomial generalized linear model (GLM) with the logit link function (choice for the odor was coded 1, whereas the choice for the control was coded 0). 
We tested the significance of the factors via likelihood ratio tests (LRT), removed nonsignificant interactions and factors from the final model, and performed a post hoc analysis with Tukey
adjustment for multiple comparisons. 
Datasets from each odor experiment (almond, banana, coffee, and mango odors) were analyzed separately. 
The difference in proportions of caterpillars that chose mango odors and that chose banana odors, on the 20th day after eclosion, was tested with a two-tailed Fisher exact test of
independence.

**Testing adult oviposition choice**
To test for oviposition choices of the odor-fed and control-fed females (for the banana and mango experiments), number of eggs laid by each female on odor-coated leaves were counted and compared
with number of eggs laid on control leaves by the same female. 
These pairs of numbers were compared with a paired ttest (if the differences between counts were normally distributed) or with a Wilcoxon signed-rank test (if the differences were not
normally distributed).
Data normality was tested a priori with Shapiro–Wilk normality tests.

**Testing the effect of parental (or paternal) diet and oviposition location on offspring naıve choice**
We tested the effect of parental diet (odor or control), number of treated parents (both the mother and father, or the father only), type of plant where eggs were laid (odor or control) (all fixed effects),
and all two-way and three-way interactions between these fixed factors, on the na¨ıve food choice of the offspring by fitting a mixed effects logistic regression for binomial data (offspring choice for
the odor was coded 1,whereas the choice for controlwas coded 0).
Family identity of the offspring was included as a random factor.
A total of 56 and 67 families were counted in the banana and the mango experiments, respectively (Supporting Information File 2).
Nonsignificant interaction terms and factors were removed from the final model. 
The significance of the factorswas tested via LRT, and the final model had the lowest Akaike Information criterium (AIC). 
Differences in the choices made by naıve caterpillars of the parental generation (that are not the parents of the F1 individuals), andbyna¨ıve offspring of the next generationwere compared using
a two-tailed Fisher exact test of independence. 
A pairwise nominal independence post hoc analysis provided adjusted P-values for multiple comparisons. Data from the banana and the mango odor treatments were analyzed separately.

**Software and versions**
All analyses were performed in the R statistical framework (R Development Core Team 2008; RStudio Team 2016)
with the packages Rmisc (Hope 2013), lme4 (Bates et al. 2015), car (Fox and Weisberg 2011), 
rcompanion (Mangiafico 2018), multcompView (Graves et al. 2015), and lsmeans (Lenth 2016)
with the help of McDonald (2014) and Mangiafico (2015, 2016).





