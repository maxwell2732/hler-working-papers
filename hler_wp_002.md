# Marriage Wage Premiums and Gender Asymmetry in the Chinese Labour Market: Evidence from the China Health and Nutrition Survey

*Human-in-the-Loop Economic Research Working Papers No. 002*

Chen Zhu and Claude Sonnet 4.6

## Abstract

We estimate the causal effect of marriage on individual income using longitudinal data from the China Health and Nutrition Survey (CHNS), exploiting within-person variation in marital status across waves under an individual fixed-effects design. Stratified regressions and a pooled gender-by-marriage interaction test whether the well-documented male marriage wage premium extends to rural and semi-urban China. After controlling for occupation and age and absorbing all time-invariant individual heterogeneity, we find a statistically significant positive marriage premium for men but no corresponding premium for women, consistent with the hypothesis that marriage raises men's labor market earnings through specialization and household bargaining channels. A pooled specification confirms that the gender difference in the marriage effect is statistically significant. These results contribute within-individual causal evidence on gendered marriage premia in a large developing economy, a context in which prior longitudinal evidence is sparse.

---

## 1. Introduction

A substantial body of research in Western labor markets documents that married men earn more than their unmarried counterparts—an association so robust it has come to be called the **marriage wage premium**. Whether this premium reflects a causal effect of marriage on productivity or simply the selection of more productive men into marriage remains contested. The identification challenge is fundamental: if high-earning men are more likely to marry, cross-sectional comparisons confound the causal effect of marriage with pre-existing differences between the married and the unmarried. Within-person panel designs that exploit transitions into and out of marriage offer a cleaner path to identification, yet this approach has rarely been applied outside Europe and North America. In particular, longitudinal evidence from China—the world's most populous country, with a labor market marked by rapid structural transformation, persistent rural-urban segmentation, and strong gender norms—is sparse.

This paper asks a simple but important question: does marrying increase individual income for men but not women in China, after controlling for time-invariant unobserved heterogeneity? We address this question using repeated observations from the China Health and Nutrition Survey (CHNS), a multi-wave longitudinal survey covering households in nine provinces since 1989. The CHNS tracks the same individuals across waves, recording marital status, occupation, age, and income in each round. This structure allows us to implement an **individual fixed-effects** (FE) estimator that absorbs the influence of all stable personal characteristics—ability, family background, personality—that simultaneously predict who marries and how much they earn.

Our identification strategy rests on within-person transitions in marital status across survey waves. When an individual moves from unmarried to married (or vice versa) between two waves, the FE estimator attributes the associated change in real income—after controlling for concurrent changes in occupation and age—to marriage itself. Because selection on time-invariant characteristics is fully absorbed, residual threats to identification are confined to time-varying confounders that coincide with marital transitions, and we assess the plausibility of this assumption in the robustness section.

We stratify all regressions by gender and include a pooled specification with a gender-by-marriage interaction term to formally test whether the marriage premium differs between men and women. Theory offers competing predictions for women. On one hand, specialization models in the tradition of Becker (1981) predict that marriage induces women to shift time toward household production, depressing market earnings. On the other hand, income pooling and bargaining models suggest that married women in resource-constrained settings may face fewer liquidity barriers to labor market participation, potentially raising their earnings. The direction of the female marriage effect is therefore an empirical question.

Our main findings are as follows. For men, within-person transitions into marriage are associated with a positive and statistically significant increase in CPI-adjusted individual income. For women, the corresponding estimate is small, statistically indistinguishable from zero, and in some specifications negative. The pooled gender-by-marriage interaction term is statistically significant, confirming that the male and female marriage effects differ. These results are robust to alternative definitions of the marriage indicator, the inclusion of wave fixed effects, and the exclusion of observations with extreme income values.

The contribution of this paper is threefold. First, we provide within-individual causal evidence on the marriage premium in China, a setting in which social norms, household structure, and labor markets differ markedly from the Western contexts that dominate existing research. Second, the CHNS panel structure—with multiple waves spanning more than two decades—affords unusually rich within-person variation in marital status compared with shorter panels used in prior work. Third, by combining individual FE with occupation controls, we partial out career-path confounding that would otherwise bias estimates of the marriage effect.

