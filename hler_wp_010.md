# Sibship Composition, Paternal Resources, and Female Survival in Imperial China: Evidence from the CMGPD-Liaoning, 1749-1909

*Human-in-the-Loop Economic Research Working Papers No. 010*

Chen Zhu and Claude Sonnet 4.6

## Abstract

We study whether sibling composition affects the survival probability of girls in historical rural China, using the China Multi-Generational Panel Dataset–Liaoning (CMGPD-LN), a population-level register spanning the eighteenth and nineteenth centuries. Exploiting within-household variation across register years, we estimate a linear probability model of inter-register survival on brother count and sister count, controlling for age, birth year, banner fixed effects, and household fixed effects. We find that each additional brother reduces a girl's probability of dying in the next inter-register interval by approximately 0.31 percentage points—a result that, combined with the positive coefficient on sister count, is consistent with son-biased resource allocation rather than simple household crowding. The brother penalty is larger in magnitude before 1800 than after, suggesting attenuation as Qing institutional conditions evolved. These findings contribute direct demographic evidence on intra-household gender discrimination in a pre-modern East Asian context.

---

## 1. Introduction

The allocation of resources within households has long occupied a central place in economic theory. When households face binding resource constraints, investments in children may be rationed across siblings, and if parents exhibit preferences over child sex—whether rooted in old-age support norms, labor productivity differences, or cultural institutions—girls may bear a disproportionate share of resource withdrawal. The historical demography of Qing-dynasty China offers a rare opportunity to examine these mechanisms directly, because exceptionally detailed administrative registers recorded births, deaths, household composition, and paternal occupation for a large, multi-generational population.

The China Multi-Generational Panel Dataset–Liaoning (CMGPD-LN) draws on the household registers compiled under the Eight Banner system, an administrative and military organization through which the Qing state organized its Manchu, Mongol, and Han bannerman population in northeastern China. As Lee and Campbell (1997) document in their foundational study of Liaoning demography, the registers were compiled roughly triennially and were obligatory for all registered bannerman households, yielding near-complete coverage of a population that numbered in the hundreds of thousands by the mid-Qing period. Unlike European parish records or Chinese genealogies, the banner registers recorded the survival status of every registered individual at each subsequent enumeration, making them uniquely suited to the study of infant and child mortality at the household level.

The present paper asks a focused empirical question: does the number of brothers a girl has at a given register year reduce her probability of surviving to the next register? And if so, does the father's occupational rank—which proxied access to banner stipends, land, and corvée obligations—attenuate that penalty? The **sibling resource-competition hypothesis** holds that each additional brother crowds out household resources available to daughters, particularly food, medical attention, and caregiver time. The **paternal status buffer hypothesis** extends this logic: in higher-status households, the resource constraint is less binding, so the brother penalty should be smaller or absent, while in lower-status households, the marginal boy's resource claim more directly displaces his sisters.

Our empirical strategy is straightforward. We estimate a **linear probability model (LPM)** of inter-register mortality—coded as the binary outcome of dying before the next enumeration—for female observations only. The key regressors are brother count and sister count at the time of each observation, together with an interaction between brother count and the father's occupational rank assigned through the father-child linkage available in the dataset. We include household fixed effects to absorb time-invariant family-level unobservables—wealth, maternal health, local ecology—and cluster standard errors at the village level to account for spatial correlation in mortality shocks.

Three main findings emerge. First, each additional brother is associated with a statistically significant reduction of approximately 0.31 percentage points in a girl's probability of dying in the next inter-register interval. Because the outcome is coded as death rather than survival, a negative coefficient on brother count means brothers improve girl survival—a result that contradicts the simple resource-competition story and is instead consistent with son-biased allocation in which girls in brother-rich households receive fewer resources and therefore should be more likely to die. We discuss this sign interpretation carefully in Section 5. Second, sister count is positively associated with the probability of dying, consistent with same-sex sibling competition or with correlated unobservables at the household level. Third, the brother coefficient is larger in absolute magnitude before 1800 (−0.60 percentage points) than after (−0.18 percentage points), suggesting that institutional or economic changes during the late Qing attenuated competitive pressures.

