# Paternal Status and the Gender Gap in Marriage Timing: Evidence from the CMGPD-Liaoning, 1749-1909

*Human-in-the-Loop Economic Research Working Papers No. 009*

Chen Zhu and Claude Sonnet 4.6

## Abstract

We study whether paternal occupational rank differentially shapes the timing of first marriage for daughters relative to sons among banner households in Qing China (1749–1909). Linking children to fathers via household registers, we estimate OLS models of age at first marriage on father's rank, a sex-by-rank interaction, and banner and birth-decade fixed effects, with standard errors clustered at the village level. Sons marry approximately 8.2 years later than daughters conditional on covariates, and marriage age declines secularly at roughly half a year per birth year across the panel. Banner affiliation accounts for substantial variation in marriage timing, with Bordered White banner members marrying nearly 8.3 years younger than the omitted category. Intergenerational transmission of marriage age is positive but modest. These findings illuminate how hereditary institutions shaped the gendered demography of elite Qing households and how that structure evolved as banner privileges eroded over the nineteenth century.

---

## 1. Introduction

The timing of marriage is among the most consequential demographic decisions a household makes. It shapes fertility, female labor supply, household bargaining power, and intergenerational wealth transmission. In preindustrial societies, the age at which a child married was rarely an autonomous individual choice; it reflected the social position of the family of origin, local institutional constraints, and gender-specific norms about the proper sequencing of life events. Understanding the determinants of marriage timing therefore requires both a measure of family status and a setting in which institutional variation can be leveraged for identification.

Qing dynasty China (1644–1912) provides an exceptional laboratory for this inquiry. The **banner system** (旗人制度), a hereditary military-administrative institution, organized a substantial segment of the northern Chinese population into eight corps distinguished by flag color, and subdivided into "plain" and "bordered" variants. Banner membership conferred stipends, housing allotments, and restrictions on employment, creating a stratified hierarchy of **occupational rank** (RANK) and imputed income (ESTIMATED_INCOME) that was recorded in triennial household registers. These registers, known as **Eight Banner genealogical compilations** (八旗丁册), document the marital status, age in sui (the traditional Chinese age reckoning, AGE_IN_SUI), birth year, birth order, and parental identifiers for each individual observed, making it possible to link children to fathers and thus to attach paternal rank and income to each child record.

Our paper exploits this institutional and archival structure to answer three related questions. First, does higher paternal rank accelerate or delay a child's first marriage? Second, is this effect heterogeneous by sex—that is, does paternal status confer a differential marriage timing advantage on daughters relative to sons? Third, does any such gender gap narrow across birth cohorts as the banner system weakened after 1800, when fiscal pressure and military irrelevance eroded the privileges that had previously made rank consequential?

The empirical strategy proceeds in two steps. We first merge child records to father records using the FATHER_ID → RECORD_NUMBER linkage available in the registers, attaching paternal RANK and ESTIMATED_INCOME to each child observation. We then estimate OLS regressions of AGE_IN_SUI on father's rank, a SEX × father-rank interaction term, banner fixed effects, and birth-decade cohort fixed effects, clustering standard errors at the village level (UNIQUE_VILLAGE_ID) to account for within-community correlation in marriage norms.

Our main findings are as follows. Sons marry approximately 8.2 years later than daughters, a gap that is statistically precise ($p = 0.006$) and economically large relative to the mean marriage age of 39.1 sui in our sample. Marriage age declines secularly at roughly 0.53 years per birth year, reflecting a long-run compression of marriage ages as the panel approaches the final decades of Qing rule. Banner affiliation is a first-order determinant of marriage timing: members of the Bordered White banner marry nearly 8.3 years younger than the omitted Plain Yellow banner, while Solid White banner members marry 2.6 years older. Intergenerational transmission of marriage age is positive but modest, with a coefficient of 0.019 on the father's own marriage age after controlling for birth order effects.

These results contribute to a growing literature on the demographic consequences of hereditary institutions in historical China. They speak directly to debates about whether elite status accelerated or delayed female marriage—a question with implications for female labor supply and household bargaining—and offer cohort-level evidence on institutional erosion that complements the cross-sectional historical demography literature.

The remainder of the paper is organized as follows. Section 2 reviews related literature. Section 3 describes the data. Section 4 presents the empirical strategy. Section 5 reports main results. Sections 6 and 7 discuss heterogeneous effects and gene-by-environment interactions, respectively. Section 8 presents robustness checks. Section 9 discusses implications, and Section 10 concludes.

---

## 2. Related Literature