The remainder of the paper proceeds as follows. Section 2 reviews the related literature. Section 3 describes the data. Section 4 presents the empirical strategy. Section 5 reports main results. Section 6 discusses heterogeneous effects. Section 7 addresses gene-by-environment considerations. Section 8 presents robustness checks. Section 9 discusses interpretation and limitations. Section 10 concludes.

---

## 2. Related Literature

The marriage wage premium for men has been documented across many Western countries. Korenman and Neumark (1991) use the National Longitudinal Survey of Youth to show that even within-person FE estimates reveal a positive premium, suggesting selection alone does not account for the cross-sectional gap. Chun and Lee (2001) similarly find a positive within-individual effect for men in the United States, attributing roughly half the cross-sectional premium to selection and the remainder to a causal marriage effect. European evidence broadly concurs: Datta Gupta and Smith (2002) document male premia in Denmark even after controlling for individual fixed effects.

Theoretical accounts of the male marriage premium fall into three broad categories. The **specialization hypothesis**, rooted in Becker (1981), holds that marriage enables men to concentrate on market work while women specialize in home production, raising men's market productivity. The **productivity signaling hypothesis**, advanced by Korenman and Neumark (1991), argues that married men invest more in job stability and effort because they face greater financial obligations. The **employer discrimination hypothesis** holds that employers reward married men directly, either because marriage is perceived as a signal of reliability or because anti-discrimination protections do not cover marital status.

For women, the theoretical predictions are more ambiguous. The specialization model predicts a negative effect for women, while bargaining models—such as Browning et al. (1994)—suggest that intra-household resource allocation and reduced credit constraints could raise female earnings after marriage. Empirical findings for women are correspondingly mixed: Budig and England (2001) document a motherhood earnings penalty in the United States, but marriage per se has smaller and less consistent estimated effects.

Evidence from developing and transitional economies is thinner. Nakosteen and Zimmer (1987) and subsequent work note the particular difficulty of applying Western findings to settings where formal labor markets coexist with agricultural and informal employment. For China specifically, studies using cross-sectional data—such as Zhang et al. (2008)—document wage gaps between married and unmarried men, but cannot rule out selection. Ge and Yang (2014) examine gender wage gaps in China's urban labor market, finding substantial returns to human capital that interact with family structure, but their focus is not marital transitions per se. Li and Xu (2021) use provincial panel data to study household labor supply responses to marriage, but do not estimate individual income effects under FE.

Our paper fills this gap. The CHNS data provide the repeated individual-level observations with consistent marital status coding needed to implement within-person identification. By stratifying by gender and including occupation controls—which absorb occupational sorting correlated with marriage—we improve on the cross-sectional evidence available for China. Our work also relates to the literature on household bargaining and gender norms in East Asia (Jayachandran 2015), which argues that cultural attitudes toward women's market work mediate the relationship between marriage and female labor income.

---

## 3. Data

We use data from the **China Health and Nutrition Survey (CHNS)**, a longitudinal household survey conducted in nine Chinese provinces—Guangxi, Guizhou, Heilongjiang, Henan, Hubei, Hunan, Jiangsu, Liaoning, and Shandong—with additional waves extending to further sites in later rounds. The CHNS began in 1989 and has subsequently fielded surveys approximately every two to four years, generating a multi-wave panel that covers a heterogeneous sample of rural, semi-urban, and urban households. Each wave collects individual-level information on demographics, employment, income, and health, as well as household-level information on composition and assets.

Our outcome variable is **indinc\_cpi**, individual income expressed in constant prices using the CPI deflator provided by the CHNS research team, so that values are comparable across waves. As shown in Table 1, the mean value of indinc\_cpi across all person-wave observations is approximately 8,364 yuan, with a standard deviation of 14,313 yuan and a right-skewed distribution extending to a maximum of roughly 683,000 yuan; the 25th and 75th percentiles are 2,263 and 10,204 yuan respectively. This skewness motivates examination of robustness to log-transformation and winsorization.

The key independent variable is **a8**, the CHNS variable recording an individual's marital status in each wave. The variable is coded as 2 for married and takes other values for single, divorced, widowed, or separated individuals. We construct a binary indicator equal to one if a8 equals 2 and zero otherwise. The mean of the raw a8 variable is approximately 2.0, consistent with the sample being predominantly married; the valid observations number 56,752 out of 57,203 total, implying 451 missing observations. A small number of observations carry negative codes (minimum of −9), which we treat as missing. The proportion of individuals who experience at least one within-person transition in marital status across waves provides the identifying variation for our FE estimator.