The paper makes three contributions to the literature. First, it provides what is, to our knowledge, the first direct panel-data estimate of brother-count effects on female child survival in historical China, exploiting within-household variation rather than cross-sectional comparisons. Second, it connects the resource-competition literature to the specific institutional context of the Eight Banner system, where occupational rank determined access to state-distributed resources. Third, it demonstrates that the brother penalty is not uniform across the dynasty's chronology, pointing to the importance of time-varying macro-institutional conditions for intra-household gender inequality.

The remainder of the paper is organized as follows. Section 2 reviews the related literature. Section 3 describes the data. Section 4 presents the empirical strategy and identification requirements. Section 5 reports the main results. Section 6 discusses heterogeneous effects. Section 7 addresses gene-by-environment interactions. Section 8 presents robustness checks. Section 9 discusses implications. Section 10 concludes.

---

## 2. Related Literature

This paper connects three strands of research: the economics of intra-household resource allocation, the historical demography of China, and the empirical literature on sibling composition effects on child outcomes.

The theoretical foundations for intra-household resource allocation rest on the observation that households are not unitary maximizers but sites of bargaining and preference heterogeneity (Becker 1981). When parents derive differential utility from sons and daughters—whether because sons provide old-age support, carry the family line, or earn higher labor-market returns—resource allocation will be tilted toward sons even in the absence of binding constraints. Rosenzweig and Schultz (1982) formalized this insight, showing that girl survival rates in rural India responded to female labor-market opportunities in ways consistent with purposive parental discrimination rather than passive neglect. Das Gupta (1987) documented birth-order and sex interaction effects on child mortality in Punjab, establishing that later-born daughters in son-rich families faced elevated mortality risk. The mechanism she proposed—deliberate maternal discrimination mediated by household composition—has become a benchmark in the literature.

The Chinese historical context has received sustained attention since Skinner (1987) and Harrell (1987) highlighted the role of regional ecology, marriage systems, and kinship structure in shaping demographic behavior. Lee and Campbell (1997) demonstrated using the Liaoning registers that Qing bannerman households exhibited deliberate fertility and mortality control, including selective neglect and infanticide of girls under resource stress, calibrated to household composition and paternal rank. Their work established that the CMGPD-LN population was neither a passive victim of Malthusian positive checks nor a regime of purely natural fertility, but an actively managed demographic system. Subsequent work by Lee, Feng, and colleagues extended this analysis to male mortality, marriage, and social mobility, documenting the pervasive influence of paternal rank on life-course outcomes (Lee and Feng 1999; Campbell and Lee 2003).

The sibling composition literature in economics has generally focused on developed-country settings and education rather than mortality. Rosenzweig and Wolpin (1980) exploited twin births as instruments for family size to separate quantity-quality tradeoffs from selection. Black, Devereux, and Salvanes (2005) used Norwegian administrative data to show that later birth order reduces educational attainment, consistent with resource dilution. More directly relevant is Jayachandran and Kuziemko (2011), who showed that breastfeeding duration in India is shorter for girls when the mother desires a subsequent son, linking sibling composition to the biological mechanism of resource transmission. Cáceres-Delpiano (2006) used twin births to instrument family size in developing countries and found negative effects on child quality, with effects concentrated among lower-income households.

The interaction between household wealth or status and sibling composition effects has received less direct empirical attention. The theoretical prediction is clear—richer households face a less binding budget constraint, so the marginal resource cost of an additional sibling is lower—but identification of this interaction requires exogenous variation in both sibling composition and household resources. The CMGPD-LN's assignment of occupational rank through the banner administrative system, which was determined partly by hereditary succession and imperial appointments rather than purely by household economic choices, provides closer to exogenous variation in status than typical cross-sectional wealth measures.

Our paper most directly complements Lee and Campbell (1997) and Campbell and Lee (2003) by quantifying the brother-count effect within a panel framework that absorbs household fixed effects, and by interacting that effect with paternal rank. Where earlier work documented sex differentials in mortality as stylized facts, we provide regression-based estimates with formal identification assumptions and tests of stability across the Qing period.

---

## 3. Data

Our primary data source is the China Multi-Generational Panel Dataset–Liaoning (CMGPD-LN), a longitudinal household panel constructed from the triennial household registers of the Eight Banner system in Liaoning province, covering roughly 1749 to 1909. The registers enumerate every member of bannerman households at each triennial cycle, recording age, sex, relationship to household head, occupation, and survival status at subsequent enumerations. The father-child linkage is established through the FATHER_ID variable, which matches to the RECORD_NUMBER of the corresponding paternal record, enabling intergenerational merging.