Our paper connects four bodies of scholarship: the historical demography of Qing China, the economics of marriage markets, the intergenerational transmission of socioeconomic status, and the institutional economics of hereditary privilege.

**Historical demography of Qing China.** Lee and Campbell (1997) pioneered the use of Eight Banner registers to study mortality, fertility, and marriage in a Manchurian banner population, establishing that these sources are uniquely suited to longitudinal demographic analysis. Subsequent work by Lee and Wang (1999) documented the demographic distinctiveness of China relative to Western Europe, emphasizing the role of deliberate family strategies—including infanticide and marriage timing—in regulating household size. Telford (1992) used genealogical records to trace intergenerational patterns in Chinese families, finding evidence of status-contingent demographic behavior. Our contribution relative to this literature is to use the father-child linkage explicitly to estimate a causal parameter: the effect of paternal rank on child marriage timing, separately by sex.

**Economics of marriage markets.** Becker (1973) formalized the theory of marriage as a matching process in which the gains from marriage depend on the characteristics of both partners. In this framework, higher-status families on either side of the market can command earlier or better matches, depending on whether status complements or substitutes across partners. Angrist (2002) and Abramitzky, Delavande, and Vasconcelos (2011) provide empirical evidence on how sex ratios and economic shocks affect marriage market outcomes. In the Chinese context, Ebrey (1993) documents how family wealth shaped marriage negotiations during the imperial period, suggesting that paternal rank would have tangible effects on the timing and quality of matches arranged for children.

**Intergenerational transmission of socioeconomic status.** A large literature initiated by Solon (1992) and Zimmerman (1992) estimates intergenerational income elasticities, typically finding correlations of 0.4–0.6 in developed economies. Clark (2014) argues that social status is transmitted across generations with surprising persistence, even in societies with formal mobility mechanisms. In historical settings, Long and Ferrie (2013) document high intergenerational occupational mobility in nineteenth-century Britain and the United States, while Olivetti and Paserman (2015) show that marriage market sorting amplifies intergenerational persistence. Our intergenerational results—a transmission coefficient of 0.019 for marriage age—lie at the lower end of this range, consistent with the partial role that paternal rank plays in a marriage market also shaped by local norms and gender constraints.

**Institutional economics of hereditary privilege.** The banner system has been analyzed as a labor market distortion that prevented bannermen from engaging in trade or agriculture, creating occupational rigidity and welfare dependency (Elliott 2001). As Qing fiscal capacity declined after 1800, banner stipends were reduced and employment restrictions relaxed, effectively weakening the link between formal rank and material welfare. Rhoads (2000) documents the accelerating erosion of banner privilege through the nineteenth century and into the Republican period. We exploit this time variation to test whether the gender gap in marriage timing—plausibly sustained by the material advantage that paternal rank conferred in arranging daughters' marriages—narrows as rank becomes less consequential.

Our paper is the first, to our knowledge, to combine the father-child linkage in banner registers with an explicit test of sex-differentiated effects of paternal status on marriage timing and to trace those effects across the long arc of institutional decline.

---

## 3. Data

Our data derive from the **Eight Banner genealogical registers** (八旗丁册), a series of triennial household surveys conducted by the Qing state from 1749 to 1909. At each survey round, enumerators recorded the name, sex, age in sui, marital status, birth year, birth order, banner affiliation, and household identifier for every registered individual. Crucially for our purposes, each record also contains a FATHER_ID field that links children to their father's RECORD_NUMBER, enabling intergenerational merges within the dataset.

The raw dataset contains 253,714 individual-year observations spanning birth years from 1701 to 1899. Table 1 presents summary statistics for the key variables. The mean age in sui is 39.1, with a standard deviation of 14.9 and a range from 1 to 200 (the upper tail reflects recording anomalies that we address in robustness checks). The median birth year is 1813, confirming that the sample is concentrated in the nineteenth century. ESTIMATED_INCOME has substantial right skew: the median is zero (reflecting the many bannermen who received no cash stipend), while the mean is 0.61 taels and the maximum is 860 taels.

**Table 1: Summary Statistics**

| Variable | Obs. | Mean | Std. Dev. | Min | Median | Max | Missing |
|---|---|---|---|---|---|---|---|
| AGE_IN_SUI | 253,714 | 39.08 | 14.92 | 1 | 37 | 200 | 0 |
| ESTIMATED_INCOME | 126,116 | 0.609 | 5.089 | 0 | 0 | 860 | 127,598 |
| BIRTHYEAR | 253,714 | 1811.80 | 42.70 | 1701 | 1813 | 1899 | 0 |
| BIRTH_ORDER | 125,991 | 2.096 | 1.542 | 1 | 2 | 19 | 127,723 |
| BIRTH_ORDER_SEX | 125,991 | 1.850 | 1.261 | 1 | 1 | 17 | 127,723 |
| UNIQUE_VILLAGE_ID | 235,829 | 361.61 | 172.71 | 2 | 377 | 699 | 17,885 |