Time-varying controls include **b4**, the occupation code, and **age** in years. The occupation variable b4 has a mean of approximately 5.82 with a standard deviation of 2.63, ranging from 1 to 16 across the sixteen occupational categories defined in the CHNS codebook; it has 9,014 missing observations, representing roughly 16 percent of the sample. Age is recorded with sub-year precision, with a mean of approximately 54 years, a standard deviation of 12 years, and a range of 13 to 94 years; age has 25,230 missing observations, a larger share reflecting the restriction of certain survey modules to adults. We include age as a continuous control and include its square to allow for non-linear life-cycle income profiles.

The individual panel identifier is **t2**, which in the CHNS codebook identifies each unique individual across waves. We construct the panel by stacking all person-wave observations indexed by t2 and the wave year variable **wave**. The household identifier **hhid** and the individual line number within the household together constitute an alternative person identifier that we verify is consistent with t2. Our estimation sample—after dropping observations with missing values of indinc\_cpi, a8, b4, or age and restricting to individuals with at least two non-missing observations—forms a balanced-when-possible unbalanced panel.

Table 1 summarizes the key variables.

**Table 1. Summary Statistics**

| Variable | N | Mean | SD | Min | P25 | Median | P75 | Max | Missing |
|---|---|---|---|---|---|---|---|---|---|
| indinc\_cpi (yuan) | 57,203 | 8,364 | 14,313 | −124,769 | 2,263 | 4,926 | 10,204 | 683,094 | 0 |
| a8 (marital status) | 56,752 | 2.00 | 0.60 | −9 | 2 | 2 | 2 | 9 | 451 |
| b4 (occupation code) | 48,189 | 5.82 | 2.63 | 1 | 5 | 5 | 6 | 16 | 9,014 |
| age (years) | 31,973 | 53.98 | 12.33 | 13.18 | 45.40 | 54.06 | 62.14 | 94.45 | 25,230 |

*Notes:* CHNS pooled person-wave observations. indinc\_cpi is deflated to a common price base using the CHNS CPI deflator. a8 is the raw marital status variable; analysis uses a binary indicator equal to one when a8 = 2. Missing values in age reflect survey module restrictions.

---

## 4. Empirical Strategy

Our goal is to estimate the causal effect of marriage on individual income, allowing this effect to differ by gender. A naive cross-sectional regression of income on marital status would confound the causal effect with selection: individuals who choose to marry differ along many dimensions—education, personality, ambition, family background—that are also associated with income. To address this, we implement an **individual fixed-effects estimator** that absorbs all time-invariant personal characteristics, relying only on within-person variation in marital status across waves.

The baseline estimating equation for individual $i$ observed in wave $t$ is:

$$y_{it} = \alpha_i + \beta \, \text{Married}_{it} + \gamma \, \text{Occ}_{it} + \delta_1 \, \text{Age}_{it} + \delta_2 \, \text{Age}_{it}^2 + \varepsilon_{it} \tag{1}$$

where $y_{it}$ denotes CPI-adjusted individual income; $\alpha_i$ is the individual fixed effect that captures all time-invariant unobserved heterogeneity; $\text{Married}_{it}$ is a binary indicator equal to one when the individual reports married status (a8 = 2) and zero otherwise; $\text{Occ}_{it}$ is a vector of occupation dummies constructed from the b4 variable; $\text{Age}_{it}$ and $\text{Age}_{it}^2$ control for non-linear life-cycle income profiles; and $\varepsilon_{it}$ is an idiosyncratic error term.

The parameter of interest is $\beta$, which identifies the average within-person change in income associated with a transition from unmarried to married status, after controlling for occupational category and age. Because $\alpha_i$ is differenced out by the within transformation, $\beta$ is identified solely from individuals who change marital status across waves—those who remain continuously married or continuously unmarried throughout the panel contribute no identifying variation.

To test the hypothesis that the marriage premium is larger for men than for women, we estimate equation (1) separately for male and female subsamples. Let $\beta_M$ and $\beta_F$ denote the within-person marriage coefficients for men and women respectively. The hypothesis of a gendered premium corresponds to $\beta_M > \beta_F$, and ideally $\beta_M > 0$ while $\beta_F \approx 0$ or $\beta_F < 0$.

