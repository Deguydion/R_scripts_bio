## Data collection and methods as published in Dion E, Pui LX, Weber K, Monteiro A. Early-exposure to new sex pheromone blends alters mate preference in female butterflies and in their offspring. Nature Communications. 2020;11(1):53.

### Data collection methods
**Female exposure to new blend or wild type males**
The female butterfly was released in a cylindrical hanging net cage less than an hour after emergence (on day 0). 
The exposure was done manually by retaining the male between the head and the thorax with narrow-tipped featherweight forceps for 3 min. 
The males were presented directly to the females in a similar way as the natural courtship behavior (same distance and orientation). 
We encouraged the male to flutter its wings towards the female by gently squeezing the forceps. 
This process mimicked the first step of the courtship sequence, the male fluttering, which facilitates the volatilization of the pheromone towards the female (Fig. 1d).
This procedure allowed a direct and controlled exposure of the females and was non-harmful to the males. 

**Mating trials**
One Wt and one NB male were placed in the same cage along with the female. 
Female’s abdomens were pre-dusted with fluorescent orange powder, which is transmitted to the male upon copulation, allowing the identification of the mating partner.
Males were checked for presence of powder every 2 h to prevent multiple mating. 
Assays were ended 6 h after the beginning of the experiment. 
The latter time point corresponds to MSP2 amounts becoming similar between Wt2 and perfumed males 
To differentiate NB2 and Wt2 males, a black dot was applied with a sharpie pen randomly at the top or the bottom of their ventral hindwing. 

**Inheritance of mate preferences**
An additional group of females were exposed to either NB1, Wt1, NB2, and Wt2 males, following the same exposure protocol as described above. 
Each exposed female was mated with a single naïve Wt males in a separate cage. 
The male was removed after mating and the female given a corn plant for egg collection.
Each female and its offspring (F1 individuals) constituted a family.
F1 pupae were sexed, and the females were submitted to the exact same isolation procedure as naïve females until mating trials tested on day 2, using identical procedures as described above. 

**Statistical analyses**
A Generalized Linear Mixed Model (GLMM) was used to analyze the effect of the different treatments on females and their offspring mating outcome, as this model includes both fixed and random effects.
Female mating outcome was the binomial response (NB male chosen or not, coded 1 and 0, respectively). 
The family identity was implemented as a random factor in the models. 
Each female from the parental generation, taken from our stock population cage, was considered as belonging to different families. 
The fixed factors included the female treatment (NB-exposed females, offspring of NB-exposed females, Wt-exposed females, offspring of Wt-exposed females, and naïve females), the age of males used for mate choice (4, 5, or 6 days old) and the position of the black mark used to differentiate males perfumed with NB2 to males perfumed with the solvent only.
Because naïve females and the offspring females were not exposed, the effect of male age during exposure (4, 5, or 6 days old) on female choice was analyzed separately with a binomial logistic regression using the parental generation only. 
p-values of factor effect were obtained by likelihood ratio tests of full regression models tested against simplified models with specific factors removed. 
Adjusted p-values were obtained using pairwise comparison of the significant fixed effects using Tukey Contrasts. 
All measurements were taken from distinct samples. 
Results from experiments 1 and 2 were analyzed separately using R v. 3.2.448 implemented in RStudio v.1.0.13649. 
Packages lme4, multcomp, car, Rmisc, and rcompanion were used.

In both experiments, we tested if females had a significant mating bias for the NB or the WT blend using a Pearson’s χ2 test in R.
The mating outcome was considered a mating bias if it significantly differed from a random mating (50:50). 
Each group was analyzed separately, and the analysis output provided the 95% confidence interval.