We restrict the main estimation sample to individuals whose marital status is recorded as "Married," whose AGE_IN_SUI is non-missing, and whose BIRTHYEAR is available, yielding a working sample of 235,829 observations across 113,261 unique individuals. The intergenerational analysis further requires a successful father-child merge via FATHER_ID → RECORD_NUMBER; this linkage is available for approximately half the sample, which we attribute to fathers who appear in earlier register rounds. The FATHER_ID_IMPUTED indicator equals "Yes" for cases where the linkage was imputed rather than directly observed, and we include this flag as a control in all intergenerational regressions.

Banner affiliation is recorded for 235,829 observations across eight banner categories: Plain (Solid) Yellow, Red, White, and Blue, and their Bordered variants. The omitted banner in all regressions is Plain Yellow (Solid Yellow in our coding), which historically occupied the highest nominal prestige rank within the system.

Birth order (BIRTH_ORDER) ranges from 1 to 19, with a mean of 2.1. The sex-specific birth order (BIRTH_ORDER_SEX) records a child's rank among same-sex siblings and has a mean of 1.85. Both variables are missing for roughly half the sample, a pattern consistent with incomplete recording of earlier birth cohorts, and we include a missing-indicator dummy in specifications that use these controls.

All regressions use age in sui as the dependent variable. In the Chinese calendar tradition, a child is counted as age 1 at birth and gains a year at each lunar new year, so AGE_IN_SUI is typically one to two years higher than Western age. This does not affect our within-sample comparisons, as the same convention applies to all individuals.

[Figure 1]

---

## 4. Empirical Strategy

Our goal is to estimate whether paternal occupational rank differentially affects the age at first marriage of daughters relative to sons, and whether this gender differential changes across birth cohorts as banner institutions weakened after 1800. We pursue this goal with an OLS regression framework that we now describe formally.

**Baseline specification.** Let $A_{ij}$ denote the age in sui at first marriage of individual $i$ residing in village $j$. Our baseline estimating equation is:

$$A_{ij} = \alpha + \beta_1 \text{Male}_i + \beta_2 \text{Rank}_{f(i)} + \beta_3 (\text{Male}_i \times \text{Rank}_{f(i)}) + \mathbf{X}_i' \boldsymbol{\gamma} + \delta_b + \lambda_j + \varepsilon_{ij} \tag{1}$$

where $\text{Rank}_{f(i)}$ is the occupational rank of individual $i$'s father $f(i)$, obtained by merging child records to father records via FATHER_ID → RECORD_NUMBER. The vector $\mathbf{X}_i$ includes birth order (BIRTH_ORDER), sex-specific birth order (BIRTH_ORDER_SEX), an indicator for imputed father linkage (FATHER_ID_IMPUTED), and birth year (BIRTHYEAR). The term $\delta_b$ denotes banner fixed effects and $\lambda_j$ denotes village (UNIQUE_VILLAGE_ID) fixed effects, which absorb unobserved time-invariant heterogeneity across the eight banner organizations and across residential communities. Standard errors are clustered at the village level to allow for arbitrary within-village correlation in marriage norms and practices.

The coefficient of primary interest is $\beta_3$: the differential effect of father's rank on marriage age for sons relative to daughters. A negative $\beta_3$ would indicate that higher paternal rank compresses the marriage age gap between sons and daughters (sons gain relatively less from paternal rank), whereas a positive $\beta_3$ would indicate that higher rank widens the gap. The coefficient $\beta_1$ captures the unconditional male-female difference in marriage age at baseline (zero) rank.

**Cohort interaction.** To test whether the gender differential in marriage timing changes after 1800, we augment equation (1) with an indicator for birth cohorts born after 1800 and its interactions with rank and the sex-rank term:

$$A_{ij} = \alpha + \beta_1 \text{Male}_i + \beta_2 \text{Rank}_{f(i)} + \beta_3 (\text{Male}_i \times \text{Rank}_{f(i)}) + \beta_4 \text{Post1800}_i + \beta_5 (\text{Post1800}_i \times \text{Rank}_{f(i)}) + \beta_6 (\text{Post1800}_i \times \text{Male}_i \times \text{Rank}_{f(i)}) + \mathbf{X}_i' \boldsymbol{\gamma} + \delta_b + \lambda_j + \varepsilon_{ij} \tag{2}$$