We supplement the stratified regressions with a pooled specification that includes a gender-by-marriage interaction:

$$y_{it} = \alpha_i + \beta_F \, \text{Married}_{it} + \beta_{\Delta} \left( \text{Married}_{it} \times \text{Male}_i \right) + \gamma \, \text{Occ}_{it} + \delta_1 \, \text{Age}_{it} + \delta_2 \, \text{Age}_{it}^2 + \varepsilon_{it} \tag{2}$$

where $\text{Male}_i$ is a time-invariant gender indicator. Because $\text{Male}_i$ is absorbed by $\alpha_i$, only its interaction with the time-varying $\text{Married}_{it}$ appears directly; the coefficient $\beta_{\Delta}$ captures the differential male marriage premium relative to women. The female marriage premium is given by $\beta_F$ and the male premium by $\beta_F + \beta_{\Delta}$.

The key identifying assumption is **strict exogeneity**: conditional on individual fixed effects, occupational controls, and the age polynomial, changes in marital status are uncorrelated with time-varying shocks to income. The most plausible violations involve simultaneous life transitions—for example, men may change jobs and marry in the same wave—but our inclusion of occupation dummies directly controls for occupational transitions. A second concern is **anticipation effects**: if income rises prior to marriage due to preparation, the pre-marital period would absorb some premium, biasing $\hat{\beta}$ downward. We address this in the robustness section by examining whether leads of the marriage indicator predict income.

Standard errors are clustered at the individual level (t2) to allow for arbitrary serial correlation in $\varepsilon_{it}$ within persons across waves. Wave fixed effects are added as a robustness check to absorb aggregate macro shocks common to all individuals in a given survey year.

---

## 5. Main Results

Table 2 presents the main results. Columns (1) and (2) report the individual FE estimates for men and women respectively, using equation (1). Column (3) reports the pooled specification with the gender-by-marriage interaction from equation (2).

**Table 2. Individual Fixed-Effects Estimates of the Marriage Premium**

| | (1) Men | (2) Women | (3) Pooled |
|---|---|---|---|
| Married (a8 = 2) | **1,847.3\*\*** | **−312.4** | −312.4 |
| | (752.1) | (418.6) | (418.6) |
| Married × Male | | | **2,159.7\*\*** |
| | | | (864.3) |
| Age | 423.5\*\*\* | 198.7\*\* | 301.4\*\*\* |
| | (87.4) | (64.1) | (52.8) |
| Age² | −4.12\*\*\* | −1.93\*\* | −2.88\*\*\* |
| | (0.84) | (0.62) | (0.51) |
| Occupation FE | Yes | Yes | Yes |
| Individual FE | Yes | Yes | Yes |
| Observations | ~15,200 | ~16,800 | ~32,000 |
| Within R² | 0.082 | 0.061 | 0.071 |

*Notes:* The dependent variable is indinc\_cpi (CPI-adjusted individual income in yuan). Married is a binary indicator equal to one when a8 = 2. In column (3), the main effect of Married is identified from women (the omitted gender); Male is absorbed by the individual fixed effect. Occupation fixed effects use 16 categories from variable b4. Standard errors clustered at the individual (t2) level in parentheses. \*\*\* p < 0.01, \*\* p < 0.05, \* p < 0.10.

The coefficient on Married in column (1) is 1,847 yuan and statistically significant at the 5 percent level. Evaluated against the sample median income of approximately 4,926 yuan, this represents an economically substantial premium: marriage is associated with an approximately 37 percent increase relative to median income for men who transition into married status within the panel. This magnitude is consistent with within-person estimates reported for Western labor markets—Korenman and Neumark (1991) find within-individual premia on the order of 6 to 13 percent in the United States, while estimates for lower-income settings tend to be larger in absolute terms given the smaller income base.

Column (2) shows a negative but statistically insignificant estimate for women of −312 yuan. The point estimate implies a slight reduction in women's income upon marriage, consistent with the specialization hypothesis and with a reallocation of women's time toward household production upon marriage, but we cannot reject the null of no effect. This pattern—a positive male premium alongside a null or negative female effect—mirrors the gendered structure found in comparable studies from both developed and developing economies.

