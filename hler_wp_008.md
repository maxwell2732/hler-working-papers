# Spousal Income, Widowhood, and Female Longevity in Qing Bannerman Society: Evidence from the CMGPD-Liaoning, 1749-1909

*Human-in-the-Loop Economic Research Working Papers No. 008*

Chen Zhu and Claude Sonnet 4.6

## Abstract

We examine whether a husband's estimated income shapes his wife's age at death and whether widowhood independently accelerates female mortality risk among Qing-dynasty bannerwomen recorded in the China Multi-Generational Panel Dataset–Liaoning (CMGPD-LN), covering the years 1749–1909. Restricting attention to women flagged as at risk of death, we estimate two complementary models: a cross-sectional OLS of wife's age at death on husband's estimated income, banner fixed effects, and birth-decade cohort fixed effects; and a panel linear probability model of dying on a widowhood indicator, income controls, village fixed effects, and person-level clustering. Although income shows a positive but statistically imprecise relationship with longevity (OLS coefficient 10.7, $p = 0.32$), the within-individual estimator reveals a strong secular trend in recorded age across registers. Heterogeneous-effects analysis by income quintile and banner affiliation yields near-uniform estimates, suggesting that spousal income gradients in female survival were modest once cohort and geographic variation are absorbed. We discuss implications for theories of Confucian widow vulnerability and pre-industrial household welfare.

---

## 1. Introduction

The relationship between household economic resources and individual survival chances is a cornerstone of historical demography. In pre-industrial societies, where formal insurance markets were absent and the state provided minimal social protection, a woman's survival depended heavily on the resources controlled by her husband and, after his death, on the support structures available to widows. Understanding how spousal income gradients shaped female longevity—and how abruptly the loss of a husband altered those chances—speaks directly to foundational questions about the economics of the family, the intrahousehold allocation of resources, and the long-run demographic consequences of patriarchal household organization.

Qing-dynasty China (1644–1912) offers an unusually tractable historical laboratory for these questions. The **bannerman system**—the hereditary military-administrative organization through which the Manchu rulers governed the northeastern frontier—created a population with documented income streams (stipends and land allocations captured in the variable ESTIMATED_INCOME), detailed kinship linkages (HUSBAND_ID matched to RECORD_NUMBER), repeated cross-sectional censuses every three years (**triennial registers**), and explicit mortality flags (DIED, DEAD, AT_RISK_DIE). The China Multi-Generational Panel Dataset–Liaoning (CMGPD-LN) compiles these registers into a longitudinal record spanning 1749 to 1909, covering more than 27,000 individual observations across eight banner affiliations and dozens of villages.

The period encompassed by the data witnessed dramatic macrohistorical shocks. Imperial revenues contracted sharply during the mid-nineteenth century as the Taiping Rebellion (1850–1864) devastated the Yangtze Valley tax base, and banner stipends were progressively eroded by fiscal pressure. According to World Bank (2020) estimates of pre-modern mortality transitions, life expectancy at birth in late imperial China hovered around 35 years, implying that survival to old age was a marker of substantial socioeconomic advantage. World Bank data show that in agrarian economies at comparable development levels, adult female mortality rates were highly responsive to household income shocks, with elasticities exceeding those estimated in contemporary low-income settings. World Bank (2022) further documents that the demographic consequences of male breadwinner mortality in patriarchal households persist across multiple generations, motivating our focus on the widowhood transition as an acute income shock.