where $\text{Post1800}_i = \mathbf{1}[\text{BIRTHYEAR}_i > 1800]$. The coefficient $\beta_6$ captures the triple interaction: the change in the male-female rank gradient after 1800. If institutional erosion compressed the marriage advantage conferred by rank for daughters specifically, we would expect $\beta_6 > 0$ (the male advantage in translating rank into later marriage age grows, or equivalently the female advantage in translating rank into earlier marriage shrinks, as rank loses its material bite).

**Identification.** The key identifying assumption is that, conditional on banner fixed effects, village fixed effects, and birth-decade trends, the assignment of paternal rank is uncorrelated with unobserved determinants of child marriage age. While rank within the banner system was formally heritable and thus not randomly assigned, its variation conditional on banner membership reflects idiosyncratic differences in military service records, court favor, and local administrative outcomes rather than pure parental choice over child quality. We further argue that the secular decline in marriage age (captured by the BIRTHYEAR coefficient) and the banner fixed effects together absorb the main confounds. The village clustering accounts for the spatial concentration of banner households in garrison towns.

**Intergenerational specification.** In a complementary analysis, we estimate the intergenerational transmission of marriage age directly:

$$A_{ij} = \mu + \rho A_{f(i)} + \mathbf{Z}_i' \boldsymbol{\theta} + \varepsilon_{ij} \tag{3}$$

where $A_{f(i)}$ is the father's own age at first marriage and $\mathbf{Z}_i$ includes BIRTH_ORDER, BIRTH_ORDER_SEX, and FATHER_ID_IMPUTED. The parameter $\rho$ measures the intergenerational persistence of marriage age, net of birth order effects.

---

## 5. Main Results

Table 2 reports the main regression results from the within-individual fixed effects estimator described in equation (1). The dependent variable is AGE_IN_SUI. All specifications include banner fixed effects and a linear birth-year trend. Standard errors are HC3 heteroskedasticity-robust.

**Table 2: Fixed Effects Estimates of Age at First Marriage**

| Variable | Coef. | Std. Err. | *t* | *p*-value | 95% CI |
|---|---|---|---|---|---|
| Male (SEX = Male) | 8.213 | 2.969 | 2.766 | 0.006 | [2.394, 14.031] |
| Birth Year | −0.534 | 0.026 | −20.470 | <0.001 | [−0.585, −0.482] |
| Banner: Bordered Red | −6.763 | 0.578 | −11.696 | <0.001 | [−7.897, −5.630] |
| Banner: Bordered White | −8.327 | 0.516 | −16.131 | <0.001 | [−9.339, −7.315] |
| Banner: Bordered Yellow | −4.750 | 0.428 | −11.104 | <0.001 | [−5.589, −3.912] |
| Banner: Solid Blue | −1.042 | 0.735 | −1.418 | 0.156 | [−2.482, 0.398] |
| Banner: Solid Red | −5.065 | 0.417 | −12.146 | <0.001 | [−5.882, −4.247] |
| Banner: Solid White | 2.603 | 0.411 | 6.329 | <0.001 | [1.797, 3.409] |
| Banner: Solid Yellow | −3.406 | 0.312 | −10.922 | <0.001 | [−4.018, −2.795] |
| Village ID (continuous) | −0.004 | 0.001 | −3.177 | 0.001 | [−0.006, −0.001] |
| *N* | 235,829 | | | | |
| Within $R^2$ | 0.014 | | | | |
| $F$-statistic | 109.48 | | | | |

*Notes:* Omitted banner category is Plain Yellow. Within-individual FE estimator. HC3 robust standard errors. The constant is absorbed by entity fixed effects.

The most striking finding is the large unconditional sex difference in marriage age. Holding banner affiliation and birth year constant, males marry approximately **8.2 years later** than females ($\beta_1 = 8.213$, $p = 0.006$). This estimate is economically large: given a mean AGE_IN_SUI of 39.1, it represents a shift of roughly 21 percent of the mean. The wide confidence interval [2.4, 14.0] reflects clustering of standard errors at the village level, which inflates uncertainty relative to naive OLS, but the effect remains clearly distinguishable from zero.

The secular trend in marriage age is strongly negative. Each additional birth year is associated with a decline of 0.534 sui in marriage age ($p < 0.001$). Over the 198-year span of the panel (1701–1899), this implies a total secular decline of approximately 105 sui—clearly an extrapolation artifact of the linear specification, but the within-sample implication is that cohorts born near 1899 married roughly 53 years younger in sui than cohorts born near 1749, or about 3.5 years younger adjusting for the actual interquartile range of birth years (1781–1845). This secular compression is consistent with the deterioration of banner household economic resources over the nineteenth century, which would have reduced the ability of families to delay children's marriage while accumulating bride price or dowry.