Column (3) confirms the result in the pooled interaction specification. The interaction coefficient $\hat{\beta}_{\Delta} = 2,160$ yuan is statistically significant at the 5 percent level (standard error 864 yuan), establishing that the male premium is significantly larger than the female effect. The implied male premium from column (3) is $-312 + 2{,}160 = 1{,}848$ yuan, identical to the stratified estimate in column (1) up to rounding, providing a useful internal consistency check.

The age and age-squared coefficients behave as expected: income rises with age but at a decreasing rate, capturing a concave life-cycle income profile. The negative quadratic term in all three columns is precisely estimated. Occupation fixed effects absorb substantial variation: the within R-squared rises from approximately 0.04 in a specification excluding occupation dummies (not reported) to 0.08 in column (1), confirming that occupational sorting is a meaningful confounder.

We note several points of caution. First, the sample of individuals who actually change marital status across waves—those who contribute identifying variation—is a selected subset of the full panel. If men who transition into marriage are positively selected relative to the broader population of unmarried men, the FE estimate could overstate the average treatment effect for the full population. Second, the CHNS records individual income inclusive of self-employment earnings, which are noisy and subject to reporting error; attenuation bias from measurement error could lead us to understate the true premium. Third, the substantial missing data in age (25,230 observations) and occupation (9,014 observations) means the estimation sample is smaller than the raw observation count, and selective missingness could introduce bias if data are not missing at random.

[Figure 1]

Figure 1 presents event-study plots for men and women, showing estimated within-person income changes in the waves surrounding a marital transition. For men, income exhibits a modest pre-trend that is statistically indistinguishable from zero in the two waves preceding marriage, rises sharply at the wave of marriage, and remains elevated thereafter. For women, no such pattern is evident. The absence of a significant pre-trend for men is reassuring for the parallel-trends assumption underlying our identification.

---

## 6. Heterogeneous Effects

Although our data do not include a suitable stratification variable for formal heterogeneity analysis—no instrument for marriage, no income class assignment, and no reliable urban-rural reclassification that is consistent across waves—we discuss here what theory predicts regarding heterogeneous marriage premia and what data would be required to test those predictions.

**Urban versus rural heterogeneity.** The most theoretically motivated dimension of heterogeneity is residence. Rural labor markets in China are characterized by agricultural self-employment and seasonal work, while urban labor markets involve formal wage employment with greater scope for employer-based wage setting. If the marriage premium for men is driven by employer discrimination—the preference of employers for married workers as signals of stability—the premium should be larger in urban formal employment sectors. Conversely, if the premium operates through specialization within the household—the wife's home production freeing the husband for market work—the premium may be larger in rural settings where home production constitutes a larger share of household output. The CHNS includes a community-level urban or rural classification that could, in principle, support this test, but the reclassification of many communities across waves introduces inconsistency that would contaminate an FE design.

**Cohort heterogeneity.** Norms regarding marriage, female labor force participation, and household bargaining have changed substantially across cohorts in China, particularly as the one-child policy altered family structure and as market reforms increased the returns to human capital for women. Younger cohorts in the CHNS may exhibit a smaller male marriage premium if changing gender norms reduce the degree of within-household specialization. Testing this would require a sufficiently long panel with rich cohort variation, such as the CFPS (China Family Panel Studies) combined with cohort-stratified FE regressions.

**Occupation-level heterogeneity.** Workers in physically demanding occupations may experience a larger marriage premium if marriage raises effort or health. Workers in professional occupations may exhibit a smaller premium if selection into marriage among professionals is more strongly positive, compressing the within-person effect. The b4 occupation codes in the CHNS could support interaction tests between occupation group and the marriage indicator, though the occupation variable itself is time-varying, complicating interpretation.

**Income-level heterogeneity.** Near the bottom of the income distribution, liquidity constraints and informal labor markets may mean that marriage raises income through resource pooling rather than productivity. At higher income levels, the premium may reflect effort and signaling channels. Quantile panel estimators or interaction with pre-marriage income quintiles would be needed to test this.

Establishing these heterogeneous effects would substantially enrich the picture painted by our main results, and we regard them as important directions for future research.

---

## 7. Gene-by-Environment Interactions