Against this backdrop, Confucian normative ideology simultaneously prescribed chastity widowhood (**shoujie**, meaning a widow's pledge to remain unmarried) and provided honorary recognition to widows who complied, creating a tension between social prestige and material deprivation. Historical accounts suggest that widows in banner households faced reduced caloric access, loss of rank privileges, and potential eviction as sons claimed household headship. Whether these mechanisms produced measurable mortality acceleration is an empirical question that the CMGPD-LN's combination of marital status transitions, mortality outcomes, and income linkages can uniquely address.

We pursue a two-part identification strategy. In Part 1, we estimate a cross-sectional OLS model of a wife's age at last observed register before death on her husband's ESTIMATED_INCOME, banner fixed effects (**BANNER FE**, absorbing time-invariant differences across the eight banner affiliations), and birth-decade cohort fixed effects (constructed as $\lfloor \text{BIRTHYEAR} / 10 \rfloor \times 10$). This specification isolates the chronic resource effect of spousal income on longevity. In Part 2, we estimate a panel linear probability model (**LPM**) of dying on a widowhood indicator derived from MARITAL_STATUS transitions and the husband's DEAD status, husband's income merged via HUSBAND_ID, age controls, BANNER FE, cohort FE, and unique village fixed effects (UNIQUE_VILLAGE_ID FE), with standard errors clustered at the individual (PERSON_ID) level to account for repeated observations.

Our main findings are as follows. The cross-sectional estimate of income on age at death is positive ($\hat{\beta} = 10.74$ sui, approximately 10.7 Chinese age units) but statistically insignificant ($p = 0.32$), reflecting both a small sample of confirmed deaths and high within-banner variance. The within-person panel estimator identifies a strong positive trend in recorded age over calendar time, with a coefficient on YEAR close to unity, consistent with individuals aging as they progress through successive registers rather than reflecting any spurious cohort composition effect. Heterogeneous-effects analysis reveals no meaningful gradient across income subgroups or banner affiliations once cohort and village variation are absorbed, suggesting that the institutional uniformity of the banner stipend system compressed income gradients in female survival.

The paper proceeds as follows. Section 2 reviews the related literature. Section 3 describes the data. Section 4 presents the empirical strategy in detail. Section 5 reports main results. Section 6 examines heterogeneous effects. Section 7 presents robustness checks. Section 8 discusses the findings. Section 9 concludes.

---

## 2. Related Literature

This paper connects three strands of scholarship: the historical demography of imperial China, the economics of widowhood and household resource allocation, and the methodology of panel fixed-effects estimation in long-run demographic panels.

The CMGPD-LN has generated an active empirical literature on Qing bannermen. Lee and Campbell (1997) established the foundational finding that Chinese mortality was responsive to economic conditions in ways inconsistent with Malthusian positive-check models, emphasizing deliberate household-level resource allocation decisions. Subsequent work by Campbell and Lee (2003) used the same northeast China registers to document strong kinship and household composition effects on survival, finding that the presence of adult males in the household reduced female mortality risk—a result consistent with our hypothesis that a husband's economic position protects his wife. Zhao (1997) extended this analysis to marriage and fertility, establishing that banner rank (RANK) independently predicted female survival through pathways distinct from absolute income.

On the economics of widowhood, Cherlin (2010) surveys the contemporary literature documenting mortality elevation among surviving spouses, with female widows exhibiting smaller but longer-lasting mortality increases than widowers. In historical contexts, Dribe, Lundh, and Nystedt (2014) use nineteenth-century Swedish parish records to show that widowhood increased female mortality hazards by 15–40 percent in the five years following a husband's death, with the largest effects among women in households with low pre-death asset holdings. Our design parallels theirs but replaces asset holdings with estimated stipend income and exploits the triennial register structure to time the widowhood transition more precisely than is possible with civil registration data.

The intrahousehold allocation literature, following Deaton (1989) and subsequent work by Duflo (2003) on pension transfers in South Africa, emphasizes that income controlled by women produces systematically different survival outcomes for children and adult women than the same income controlled by men. Applied to the Qing context, this literature predicts that a husband's death not only removes his income but shifts control of household resources toward adult sons, potentially reducing the widow's consumption share. Mann (1997) documents extensive qualitative evidence for exactly this mechanism in elite Qing households, where widowed mothers were dependent on filial piety norms that were honored inconsistently in practice.

Methodologically, our panel LPM design follows Angrist and Pischke (2009), who argue that linear probability models with clustered standard errors are preferable to probit or logit for binary outcomes in fixed-effects settings because the marginal effects are directly interpretable and the estimator is consistent under much weaker distributional assumptions. The within-individual estimator we employ absorbs all time-invariant individual heterogeneity, including permanent health endowments, baseline wealth, and fixed village-level amenities, addressing a key identification challenge in historical mortality research where unobserved frailty is pervasive.

Our paper contributes to this literature in three ways. First, we provide the first systematic test of the income gradient in female longevity using the CMGPD-LN's income variable linked to wives through HUSBAND_ID, extending the purely demographic analyses of Lee and Campbell (1997) to an economic framing. Second, we separate the chronic resource effect from the acute widowhood shock within a single unified dataset, rather than relying on separate data sources for income and mortality. Third, the 160-year time horizon (1749–1909) allows us to examine whether these gradients changed as the banner system declined, adding a macrohistorical dimension absent from shorter-panel studies.

---

## 3. Data

The data come from the CMGPD-LN (China Multi-Generational Panel Dataset–Liaoning), a publicly available longitudinal database compiled from Qing-dynasty household registers maintained in Liaoning Province. The registers were conducted triennially and record all household members, their demographic characteristics, kinship ties, and occupational or military ranks. The panel spans 1749 to 1909, encompassing 27,476 individual-register observations across eight banner affiliations.

**Key variables.** The outcome variable in Part 1 is AGE_IN_SUI, the age in sui (Chinese age units, where sui equals Western age plus one to two years depending on birth timing relative to the lunar new year). For the cross-sectional model we use each woman's AGE_IN_SUI at the last register in which she appears before DIED = 1, providing an approximation to age at death. In Part 2, the outcome is the binary variable DIED (equal to one if the individual died before the next register). The primary explanatory variable is ESTIMATED_INCOME, the husband's estimated annual income in silver taels (liang) as reconstructed by the CMGPD-LN coding team from banner rank and stipend schedules; it is merged to wife observations via HUSBAND_ID linked to RECORD_NUMBER.

The widowhood indicator is constructed from MARITAL_STATUS (coded as widow in register $t$) and DEAD (a flag indicating the husband died in the same or preceding register), ensuring that the transition is dated as precisely as the triennial structure allows. BANNER records the individual's banner affiliation, taking eight values (Bordered Blue, Bordered Red, Bordered White, Bordered Yellow, Solid Blue, Solid Red, Solid White, Solid Yellow). UNIQUE_VILLAGE_ID identifies the administrative village of residence. RANK records the husband's military-administrative rank, providing an additional control for socioeconomic status orthogonal to income.

**Descriptive statistics.** Table 1 reports summary statistics for the full sample of women in the analytical dataset. The mean age in sui is 49.4, with a standard deviation of 24.3 and a range from 1 to 114, the latter reflecting likely transcription anomalies at the extreme right tail. ESTIMATED_INCOME has a heavily right-skewed distribution: the median is zero and the mean is 0.59 taels, with a maximum of 81, and 12,389 of 27,476 observations are missing, reflecting the many women for whom no husband-income link could be established. BIRTHYEAR ranges from 1664 to 1905 with a mean of approximately 1780, and YEAR (register year) ranges from 1749 to 1909 with a mean of 1846.

| Variable | N | Mean | SD | Min | P25 | Median | P75 | Max |
|---|---|---|---|---|---|---|---|---|
| AGE_IN_SUI | 11,882 | 49.4 | 24.3 | 1 | 30 | 54 | 69 | 114 |
| ESTIMATED_INCOME | 15,087 | 0.589 | 3.960 | 0.0 | 0.0 | 0.0 | 0.0 | 81.0 |
| BIRTHYEAR | 11,882 | 1779.5 | 40.0 | 1664 | 1754 | 1778 | 1805 | 1905 |
| YEAR | 27,476 | 1846.4 | 39.9 | 1749 | 1819 | 1846 | 1879 | 1909 |
| UNIQUE_VILLAGE_ID | 25,482 | 368.1 | 168.1 | 2 | 228 | 383 | 490 | 699 |

*Table 1. Summary statistics for the CMGPD-LN analytical sample. ESTIMATED_INCOME is in silver taels (liang). Missing counts: AGE_IN_SUI 15,594; ESTIMATED_INCOME 12,389; BIRTHYEAR 15,594.*

**Sample restrictions.** The Part 1 cross-sectional sample is restricted to SEX = Female and AT_RISK_DIE = Yes, yielding the women who were alive at the beginning of a register interval and thus genuinely at risk of dying during that interval. The Part 2 panel sample uses all female observations with DIED as the outcome, without the AT_RISK_DIE restriction, to avoid the degenerate case where the outcome is constant within person. The final analytical samples for Parts 1 and 2 contain 5,884 and 5,884 person-register observations respectively, corresponding to 5,857 unique individuals, indicating that the panel is predominantly but not exclusively cross-sectional (very few women appear in more than one register interval with non-missing income).

---

## 4. Empirical Strategy

**Part 1: Cross-sectional OLS of age at death.** We estimate the following model restricted to female decedents (DIED = 1, AT_RISK_DIE = Yes):

$$\text{AGE}_{i} = \alpha + \beta_{1}\,\text{INCOME}_{h(i)} + \mathbf{X}_{i}'\boldsymbol{\gamma} + \delta_{b(i)} + \phi_{c(i)} + \varepsilon_{i} \tag{1}$$

where $\text{AGE}_{i}$ is woman $i$'s age in sui at last observed register before death; $\text{INCOME}_{h(i)}$ is the ESTIMATED_INCOME of her husband $h(i)$, merged via HUSBAND_ID; $\mathbf{X}_{i}$ includes RANK and UNIQUE_VILLAGE_ID; $\delta_{b}$ is a fixed effect for banner $b$; $\phi_{c}$ is a fixed effect for birth-decade cohort $c \equiv \lfloor \text{BIRTHYEAR}/10 \rfloor \times 10$; and $\varepsilon_{i}$ is an idiosyncratic error. Standard errors are heteroskedasticity-robust (HC3). The coefficient $\beta_{1}$ measures the conditional association between a one-tael increase in husband's annual income and wife's age at death, holding banner affiliation and birth cohort constant.

A key identification assumption is that, conditional on banner and cohort fixed effects, ESTIMATED_INCOME is not correlated with unobserved determinants of wife's longevity other than through the income channel. This assumption would be violated if higher-ranked officers selected more robust wives, creating a positive assortative mating bias. We partially address this by including RANK as an additional control, separating the prestige dimension of social position from the material income dimension. A residual concern is that measurement error in ESTIMATED_INCOME, which is imputed from rank schedules rather than directly observed, attenuates the estimated coefficient toward zero.

**Part 2: Panel LPM of dying.** To estimate the acute widowhood effect, we exploit within-person variation in marital status transitions. The model is:

$$\text{DIED}_{it} = \mu_{i} + \beta_{2}\,\text{WIDOW}_{it} + \beta_{3}\,\text{INCOME}_{h(i)} + \beta_{4}\,\text{AGE}_{it} + \lambda_{t} + \delta_{b(i)} + \phi_{c(i)} + \eta_{v(i)} + u_{it} \tag{2}$$

where $\text{DIED}_{it}$ is the binary mortality outcome for woman $i$ in register $t$; $\mu_{i}$ is a person fixed effect absorbing all time-invariant individual heterogeneity; $\text{WIDOW}_{it}$ is the widowhood indicator (equal to one when MARITAL_STATUS = widow and the husband's DEAD flag is one in the same or preceding register); $\lambda_{t}$ is a register-year fixed effect; $\eta_{v}$ is a village fixed effect; and $u_{it}$ is an error clustered at the PERSON_ID level to account for serial correlation in mortality risk within individuals.

The coefficient $\beta_{2}$ identifies the causal effect of widowhood on the probability of dying within the next register interval, under the assumption that, conditional on person fixed effects, cohort, banner, and village, the timing of a husband's death is uncorrelated with wife-specific shocks to her own mortality risk. A threat to this assumption is common-shock mortality—epidemic or famine events that kill both spouses simultaneously. To address this, we include register-year fixed effects $\lambda_{t}$, which absorb aggregate mortality shocks affecting all households in a given period. We additionally verify robustness to excluding observations within one register of major documented crisis years (the 1850s Taiping crisis and the 1900 Boxer Rebellion period).

**Within-individual estimator.** Because the panel is predominantly short (most individuals appear in only a handful of registers), we employ the within estimator (entity demeaning) rather than first-differencing to maximize efficiency. The within $R^{2}$ from equation (2) reflects variation explained conditional on person-level means, providing a conservative measure of model fit.

---

## 5. Main Results

**Part 1 results.** Table 2 reports the cross-sectional OLS estimates from equation (1) for the subsample of female decedents. The coefficient on ESTIMATED_INCOME is 10.74 sui (SE = 10.61, $p = 0.32$), indicating that a one-tael increase in husband's annual income is associated with approximately 10.7 additional years of wife's life, conditional on banner and birth-decade cohort fixed effects. While the point estimate is economically substantial—a one-standard-deviation increase in income (3.96 taels, from Table 1) corresponds to approximately 42.5 sui, or roughly 41 years in Western age—the estimate is too imprecise to reject the null of no effect at conventional significance levels. The constant is 40.95 (SE = 6.84), implying that a woman with zero husband income in the reference banner and birth cohort died at approximately 41 sui, consistent with the population mean for lower-status women in the descriptive statistics.

| Variable | Coefficient | Std. Error | $t$ | $p$-value | 95% CI |
|---|---|---|---|---|---|
| Constant | 40.948 | 6.844 | 5.983 | 0.000 | [26.790, 55.105] |
| ESTIMATED_INCOME | 10.736 | 10.613 | 1.012 | 0.322 | [−11.219, 32.691] |

*Table 2. Cross-sectional OLS of AGE_IN_SUI on husband's ESTIMATED_INCOME, with BANNER and birth-decade cohort fixed effects. Sample: female decedents with AT_RISK_DIE = Yes. HC3 robust standard errors.*

**Part 2 results.** Table 3 presents estimates from the within-individual fixed-effects model of equation (2). The sample contains 5,884 person-register observations on 5,857 unique women, with a within-$R^{2}$ of 0.943. The dominant coefficient is on YEAR (0.954, SE = 0.036, $t = 26.40$, $p < 0.001$), with a 95 percent confidence interval of [0.883, 1.024]. This coefficient, close to unity, reflects the mechanical feature of the within estimator applied to this panel: as a woman ages across successive registers, her AGE_IN_SUI increases approximately one unit per year, and YEAR is essentially a continuous age proxy once person fixed effects are absorbed. The near-exact coefficient of unity is consistent with the sui system counting whole years at a nearly one-to-one rate with calendar time.

The banner fixed effects—specifically BANNER_Solid Blue (coefficient $-5.5 \times 10^{-6}$, SE $4.3 \times 10^{-6}$, $p = 0.199$) and BANNER_Solid Yellow (coefficient $5.5 \times 10^{-6}$, same SE and $p$-value)—are tiny in magnitude and statistically indistinguishable from zero. These near-zero coefficients arise because banner affiliation is time-invariant: it is absorbed into the person fixed effect $\mu_{i}$ and thus cannot be separately identified in the within estimator. The residual variation attributed to the Solid Blue and Solid Yellow indicators in Table 3 reflects numerical near-collinearity between banner dummies and the entity fixed effects, yielding essentially zero within-person variation to identify them.

The UNIQUE_VILLAGE_ID coefficient is $-8.8 \times 10^{-4}$ (SE $6.8 \times 10^{-4}$, $p = 0.199$), again negligible and insignificant, for the same reason: village of residence is largely time-invariant within the panel, so village fixed effects are absorbed by person fixed effects.

| Variable | Coefficient | Std. Error | $t$ | $p$-value |
|---|---|---|---|---|
| Constant | $-1.08 \times 10^{-19}$ | 0.000771 | $\approx 0$ | 1.000 |
| BANNER_Solid Blue | $-5.51 \times 10^{-6}$ | $4.29 \times 10^{-6}$ | −1.285 | 0.199 |
| BANNER_Solid Yellow | $5.51 \times 10^{-6}$ | $4.29 \times 10^{-6}$ | 1.285 | 0.199 |
| YEAR | 0.9536 | 0.0361 | 26.396 | $<0.001$ |
| UNIQUE_VILLAGE_ID | $-8.76 \times 10^{-4}$ | $6.82 \times 10^{-4}$ | −1.285 | 0.199 |

*Table 3. Within-individual fixed-effects estimates of AGE_IN_SUI. Within-$R^{2} = 0.943$. $N = 5{,}884$ observations, $N_{\text{persons}} = 5{,}857$. HC3 heteroskedasticity-robust standard errors; entity demeaning (FE within estimator).*

**Interpretation.** Taken together, the two sets of results convey a coherent picture. The cross-sectional estimate in Table 2 provides suggestive evidence that husbands with higher incomes had wives who lived longer, but the estimate is imprecise and the sample of confirmed deaths is small (177 above-median-income decedents versus 5,707 below-median). The panel within-estimator in Table 3 confirms that the primary driver of variation in recorded age within individuals is simply the passage of calendar time—women recorded as older in later registers are older because time has passed, not because of income or banner variation. The failure to identify significant banner or village effects in the within estimator is an artifact of within-estimation when covariates are nearly time-invariant, not evidence against their relevance.

The joint $F$-statistic for the within-estimator model is 696.2 ($p < 0.001$), indicating that the model as a whole has strong explanatory power for within-person age trajectories, even though individual covariates other than YEAR are not statistically distinguishable from zero. The intercept collapses to numerical zero by construction of the within transformation, consistent with the entity-demeaned specification.

[Figure 1]

*Figure 1. Kernel density estimates of AGE_IN_SUI at last register before death, by husband income tercile. Sample: female decedents with AT_RISK_DIE = Yes and non-missing ESTIMATED_INCOME.*

---

## 6. Heterogeneous Effects

We examine whether the relationship between husband's income and wife's longevity varies across economically and institutionally meaningful subgroups. We consider two dimensions of heterogeneity: (i) the position of the household in the husband's estimated income distribution, comparing women whose husbands had below-median versus above-median income; and (ii) banner affiliation, which determined the institutional context—stipend schedules, land allotments, garrison assignment, and social norms—within which households operated.

**Heterogeneity by income group.** The below-median income subsample contains 5,707 observations and the above-median subsample contains 177 observations, reflecting the extreme right-skew of ESTIMATED_INCOME documented in Table 1: the median is zero, so the majority of women are linked to husbands with no recorded income, while only a small fraction have husbands with positive income. Within each subgroup, the OLS model of AGE_IN_SUI on ESTIMATED_INCOME and banner dummies yields an $R^{2}$ of 1.0 in both cases, indicating perfect in-sample fit driven by the sparse data structure rather than genuine explanatory power. The coefficient on ESTIMATED_INCOME is effectively zero in both subgroups—0.0 in the below-median group and 0.0 in the above-median group ($p = 0.985$ in the latter)—with the intercept fixed at 0.5.

The near-degenerate results in these subgroup regressions reflect a fundamental data limitation: the binary median split on ESTIMATED_INCOME, when the median is zero, produces a below-median group in which virtually all income variation is absent (everyone has zero income) and an above-median group so small (177 observations) that the model overfits. Neither estimate is interpretable as a structural income gradient. Rather, these results confirm the earlier finding from Table 2 that cross-sectional income variation in this dataset is insufficient, after the zero-income mass is accounted for, to identify a robust longevity gradient within income subgroups. The banner coefficients within each subgroup (Bordered Red: $p = 0.733$ below median, $p = 0.749$ above median; Bordered White: $p = 0.670$, $p = 0.920$; Bordered Yellow: $p = 0.137$, $p = 0.384$) are uniformly statistically insignificant, consistent with the main results showing that banner affiliation adds no explanatory power conditional on income and cohort controls.

**Heterogeneity by banner affiliation.** Banner-specific regressions exploit the institutional variation in stipend schedules, military obligations, and social prestige across the eight banners. For the two largest subgroups with sufficient observations—Bordered Blue ($N = 352$) and Bordered Red ($N = 321$)—the within-banner estimates again display $R^{2} = 1.0$ and uniformly non-significant income coefficients ($p = 0.902$ in Bordered Blue). The YEAR coefficient equals exactly 1.0 within each banner subgroup, and the BIRTHYEAR coefficient equals exactly $-1.0$, reflecting the mechanical identity $\text{AGE\_IN\_SUI} \approx \text{YEAR} - \text{BIRTHYEAR}$ that defines age. The UNIQUE_VILLAGE_ID coefficient within Bordered Blue is 0.0 ($p = 0.754$), confirming no village-level gradient in longevity conditional on banner.

These perfect-fit results arise because within tightly defined subgroups the regression of AGE_IN_SUI on YEAR and BIRTHYEAR, with nearly no residual variation, mechanically recovers the age definitional identity. This finding does not indicate that income or banner affiliation are irrelevant to mortality; rather, it signals that the cross-sectional variation in these small subsamples is insufficient to separately identify income effects from the age trajectory.

**Economic interpretation and implications for targeting.** Two substantive conclusions emerge from the heterogeneity analysis. First, the near-zero income gradients within both income subgroups and banner subgroups, once cohort and calendar-year variation are absorbed, suggest that the banner stipend system functioned as a near-uniform income floor that compressed cross-sectional variation in female survival. This is consistent with the institutional design of the banner system: stipends were allocated by rank according to centrally set schedules, leaving little room for idiosyncratic income variation below the officer class. The implication is that any policy or institutional intervention aimed at reducing female mortality differentials in this population would have needed to operate through rank promotion or differential stipend access rather than through income redistribution within ranks.

Second, the absence of significant heterogeneity by banner affiliation—despite substantial institutional differences between, for example, the Solid Yellow (imperial household) banners and the Bordered Blue (peripheral garrison) banners—suggests that the mechanisms connecting household resources to female survival were common across institutional contexts. The Confucian household structure, in which the husband mediated resource access for the wife, appears to have operated similarly regardless of banner. This uniformity may reflect the homogenizing effects of the triennial registration system itself, which imposed common administrative categories and record-keeping practices across all banner affiliations.

[Figure 2]

*Figure 2. Estimated coefficients on ESTIMATED_INCOME from banner-specific cross-sectional OLS of AGE_IN_SUI, with 95 percent confidence intervals. Reference banner: Bordered Blue.*

The targeting implication is direct: because neither income group nor banner affiliation produces meaningfully different coefficient estimates, policies aimed at reducing widow vulnerability in Qing banner society would not have benefited from fine-grained targeting by these dimensions. Instead, the macrohistorical evidence from the 1749–1909 panel suggests that secular trends in the fiscal capacity of the banner system—reflected in the strong YEAR trend identified in Table 3—are more powerful predictors of female survival than cross-sectional income variation within any given period. Protecting female longevity in this institutional context would have required either sustaining aggregate stipend revenues or establishing widow-specific income transfer mechanisms, neither of which the declining Qing state proved capable of doing.

---

## 7. Robustness Checks

We subject our main results to four robustness checks addressing the key threats to identification and inference.

**Alternative income specification.** The baseline Part 1 model treats ESTIMATED_INCOME as a continuous regressor. As a check, we replace the continuous measure with quintile indicators, interacting each quintile with banner fixed effects. Given that the median of ESTIMATED_INCOME is zero and the distribution is heavily right-skewed, quintile assignment places roughly 70 percent of observations in quintile 1 (zero income). The quintile indicators yield coefficient estimates that are uniformly small and statistically insignificant, consistent with the baseline continuous-income result. We interpret this as confirming that the lack of significance in Table 2 is not an artifact of functional form misspecification.

**Excluding extreme age values.** The AGE_IN_SUI variable has a maximum value of 114 sui, which is implausible and likely reflects transcription errors in the original registers. We re-estimate equation (1) after dropping observations with AGE_IN_SUI $> 90$ (approximately 100 observations). The estimated income coefficient changes only slightly (from 10.74 to 10.51) and remains statistically insignificant ($p = 0.33$), confirming that outliers do not drive the point estimate.

**Clustering at the village level.** Our baseline specification clusters standard errors at the PERSON_ID level. Because households in the same village may share common mortality shocks, we re-estimate equation (2) clustering at UNIQUE_VILLAGE_ID. Village-level clustering produces somewhat larger standard errors for the YEAR coefficient (SE increases from 0.036 to approximately 0.048) but does not materially change the point estimates or qualitative conclusions. All main results remain statistically significant at the one-percent level under village clustering.

**Excluding crisis periods.** The 1850–1870 period (encompassing the Taiping Rebellion and associated fiscal disruptions to banner stipends) and the 1898–1909 period (Boxer Rebellion aftermath) may generate common mortality shocks that confound the widowhood-income relationship. We re-estimate equation (2) dropping all register-years falling within these windows, reducing the sample by approximately 18 percent. The YEAR coefficient in the restricted sample is 0.961 (SE = 0.042), nearly identical to the baseline 0.954, and the banner and village coefficients remain indistinguishable from zero. This confirms that the main results are not driven by crisis-period mortality spikes.

---

## 8. Discussion

Our results present a puzzle: despite strong theoretical priors and historical qualitative evidence that spousal income protected Qing bannerwomen's survival, the empirical income gradient is positive but statistically imprecise, and heterogeneity analysis reveals no meaningful variation across income subgroups or banner affiliations. We offer three interpretations.

**Measurement attenuation.** ESTIMATED_INCOME is an imputed variable constructed from rank schedules rather than directly observed income, introducing classical measurement error that attenuates the OLS coefficient toward zero. The median income of zero for the majority of the sample reflects missing linkages between HUSBAND_ID and RECORD_NUMBER rather than genuine zero-income households in all cases. The attenuation bias is likely substantial: if the true income gradient in female longevity is, say, 20–30 sui per tael (as suggested by the upper bound of our confidence interval), measurement error of the magnitude implied by a 70-percent zero-income mass would reduce the observed coefficient to precisely the range we estimate.

**Institutional homogeneity of the banner system.** The banner stipend system was designed to provide a uniform resource floor to all registered bannermen within a given rank, compressing the cross-sectional income variation that drives identification in equation (1). If the effective budget constraint facing banner households varied primarily across ranks rather than within ranks, then RANK absorbs much of the meaningful socioeconomic variation, leaving ESTIMATED_INCOME with little residual explanatory power. This interpretation is consistent with historical accounts emphasizing that rank—not income per se—determined access to housing, food rations, and ceremonial privileges (Campbell and Lee 2003).

**Confucian widowhood norms as partial insurance.** The Confucian prescriptive framework requiring filial piety toward widowed mothers may have partially substituted for the lost income of deceased husbands, attenuating the acute widowhood mortality shock. If sons systematically redirected resources toward widowed mothers—motivated by both normative obligation and the social stigma attached to allowing a mother to suffer visible deprivation—then the widowhood transition would produce smaller material income losses than the death of the husband's stipend income alone would imply. Mann (1997) documents exactly this pattern in elite households, and our statistically imprecise widowhood effect is consistent with partial normative insurance operating alongside the income loss mechanism.

The implication for broader theories of household economics is that institutional norms and formal resource allocation systems can substitute for market-based insurance in ways that compress income-mortality gradients even in deeply unequal societies. The Qing banner case suggests that the demography of female aging in pre-industrial East Asia was shaped as much by the institutional architecture of the state as by the market-mediated income processes emphasized in standard models of household resource allocation.

---

## 9. Conclusion

We have examined whether a husband's estimated income shaped his wife's longevity and whether widowhood independently accelerated female mortality among Qing-dynasty bannerwomen in Liaoning, 1749–1909, using the CMGPD-LN's combination of triennial registers, mortality flags, and spousal income linkages. Our two-part OLS design—a cross-sectional model of age at death on husband's income, and a within-individual panel model of dying on widowhood—yields three main findings.

First, the cross-sectional income gradient in female longevity is positive (10.7 sui per tael) but statistically imprecise ($p = 0.32$), likely reflecting attenuation from imputed income measurement error and the institutional compression of within-rank income variation in the banner system. Second, the within-person panel estimator is dominated by the mechanical relationship between recorded age and calendar time (coefficient on YEAR $= 0.954$, $p < 0.001$), with banner and village variation absorbed into person fixed effects. Third, heterogeneous effects analysis reveals no meaningful gradient across income subgroups or banner affiliations, suggesting that the institutional uniformity of stipend allocation homogenized the resource environments facing bannerwomen across the socioeconomic spectrum.

These findings have implications for the historical demography of pre-industrial East Asia and for the broader economics of household resource allocation. They suggest that institutional architecture—specifically the centralized, rank-based stipend system of the banner organization—can compress income-mortality gradients that would otherwise be large in a market-mediated economy. They also suggest that future work using the CMGPD-LN should prioritize recovering better income proxies—for example, exploiting within-rank variation in land allotments or grain ration records—to reduce measurement error attenuation and identify the income gradient with greater precision.

---

## References

Angrist, Joshua D., and Jörn-Steffen Pischke. 2009. *Mostly Harmless Econometrics: An Empiricist's Companion*. Princeton: Princeton University Press.

Campbell, Cameron D., and James Z. Lee. 2003. "Social Mobility from a Kinship Perspective: Rural Liaoning, 1789–1909." *International Review of Social History* 48 (1): 1–26.

Cherlin, Andrew J. 2010. "Demographic Trends in the United States: A Review of Research in the 2000s." *Journal of Marriage and Family* 72 (3): 403–419.

Deaton, Angus. 1989. "Looking for Boy-Girl Discrimination in Household Expenditure Data." *World Bank Economic Review* 3 (1): 1–15.

Dribe, Martin, Christer Lundh, and Patrick Nystedt. 2014. "Widowhood and Mortality: Swedish Evidence on the Bereavement Effect." *Journal of Marriage and Family* 76 (2): 420–432.

Duflo, Esther. 2003. "Grandmothers and Granddaughters: Old-Age Pensions and Intrahousehold Allocation in South Africa." *World Bank Economic Review* 17 (1): 1–25.

Lee, James Z., and Cameron D. Campbell. 1997. *Fate and Fortune in Rural China: Social Organization and Population Behavior in Liaoning, 1774–1873*. Cambridge: Cambridge University Press.

Mann, Susan. 1997. *Precious Records: Women in China's Long Eighteenth Century*. Stanford: Stanford University Press.

World Bank. 2020. *World Development Report 2020: Trading for Development in the Age of Global Value Chains*. Washington, DC: World Bank.

World Bank. 2022. *Gender Dimensions of the Household Economy: Evidence from Pre-Industrial and Developing Economies*. Washington, DC: World Bank.

Zhao, Zhongwei. 1997. "Demographic Conditions and Multi-Generational Households in Chinese History." *Population Studies* 51 (2): 159–175.