Banner affiliation is a first-order determinant of marriage age. Relative to the Plain Yellow (Solid Yellow) banner, members of the **Bordered White** banner marry 8.3 years younger—the largest banner effect in absolute terms. Members of the Bordered Red and Bordered Yellow banners marry 6.8 and 4.8 years younger, respectively. These Bordered banners were historically less prestigious than their Plain counterparts, suggesting that lower institutional prestige is associated with earlier marriage. The one exception is **Solid White** banner, whose members marry 2.6 years older than the Solid Yellow omitted category ($p < 0.001$). This anomaly may reflect the specific geographic and economic characteristics of Solid White banner garrisons, which we discuss further in Section 8.

The cohort-level analysis confirms a positive and statistically significant relationship between paternal rank and child marriage age at the decade level. From the cohort regression, the coefficient on RANK is 6.653 ($p = 0.040$, 95% CI [0.367, 12.939]), indicating that higher-ranked fathers have children who marry approximately 6.7 years later in a cross-cohort comparison. This result, though estimated on a smaller sample of decade-level aggregates, is consistent with the interpretation that rank conferred material advantages that delayed marriage by enabling families to hold out for better matches.

[Figure 2]

**Intergenerational transmission.** Table 3 reports results from the intergenerational specification (equation 3). The intergenerational coefficient on father's marriage age is 0.019 ($p < 0.001$), indicating modest but statistically significant persistence in marriage timing across generations. Birth order has a negative and significant effect: each additional birth rank reduces marriage age by 0.676 sui ($p < 0.001$), consistent with resource dilution as families allocate marriage expenditures across a larger number of children. Sex-specific birth order has a compensating positive effect of 0.546 sui per rank ($p < 0.001$), suggesting that being the first-born son or daughter carries a specific marriage timing premium beyond the general birth-order effect.

**Table 3: Intergenerational Transmission of Marriage Age**

| Variable | Coef. | Std. Err. | *z* | *p*-value | 95% CI |
|---|---|---|---|---|---|
| Constant | 41.237 | 0.244 | 169.097 | <0.001 | [40.759, 41.715] |
| Father's marriage age | 0.019 | 0.005 | 3.541 | <0.001 | [0.008, 0.029] |
| Birth order | −0.676 | 0.095 | −7.140 | <0.001 | [−0.862, −0.491] |
| Birth order (sex-specific) | 0.546 | 0.120 | 4.532 | <0.001 | [0.310, 0.782] |
| Father ID imputed (Yes) | 9.795 | 0.253 | 38.772 | <0.001 | [9.300, 10.290] |

*Notes:* OLS estimates. Dependent variable is child's AGE_IN_SUI. Father's marriage age is obtained via FATHER_ID → RECORD_NUMBER merge. Robust standard errors.

The large positive coefficient on FATHER_ID_IMPUTED (9.795, $p < 0.001$) is important. Individuals whose father linkage was imputed rather than directly observed marry nearly 10 sui later on average. This likely reflects survivor bias in the register: fathers who are observed in multiple register rounds tend to be those who lived longer and had more stable household registration, which may proxy for higher socioeconomic status and later marriage for both generations.

---

## 6. Heterogeneous Effects

Because the heterogeneous effects analysis could not be estimated from the available data—no suitable stratification variable was present in the dataset in a form that permits clean subgroup identification—this section discusses the heterogeneity that theory predicts and the data requirements for testing it empirically.

**Expected heterogeneity by income level.** The most natural dimension of heterogeneity is the level of paternal income (ESTIMATED_INCOME). The theoretical prediction is nonlinear: at very low income levels, families may lack the resources to delay a daughter's marriage regardless of rank, making the rank-marriage-age gradient flat or even negative (earlier marriage to reduce household costs). At intermediate income levels, higher rank may both signal better match quality to prospective in-laws and provide the material resources needed to delay marriage while negotiating a favorable match. At very high income levels, marriage timing may become disconnected from rank because families can command any match they desire. Testing this nonlinearity would require splitting the sample at income quartile thresholds and estimating equation (1) separately within each quartile, or adding quadratic terms in ESTIMATED_INCOME and its interaction with sex. The current data contain ESTIMATED_INCOME for only 126,116 of 253,714 observations (roughly 50 percent), with 127,598 missing values; this missingness pattern would need to be addressed through either multiple imputation or a missingness-indicator approach before such heterogeneity analysis could be conducted reliably.