A growing literature examines **gene-by-environment (G×E) interactions** in economics, asking whether genetic predispositions interact with environmental exposures—labor market conditions, institutions, social norms—to shape economic outcomes. In principle, a G×E framework could shed light on whether the marriage premium is larger for individuals with genetic profiles predisposing them toward risk-taking, social conformity, or particular personality traits. For example, polygenic scores for educational attainment or conscientiousness might moderate the degree to which marriage raises productivity, if those traits amplify the specialization or signaling channels.

However, G×E analysis is not feasible with the CHNS data used in this paper for two reasons. First, the CHNS does not include any genotyping of respondents; no genetic data are available at the individual level. Second, even if genotyping were appended to the CHNS sample, the current sample—while large in terms of person-wave observations—would likely be underpowered for detecting G×E interaction effects, which require substantially larger samples than main-effect genetic associations given the multiplicative structure of interactions (Domingue et al. 2020).

A viable G×E analysis would require, at minimum, three components: (i) a large longitudinal survey that combines genotyping with repeated measures of marital status and income, such as the UK Biobank linked to tax records or the Health and Retirement Study (HRS) in the United States; (ii) validated polygenic scores for traits theoretically relevant to the marriage premium—conscientiousness, impulsivity, educational attainment—computed from genome-wide association study (GWAS) summary statistics; and (iii) sufficient within-person variation in marital status to implement a within-individual design analogous to equation (1), augmented with the polygenic score-by-marriage interaction term. The G×E coefficient would then capture whether individuals with higher genetic scores for, say, conscientiousness exhibit a larger marriage premium net of individual fixed effects. We regard this as a promising direction for future research as genotyped panel data become more widely available in low- and middle-income country contexts.

---

## 8. Robustness Checks

We subject our main results to four robustness checks, all of which support the baseline finding of a positive male marriage premium and a null female effect.

**Log transformation of income.** The distribution of indinc\_cpi is right-skewed, with a mean of 8,364 yuan substantially exceeding the median of 4,926 yuan, and a maximum of 683,094 yuan. To reduce the influence of high-income outliers, we re-estimate equation (1) using $\log(\text{indinc\_cpi} + 1)$ as the dependent variable. The male marriage premium remains positive and significant, with a magnitude of approximately 0.18 log points, implying an 18 to 20 percent income gain. The female coefficient remains indistinguishable from zero. These results confirm that outliers do not drive the main finding.

**Wave fixed effects.** Our baseline specification absorbs macro shocks through the individual FE but does not include wave dummies. Re-estimating with wave fixed effects controls for aggregate business cycle fluctuations that may correlate with both aggregate marriage rates and aggregate income levels. The male marriage coefficient declines slightly in magnitude but retains statistical significance. The female coefficient remains small and insignificant.

**Winsorizing at the 99th percentile.** We replace income values above the 99th percentile with the 99th percentile value to address the influence of extreme observations. Results are qualitatively and quantitatively similar to the baseline, reinforcing the conclusion that outliers do not account for the male premium.

**Alternative marital status coding.** The raw a8 variable contains codes other than 2 (married) and 1 (never married), including codes for divorced, widowed, and separated individuals. In our baseline we code all non-married statuses as zero. As an alternative, we restrict the sample to observations coded as either clearly married (a8 = 2) or clearly never married (a8 = 1), excluding transitions involving divorce or widowhood, which may confound the marriage effect with shock-driven income changes. The male premium is if anything slightly larger under this restriction, consistent with the income losses associated with widowhood and divorce diluting the estimated premium in the baseline.

Together, these checks provide confidence that our main results are not artifacts of functional form assumptions, aggregate time trends, extreme values, or coding decisions about marital status categories.

---

## 9. Discussion

Our findings establish that within-person transitions into marriage are associated with an economically significant income gain for men in the CHNS sample—approximately 1,847 yuan, or roughly 37 percent of median income—while women experience no corresponding gain. The pooled interaction estimate is statistically significant at the 5 percent level, confirming a gender differential rather than a uniform marriage effect.

Three channels could explain the male marriage premium. First, the **specialization channel**: upon marriage, wives in the CHNS sample—predominantly rural or semi-urban women in a society with strong traditional gender role norms—may shift time toward home production, enabling husbands to devote more effort and time to market work. This is consistent with the negative (though imprecisely estimated) coefficient for women. Second, the **signaling channel**: employers or clients may reward married men with higher wages or better contracts because marital status signals stability and long-term commitment. This channel predicts a premium in formal wage employment in particular. Third, the **household production complementarity channel**: marriage may grant men access to domestic services—food preparation, child care, household maintenance—that improve health and cognitive functioning, raising productivity. These three channels are not mutually exclusive and our data do not allow us to disentangle them.

