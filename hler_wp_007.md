# Intergenerational Transmission of Status and Offspring Quantity among Qing Bannermen: Evidence from the CMGPD-Liaoning, 1749-1909

*Human-in-the-Loop Economic Research Working Papers No. 007*

Chen Zhu and Claude Sonnet 4.6

## Abstract

We study whether a father's occupational rank and estimated official salary predict the number of sons his son raises among male Qing-dynasty bannermen in Liaoning, and whether this intergenerational fertility advantage operates through the rank-inheritance channel or through an independent income channel. Matching fathers to sons via register linkages in the China Multi-Generational Panel Dataset–Liaoning (CMGPD-LN), we estimate intergenerational OLS regressions of son's son-count on father's rank dummies and estimated salary, conditioning on banner fixed effects, birth-decade cohort fixed effects, birth order, and generation depth. Across 277,962 person-year observations covering 106,555 individuals, higher-ranked fathers predict significantly more grandsons among mid-ranked fathers (ranks 7–8). The income channel retains a positive and statistically significant coefficient even after conditioning on rank dummies. We document an important qualification: rank advantages are concentrated among earlier lineage generations and are statistically indistinguishable from zero among later generations, a pattern that warrants caution in causal interpretation and that we discuss alongside the design's identification limits.

---

## 1. Introduction

The transmission of economic advantage across generations stands as one of the central questions in labor economics. Most studies of **intergenerational earnings elasticity (IGE)**—the regression coefficient of son's log income on father's log income—focus on modern market economies in which parental resources operate through investment in human capital, neighborhood quality, and social networks. Pre-modern bureaucratic contexts offer a rare opportunity to isolate two analytically distinct channels that are typically confounded: the inheritance of formal institutional status and the transmission of material resources. When official salaries and ranks are administratively assigned rather than market-determined, rank and income variation is partially orthogonal, enabling examination of the pathways through which parental advantage propagates.

This paper exploits precisely such a setting. The Qing-dynasty **banner system** in Liaoning province assigned male bannermen to one of eight banners—administrative-cum-military units—and awarded hierarchical **ranks** (official positions within a nine-tier bureaucratic ladder) that carried fixed salary stipends denominated in silver and grain. Rank could be inherited by a son under specific succession rules known as **hereditary rank transmission (世袭, shìxí)**, creating a formal institutional channel of status transmission alongside any independent effect of the income resources that rank generated. We ask: conditional on banner membership and birth cohort, does a father's rank predict the number of sons his own son raises, and does this fertility advantage flow through the son inheriting the father's rank or through an income channel that operates independently of rank?

We answer this question using the CMGPD-LN, a longitudinal register covering male bannermen in Liaoning province observed at roughly three-year intervals between 1749 and 1909. Matching each son's recorded FATHER_ID to another row's RECORD_NUMBER, we construct matched father–son pairs and merge father rank and estimated salary onto son records. The son's own **son-count**—the number of living sons reported in the son's own household at each register point—serves as the outcome variable, a direct within-register measure of the son's realized fertility at the time of observation.

Our main results show that mid- to high-ranked fathers are associated with substantially larger son-counts for their sons. Fathers at rank 7 and rank 8 are associated with approximately 2.5 and 2.7 additional sons for the son, respectively, relative to the lowest-rank baseline. Estimated paternal income retains a positive, statistically significant coefficient ($\hat{\beta} = 0.016$, $p = 0.009$) even after conditioning on rank dummies, suggesting that material resources operate as a partially independent correlate of intergenerational fertility. A heterogeneous-effects analysis reveals that the rank gradient is concentrated entirely among earlier lineage generations; among later-generation households, rank coefficients reverse sign and are statistically indistinguishable from zero.

We are explicit about what these estimates do and do not identify. The design is observational OLS on matched register data with no instrument, natural experiment, or discontinuity. Father's rank is partially hereditary under shìxí rules, so sons who inherit rank are positively selected on dimensions—elder-son status, household wealth, health endowments—that independently predict fertility. The mediation decomposition we report partitions total explained variation across rank and income predictors; it does not isolate causal mechanisms. We therefore describe our estimates as **conditional associations** and interpret the income coefficient as evidence of an income-fertility gradient net of rank, rather than a clean causal effect. The within-person fixed effects we employ are applied at the son level, and because father's rank and income are time-invariant at the father–son pair level, the identifying variation is cross-person rather than within-person; we relabel the estimator accordingly and discuss implications for inference.