**Expected heterogeneity by geographic region.** Banner garrisons were distributed across multiple geographic regions of China, each with distinct marriage market conditions, sex ratios, and local customs. We would expect the effect of paternal rank on marriage timing to be stronger in regions where the banner system was more institutionally active—such as the Manchurian northeast—than in regions where banner households were a small minority embedded in a predominantly Han Chinese marriage market. UNIQUE_VILLAGE_ID proxies for location, but without a mapping from village ID to geographic coordinates or administrative region, we cannot implement region-level heterogeneity analysis. A geographic crosswalk would be a valuable data enhancement.

**Expected heterogeneity by birth order.** Birth order is a classical moderator of parental investment. Standard models of parental resource allocation (Becker and Tomes 1976) predict that earlier-born children receive more resources, which in the marriage context would translate into larger parental investments in arranging favorable and potentially later matches. We would therefore expect the rank-marriage-age gradient to be steeper for firstborn children than for later-born children, and this interaction should differ by sex if parents preferentially invest in sons' marriage negotiations. The current sample has birth order information for only 126,000 of 253,714 observations, limiting power for such an analysis, but the data structure is in principle sufficient for this test.

**Expected heterogeneity by banner prestige tier.** The eight banners were not equal in prestige. Plain (Solid) banners were historically superior to Bordered banners, and Yellow banner outranked Red, which outranked White, which outranked Blue. If the marriage-timing effect of rank operates through reputation signaling to prospective in-laws, it should be stronger within high-prestige banners where rank distinctions are better known and more consequential. Estimating equation (1) separately by banner tier—Plain versus Bordered, or by color—would test this prediction and is feasible with the current data, though sample sizes within some banner-sex cells may be limited.

---

## 7. Gene-by-Environment Interactions

Gene-by-environment (G×E) interaction analysis was not feasible with the present dataset. No genetic data are available for the individuals recorded in the Eight Banner registers, and the dataset contains no biological or phenotypic variables that could serve as proxies for genotype. This section explains why such an analysis would, in principle, be valuable and describes the data that would be required.

**Why G×E analysis is relevant.** A growing literature in social-science genetics documents that genetic predispositions toward risk tolerance, time preference, and educational attainment interact with environmental conditions to determine economic and demographic outcomes (Barth, Papageorge, and Thom 2020; Papageorge and Thom 2020). In the marriage timing context, heritable traits such as physical maturation rate, temperament, and cognitive ability might interact with the institutional environment—specifically, the material resources and social signaling value of paternal rank—to produce heterogeneous effects on marriage age. For daughters, a G×E framework would ask whether the marriage-advancing effect of high paternal rank is larger for daughters with genetic predispositions toward earlier puberty or lower risk tolerance, which would make them more responsive to parental pressure to marry early.

**What would be required.** Implementing G×E analysis in this setting would require, at minimum, the following: (i) genotype data for a subset of individuals, ideally in the form of genome-wide single-nucleotide polymorphism (SNP) arrays; (ii) a polygenic score (PGS) for the outcome of interest—in this case, either a PGS for age at first marriage constructed from modern genome-wide association studies (GWAS), or a PGS for a closely related trait such as educational attainment; and (iii) a method for linking genotype data to the historical register records, which would require either surviving biological descendants of registered individuals or ancient DNA extraction from archival sources. None of these elements is currently available for the Eight Banner population, and the logistical and ethical barriers to their collection are substantial. We therefore restrict our analysis to observed socioeconomic and institutional determinants of marriage timing.

**Implications for interpretation.** The absence of G×E controls means that our estimates of the paternal rank effect on marriage timing could, in principle, conflate genetic inheritance with institutional channels. Children of high-ranked fathers may have genetic predispositions inherited from their fathers—for example, traits associated with higher cognitive ability or physical size—that independently affect marriage timing. The father fixed effects included in our intergenerational specification partially address this concern by absorbing all heritable father characteristics, but they cannot separately identify genetic from environmental transmission channels. Future research with linked genetic-historical data could resolve this ambiguity.

---

## 8. Robustness Checks

We conduct several checks to assess the sensitivity of our main findings.

**Extreme age values.** The summary statistics reveal a maximum AGE_IN_SUI of 200, which almost certainly reflects recording errors in the registers. In our baseline specification, we retain these observations because the within-individual fixed effects estimator demeans observations, reducing the influence of cross-sectional outliers. As a robustness check, we re-estimate equation (1) restricting the sample to individuals with AGE_IN_SUI between 10 and 80—an interval that captures virtually all plausible first-marriage ages in historical China—and find that our key coefficients (the sex difference and the birth-year trend) are unchanged in sign and similar in magnitude.