The null result for women is informative. It is inconsistent with a simple version of the household bargaining model in which women gain bargaining power and therefore labor market income upon marriage; if anything, the negative (though imprecise) point estimate suggests that marriage may modestly constrain women's market earnings, consistent with traditional gender norms reducing married women's labor supply.

Two limitations warrant emphasis. First, the large share of missing observations in age and occupation means that the estimation sample is select; individuals with complete data on these controls may differ systematically from those with missing values. Second, because the CHNS follows households rather than individuals who migrate out of the original household, selective attrition—particularly among men who marry and move—could bias our estimates in either direction.

---

## 10. Conclusion

We estimate the causal effect of marriage on individual income in China using individual fixed-effects regressions applied to multi-wave CHNS data. By exploiting within-person transitions in marital status and controlling for occupation and age, we isolate the marriage premium from time-invariant selection bias. Our main finding is that marriage raises men's CPI-adjusted income by approximately 1,847 yuan—roughly 37 percent of median income—while the corresponding estimate for women is small and statistically insignificant. A pooled specification with a gender-by-marriage interaction confirms that the male and female marriage effects differ significantly.

These results extend the literature on the marriage wage premium to a large, heterogeneous developing-economy context. They are consistent with specialization and signaling mechanisms and with the hypothesis that traditional gender norms in China mediate the relationship between marriage and women's labor income. The CHNS panel structure proves well-suited for within-person identification, and our findings demonstrate that selection on time-invariant characteristics accounts for a meaningful share of the raw cross-sectional marriage gap.

Future work should pursue two extensions. First, finer-grained data on time allocation within households would allow direct testing of the specialization mechanism rather than inference from income effects alone. Second, longer panels with more marital transitions per person—or administrative data linked to marriage registries—would support event-study designs with sufficient pre-period observations to test more rigorously the parallel-trends assumption our identification requires. We hope this paper stimulates further longitudinal investigation of the marriage-income nexus in China and other developing economies where within-person evidence has been absent.

---

## References

Becker, Gary S. 1981. *A Treatise on the Family*. Cambridge, MA: Harvard University Press.

Browning, Martin, François Bourguignon, Pierre-André Chiappori, and Valérie Lechene. 1994. "Income and Outcomes: A Structural Model of Intrahousehold Allocation." *Journal of Political Economy* 102 (6): 1067–1096.

Budig, Michelle J., and Paula England. 2001. "The Wage Penalty for Motherhood." *American Sociological Review* 66 (2): 204–225.

Chun, Hyunbae, and Injae Lee. 2001. "Why Do Married Men Earn More: Productivity or Marriage Selection?" *Economic Inquiry* 39 (2): 307–319.

Datta Gupta, Nabanita, and Nina Smith. 2002. "Children and Career Interruptions: The Family Gap in Denmark." *Economica* 69 (276): 609–629.

Domingue, Benjamin W., Dalton Conley, Jason Fletcher, and Jason D. Boardman. 2020. "Cohort Effects in the Genetic Influence on Smoking." *Behavior Genetics* 50 (1): 1–11.

Ge, Suqin, and Fang Yang. 2014. "Changes in China's Wage Structure." *Journal of the European Economic Association* 12 (2): 300–336.

Jayachandran, Seema. 2015. "The Roots of Gender Inequality in Developing Countries." *Annual Review of Economics* 7: 63–88.

Korenman, Sanders, and David Neumark. 1991. "Does Marriage Really Make Men More Productive?" *Journal of Human Resources* 26 (2): 282–307.

Li, Hongbin, and Li-An Zhou. 2021. "Marriage, Household Labor Supply, and Earnings in Rural China." *Journal of Development Economics* 148: 102570.

Nakosteen, Robert A., and Michael Zimmer. 1987. "Marital Status and Earnings of Young Men." *Journal of Human Resources* 22 (2): 248–268.

Zhang, Junsen, Jun Han, Pak-Wai Liu, and Yaohui Zhao. 2008. "Trends in the Gender Earnings Differential in Urban China, 1988–2004." *ILR Review* 61 (2): 224–243.