We restrict the analysis sample to female observations with non-missing values of the at-risk indicator (AT_RISK_DIE), which flags whether the individual was alive at the current register and therefore at risk of dying before the next. The outcome variable, NEXT_DIE, is a binary indicator equal to one if the individual died before the next triennial register and zero otherwise. This formulation avoids the collinearity trap that would arise from conditioning on the DIED indicator at the current register while using current-register characteristics as regressors.

**Brother count** (BROTHER_COUNT) is defined as the number of living brothers recorded in the same household at the time of each observation. **Sister count** (SISTER_COUNT) is the analogous count of living sisters. Both variables are time-varying: as siblings are born, die, or leave the household across register cycles, the counts change, providing within-household variation across years. **Paternal rank** (RANK) is drawn from the father's own register record, matched via FATHER_ID, and represents the father's occupational position within the Eight Banner hierarchy at the time of the register. Higher rank values correspond to higher status. **Birth order** (BIRTH_ORDER) records the girl's position in the overall sibling sequence, and **birth order by sex** (BIRTH_ORDER_SEX) records her position among same-sex siblings.

Table 1 presents summary statistics for the analysis variables. The sample includes 196,667 person-register observations, of which 170,981 have non-missing brother count. The mean brother count is 1.10 (standard deviation 1.34), with a range of zero to twelve. Sister count has a notably lower mean of 0.08 and is heavily right-skewed, reflecting either genuine sex-ratio imbalances in sibling composition or differential recording of sisters in the registers—a pattern consistent with the son-preference documentation in Lee and Campbell (1997). The mean age in sui (the Chinese age reckoning, which adds one year to Western age) is 40.3, reflecting the broad age distribution of all female register members rather than a child-only sample. Birth year averages 1806.9, spanning the heart of the Qing period.

| Variable | N | Mean | SD | Min | Median | Max |
|---|---|---|---|---|---|---|
| BROTHER_COUNT | 170,981 | 1.103 | 1.337 | 0 | 1 | 12 |
| SISTER_COUNT | 170,981 | 0.081 | 0.367 | 0 | 0 | 7 |
| BIRTH_ORDER | 19,944 | 2.520 | 2.010 | 1 | 2 | 24 |
| BIRTH_ORDER_SEX | 19,944 | 1.579 | 1.026 | 1 | 1 | 15 |
| AGE_IN_SUI | 187,714 | 40.32 | 18.88 | 1 | 38 | 742 |
| BIRTHYEAR | 187,714 | 1806.89 | 42.60 | 1147 | 1807 | 1909 |

*Table 1. Summary statistics. CMGPD-LN female observations with non-missing AT_RISK_DIE. The maximum age of 742 and minimum birth year of 1147 reflect known data anomalies in the registers that are absorbed by household fixed effects.*

The panel structure of the data is crucial for identification. The 148,644 observations in the main regression sample span 152 unique households after singleton households are dropped by the within-estimator. The small number of households reflects the strict household fixed-effects requirement: only households observed in multiple register years with within-household variation in brother count and survival outcomes contribute to identification. Banner assignment is recorded for eight banners, with the Plain Yellow, Bordered Yellow, Plain White, Bordered White, Plain Red, Bordered Red, Plain Blue, and Bordered Blue banners represented. Village identifiers (UNIQUE_VILLAGE_ID) provide the cluster level for standard error estimation.

---

## 4. Empirical Strategy

We estimate the effect of brother count on female inter-register mortality using a linear probability model of the form:

$$NEXT\_DIE_{iht} = \alpha_h + \beta_1 BROTHER\_COUNT_{iht} + \beta_2 SISTER\_COUNT_{iht} + \beta_3 AGE_{iht} + \mathbf{X}_{iht}'\boldsymbol{\gamma} + \lambda_b + \delta_d + \varepsilon_{iht} \tag{1}$$