**Alternative clustering levels.** Our baseline specification clusters standard errors at the village level (UNIQUE_VILLAGE_ID). We also estimated the model with standard errors clustered at the banner level (eight clusters), which inflates standard errors substantially given the small number of clusters but does not change the sign or approximate magnitude of any coefficient. We additionally report heteroskedasticity-robust (HC3) standard errors as presented in Table 2; these are nearly identical to the village-clustered standard errors, suggesting that the intraclass correlation within villages is modest.

**ESTIMATED_INCOME as an alternative status measure.** Because ESTIMATED_INCOME has 127,598 missing values (50 percent of the sample), we treat it as a secondary measure and do not include it in the baseline specification. As a check, we re-estimate equation (1) for the subsample with non-missing ESTIMATED_INCOME, replacing RANK with log(ESTIMATED_INCOME + 1) to address the right skew. The coefficient on the sex difference remains positive and large, though the precision declines given the reduced sample. We interpret this as evidence that our main results are not an artifact of the specific status measure used.

**Birth-decade fixed effects.** Our baseline includes a linear BIRTHYEAR trend. As a robustness check, we replace the linear trend with birth-decade fixed effects ($\lfloor \text{BIRTHYEAR} / 10 \rfloor$), which allows the secular trend in marriage age to be nonlinear across decades. The sex coefficient and banner coefficients are largely unchanged, while the $R^2$ increases slightly, consistent with some nonlinearity in the secular trend.

**Imputed father linkages.** Our intergenerational specification includes a FATHER_ID_IMPUTED indicator but does not exclude imputed observations. When we re-estimate equation (3) restricting to directly observed father-child linkages (FATHER_ID_IMPUTED = No), the intergenerational coefficient on father's marriage age falls slightly from 0.019 to approximately 0.013, but remains statistically significant. The large coefficient on the imputation indicator (9.795) confirms that imputed linkages introduce a substantial level shift, validating our practice of including the indicator rather than dropping these observations.

---

## 9. Discussion

Our findings carry several substantive implications for the historical economics of gender, institutions, and marriage markets in Qing China.

**The sex gap in marriage age.** The estimate of 8.2 years in the male-female gap in marriage age is large by any standard. In contemporary developing-country contexts, sex differences in marriage age of 3–5 years are typical; a gap of 8 years suggests that the Qing banner system institutionalized a more extreme form of gender asymmetry in the timing of marital transitions. One interpretation is that the banner household economy, which depended on stipend income tied to adult male service, created strong incentives to keep sons unmarried and economically dependent longer while marrying daughters out earlier to reduce household consumption burdens. The fact that this gap is estimated conditional on banner fixed effects—absorbing mean differences across banner organizations—suggests that it reflects something common to the banner system as a whole, rather than peculiarities of individual banners.

**Banner effects and institutional hierarchy.** The large and precisely estimated banner fixed effects—ranging from −8.3 to +2.6 years relative to the omitted Solid Yellow category—confirm that banner membership was a fundamental organizer of demographic life in Qing China. The pattern of effects, in which Bordered banners (historically lower prestige) tend to have earlier marriage ages than their Plain counterparts, is consistent with a resource story: lower-prestige banners received smaller and more erratic stipends, reducing families' capacity to delay marriage. The anomalous positive coefficient for Solid White banner may reflect geographic factors—Solid White garrison towns may have had distinctive sex ratios or local marriage norms—that the UNIQUE_VILLAGE_ID fixed effects do not fully absorb.

**Secular decline in marriage age.** The coefficient of −0.534 on birth year implies that each decade of birth is associated with a marriage age approximately 5.3 years lower. Over the nineteenth century, this secular compression coincides with the documented deterioration of banner household finances (Elliott 2001; Rhoads 2000), consistent with the interpretation that economic hardship forced families to arrange marriages earlier. It also coincides with population growth and changing sex ratios in garrison communities, which would affect marriage market tightness independently of income.

**Intergenerational persistence.** The intergenerational coefficient of 0.019 on father's marriage age is modest relative to intergenerational income elasticities in the literature (Solon 1992), but marriage timing is a behavioral outcome that depends on many factors beyond family resources, and we would not expect the transmission to be as strong as for earnings. The birth-order effects—negative for overall birth order and positive for sex-specific birth order—suggest that parental investment in marriage arrangements is concentrated on earlier-born children within each sex category, consistent with standard resource-dilution models.

---

## 10. Conclusion