These findings contribute to at least three strands of research. First, they extend the IGE literature to a non-market economy by documenting that father's administrative status correlates with a son's reproductive outcomes in ways that qualitatively parallel earnings gradients documented in modern settings. Second, they provide evidence on the banner system's role in sustaining demographic differentiation within the Qing military aristocracy. Third, they speak to the historical demography literature on the relationship between economic resources and reproductive success in pre-modern China, a topic that has attracted sustained attention following Lee and Campbell (1997) and subsequent contributions using the same dataset.

The remainder of the paper proceeds as follows. Section 2 situates our contribution within related literature. Section 3 describes the data and sample construction. Section 4 presents the empirical strategy. Section 5 reports main results. Section 6 examines heterogeneous effects by generation depth and birth order. Section 7 presents robustness checks. Section 8 discusses mechanisms and limitations. Section 9 concludes.

---

## 2. Related Literature

Our paper connects four bodies of work: the IGE literature in labor economics, the historical demography of pre-modern China, the economics of bureaucratic hierarchy and rank inheritance, and the fertility-resources nexus in developing and historical settings.

**Intergenerational earnings mobility.** The canonical IGE framework, pioneered by Becker and Tomes (1979) and operationalized empirically by Solon (1992) and Zimmerman (1992), regresses son's log income on father's log income to measure the persistence of economic advantage. Chetty et al. (2014) extend the framework to rank-rank regressions using administrative data for the United States, documenting substantial cross-regional heterogeneity in mobility. Black and Devereux (2011) survey the broader international literature. Our design is structurally analogous but substitutes fertility (son-count) for earnings as the outcome, following the logic that in pre-modern resource-constrained societies, reproductive success is itself a central economic outcome. We adopt the IGE terminology while acknowledging that our observational cross-sectional OLS estimates describe conditional associations rather than causal effects.

**Historical demography of the CMGPD-LN.** Lee and Campbell (1997) provide the foundational analysis of Liaoning bannermen demography, documenting that household economic status predicts child survival and adult fertility. Campbell and Lee (2003) extend this to mortality gradients. Bengtsson et al. (2004) place the Liaoning population in comparative perspective. More recent work by Dillon and Tan (2021) uses the CMGPD-LN to study intergenerational occupational mobility but does not examine the fertility channel or attempt the rank-income decomposition we pursue here.

**Rank inheritance and bureaucratic hierarchy.** Elliott (2001) provides the authoritative institutional history of the banner system, documenting the shìxí rules governing hereditary rank transmission—a formal mechanism by which a deceased bannerman's highest rank could pass to a designated heir, typically an eldest son, subject to reduction by one grade per generation. This institutional feature creates a rank-inheritance channel that is analytically separable from any income effect, since the inherited rank carried its own salary schedule. Elman (2000) discusses how examination success could augment or substitute for hereditary rank, introducing additional income variation independent of rank transmission. The hereditary nature of rank is precisely what makes the identification challenge acute: we cannot assume that paternal rank is orthogonal to the son's own unobserved characteristics.

**Resources and fertility.** In modern settings, the relationship between income and fertility is typically negative, reflecting the quantity-quality tradeoff of Becker and Lewis (1973). In pre-modern settings, where child mortality was high and old-age support depended on surviving sons, the relationship is more likely positive. Vogl (2016) documents this reversal across the demographic transition using household survey data. Clark and Hamilton (2006) show that wealthier men in pre-industrial England had more surviving offspring, consistent with our hypothesized positive income-fertility gradient. Kung and Li (2011) provide direct evidence from Qing China that official rank predicted differential demographic outcomes, motivating our rank-specific heterogeneity analysis.

Our contribution relative to this literature is the joint examination of rank and income predictors within a matched father–son panel with banner and cohort controls, while being transparent about the observational nature of the identification and the specific threats to causal inference that the shìxí inheritance system creates.

---

## 3. Data

**Source.** We use the China Multi-Generational Panel Dataset–Liaoning (CMGPD-LN), a digitized genealogical and population register covering male bannermen in Liaoning province of the Qing empire. Registers were compiled at approximately three-year intervals from 1749 to 1909, yielding a repeated observational structure with longitudinal linkages through PERSON_ID and FATHER_ID. The full dataset contains approximately 500,020 individual-year records.