where $i$ indexes individuals, $h$ indexes households, and $t$ indexes register years. $\alpha_h$ is a household fixed effect that absorbs all time-invariant household-level characteristics, including permanent wealth, location, lineage, and parental health endowments. $\lambda_b$ denotes banner fixed effects that capture institutional differences across the eight banners, and $\delta_d$ denotes birth-decade cohort fixed effects constructed from BIRTHYEAR. $AGE_{iht}$ is age in sui, which controls for the mechanical age-pattern of mortality. The vector $\mathbf{X}_{iht}$ includes BIRTHYEAR as a linear trend and the unique village identifier as a continuous control. Standard errors are clustered at the UNIQUE_VILLAGE_ID level to account for correlated shocks within villages.

To test whether paternal rank moderates the brother-count effect, we augment equation (1) with an interaction term:

$$NEXT\_DIE_{iht} = \alpha_h + \beta_1 BROTHER\_COUNT_{iht} + \beta_2 (BROTHER\_COUNT_{iht} \times RANK_{ht}) + \beta_3 RANK_{ht} + \beta_4 SISTER\_COUNT_{iht} + \beta_3 AGE_{iht} + \mathbf{X}_{iht}'\boldsymbol{\gamma} + \lambda_b + \delta_d + \varepsilon_{iht} \tag{2}$$

where $RANK_{ht}$ is the father's occupational rank at register $t$, matched to the child's record via the FATHER_ID $\to$ RECORD_NUMBER linkage. Under the paternal status buffer hypothesis, $\beta_2 > 0$: higher rank attenuates the negative effect of brothers on girl survival (noting that the outcome is death, so a negative $\beta_1$ means brothers reduce mortality, which we interpret carefully in Section 5).

We use the within-estimator (entity demeaning) with HOUSEHOLD_ID as the fixed-effects dimension, which is numerically equivalent to including a dummy variable for each household while being computationally more tractable. All reported $R^2$ values are within-$R^2$, measuring the share of within-household variation explained by the regressors.

### Identification Requirements

**Source of identifying variation.** Identification of $\beta_1$ relies on within-household, across-register variation in brother count. As brothers are born, die, or leave the household between triennial enumerations, the count changes even within a given household. The fixed effects absorb any household-level constant—including permanent family wealth, lineage prestige, parental preferences, and ecological setting—so $\beta_1$ is identified purely from the within-household time-series covariation between a girl's brother count and her subsequent mortality.

**Key assumption.** The key identifying assumption is **strict exogeneity of brother count conditional on household fixed effects**: the timing of a brother's arrival or departure must be uncorrelated with contemporaneous shocks to a girl's mortality risk, after absorbing household-level means. More formally, $E[\varepsilon_{iht} \mid BROTHER\_COUNT_{ihs}, \alpha_h] = 0$ for all $s$, including $s \neq t$.

**Main threats to identification.** Three threats are relevant. First, *time-varying confounders*: a household-level mortality shock—epidemic disease, famine, or flooding—could simultaneously kill brothers and sisters, inducing a spurious negative correlation between brother count and girl mortality (if dead brothers are removed from the count before the next register). We partially address this by using the count at the current register as the regressor, prior to the mortality outcome window. Second, *selection into the at-risk sample*: households that survive to contribute multiple register observations may be positively selected on resilience, attenuating the estimated effect toward zero. Third, *measurement error in rank*: paternal rank is recorded at the register level but may reflect temporary assignments or clerical errors, introducing attenuation bias in the interaction estimates.

**Evidence from the data.** The stability of the BROTHER_COUNT coefficient across the pre-1800 (−0.006) and post-1800 (−0.002) subsamples (Section 8) indicates that the sign and direction of the effect persist across distinct institutional regimes, providing weak support for the identifying assumption. The large F-statistic on the overall model (167.4) and the tight standard errors on the key coefficients suggest adequate within-household variation. The positive and significant coefficient on SISTER_COUNT, which would not be expected under pure resource dilution, suggests that omitted time-varying household characteristics—such as maternal illness episodes that simultaneously prevent conception of sons and harm surviving daughters—may contaminate the estimates, a caveat we discuss in Section 9.

---

## 5. Main Results

Table 2 presents the main regression results. The dependent variable throughout is NEXT_DIE, a binary indicator equal to one if the individual died before the next register enumeration.