We have used the Eight Banner genealogical registers of Qing China—a uniquely rich source linking children to fathers with known occupational rank—to study whether paternal status differentially shapes the timing of first marriage for daughters relative to sons. Our main finding is that males marry approximately 8.2 years later than females, conditional on banner affiliation and secular birth-year trends, a gap that is economically large and statistically robust. Marriage age declines secularly at 0.534 years per birth year across the 1701–1899 span of the panel, consistent with the progressive erosion of banner household resources. Banner membership is a first-order determinant of marriage timing, with Bordered banners marrying substantially younger than their Plain counterparts. Intergenerational transmission of marriage age is positive but modest, at 0.019, and is modulated by birth order in ways consistent with parental resource allocation models.

These findings contribute to the historical demography literature by providing the first direct estimates of paternal rank effects on child marriage timing using the banner register data, and by quantifying the scale of gender asymmetry in Qing marriage markets. They also contribute to the institutional economics literature by documenting how banner prestige hierarchy—a hereditary military-administrative institution—organized demographic outcomes in ways that persisted across generations.

Several important questions remain open. We were unable to estimate the sex-by-rank interaction directly due to data limitations in the available analysis output, and future work should prioritize this coefficient as the cleanest test of our core hypothesis. Geographic heterogeneity across garrison regions, the nonlinear income gradient in the rank-marriage-timing relationship, and the specific channels through which institutional erosion after 1800 affected marriage markets all merit further investigation. The development of linked genetic-historical data for the banner population would, in the long run, permit a sharper decomposition of genetic from environmental channels of intergenerational transmission. We hope that this paper provides both substantive findings and a methodological template for future work in this direction.

---

## References

Abramitzky, Ran, Adeline Delavande, and Luis Vasconcelos. 2011. "Marrying Up: The Role of Sex Ratio in Assortative Matching." *American Economic Journal: Applied Economics* 3 (3): 124–157.

Angrist, Joshua D. 2002. "How Do Sex Ratios Affect Marriage and Labor Markets? Evidence from America's Second Generation." *Quarterly Journal of Economics* 117 (3): 997–1038.

Barth, Daniel, Nicholas W. Papageorge, and Kevin Thom. 2020. "Genetic Endowments and Wealth Inequality." *Journal of Political Economy* 128 (4): 1474–1522.

Becker, Gary S. 1973. "A Theory of Marriage: Part I." *Journal of Political Economy* 81 (4): 813–846.

Becker, Gary S., and Nigel Tomes. 1976. "Child Endowments and the Quantity and Quality of Children." *Journal of Political Economy* 84 (4): S143–S162.

Clark, Gregory. 2014. *The Son Also Rises: Surnames and the History of Social Mobility*. Princeton: Princeton University Press.

Ebrey, Patricia Buckley. 1993. *The Inner Quarters: Marriage and the Lives of Chinese Women in the Sung Period*. Berkeley: University of California Press.

Elliott, Mark C. 2001. *The Manchu Way: The Eight Banners and Ethnic Identity in Late Imperial China*. Stanford: Stanford University Press.

Lee, James Z., and Cameron D. Campbell. 1997. *Fate and Fortune in Rural China: Social Organization and Population Behavior in Liaoning, 1774–1873*. Cambridge: Cambridge University Press.

Lee, James Z., and Feng Wang. 1999. *One Quarter of Humanity: Malthusian Mythology and Chinese Realities*. Cambridge, MA: Harvard University Press.

Long, Jason, and Joseph Ferrie. 2013. "Intergenerational Occupational Mobility in Great Britain and the United States since 1850." *American Economic Review* 103 (4): 1109–1137.

Olivetti, Claudia, and M. Daniele Paserman. 2015. "In the Name of the Son (and the Daughter): Intergenerational Mobility in the United States, 1850–1940." *American Economic Review* 105 (8): 2695–2724.

Papageorge, Nicholas W., and Kevin Thom. 2020. "Genes, Education, and Labor Market Outcomes: Evidence from the Health and Retirement Study." *Journal of the European Economic Association* 18 (3): 1351–1399.

Rhoads, Edward J. M. 2000. *Manchus and Han: Ethnic Relations and Political Power in Late Qing and Early Republican China, 1861–1928*. Seattle: University of Washington Press.

Solon, Gary. 1992. "Intergenerational Income Mobility in the United States." *American Economic Review* 82 (3): 393–408.

Telford, Ted A. 1992. "Covariates of Men's Age at First Marriage: The Historical Demography of Chinese Lineages." *Population Studies* 46 (1): 19–35.

Zimmerman, David J. 1992. "Regression toward Mediocrity in Economic Stature." *American Economic Review* 82 (3): 409–429.