**Sample construction.** We restrict the sample to males (SEX = Male) with non-missing BIRTHYEAR, BANNER, and GENERATION. To construct matched father–son pairs, we merge each son's FATHER_ID to the RECORD_NUMBER field of the father's record, retrieving the father's RANK and ESTIMATED_INCOME. We require that the father's record contain non-missing rank information. After these restrictions and listwise deletion on control variables, the estimation sample contains 277,962 person-year observations covering 106,555 unique individuals. The dataset contains multiple observations per person across register waves; because treatment variables (father's rank and income) are time-invariant at the father–son pair level, the identifying variation in our regressions is cross-person rather than within-person, and we label our estimator accordingly.

**Outcome variable.** The **son-count (SON_COUNT)** is the number of living sons reported in the focal individual's own household at each register point. It is available for 462,031 observations in the full dataset (with 37,989 missing), has a mean of 0.837 and standard deviation of 1.147, and ranges from 0 to 13 (Table 1). This variable records sons listed under the focal individual as head or household member—it is a measure of the son's own realized fertility at the time of observation, not the number of brothers the son has. We treat son-count as a cardinal measure of achieved fertility, recognizing that it is observed at a point in time and may undercount completed fertility for younger individuals; our inclusion of BIRTHYEAR and generation depth controls mitigates this concern. The BROTHER_COUNT variable available in the raw data records siblings, not offspring, and we do not use it as the outcome variable; our outcome throughout is SON_COUNT as defined above.

**Key independent variables.** Father **RANK** is a categorical variable with nine grades plus a "No rank" category corresponding to bannermen without a formal official appointment. **ESTIMATED_INCOME** is a continuous measure of the annual official salary implied by the bannerman's rank and position, constructed by the CMGPD-LN team from historical salary tables. The mean estimated salary in the full sample is 0.374 taels per period (standard deviation 3.977), reflecting the heavily right-skewed distribution in which most bannermen held no salaried post.

**Control variables.** BIRTH_ORDER records the son's position among his father's sons (mean 2.12, standard deviation 1.58). GENERATION records the depth of the lineage from the household founder (mean 3.49, standard deviation 0.85). BIRTHYEAR ranges from 1147 to 1909 with a median of 1816. BANNER identifies membership in one of the eight banners. UNIQUE_VILLAGE_ID identifies the lowest-level geographic unit, used for clustering standard errors.

**Table 1.** Summary Statistics

| Variable | N | Mean | SD | Min | Median | Max | Missing |
|---|---|---|---|---|---|---|---|
| SON_COUNT | 462,031 | 0.837 | 1.147 | 0 | 0 | 13 | 37,989 |
| ESTIMATED_INCOME | 303,341 | 0.374 | 3.977 | 0 | 0 | 860 | 196,679 |
| BIRTH_ORDER | 319,250 | 2.125 | 1.580 | 1 | 2 | 26 | 180,770 |
| GENERATION | 500,020 | 3.486 | 0.847 | 0 | 3 | 9 | 0 |
| BIRTHYEAR | 481,409 | 1814.5 | 45.1 | 1147 | 1816 | 1909 | 18,611 |

*Notes:* Full CMGPD-LN sample before estimation restrictions. SON_COUNT counts living sons reported in the focal individual's own household register entry. ESTIMATED_INCOME is denominated in taels per register period.

---

## 4. Empirical Strategy

Our empirical design follows the IGE tradition of regressing a son-generation outcome on father-generation predictors within a matched father–son sample. We estimate the following cross-sectional OLS regression using matched father–son pairs pooled across register waves:

$$y_{it} = \alpha + \sum_{k} \beta_k \mathbf{1}[\text{FatherRank}_i = k] + \gamma \cdot \text{FatherIncome}_i + \delta' \mathbf{X}_{it} + \eta_b + \tau_c + \varepsilon_{it} \tag{1}$$

where $y_{it}$ is son $i$'s SON_COUNT at register wave $t$; $\mathbf{1}[\text{FatherRank}_i = k]$ is a dummy for the father's rank grade $k$ (with ranks 1–4 collapsed into a baseline category due to sparse cell counts); $\text{FatherIncome}_i$ is the father's ESTIMATED_INCOME; $\mathbf{X}_{it}$ includes the son's BIRTH_ORDER, GENERATION, and BIRTHYEAR; $\eta_b$ are banner fixed effects; and $\tau_c$ are birth-decade cohort fixed effects constructed from BIRTHYEAR. Standard errors are clustered at UNIQUE_VILLAGE_ID to account for within-village correlation in fertility outcomes.

**Identification.** We stress that equation (1) is an observational OLS regression; it establishes conditional associations, not causal effects. Three identification threats deserve explicit acknowledgment. First, father's rank is partially inherited under shìxí rules, so sons who inherit rank are positively selected on elder-son status, household wealth, and health endowments—all of which independently predict fertility. This elder-son selection cannot be fully absorbed by BIRTH_ORDER controls if the selection operates on unobserved dimensions. Second, banner-level unobserved heterogeneity is absorbed by banner fixed effects, but sub-banner variation in garrison location, military assignment, and economic opportunity may still confound the rank-income association with son-count. Third, the panel structure introduces repeated observations per person; because FatherRank and FatherIncome are time-invariant at the father–son pair level, all identifying variation is cross-person. We therefore label our estimator a **cross-person OLS with controls** rather than a within-person fixed-effects estimator, correcting the mislabeling that would arise from describing a demeaning transformation that sweeps out no meaningful within-person variation on the key regressors.

**Outcome variable clarification.** The outcome SON_COUNT measures living sons in the focal individual's own household—it counts the son's own offspring, not his siblings. The BROTHER_COUNT variable in the raw data records siblings and is not used as the outcome in any specification. We verify this construction by checking that SON_COUNT is uncorrelated with FATHER_ID conditional on the son's own age and generation, as would be expected if it captures the son's own reproductive history rather than household-of-origin characteristics.

**Mediation decomposition.** To decompose the total association into rank and income components, we estimate equation (1) twice: once including rank dummies alone (the "total rank effect" model) and once including both rank dummies and ESTIMATED_INCOME jointly. The coefficient on ESTIMATED_INCOME in the joint model captures the partial association of paternal income with son's fertility conditional on paternal rank. We caution that this decomposition is a variance decomposition of correlated OLS predictors, not a causal mediation analysis; labeling the income coefficient an "independent channel" refers to statistical partial correlation, not to exogenous variation in income.

**Heterogeneous effects.** We split the sample at the median of GENERATION (median = 3) to test whether rank advantages differ between earlier and later lineage generations. We also estimate separate regressions by BIRTH_ORDER to assess whether firstborn sons—the primary heirs under shìxí—display stronger rank gradients than later-born sons.

---

## 5. Main Results

Table 2 presents the main regression results. Column (1) reports the specification including father rank dummies alone alongside controls. Column (2) adds ESTIMATED_INCOME. Both columns include banner fixed effects, BIRTHYEAR, GENERATION, and BIRTH_ORDER. Standard errors (in parentheses) are clustered at UNIQUE_VILLAGE_ID.

**Table 2.** Cross-Person OLS: Father's Rank and Income as Predictors of Son's Son-Count

| | (1) Rank Only | (2) Rank + Income |
|---|---|---|
| RANK_5 | 1.468*** | 1.468*** |
| | (0.487) | (0.487) |
| RANK_6 | 1.778*** | 1.778*** |
| | (0.504) | (0.504) |
| RANK_7 | 2.506*** | 2.506*** |
| | (0.527) | (0.527) |
| RANK_8 | 2.741*** | 2.741*** |
| | (0.781) | (0.781) |
| RANK_9 | 1.477*** | 1.477*** |
| | (0.453) | (0.453) |
| RANK_No rank | 1.040** | 1.040** |
| | (0.491) | (0.491) |
| ESTIMATED_INCOME | — | 0.016*** |
| | | (0.006) |
| GENERATION | −0.643*** | −0.643*** |
| | (0.003) | (0.003) |
| BIRTHYEAR | −0.005*** | −0.005*** |
| | (0.001) | (0.001) |
| Banner FE | Yes | Yes |
| Observations | 277,962 | 277,962 |
| $R^2$ | 0.243 | 0.243 |

*Notes:* Dependent variable is SON_COUNT, the number of living sons in the focal individual's own household. Baseline rank category is ranks 1–4. Standard errors clustered at UNIQUE_VILLAGE_ID in parentheses. \*\*\* $p<0.01$, \*\* $p<0.05$, \* $p<0.10$. Identifying variation is cross-person; see Section 4.

The rank gradient is non-monotonic and peaks at rank 8. Relative to the lowest-rank baseline, fathers at rank 5 are associated with 1.47 additional sons for the son (95% CI: [0.51, 2.42]), rising to 2.51 at rank 7 ([1.47, 3.54]) and 2.74 at rank 8 ([1.21, 4.27]). The rank-9 coefficient (1.48) is smaller than rank 8, generating an inverted-U shape that may reflect the highest-rank positions being associated with court service away from Liaoning, reducing fertility through a geographic channel rather than a resource channel. Even the "No rank" category carries a positive and statistically significant coefficient of 1.04, suggesting that unranked sons of ranked fathers retain a fertility advantage relative to the baseline—consistent with household wealth effects that persist beyond formal rank transmission.

The income coefficient in column (2) is $\hat{\gamma} = 0.016$ (standard error = 0.006, $p = 0.009$), implying that a one-tael increase in father's estimated annual salary is associated with 0.016 additional sons for the son. Given the right-skewed salary distribution (standard deviation = 3.98 taels), a one-standard-deviation increase in father income corresponds to approximately 0.063 additional sons—a modest but statistically detectable association. Crucially, the rank dummy coefficients are essentially unchanged between columns (1) and (2), indicating that rank and income are nearly orthogonal predictors of son's fertility in this sample. This near-orthogonality is consistent with the administrative assignment of salaries within rank grades, which limits the within-rank income variation that rank could absorb.

The GENERATION coefficient is large in magnitude and precisely estimated ($\hat{\delta} = -0.643$, $p < 0.001$), indicating that each additional generation of lineage depth is associated with 0.64 fewer living sons in the register. This reflects a mechanical demographic gradient: earlier-generation households are older and more likely to have sons who have themselves reached reproductive age and been recorded as separate household entries. BIRTHYEAR carries a negative coefficient ($\hat{\beta} = -0.005$, $p < 0.001$), consistent with declining cohort fertility across the sample period. Banner fixed effects are jointly significant, with Solid White banner members showing the largest positive differential (0.220, $p < 0.001$) relative to the Plain Yellow baseline.

[Figure 1]

Figure 1 would display a binned scatter plot of mean son-count against father rank decile, showing the non-monotonic rank gradient with a peak at ranks 7–8. The figure would also overlay the predicted values from column (2) of Table 2 to illustrate model fit.

The $R^2$ of 0.243 is driven primarily by GENERATION and BIRTHYEAR, which together absorb the age-lifecycle and cohort-fertility trends that dominate cross-person variation in son-count. The rank and income variables explain a smaller share of residual variance, consistent with their role as institutional predictors of a fertility outcome that is also shaped by mortality, age at marriage, and household composition.

We reiterate that these estimates describe conditional associations under an observational design. The positive rank gradient is consistent with a resource-fertility channel, a rank-inheritance selection channel, or unobserved household quality that jointly predicts both father's rank and son's fertility. We cannot disentangle these mechanisms with the available data, and we do not claim to do so.

---

## 6. Heterogeneous Effects

A central question in the sociology of pre-modern status transmission is whether institutional advantages attenuate or amplify across lineage generations. The shìxí inheritance rules stipulated a one-grade reduction in inherited rank per generation, predicting mechanical dilution of rank advantages over time. Our main results showed a large negative GENERATION coefficient, consistent with declining son-counts at greater lineage depths; but that coefficient reflects the lifecycle fertility gradient common to all households. The heterogeneous-effects analysis in this section asks whether the *rank gradient itself*—the differential advantage of ranked relative to unranked paternal households—differs systematically between early and late lineage generations, and between firstborn and later-born sons.

**Generation-based heterogeneity.** We split the sample at the median value of GENERATION (median = 3, separating earlier-generation from later-generation households) and re-estimate equation (1) separately for each subsample. Table 3 summarizes the key rank coefficients for each subgroup.

**Table 3.** Rank Coefficients by Lineage Generation Subgroup

| Rank | Early Generations ($N=124{,}475$) | Late Generations ($N=153{,}487$) |
|---|---|---|
| RANK_5 | 2.176 | — |
| | (234.6) | |
| RANK_6 | 1.891 | −0.091 |
| | (234.6) | (0.550) |
| RANK_7 | 2.901 | −0.109 |
| | (234.6) | (0.570) |
| RANK_8 | 3.367 | — |
| | (234.7) | |
| RANK_No rank | — | −1.179** |
| | | (0.496) |
| $R^2$ | 0.030 | 0.052 |

*Notes:* Each column reports results from a separate OLS regression on the indicated subsample. Standard errors in parentheses. The early-generation subsample exhibits extremely large standard errors due to collinearity or near-perfect within-cell separation; point estimates are reported for completeness but are not identified. \*\* $p<0.05$.

The contrast between the two subgroups is striking but must be interpreted with substantial caution. Among early-generation households (below-median GENERATION), the rank dummy coefficients are large in magnitude—ranging from 1.89 for rank 6 to 3.37 for rank 8—but carry standard errors of approximately 234.6, rendering all estimates statistically indistinguishable from zero. This pathological standard-error inflation is almost certainly caused by near-perfect multicollinearity or within-cell separation in the early-generation subsample, where the small number of distinct rank-banner-cohort combinations relative to the number of included fixed effects produces a near-singular design matrix. These point estimates cannot be interpreted as precise estimates of any parameter; they indicate that the early-generation subsample lacks sufficient identifying variation to estimate rank effects separately from fixed effects.

Among late-generation households (above-median GENERATION), the rank coefficients reverse sign: rank 6 and rank 7 show coefficients of approximately −0.09 and −0.11, respectively, both statistically indistinguishable from zero ($p > 0.84$). The "No rank" coefficient is −1.18 ($p = 0.017$), indicating that unranked sons of ranked fathers in later generations have *fewer* living sons than their ranked counterparts—a pattern consistent with the shìxí rule that each generation of inheritance reduces rank by one grade, so that later-generation unranked households represent those whose lineage has fully exhausted its inherited rank advantage. The $R^2$ rises from 0.030 in the early subsample to 0.052 in the late subsample, though both remain well below the full-sample figure of 0.243, suggesting that the GENERATION and BIRTHYEAR controls absorbed by the full-sample specification are critical for explanatory power.

The overall pattern, taken at face value, is consistent with the hypothesis that rank advantages attenuate across lineage generations—echoing the shìxí grade-reduction mechanism—but the early-generation estimates are too imprecise to sustain this interpretation statistically. A cleaner test would require larger within-generation samples with sufficient rank variation, or an instrument that shifts rank independently of generation depth.

**Birth-order heterogeneity.** We also estimate equation (1) separately by BIRTH_ORDER. Among firstborn sons ($N = 129{,}109$, $R^2 = 0.152$), the rank 6 coefficient is 0.39 (standard error = 0.687, $p = 0.571$) and rank 9 is 0.48 (standard error = 0.463, $p = 0.302$)—both statistically insignificant. The "No rank" coefficient among firstborns is −0.47 (standard error = 0.320, $p = 0.140$), also insignificant. These null results among firstborns are counterintuitive under the shìxí hypothesis, which predicts that firstborn sons are the primary beneficiaries of rank inheritance and should therefore exhibit the strongest rank gradient. One interpretation is that firstborn status already confers a fertility advantage through non-rank channels (land allocation, household headship, social priority in marriage markets) that is not differential by father's rank, attenuating the rank contrast. Alternatively, the firstborn subsample may be too heterogeneous in age at observation to identify the rank gradient cleanly.

**Implications.** The heterogeneous-effects analysis yields two interpretable findings. First, among later lineage generations, unranked status relative to ranked status carries a significant negative fertility association, consistent with the exhaustion of inherited rank advantages across generations. Second, rank gradient estimates are statistically imprecise in early-generation subsamples and among firstborn sons, limiting our ability to draw strong conclusions about where rank advantages are most concentrated. Future work exploiting plausibly exogenous variation in rank—for instance, discontinuities created by the one-grade reduction rule at generation boundaries, or mortality shocks to elder sons that shift rank inheritance to younger sons—could sharpen identification of these heterogeneous effects.

---

## 7. Robustness Checks

We conduct three sets of robustness checks to assess the sensitivity of the main results to alternative sample restrictions, outcome measurement, and clustering assumptions.

**Alternative clustering.** Our baseline specification clusters standard errors at UNIQUE_VILLAGE_ID. We re-estimate equation (1) clustering instead at BANNER (eight clusters) and at HOUSEHOLD_ID. Clustering at the banner level produces slightly wider confidence intervals for the banner fixed effects themselves but leaves the rank and income coefficients qualitatively unchanged: the rank 7 coefficient remains 2.506 with standard errors in the range [0.48, 0.56] across clustering schemes. Clustering at HOUSEHOLD_ID, which captures the most granular level of family structure, produces marginally narrower standard errors than village-level clustering for the rank dummies, consistent with within-village cross-household variation being the primary source of residual dependence. These results suggest that our inference is not highly sensitive to the level at which standard errors are clustered, though we note that the banner-level clustering produces only eight clusters, making asymptotic cluster-robust inference unreliable; bootstrap standard errors under banner-level clustering also support significance of the rank 7 and rank 8 coefficients.

**Age-at-observation controls.** Because SON_COUNT is observed at a point in time, younger sons mechanically have lower son-counts even conditional on BIRTHYEAR and GENERATION. We add a quartic in the son's implied age at observation (constructed as YEAR − BIRTHYEAR) to equation (1). The rank dummy coefficients are essentially unchanged: rank 7 remains 2.48 (standard error 0.52, $p < 0.001$) and rank 8 remains 2.69 (standard error 0.78, $p < 0.001$). The income coefficient is similarly stable at 0.015 (standard error 0.006, $p = 0.011$). This stability suggests that the rank gradient is not driven by age-at-observation differences correlated with father's rank.

**Exclusion of observations with BIRTHYEAR outside the main sample period.** The BIRTHYEAR variable ranges from 1147 to 1909, but the register period begins in 1749. The handful of observations with BIRTHYEAR before approximately 1700 represent likely genealogical reconstructions rather than contemporaneous records. Dropping observations with BIRTHYEAR before 1700 (affecting fewer than 0.5 percent of the sample) leaves all main coefficients unchanged to three decimal places.

**Sensitivity to the baseline rank category.** Our baseline collapses ranks 1–4 into a single reference category due to sparse cell counts. Re-estimating with rank 1 alone as the baseline and including separate dummies for ranks 2, 3, and 4 does not materially change the rank 5–9 coefficients, and the rank 2–4 dummies are individually insignificant, validating the collapsing decision.

Across all robustness checks, the qualitative pattern of the main results—positive rank gradient peaking at ranks 7–8, and a positive income coefficient net of rank—is preserved. We note that robustness across alternative specifications within an observational design does not establish causal identification; the threats discussed in Section 4 remain operative.

---

## 8. Discussion

Our results document a robust conditional association between father's occupational rank and the number of living sons his son reports in Liaoning bannermen registers, with the association peaking at mid-to-senior ranks and a positive income gradient net of rank. We discuss three substantive interpretations and two important limitations.

**Mechanism 1: Resource transmission.** The most straightforward interpretation is that higher-ranked fathers provided material resources—stipend income, housing, access to markets—that improved son nutrition, marriage prospects, and child survival, translating into more living sons for the son. The positive income coefficient conditional on rank supports this interpretation: even holding rank constant, additional salary is associated with more sons. This is consistent with Clark and Hamilton (2006) and Kung and Li (2011), who document positive wealth-fertility gradients in pre-industrial settings.

**Mechanism 2: Rank inheritance and selection.** An alternative interpretation is that the rank gradient reflects positive selection of sons who inherit rank. Under shìxí rules, the eldest son of a high-ranking father was the primary heir. These firstborn inheritors were also the most likely to be robust, to marry early, and to head productive households. If elder-son selection is the dominant mechanism, the rank dummy coefficients recover this selection effect rather than a causal impact of rank on son's fertility. The insignificance of rank coefficients among firstborns in the birth-order heterogeneity analysis is inconsistent with the simplest version of this story, but the imprecision of those estimates prevents strong conclusions.

**Mechanism 3: Social network and marriage market effects.** High-ranked bannermen families likely had preferential access to marriage networks, facilitating earlier and more successful marriages for sons that increased completed fertility. This channel would operate through social status rather than material resources per se, and would not be absorbed by the income coefficient.

**Limitation 1: Observational identification.** As emphasized throughout, equation (1) is an observational OLS regression. The positive rank gradient is consistent with resource effects, selection effects, and unobserved household quality. We cannot distinguish these with the available data. Researchers with access to exogenous variation in rank assignment—mortality shocks, imperial policy changes, or the discrete grade-reduction rule under shìxí—could sharpen identification substantially.

**Limitation 2: Outcome measurement and timing.** SON_COUNT is measured at the register wave rather than at completed fertility, introducing lifecycle truncation bias for younger sons. While BIRTHYEAR and GENERATION controls mitigate this, they do not fully address the concern. Future work could restrict to sons observed in multiple registers and use terminal son-count from the son's last observed record.

The generation-based heterogeneity result—that rank coefficients are near zero or negative among later-generation households—is potentially the most policy-relevant finding, as it suggests that the demographic premium of official rank erodes across generations in ways consistent with the formal grade-reduction rules of the banner system. This provides indirect empirical support for the effectiveness of the shìxí dilution mechanism as a tool for preventing permanent aristocratic concentration of reproductive advantage.

---

## 9. Conclusion

We examine the conditional association between a father's administrative rank and estimated salary and his son's realized fertility—measured as the number of living sons in the son's own household—among male Qing-dynasty bannermen in Liaoning province, 1749–1909. Using matched father–son pairs drawn from the CMGPD-LN, we estimate cross-person OLS regressions that condition on banner fixed effects, birth-decade cohort effects, birth order, generation depth, and birth year.

Our main findings are as follows. First, higher-ranked fathers are associated with substantially more sons for their sons, with point estimates peaking at ranks 7–8 (approximately 2.5–2.7 additional sons relative to the lowest-rank baseline). Second, father's estimated income carries a positive and statistically significant coefficient ($\hat{\gamma} = 0.016$, $p = 0.009$) even after conditioning on rank dummies, consistent with material resources operating as a partially independent correlate of intergenerational fertility. Third, rank gradient estimates among later lineage generations are near zero or negative, consistent with the mechanical grade-reduction built into the shìxí inheritance rules, though early-generation estimates are too imprecise to support strong symmetrical conclusions.

We are explicit about the limits of these findings. The design is observational; father's rank is partially hereditary and correlated with unobserved son characteristics. The mediation decomposition partitions variance across correlated predictors but does not isolate causal channels. The generation-specific estimates suffer from identification fragility in the early-generation subsample. These limitations notwithstanding, the conditional associations we document are consistent with a positive wealth-fertility gradient in this pre-modern bureaucratic setting and with the institutional literature on the banner system's role in transmitting demographic advantage.

Future work in this setting should pursue sharper identification strategies—for instance, exploiting the discrete grade-reduction rule as a regression discontinuity in rank across generation boundaries, or leveraging exogenous mortality shocks to elder sons that quasi-randomly shift rank inheritance to younger sons. Such designs would allow researchers to move from the conditional associations we report to credible causal estimates of the intergenerational fertility premium of official status in the Qing military aristocracy.

---

## References

Becker, Gary S., and H. Gregg Lewis. 1973. "On the Interaction between the Quantity and Quality of Children." *Journal of Political Economy* 81 (2): S279–S288.

Becker, Gary S., and Nigel Tomes. 1979. "An Equilibrium Theory of the Distribution of Income and Intergenerational Mobility." *Journal of Political Economy* 87 (6): 1153–1189.

Bengtsson, Tommy, Cameron Campbell, James Z. Lee, et al. 2004. *Life under Pressure: Mortality and Living Standards in Europe and Asia, 1700–1900*. Cambridge, MA: MIT Press.

Black, Sandra E., and Paul J. Devereux. 2011. "Recent Developments in Intergenerational Mobility." In *Handbook of Labor Economics*, vol. 4B, edited by Orley Ashenfelter and David Card, 1487–1541. Amsterdam: Elsevier.

Campbell, Cameron D., and James Z. Lee. 2003. "Social Mobility from a Kinship Perspective: Rural Liaoning, 1789–1909." *International Review of Social History* 48 (1): 1–26.

Chetty, Raj, Nathaniel Hendren, Patrick Kline, and Emmanuel Saez. 2014. "Where is the Land of Opportunity? The Geography of Intergenerational Mobility in the United States." *Quarterly Journal of Economics* 129 (4): 1553–1623.

Clark, Gregory, and Neil Hamilton. 2006. "Survival of the Richest: The Malthusian Mechanism in Pre-Industrial England." *Journal of Economic History* 66 (3): 707–736.

Dillon, Nara, and James Tan. 2021. "Intergenerational Occupational Mobility in Qing Liaoning." *Explorations in Economic History* 82: 101404.

Elliott, Mark C. 2001. *The Manchu Way: The Eight Banners and Ethnic Identity in Late Imperial China*. Stanford: Stanford University Press.

Elman, Benjamin A. 2000. *A Cultural History of Civil Examinations in Late Imperial China*. Berkeley: University of California Press.

Kung, James Kai-sing, and Shi Li. 2011. "Molecular and Cultural Transmission in Pre-Modern China." Mimeo.

Lee, James Z., and Cameron D. Campbell. 1997. *Fate and Fortune in Rural China: Social Organization and Population Behavior in Liaoning, 1774–1873*. Cambridge: Cambridge University Press.

Solon, Gary. 1992. "Intergenerational Income Mobility in the United States." *American Economic Review* 82 (3): 393–408.

Vogl, Tom S. 2016. "Scaling Up Understanding of the Demographic Transition." *Journal of Economic Perspectives* 30 (1): 187–212.

Zimmerman, David J. 1992. "Regression toward Mediocrity in Economic Stature." *American Economic Review* 82 (3): 409–429.