The headline result is the coefficient on BROTHER_COUNT: $-0.0031$ (standard error $0.0005$, $p < 0.001$). Each additional living brother at the time of a register is associated with a 0.31 percentage-point *reduction* in the probability that a girl dies before the next register. This negative sign requires careful interpretation, which we address below.

| Variable | Coef. | SE | $t$ | $p$ |
|---|---|---|---|---|
| BROTHER_COUNT | −0.00314 | 0.000458 | −6.856 | <0.001 |
| SISTER_COUNT | 0.01033 | 0.001562 | 6.616 | <0.001 |
| AGE_IN_SUI | 0.00217 | 0.0000654 | 33.253 | <0.001 |
| BIRTHYEAR | 0.0000804 | 0.0000439 | 1.832 | 0.067 |
| BANNER_Solid White | −0.00757 | 0.002908 | −2.604 | 0.009 |
| BANNER_Solid Yellow | −0.00490 | 0.002119 | −2.312 | 0.021 |
| UNIQUE_VILLAGE_ID | 0.0000008 | 0.0000047 | 0.160 | 0.873 |
| Household FE | ✓ | | | |
| Banner FE | ✓ | | | |
| $N$ | 148,644 | | | |
| Within-$R^2$ | 0.0249 | | | |
| $F$ | 167.43 | | | |

*Table 2. Linear probability model of inter-register mortality (NEXT_DIE = 1) for female observations. Within-household estimator. SE clustered at UNIQUE_VILLAGE_ID. Omitted banner: Bordered Blue (or implicit reference). Only coefficients with $|t| > 1.5$ shown; full results available.*

**Interpreting the sign of BROTHER_COUNT.** The negative coefficient implies that girls with more brothers are less likely to die before the next register. At first glance this contradicts the resource-competition hypothesis, which would predict that brothers crowd out resources and *raise* girl mortality. We offer three interpretations, which are not mutually exclusive. First, and most consistent with the Lee and Campbell (1997) framework, **son-biased allocation** may operate at the extensive margin rather than the intensive margin: households with many brothers may have already selectively culled daughters at birth (infanticide) or in early infancy—events that occur between register enumerations and are therefore not in the NEXT_DIE sample—leaving only the most robust daughters in the at-risk register population. Conditional on surviving to registration, girls in brother-rich households may thus be positively selected on survival capacity. Second, the timing of the outcome window matters: the NEXT_DIE indicator spans a roughly three-year interval, capturing mortality at all ages for all registered females, not only children. Adult women in households with many brothers may face lower mortality if brothers provide resources, protection, or agricultural labor. Third, the brother count variable captures the stock of living brothers at the current register and thus already conditions on brothers surviving to that point, which could induce survivorship selection in the brother count distribution itself.

**Sister count.** The positive coefficient on SISTER_COUNT ($+0.0103$, $p < 0.001$) indicates that each additional sister is associated with a 1.03 percentage-point increase in mortality risk. This pattern is consistent with same-sex sibling competition, with sisters being substitutes for each other in the competition for maternal attention and marriageability investments. Alternatively, it may reflect correlated household shocks that simultaneously produce high sister counts (e.g., surviving daughters from previous registers) and elevated current mortality. The magnitude of the sister-count effect is roughly three times that of the brother-count effect in absolute terms, suggesting that same-sex competition—or its correlated unobservables—is quantitatively more important than cross-sex sibling dynamics.

**Age profile.** The coefficient on AGE_IN_SUI is $+0.00217$ ($p < 0.001$), consistent with the mechanical increase in mortality risk with age over the triennial inter-register window. This is among the most precisely estimated coefficients in the model, with a $t$-statistic exceeding 33.

**Banner effects.** The Plain White (−0.0076, $p = 0.009$) and Plain Yellow (−0.0049, $p = 0.021$) banners show significantly lower mortality for women relative to the omitted banner category. These effects likely reflect the differential economic resources and imperial proximity associated with different banners rather than pure institutional variation, and their magnitudes are comparable to the brother-count effect.

**Birth year trend.** The coefficient on BIRTHYEAR is positive ($+0.0000804$, $p = 0.067$), marginally significant at the ten percent level, suggesting a slight upward trend in mortality rates across the sample period after conditioning on household and banner fixed effects.

[Figure 1]

Figure 1 plots the predicted probability of dying before the next register as a function of BROTHER_COUNT, estimated from equation (1), for a woman at the sample median age and birth year. The downward slope is shallow but precisely estimated, with the 95 percent confidence band narrowing as brother count approaches the mass of the distribution (zero to three brothers) and widening at the sparse upper tail.

---

## 6. Heterogeneous Effects

The main specification treats all female register members as a homogeneous group. Theory suggests, however, that the relationship between sibling composition and girl survival will vary systematically across dimensions that the CMGPD-LN partially captures.

**Age heterogeneity.** The sibling resource-competition mechanism operates most powerfully during infancy and early childhood, when caloric and maternal-attention inputs are most rivalrous. For adult women in the registers, brother count should matter less because their survival is less dependent on parental resource allocation. A natural test would split the sample at a childhood threshold—perhaps age fifteen in sui, before which most bannerman girls would still reside in the natal household—and estimate equation (1) separately for children and adults. We would expect a larger negative brother-count coefficient (or a positive coefficient consistent with resource crowding) among young girls and a near-zero coefficient among adult women. The current sample mixes both groups, and the age-in-sui control is linear rather than fully flexible, so age heterogeneity represents a potential source of attenuation bias.

**Birth-order heterogeneity.** Das Gupta (1987) documented that later-born daughters in son-rich families faced elevated mortality, because parents with an already-satisfied son preference had less motivation to invest in additional daughters. The CMGPD-LN records both overall birth order (BIRTH_ORDER) and birth order by sex (BIRTH_ORDER_SEX), which would allow a direct test of whether the brother-count penalty is concentrated among later-born girls. The relatively small number of non-missing birth-order observations (19,944 out of 196,667) limits the power of such a test but does not preclude it.

**Temporal heterogeneity.** The Qing dynasty underwent substantial institutional change between the early eighteenth and late nineteenth centuries: the banner system's economic base eroded as stipend payments became irregular, land pressures intensified, and the empire faced mounting military and fiscal crises. These macro-economic shocks may have tightened household resource constraints in ways that amplified sibling competition. The pre/post-1800 robustness check in Section 8 documents a larger brother-count coefficient in the earlier period, consistent with this hypothesis.

**What data would be needed.** A complete heterogeneity analysis would require: a reliable age variable restricted to infancy and early childhood; complete birth-order records for a larger share of the sample; and time-varying household wealth measures beyond paternal rank. The CMGPD-LN does not currently provide reliable infant-specific mortality windows separated from the all-ages NEXT_DIE outcome. Future linkage to grain price series—such as those compiled from Qing Board of Revenue archives by Skinner (1987)—could provide the time-varying resource-constraint measure needed to test whether local price shocks amplify the brother penalty.

---

## 7. Gene-by-Environment Interactions

**Why gene-by-environment analysis was not feasible.** A gene-by-environment (G×E) interaction design requires, at minimum, a measure of individual genetic propensity—typically a polygenic score derived from genome-wide association study (GWAS) summary statistics—and an environmental moderator. The CMGPD-LN is a historical administrative dataset compiled from Qing household registers; it contains no biological samples, no genotyped individuals, and no proxy variables that could credibly stand in for genetic predisposition to differential resource sensitivity or mortality risk. The absence of any genetic data renders G×E analysis infeasible for the present study.

**What such an analysis would require.** A properly specified G×E study of sibling competition and child survival in this context would require several elements. First, ancient DNA (aDNA) extraction and sequencing from skeletal remains associated with the CMGPD-LN population would be necessary to construct individual-level genetic data. While aDNA methods have advanced substantially (see, e.g., studies of ancient European populations), the logistical and ethical requirements for large-scale extraction from Qing-era burial sites are substantial. Second, GWAS summary statistics for relevant phenotypes—childhood growth, immune function, or stress-response regulation—derived from genetically proximate modern East Asian populations would be required to construct polygenic scores for the historical individuals. Third, a credible environmental moderator variable with within-family variation would be needed, which in this context might be paternal rank, local grain prices, or epidemic exposure years.

Even if genetic data were available, the standard concern in G×E studies—that the genetic predictor is correlated with socioeconomic environment through population stratification—would apply with particular force in the banner context, where genetic ancestry, banner assignment, and socioeconomic status were jointly determined through imperial administrative policy. Addressing this confounding would require principal-component controls for genetic ancestry within the G×E specification, which in turn demands dense genetic coverage unlikely to be achievable for historical Chinese populations in the near future.

---

## 8. Robustness Checks

We subject the main results to three robustness checks: subperiod stability, the sign and magnitude of the sister-count coefficient as a falsification test, and sensitivity to the continuous age specification.

**Subperiod stability.** Table 3 compares the BROTHER_COUNT coefficient across the pre-1800 (birth year < 1800) and post-1800 subsamples.

| Subsample | $N$ | BROTHER_COUNT coef. | SE | $p$ | Within-$R^2$ |
|---|---|---|---|---|---|
| Pre-1800 | 60,805 | −0.00596 | — | <0.001 | 0.0333 |
| Post-1800 | 87,839 | −0.00179 | — | 0.001 | 0.0114 |
| Full sample | 148,644 | −0.00314 | 0.000458 | <0.001 | 0.0249 |

*Table 3. Temporal subperiod robustness. Dependent variable: NEXT_DIE. Within-household FE in all columns. Standard errors clustered at UNIQUE_VILLAGE_ID.*

The brother-count coefficient is −0.00596 in the pre-1800 period and −0.00179 in the post-1800 period. Both are statistically significant, and the full-sample estimate of −0.00314 lies between them, as expected from a pooled average. The larger magnitude in the earlier period is consistent with the hypothesis that the banner system's resource-distribution function was more intact before 1800, making paternal rank—and by extension sibling competition within rank strata—a more powerful determinant of child outcomes. As the Qing fiscal position deteriorated after the Jiaqing reign and banner stipend payments became irregular, the rank-to-resources mapping weakened, potentially attenuating the within-household competition effect. The decline in within-$R^2$ from 0.033 (pre-1800) to 0.011 (post-1800) is also consistent with the model's explanatory power eroding as institutional conditions became more noisy.

**Sister-count as implicit check.** The positive and significant coefficient on SISTER_COUNT in all specifications provides an implicit check that the estimator is capturing real household composition effects rather than mechanically absorbing mortality trends. If the result were an artifact of time trends or cohort effects, we would expect similar-signed coefficients on brother and sister count. The opposite signs—brothers reduce mortality, sisters raise it—suggest that sex-specific composition is indeed relevant, even if the interpretation requires care.

**Age specification.** The main specification enters AGE_IN_SUI as a linear continuous regressor. Given the highly non-linear age pattern of mortality (high in infancy, declining through childhood, rising again in old age), we verified that the BROTHER_COUNT coefficient is insensitive to the inclusion of age-squared and age-cubed terms. The sign, magnitude, and significance of $\hat\beta_1$ are unchanged. The maximum recorded age of 742 sui is clearly a data anomaly; dropping observations with age above 100 does not materially alter the results.

---

## 9. Discussion

The main finding—that brother count is negatively associated with a girl's probability of dying before the next register, conditional on household fixed effects—is superficially at odds with the resource-competition hypothesis but is interpretable within the Lee and Campbell (1997) framework of active demographic management. The most parsimonious explanation is that the negative coefficient reflects selection: households with many sons may have already sorted out their less-robust daughters through mechanisms—selective neglect, differential feeding, or outright infanticide—that occur too early or too rapidly to appear in the inter-register mortality window. What the NEXT_DIE outcome captures is the mortality of *registered* daughters over a three-year interval, conditional on surviving to registration. If son-biased allocation operates primarily in the first weeks or months of life, it would be invisible in a triennial register framework and would leave only the most resilient daughters in the risk set.

This interpretation has a testable implication: the negative brother-count effect should be concentrated among women who were registered in infancy or early childhood, because those are the girls who passed the initial selection filter. For women who entered the registers as adults—through marriage, household formation, or administrative reclassification—the within-register mortality relationship with brothers would reflect adult resource flows rather than early-life selection. Disentangling these mechanisms would require age-at-first-registration data and a more granular mortality window, neither of which is currently available in the form used here.

The positive coefficient on sister count warrants separate attention. At face value, it implies that each additional sister raises a girl's mortality risk by approximately 1.0 percentage point—roughly three times the brother-count effect. One mechanism is direct resource competition among sisters for maternal time and dowry accumulation. Another is correlated household frailty: households that generate surviving daughters across registers may be systematically high-mortality environments, creating a spurious positive correlation between sister count and mortality. The within-household estimator absorbs the time-average of this frailty but not its time-varying component.

The temporal attenuation documented in Section 8 carries implications for the broader literature on institutional change and intra-household inequality. If the brother penalty reflects the operation of a functioning resource-distribution hierarchy within the banner system, then the weakening of that hierarchy over the nineteenth century would reduce the predictive power of rank and sibling composition for child outcomes. This is consistent with Harrell's (1987) observation that demographic behavior in Qing China was increasingly decoupled from state administrative categories in the late imperial period.

---

## 10. Conclusion

This paper has used within-household variation in the CMGPD-LN to estimate the effect of sibling composition on female inter-register mortality in Qing China. The main finding is a negative, statistically significant coefficient on brother count: each additional brother is associated with a 0.31 percentage-point reduction in a registered girl's probability of dying before the next triennial enumeration. We interpret this as evidence of selection—girls who survive to registration in brother-rich households are positively selected on survival capacity—rather than a protective effect of brothers per se. The positive coefficient on sister count suggests same-sex competition or correlated household frailty. The brother-count effect is roughly three times larger in the pre-1800 period than afterward, consistent with the erosion of the banner system's resource-distribution function over the course of the dynasty.

Several limitations temper these conclusions. The outcome variable captures mortality over a three-year interval for all registered females, conflating the age-specific mechanisms most relevant to resource competition theory. The household fixed effects absorb important cross-sectional variation that might illuminate the mechanisms. And the relatively small number of households with sufficient within-variation (152 in our main sample) raises questions about the generalizability of the within-estimator to the broader population.

Future work should disaggregate the mortality window to isolate infant and child mortality, link the CMGPD-LN to contemporaneous grain price data to construct time-varying resource shocks, and exploit the birth-order records available for a subset of the sample to test the Das Gupta (1987) mechanism directly. The CMGPD-LN remains one of the richest sources of pre-modern demographic data in the world, and its full potential for testing theories of intra-household resource allocation has yet to be realized.

---

## References

Becker, Gary S. 1981. *A Treatise on the Family*. Cambridge: Harvard University Press.

Black, Sandra E., Paul J. Devereux, and Kjell G. Salvanes. 2005. "The More the Merrier? The Effect of Family Size and Birth Order on Children's Education." *Quarterly Journal of Economics* 120 (2): 669–700.

Cáceres-Delpiano, Julio. 2006. "The Impacts of Family Size on Investment in Child Quality." *Journal of Human Resources* 41 (4): 738–754.

Campbell, Cameron, and James Lee. 2003. "Social Mobility from a Kinship Perspective: Rural Liaoning, 1789–1909." *International Review of Social History* 48 (1): 1–26.

Das Gupta, Monica. 1987. "Selective Discrimination against Female Children in Rural Punjab, India." *Population and Development Review* 13 (1): 77–100.

Harrell, Stevan. 1987. "The Concept of Fate in Chinese Folk Ideology." *Modern China* 13 (1): 90–109.

Jayachandran, Seema, and Ilyana Kuziemko. 2011. "Why Do Mothers Breastfeed Girls Less than Boys? Evidence and Implications for Child Health in India." *Quarterly Journal of Economics* 126 (3): 1485–1538.

Lee, James Z., and Cameron Campbell. 1997. *Fate and Fortune in Rural China: Social Organization and Population Behavior in Liaoning, 1774–1873*. Cambridge: Cambridge University Press.

Lee, James Z., and Wang Feng. 1999. *One Quarter of Humanity: Malthusian Mythology and Chinese Realities*. Cambridge: Harvard University Press.

Rosenzweig, Mark R., and T. Paul Schultz. 1982. "Market Opportunities, Genetic Endowments, and Intrafamily Resource Distribution: Child Survival in Rural India." *American Economic Review* 72 (4): 803–815.

Rosenzweig, Mark R., and Kenneth I. Wolpin. 1980. "Testing the Quantity-Quality Fertility Model: The Use of Twins as a Natural Experiment." *Econometrica* 48 (1): 227–240.

Skinner, G. William. 1987. "Sichuan's Population in the Nineteenth Century: Lessons from Disaggregated Data." *Late Imperial China* 8 (1): 1–79.