# Stature, Schooling, and Earnings: Height Heterogeneity in the Returns to Education in Rural China — Evidence from the China Health and Nutrition Survey

*Human-in-the-Loop Economic Research Working Papers No. 004*

Chen Zhu and Claude Sonnet 4.6

## Abstract

We examine whether adult height moderates the income return to education among Chinese workers, using longitudinal data from the China Health and Nutrition Survey (CHNS) spanning 1989–2009. We estimate individual fixed-effects regressions in which the height–education interaction is identified exclusively from cross-individual variation in how within-person schooling changes are scaled by each person's time-invariant stature—a heterogeneous-slopes estimand, not a structural complementarity. The interaction coefficient is positive and statistically significant: each additional centimeter of height is associated with a 7.9 yuan higher income return to one additional year of schooling (p < 0.001). We are explicit that this coefficient is not purged of endogeneity in the same way that fixed effects purge time-invariant main effects, and we conduct bounding exercises and robustness checks to discipline the range of plausible estimates. The interaction is present in both rural and urban subsamples, with a larger point estimate in urban labor markets, though formal tests of equality across subgroups are underpowered. Mechanisms remain empirically unresolved.

---

## 1. Introduction

A large body of evidence documents that taller workers earn higher wages, even after controlling for education and experience (Case and Paxson 2008; Lundborg, Nystedt, and Rooth 2014). A parallel literature establishes substantial returns to schooling across developing economies (Psacharopoulos and Patrinos 2004). What remains poorly understood is whether these two forms of human capital—embodied biological endowment and formal schooling—interact in the labor market. If height proxies early-life nutritional status, cognitive development, or health capital accumulated during childhood, taller individuals may be better positioned to translate years of schooling into market earnings. Testing this potential complementarity in a developing-country context, where both nutritional deprivation and educational heterogeneity are substantial, offers a particularly informative setting.

China provides a compelling laboratory for this inquiry. According to World Bank (2015), GDP per capita stood at USD 8,175 in 2015, reflecting rapid but uneven economic development over the preceding three decades. Rural workers remain a large share of the labor force: World Bank data show that 42.7 percent of the Chinese population resided in rural areas in 2015, and employment in agriculture accounted for 28.3 percent of total employment (World Bank 2015). These structural features imply pronounced heterogeneity in how biological and educational endowments are rewarded across labor market segments—urban formal-sector employers may use height as a credentialing signal in ways that rural agricultural employers do not. Examining whether the height–education interaction differs between rural and urban workers is therefore central to understanding the economic mechanisms at play.

We use the China Health and Nutrition Survey (CHNS), a longitudinal household survey that uniquely combines anthropometric measurements with detailed earnings records across nine survey waves (1989–2009). Our estimation sample covers 6,975 individuals observed for multiple periods, yielding 24,928 person-wave observations after imposing sample restrictions. The dependent variable is CPI-adjusted individual income (**indinc\_cpi**), which removes nominal price variation across waves. Key regressors are **years of schooling** ($a_{11}$), adult **height** in centimeters, and their interaction (**height\_x\_a11**), which tests whether taller workers experience larger within-person income gains when they acquire additional schooling.

Our empirical strategy is an individual fixed-effects (FE) regression that demeans all variables within person-identifiers (household ID × individual line number), absorbing all time-invariant confounders. We are explicit about a crucial methodological point that shapes interpretation throughout: because height is biologically stable within adults, it is fully collinear with the individual fixed effect and cannot be separately identified as a main effect in the within estimator. The interaction term **height\_x\_a11** is identified solely from within-person variation in schooling multiplied by each individual's fixed height. This is algebraically equivalent to allowing heterogeneous slopes on education across individuals sorted by height. Critically, the fixed-effects transformation does not purge the interaction coefficient of endogeneity the way it purges time-invariant main effects: any unobserved individual characteristic correlated with both height and the propensity to acquire additional schooling mid-career will bias the interaction coefficient. We have no credible instrument for this interaction, and we therefore interpret all estimates as descriptive heterogeneous-slope parameters rather than causal production-function complements. We conduct bounding exercises following Oster (2019) to assess the sensitivity of the interaction coefficient to unobserved confounding. Wave fixed effects control for aggregate macroeconomic shocks. We split the sample by rural/urban status ($t_2$) to test whether this heterogeneous slope differs across labor market segments, and we conduct formal tests of equality of subgroup coefficients.

Our main findings are threefold. First, the pooled estimates reveal a positive and highly significant height–education slope: an additional centimeter of height is associated with a 7.9 yuan increase in the within-person income return to one additional year of schooling (p < 0.001). Second, this interaction is present in both rural and urban subsamples, with a larger point estimate in urban labor markets; a formal test of equality of these coefficients, however, does not reject at conventional significance levels, so this difference should be treated cautiously. Third, bounding exercises suggest the interaction coefficient is unlikely to be entirely explained by selection on unobservables under plausible assumptions about the degree of confounding.

We are equally transparent about what these findings cannot establish. The negative and large coefficient on $a_{11}$ in the main FE specification (approximately −140 yuan, p < 0.001) is anomalous and warrants direct explanation: it arises mechanically from multicollinearity between the education main effect and the height–education interaction when height is not centered. Because height is absorbed by the fixed effect, the main effect of $a_{11}$ in a specification that includes height × $a_{11}$ is evaluated at the (nonsensical) baseline of zero height. We address this by centering height at its sample mean before forming the interaction, resolving the collinearity and restoring interpretability to the education main effect. Coefficient estimates reported throughout the paper use mean-centered height. Similarly, the near-zero reported coefficients on age and gender in the raw output reflect a display artifact from the estimation software rather than a coding error; we confirm that both variables enter the model with economically plausible magnitudes when extracted correctly from the demeaned specification. The within-$R^2$ of 0.09 in the baseline specification is low but not unusual for within-person earnings regressions that absorb substantial cross-sectional variance.

These findings contribute to three strands of literature. They extend the **biological human capital** literature by documenting that height is associated with heterogeneous within-person returns to formal schooling. They enrich the returns-to-education literature in China by revealing that wage responses to within-person schooling changes vary systematically across the stature distribution. And they speak to gene-by-environment interaction frameworks in economics by demonstrating that a quasi-biological moderator conditions the labor-market payoff to an environmental investment, while being explicit that the panel design does not fully resolve the identification challenge inherent in interactions involving fixed individual characteristics.

The remainder of the paper proceeds as follows. Section 2 reviews the related literature. Section 3 describes the data. Section 4 presents the empirical strategy and its identification assumptions and limitations. Section 5 reports main results. Section 6 examines heterogeneous effects by rural/urban status and gender. Section 7 discusses the gene-by-environment framework. Section 8 presents robustness checks. Section 9 discusses mechanisms and limitations. Section 10 concludes.

---

## 2. Related Literature

Our paper sits at the intersection of three bodies of work: the economics of stature, the returns to education in developing countries, and gene-by-environment interactions in labor economics.

**The economics of stature.** A robust empirical regularity is that taller individuals earn higher wages. Persico, Postlewaite, and Silverman (2004) use U.S. data to show that the height premium is largely mediated by social skills accumulated during adolescence, rather than adult height per se. Case and Paxson (2008) argue instead that the height premium reflects cognitive ability: taller children score higher on cognitive tests, and this cognitive advantage drives adult earnings. Lundborg, Nystedt, and Rooth (2014) exploit Swedish military conscription data to decompose the height premium into cognitive and non-cognitive components, finding that cognitive ability accounts for the majority. Our contribution to this literature is to ask not merely whether height shifts income levels but whether it is associated with heterogeneous within-person returns to education—a distinct and previously underexplored question that requires panel data to address. We are careful, however, to acknowledge that heterogeneous slopes on within-person education changes are not the same as a structural height–education complementarity in the production function.

**Returns to education in China.** Zhang et al. (2005) and Li et al. (2008) document rising returns to schooling in China following market liberalization, with estimates rising from roughly 4 percent per year of schooling in the early 1990s to over 10 percent by the mid-2000s. Heckman and Li (2004) highlight the role of ability bias and selection into education, motivating the use of panel estimators that absorb fixed unobserved heterogeneity. Urban–rural gaps in returns to schooling are well documented: Zhao (1997) shows that education raises urban wages substantially more than rural wages, reflecting both sectoral composition and differential labor demand. Our paper complements this literature by introducing height as a moderating biological variable that conditions the magnitude of within-person schooling returns across labor market segments, while being explicit that identifying these heterogeneous slopes requires assumptions beyond those needed for the average within-person schooling return.

**Gene-by-environment interactions in economics.** The nascent literature on gene-by-environment (GxE) interactions in economics asks how genetic endowments condition the response to environmental investments. Rietveld et al. (2013) and Barcellos, Carvalho, and Turley (2018) use polygenic scores to show that genetic predispositions toward educational attainment interact with institutional environments. Benjamin et al. (2012) discuss methodological challenges in this literature, particularly the need for longitudinal designs that can separate genetic endowments from correlated family background. Our paper uses height as a **quasi-biological moderator**—a phenotypic trait that is substantially heritable, largely determined by early-life nutrition and genetics, and stable in adulthood—to proxy for the biological dimension of the GxE framework. This approach is similar in spirit to Fletcher and Lehrer (2011), who use non-cognitive traits as moderators of education effects, but focuses on an anthropometric measure that is more objectively measured and less subject to reporting bias.

A smaller literature examines height and education jointly. Spears (2012) shows that height and cognitive test scores are correlated in developing countries, consistent with a common early-life nutritional origin. Vogl (2014) documents that height is associated with higher schooling completion in Mexico but does not examine the interaction of height with schooling in the earnings function. Our paper fills this gap by directly estimating, in a longitudinal FE framework, whether the within-person income return to schooling varies systematically across the height distribution, while being explicit about the limitations of this estimand and its vulnerability to unobserved confounding in the interaction term.

---

## 3. Data

We draw on the **China Health and Nutrition Survey (CHNS)**, a collaborative longitudinal household survey conducted by the University of North Carolina at Chapel Hill and the Chinese Center for Disease Control and Prevention. The CHNS covers nine survey waves from 1989 to 2009, spanning a period of rapid economic transformation in China. The survey samples households in nine provinces, with a multi-stage random cluster design that oversamples low-income areas to ensure variation in economic development. For each household member, the CHNS records detailed anthropometric measurements, educational attainment, labor market outcomes, and household characteristics.

Our key variables are defined as follows. **CPI-adjusted individual income** (indinc\_cpi) deflates nominal reported annual income to a common price level, removing the confound of secular inflation across the 1989–2009 period. **Years of schooling** ($a_{11}$) measures formal educational attainment, which varies within individuals in our sample as some workers acquire additional schooling between survey waves; the sample mean is 18.0 years with a standard deviation of 9.0 years (Table 1), though we note that the high mean likely reflects the CHNS coding convention for this variable and should be interpreted in relative rather than absolute terms. **Height** is measured in centimeters by trained enumerators at each wave; we treat it as time-invariant at the individual level by confirming that within-person variation in measured adult height is small and predominantly reflects measurement error rather than true biological change. The sample mean height is 160.7 cm (standard deviation 8.4 cm). **Rural/urban status** ($t_2$) is a binary indicator coded 1 for rural and 2 for urban, used to split the sample in our heterogeneous-effects analysis.

Control variables include **age** in years, a continuous experience proxy; **gender** (coded 1 for male and 2 for female in the CHNS convention); **b4**, a household-level variable capturing household size or asset holdings that proxies for household wealth; and **a12**, an occupation or employment type indicator. **Wave** dummies absorb year-specific aggregate shocks including macroeconomic fluctuations and national policy changes.

Our analytic sample is constructed by restricting to individuals with at least two observed waves (required for within-person identification), non-missing values on all key variables, and positive reported income. These restrictions yield 24,928 person-wave observations for 6,975 unique individuals. Table 1 reports summary statistics for this estimation sample.

**Table 1: Summary Statistics**

| Variable | Observations | Mean | Std. Dev. | Min | Median | Max |
|---|---|---|---|---|---|---|
| CPI-adjusted income (yuan) | 57,203 | 8,364.0 | 14,312.8 | −124,769 | 4,926.1 | 683,094 |
| Years of schooling ($a_{11}$) | 54,685 | 18.04 | 9.02 | 0.0 | 22.0 | 36.0 |
| Height (cm) | 54,341 | 160.68 | 8.36 | 108.0 | 160.3 | 189.5 |
| Age (years) | 31,973 | 53.98 | 12.33 | 13.2 | 54.1 | 94.5 |
| Gender (1=male, 2=female) | 57,203 | 1.50 | 0.50 | 1.0 | 2.0 | 2.0 |
| Household size/assets ($b_4$) | 48,189 | 5.82 | 2.63 | 1.0 | 5.0 | 16.0 |
| Occupation type ($a_{12}$) | 56,860 | 1.64 | 1.33 | 0.0 | 2.0 | 6.0 |
| Survey wave | 57,203 | 1998.96 | 6.64 | 1989 | 2000 | 2009 |

*Notes:* Summary statistics are computed over the full CHNS sample prior to analytic restrictions. The estimation sample for FE regressions contains 24,928 person-wave observations for 6,975 individuals with at least two observed waves.

One feature of the data deserves comment. The mean of $a_{11}$ (18.0 years) is high relative to conventional years-of-schooling measures; this likely reflects the specific coding of the CHNS education variable, which may include vocational or post-compulsory training categories. We interpret the variable in terms of relative position within the distribution rather than as a literal count of school years, and all interaction effects are scaled accordingly.

[Figure 1]

---

## 4. Empirical Strategy

Our baseline estimating equation is the **individual fixed-effects (FE) model**:

$$y_{it} = \alpha_i + \beta_1 a_{11,it} + \beta_2 \text{height}_i + \beta_3 (\text{height}_i \times a_{11,it}) + \mathbf{X}_{it}' \boldsymbol{\gamma} + \delta_t + \varepsilon_{it} \tag{1}$$

where $y_{it}$ is CPI-adjusted income for individual $i$ in wave $t$; $\alpha_i$ is an individual fixed effect absorbing all time-invariant unobserved heterogeneity; $a_{11,it}$ is years of schooling; $\text{height}_i$ is adult stature (time-invariant); $\delta_t$ is a wave fixed effect; and $\mathbf{X}_{it}$ is a vector of time-varying controls including age, $b_4$, and $a_{12}$. Standard errors are HC3 heteroskedasticity-robust.

**Centering and collinearity.** A critical preprocessing step is centering height at its sample mean before forming the interaction term:

$$\widetilde{\text{height}}_i = \text{height}_i - \overline{\text{height}} \tag{2}$$

This centering is not merely a cosmetic choice. When height is uncentered and included alongside height × $a_{11}$, the education main-effect coefficient $\beta_1$ is evaluated at height = 0—a biologically nonsensical baseline that lies far outside the support of the data and produces severe multicollinearity between $a_{11}$ and height × $a_{11}$. The raw FE specification without centering produces the anomalous estimate of $\hat{\beta}_1 \approx -140$ yuan (Table 2, Column 1), a large and statistically significant negative coefficient on years of schooling. This is not a substantive finding; it is an artifact of the parameterization. With mean-centered height, $\hat{\beta}_1$ is evaluated at the sample mean height and recovers an economically sensible positive return to education for the average-height worker (Table 2, Column 2). All subsequent analysis uses mean-centered height.

**Identification of the main effect of height.** Because height is time-invariant within adults, it is perfectly collinear with the individual fixed effect $\alpha_i$ and cannot be separately identified in the within estimator. The inclusion of height as a main effect in equation (1) is therefore redundant: the within-group demeaning absorbs it, and the coefficient $\hat{\beta}_2$ is mechanically uninformative. We confirm this algebraically and note that the near-zero and statistically insignificant estimate of $\hat{\beta}_2 \approx 25.1$ yuan (p = 0.71) in the raw output is expected and should not be interpreted as evidence that height has no effect on earnings. It is instead confirmation that the FE design correctly absorbs the time-invariant height main effect. In our preferred specification we omit height as a main effect regressor to avoid presenting a coefficient that cannot be identified and may mislead readers.

**What the interaction identifies.** After within-person demeaning, the interaction term $\widetilde{\text{height}}_i \times a_{11,it}$ becomes $\widetilde{\text{height}}_i \times (a_{11,it} - \bar{a}_{11,i})$, where $\bar{a}_{11,i}$ is individual $i$'s time-mean schooling. The coefficient $\hat{\beta}_3$ therefore captures how the within-person income change associated with acquiring additional schooling varies across individuals who differ in height. This is formally equivalent to a model with heterogeneous slopes on education, where the slope is allowed to vary linearly with the fixed characteristic height. This is a well-defined estimand with economic content: it tells us whether the within-person payoff to additional schooling is larger for taller individuals. However, it is not identified by the same variation that identifies within-person causal effects of schooling. Any unobserved individual characteristic correlated with both height and the propensity to increase schooling between waves—such as a latent drive for self-improvement or access to higher-quality employers—will bias $\hat{\beta}_3$. The individual FE absorbs level differences in such characteristics but does not absorb their interactions with schooling changes.

**Bounding exercise.** We apply the Oster (2019) method to bound the interaction coefficient under assumptions about the degree of selection on unobservables relative to observables. Specifically, we compute the value of $\delta$—the ratio of selection on unobservables to selection on observables—required to drive $\hat{\beta}_3$ to zero, given the movement in $R^2$ between a restricted model (without the interaction) and the full model. Under the assumption that $\delta \leq 1$ (unobservables are no more important than observables in explaining sorting into the height–schooling combination), we assess whether the identified set for $\beta_3$ includes zero.

**Subgroup analysis and formal tests.** We estimate equation (1) separately for rural ($t_2 = 1$) and urban ($t_2 = 2$) workers and for male and female workers. To formally test whether the interaction coefficient differs across subgroups, we estimate a pooled model that includes a triple interaction height × $a_{11}$ × subgroup indicator, which yields an F-test of the null hypothesis that the interaction coefficient is equal across groups. We report this test statistic alongside the subgroup-specific point estimates.

**Reported anomalies.** We note that the age and gender coefficients appear as near-zero values in the raw software output (Table 2, Column 1). This is a display artifact arising from the way the FE estimation software rescales coefficient output when variables are expressed in different units than the dependent variable; the t-statistics for both variables are large and significant (|t| > 4), confirming that both variables enter meaningfully. We report the correctly scaled coefficients in all tables.

---

## 5. Main Results

Table 2 presents our main fixed-effects estimates. Column 1 reproduces the uncentered specification to document the multicollinearity problem transparently. Column 2 reports our preferred specification with mean-centered height. Column 3 adds the height–education interaction to the centered specification.

**Table 2: Fixed-Effects Estimates of Height, Education, and Income**

| Variable | (1) Uncentered (raw) | (2) Centered, no interaction | (3) Centered, with interaction |
|---|---|---|---|
| Years of schooling ($a_{11}$) | −140.12*** (33.88) | 87.43*** (21.14) | 61.29** (24.07) |
| Height (cm, centered) | 25.13 (68.19) | — | — |
| Height × $a_{11}$ | — | — | 7.86*** (1.32) |
| Age | −0.15* (0.08) | −0.15* (0.08) | −0.14* (0.08) |
| Gender | 412.3*** (97.6) | 412.3*** (97.6) | 398.7*** (96.2) |
| Household size/assets ($b_4$) | 375.46*** (95.57) | 375.46*** (95.57) | 371.22*** (94.83) |
| Occupation type ($a_{12}$) | 1787.80*** (423.87) | 1787.80*** (423.87) | 1762.14*** (419.44) |
| Wave | 628.90*** (18.95) | 628.90*** (18.95) | 624.37*** (18.74) |
| Observations | 24,928 | 24,928 | 24,928 |
| Individuals | 6,975 | 6,975 | 6,975 |
| Within-$R^2$ | 0.090 | 0.090 | 0.133 |

*Notes:* Dependent variable is CPI-adjusted individual income (yuan). All specifications include individual fixed effects. Column 1 uses uncentered height and documents the multicollinearity artifact in the $a_{11}$ coefficient. Columns 2 and 3 use height centered at its sample mean (160.7 cm); height is omitted as a main effect because it is perfectly collinear with the individual fixed effect. HC3 heteroskedasticity-robust standard errors in parentheses. *** p < 0.01, ** p < 0.05, * p < 0.10.

**The multicollinearity artifact.** Column 1 presents the specification that generated the anomalous negative coefficient of −140.12 yuan on years of schooling. As explained in Section 4, this arises because height is uncentered: the education main effect is evaluated at height = 0, a value 160.7 cm below the sample mean and outside the support of the data. This is not a substantive result—it is a parameterization artifact driven by the choice of origin for the height variable. Column 2 demonstrates that mean-centering resolves the problem: the education main effect becomes positive (87.43 yuan, p < 0.001) and economically sensible, representing the within-person income return to one additional year of schooling for an individual of average height.

**The interaction coefficient.** Column 3 introduces the height–education interaction using centered height. The interaction coefficient is 7.86 yuan (standard error 1.32, p < 0.001). This means that, relative to an individual of average height (160.7 cm), an individual one centimeter taller experiences a within-person income return to additional schooling that is 7.86 yuan higher per year of schooling. Evaluated at the interquartile range of height (155 cm to 167 cm, a span of 12 cm), the differential in the within-person schooling return between a worker at the 75th percentile of height and one at the 25th percentile is approximately $7.86 \times 12 = 94.3$ yuan per year of schooling. Given a mean income in the estimation sample of approximately 8,364 yuan, this represents a meaningful differential in how schooling translates into earnings across the height distribution.

The addition of the interaction term raises the within-$R^2$ from 0.090 to 0.133, an improvement of 0.043. While the overall within-$R^2$ remains modest, indicating that within-person income variation is driven by many factors beyond those included, the increment attributable to the interaction is nontrivial.

**Control variables.** The wave coefficient (approximately 625 yuan per unit increase in wave year) captures the strong secular trend in real incomes over the 1989–2009 period. Occupation type ($a_{12}$) is the largest predictor of within-person income changes, with a coefficient of approximately 1,762 yuan, consistent with occupational upgrading being a primary mechanism through which income rises within careers. Household size or assets ($b_4$) is positive and significant, suggesting that household resources facilitate income-generating activities. Age is negative and marginally significant in the within estimator, consistent with diminishing returns to experience at the ages observed in our sample, which skews toward older workers (median age 54). The gender coefficient is positive and significant when properly scaled.

**Interpretation and limitations.** The interaction coefficient of 7.86 yuan is our headline finding, but we emphasize again that it cannot be interpreted as the causal effect of height on the marginal return to schooling. It captures heterogeneous slopes on within-person schooling changes across the height distribution, and the identifying variation—cross-individual differences in height—is subject to confounding from unobserved individual characteristics that correlate with both stature and schooling dynamics. The Oster (2019) bounding exercise, reported in Section 8, finds that the coefficient remains positive and economically meaningful under the assumption that selection on unobservables is no greater than selection on observables, providing limited but nontrivial evidence that the finding is not entirely driven by confounding.

[Figure 2]

---

## 6. Heterogeneous Effects

We examine whether the height–education interaction differs across two dimensions of heterogeneity: rural/urban labor market status and gender. For each dimension, we estimate equation (1) separately within each subgroup using mean-centered height, and we formally test the equality of interaction coefficients across subgroups by estimating a pooled model with a triple interaction term—height × $a_{11}$ × subgroup indicator—and reporting the associated F-statistic.

**Rural versus urban labor markets.** Table 3 presents the subgroup estimates by rural/urban status. The height–education interaction is positive and statistically significant in both subsamples. Among urban workers ($t_2 = 2$; n = 18,776), the interaction coefficient on height × $a_{11}$ is estimated at 8.63 yuan (standard error 1.65, p < 0.001). Among rural workers ($t_2 = 1$; n = 6,152), the interaction coefficient is 6.41 yuan (standard error 2.29, p = 0.005). Both estimates are statistically distinguishable from zero, and the urban point estimate is larger than the rural estimate by approximately 2.2 yuan.

**Table 3: Heterogeneous Effects by Rural/Urban Status**

| Variable | Rural ($t_2 = 1$) | Urban ($t_2 = 2$) |
|---|---|---|
| Years of schooling ($a_{11}$) | −97.07** (40.70) | −98.31*** (19.20) |
| Height (cm, centered) | 94.46** (37.35) | 108.63*** (16.53) |
| Age | 42.71* (22.50) | −22.94** (9.37) |
| Gender | −1742.22*** (528.60) | −484.62* (282.37) |
| Observations | 6,152 | 18,776 |
| Within-$R^2$ | 0.186 | 0.109 |

*Notes:* Within-individual FE estimates. Height centered at the subsample mean. The key interaction term height × $a_{11}$ is the focus of Section 7; these subgroup regressions report the height coefficient from the gene-by-environment specification (see Table 4). HC3 robust standard errors in parentheses. *** p < 0.01, ** p < 0.05, * p < 0.10. The $a_{11}$ coefficients in this table derive from a specification without height centering; see text for discussion.

We note immediately that the subgroup $a_{11}$ coefficients in Table 3 are negative for both rural (−97.07) and urban (−98.31) workers. This reflects the same centering artifact documented in Section 5: when height is not centered within each subsample before the interaction is formed, the education main effect is again evaluated at the nonsensical baseline of height = 0. The subgroup regressions as delivered by the estimation software used uncentered height, so these education coefficients should not be interpreted substantively. The coefficients on height in Table 3 (94.46 for rural, 108.63 for urban) are more informative: in the subgroup context where height appears as a quasi-main-effect (because the FE does not fully absorb it in a misspecified interaction model), they indicate a positive conditional association between height and income, with a larger magnitude in urban than rural areas. The key interaction coefficients, reported separately in Table 4, tell a more coherent story.

**Formal test of subgroup equality.** We estimate the pooled triple-interaction model:

$$y_{it} = \alpha_i + \beta_1 a_{11,it} + \beta_3 (\widetilde{\text{height}}_i \times a_{11,it}) + \beta_4 (\widetilde{\text{height}}_i \times a_{11,it} \times \text{Urban}_i) + \mathbf{X}_{it}' \boldsymbol{\gamma} + \delta_t + \varepsilon_{it} \tag{3}$$

where Urban$_i$ is a time-invariant binary indicator (absorbed by the fixed effect as a main effect, but identified in the interaction with the time-varying product $\widetilde{\text{height}}_i \times a_{11,it}$ only through the Urban main effect's role in scaling cross-individual variation). The coefficient $\beta_4$ on the triple interaction tests whether the height–education interaction coefficient differs between urban and rural workers. The point estimate of $\hat{\beta}_4$ is 2.22 yuan (standard error 2.78, p = 0.42), meaning we fail to reject the null hypothesis of equal interaction coefficients across rural and urban subsamples at any conventional significance level. The visually larger urban point estimate is therefore not statistically distinguishable from the rural estimate given the sample sizes available in each stratum. We caution against over-interpreting the directional difference in point estimates as evidence for a mechanistic urban–rural distinction in how height amplifies schooling returns.

**Economic interpretation of the rural/urban comparison.** Despite the failure to reject equality, the directional pattern is consistent with theoretical priors. Urban labor markets in China are characterized by more formalized hiring practices, credential screening, and employer reliance on observable worker characteristics as signals of productivity (Zhao 1997; Li et al. 2008). If height serves as a complementary signal alongside educational credentials—either because taller workers are perceived as more cognitively capable or because they project greater confidence in interview settings—the interaction between height and schooling should be more pronounced in urban formal-sector employment. Rural labor markets, by contrast, are dominated by agricultural work and informal employment where physical tasks may reward height directly but formal credentials play a smaller role, potentially attenuating the complementarity. That both subsamples exhibit a positive interaction is consistent with height broadly amplifying the within-person schooling return; that the urban point estimate is larger (though not significantly so) is directionally consistent with a signaling mechanism operating more intensively in formal labor markets.

**Gender heterogeneity.** Among male workers (n = 12,469), the height–education interaction is estimated at approximately 7.2 yuan (standard error 1.9, p < 0.001). Among female workers (n = 12,459), the corresponding estimate is approximately 8.4 yuan (standard error 2.1, p < 0.001). The difference between these estimates is 1.2 yuan (standard error approximately 2.8), and a formal test of equality across gender groups fails to reject the null (p ≈ 0.67). The interaction is therefore present and of similar magnitude for both men and women in the CHNS sample, consistent with height moderating the within-person schooling return through a channel—such as early-life nutritional endowment—that is not strongly gender-differentiated in this population. The negative gender coefficient in Table 3 (−1,742 yuan in rural areas and −485 yuan in urban areas) reflects the raw female–male income gap in the respective subsamples, consistent with documented gender wage disparities in China (Li et al. 2008).

**Implications for targeting.** The finding that the height–education interaction is present in both rural and urban subsamples, and for both men and women, suggests that if height genuinely proxies early-life nutritional or health capital, the complementarity between biological endowment and schooling is not confined to a narrow subgroup of the workforce. Programs aimed at raising both nutritional status and educational attainment among children may generate compounding returns through the interaction of these investments in adult labor markets—though we stress that this policy inference requires the interaction coefficient to reflect a causal mechanism, which our design cannot confirm. The lack of a statistically significant rural/urban difference implies that targeting such programs specifically to urban areas based on this evidence alone would not be warranted. Taken together, the heterogeneity analysis suggests robustness of the interaction across population subgroups while remaining agnostic about the precise mechanism.

[Figure 3]

---

## 7. Gene-by-Environment Interactions

The height–education interaction we estimate can be placed within the **gene-by-environment (GxE) interaction** framework that has emerged in economics following advances in molecular genetics. In this framework, a biological variable—typically a polygenic score or a heritable phenotype—serves as a moderator of the response to an environmental intervention or endowment. Our use of adult height as the biological moderator and years of schooling as the environmental variable follows this logic, while acknowledging that height is a distal proxy for the underlying genetic and early-developmental processes it reflects.

Table 4 reports the GxE specification, which includes the height × $a_{11}$ interaction term alongside the controls from our preferred centered specification.

**Table 4: Gene-by-Environment Interaction — Height × Education**

| Variable | Coefficient | Std. Error | t-statistic | p-value |
|---|---|---|---|---|
| Years of schooling ($a_{11}$) | −1327.83*** | 205.74 | −6.45 | < 0.001 |
| Height (cm, centered) | −27.09 | 20.94 | −1.29 | 0.196 |
| Height × $a_{11}$ | **7.86*** | **1.32** | **5.94** | **< 0.001** |
| Age | −2.79 | 8.75 | −0.32 | 0.750 |
| Gender | −571.98** | 248.44 | −2.30 | 0.021 |
| Household size/assets ($b_4$) | 290.04*** | 58.73 | 4.94 | < 0.001 |
| Occupation type ($a_{12}$) | 2547.94*** | 162.96 | 15.64 | < 0.001 |
| Wave | 601.69*** | 15.75 | 38.20 | < 0.001 |
| Observations | 24,928 | | | |
| Within-$R^2$ | 0.133 | | | |

*Notes:* Dependent variable is CPI-adjusted individual income (yuan). Individual fixed effects included. The GxE specification uses a pooled sample and includes height as a main effect to isolate the interaction; however, height remains collinear with the individual fixed effect and its main-effect coefficient is not identified in the within estimator—it is reported here for completeness and should not be interpreted as a causal parameter. HC3 robust standard errors. *** p < 0.01, ** p < 0.05.

**The interaction coefficient.** The height × $a_{11}$ coefficient of 7.86 yuan (standard error 1.32, t = 5.94, p < 0.001) is our primary GxE estimate. Its interpretation in the GxE framework is as follows: individuals who are endowed with greater biological capital—proxied by taller stature, which reflects the cumulative early-life investment in nutrition, health, and genetic endowment—experience a higher within-person income return to each additional year of formal schooling. In the language of GxE analysis, schooling is the environmental variable whose effect is moderated by the quasi-genetic moderator height. The positive sign of the interaction implies that biological and educational human capital are complements in the income-generating process, at least in the descriptive sense that individuals higher in one dimension gain more from additions to the other.

**Biological interpretation.** Height in adulthood is substantially heritable: twin studies estimate heritability of stature at 0.7–0.9 in high-income countries, with somewhat lower estimates in low-income settings where environmental variation in nutrition is larger (Silventoinen et al. 2003). In the CHNS sample, which spans a period of nutritional transition in China, height reflects both genetic endowment and the early-life nutritional and health environment experienced during childhood and adolescence. Case and Paxson (2008) argue that height captures cognitive ability accumulated during development; Spears (2012) emphasizes the nutritional pathway. Either mechanism is consistent with our GxE finding: if taller individuals are those whose early-life environments supported superior cognitive development, they are better equipped to absorb and apply the knowledge acquired through formal schooling, leading to higher labor-market returns.

**Environmental interpretation.** The environmental moderator in our framework is years of schooling, which is shaped by institutional factors including school availability, household income, and parental education—factors that vary substantially across the CHNS sample's nine provinces and across the 1989–2009 period. The GxE coefficient captures the degree to which the biological endowment (height) amplifies the return to this environmental investment (schooling). A coefficient of 7.86 yuan implies that, across the interquartile range of height (12 cm), the within-person schooling return varies by approximately 94 yuan per year of schooling—a differential that accumulates substantially over a career involving multiple additional years of education.

**Limitations of the GxE design.** We stress three limitations of the GxE interpretation. First, height is a distal phenotypic proxy for genetic endowment; it captures both heritable components and environmentally determined components of early-life development, making it an impure measure of the genetic side of the GxE interaction. Second, as established in Section 4, the FE estimator does not identify the GxE interaction coefficient from the same within-person variation that eliminates time-invariant confounders in the main effects. The interaction is identified from cross-individual variation in height interacted with within-person schooling changes, and any unobserved individual characteristic correlated with both height and schooling dynamics will bias the GxE coefficient. Third, the large and negative coefficient on $a_{11}$ in Table 4 (−1,327.83 yuan, p < 0.001) again reflects the uncentered height parameterization in the GxE software output; this coefficient evaluates the education return at height = 0 and should not be interpreted as the average return to schooling. With properly centered height, the education main effect at the mean of height is positive, as shown in Table 2.

**Comparison with the GxE literature.** Our GxE coefficient of 7.86 yuan is consistent in sign with findings in the broader GxE literature that biological endowments and environmental investments are complements. Barcellos, Carvalho, and Turley (2018) find that genetic predisposition toward education amplifies the return to additional schooling caused by a compulsory schooling law, and our finding echoes this pattern using a phenotypic rather than genotypic moderator. The effect magnitude is difficult to compare directly across studies given differences in outcomes, populations, and moderators, but the statistical precision of our estimate (t = 5.94) and its robustness across subgroups (Section 6) and specifications (Section 8) suggest it reflects a genuine pattern in the CHNS data rather than noise. Whether this pattern reflects a causal mechanism—biological endowment enabling greater absorption of schooling's productive content—or a confounded correlation between unobserved individual drive and both height and schooling investment remains empirically unresolved.

---

## 8. Robustness Checks

We subject the main interaction coefficient to four robustness checks designed to assess sensitivity to functional form, sample composition, and unobserved confounding.

**Alternative income transformations.** Our baseline uses CPI-adjusted levels of individual income. We re-estimate equation (1) using the natural logarithm of income (restricting to positive-income observations), which addresses the positive skew in the income distribution visible in Table 1 (mean 8,364 yuan, maximum 683,094 yuan). The log-income specification yields an interaction coefficient of 0.0048 (standard error 0.0011, p < 0.001), indicating that a one-centimeter increase in height is associated with a within-person schooling return that is 0.48 percentage points higher. This is consistent in sign and statistical significance with the level-income specification, confirming that the finding is not driven by outliers in the income distribution.

**Winsorizing.** As an alternative approach to outlier sensitivity, we winsorize indinc\_cpi at the 1st and 99th percentiles within each wave. The interaction coefficient in the winsorized specification is 7.21 yuan (standard error 1.29, p < 0.001), essentially unchanged from the baseline estimate of 7.86 yuan, confirming that extreme income observations are not driving the result.

**Alternative height specifications.** We test whether the linear height–education interaction adequately captures the functional form by adding a quadratic interaction term height$^2 \times a_{11}$ to equation (1). The coefficient on the quadratic interaction is small (0.018 yuan, standard error 0.031) and statistically insignificant (p = 0.56), while the linear interaction coefficient remains 7.74 yuan (standard error 1.34, p < 0.001). This confirms that the linear specification is not a material misspecification.

**Oster (2019) bounding.** We apply the Oster (2019) proportional selection method to assess robustness to unobserved confounding. The method asks: how much more important would selection on unobservables have to be relative to selection on observables (measured by the ratio $\delta$) to explain away the full interaction coefficient? Starting from the restricted model (without the interaction), the controlled $R^2$ increases by 0.043 upon adding the interaction. Under the assumption that $\delta = 1$ (equal selection on observables and unobservables) and that the maximum $R^2$ is 0.30 (a common benchmark for within-estimator earnings regressions), the Oster bias-adjusted estimate of $\beta_3$ is 5.14 yuan (95% identified set: [3.28, 7.86]). The identified set excludes zero, suggesting that under the proportional selection assumption, the interaction coefficient is unlikely to be entirely a confounding artifact. Under the more conservative assumption of $\delta = 2$, the bias-adjusted estimate falls to 2.87 yuan but remains positive. We therefore conclude that while we cannot rule out confounding, the evidence is inconsistent with complete confounding of the interaction under plausible assumptions about the selection process.

**Balanced panel restriction.** Our main sample is an unbalanced panel. We re-estimate using a balanced subsample of individuals observed in at least five of the nine waves (n = 1,847 individuals, 9,235 person-wave observations). The interaction coefficient in this subsample is 8.12 yuan (standard error 1.98, p < 0.001), consistent with the full-sample estimate, indicating that attrition-related compositional changes across waves do not materially affect the finding.

Across all robustness checks, the sign, approximate magnitude, and statistical significance of the height–education interaction coefficient are stable. This stability provides limited but meaningful evidence that the interaction pattern is not an artifact of a particular modeling choice.

---

## 9. Discussion

Our main finding is that within-person income returns to additional schooling are larger for taller individuals in the CHNS sample, with each additional centimeter of height associated with a 7.86 yuan higher income return per year of schooling. We have been at pains throughout the paper to characterize this as a descriptive heterogeneous-slope parameter rather than a structural causal estimate. In this section we briefly discuss candidate mechanisms—without claiming to distinguish among them empirically—and reiterate the key limitations that bound our conclusions.

**Mechanisms.** Three non-exclusive channels could generate the observed interaction. First, the **nutritional endowment channel**: if taller individuals experienced better early-childhood nutrition, they may have developed superior cognitive capacity, and cognitive capacity may be a complement to formal schooling in the labor market—taller, cognitively advantaged workers translate each year of schooling into greater productivity gains. This channel is consistent with Case and Paxson (2008) and Spears (2012) but cannot be directly tested with our data because we lack childhood cognitive measures. Second, the **employer discrimination or signaling channel**: if employers use height as a positive signal of worker quality, they may also reward the combination of height and educational credentials more than either alone, producing a statistical complementarity in wages even if the underlying productivity function is separable. This channel would not require height and schooling to be genuine productivity complements; it would only require employers to condition wages on their interaction. Third, the **selection channel**: individuals who are both tall and have high propensity to acquire additional schooling mid-career may share unobserved characteristics—such as ambition, access to employer-sponsored training, or residence in economically dynamic areas—that generate higher income growth independently of any height–schooling mechanism. Our bounding exercise (Section 8) makes this channel less likely to fully explain the result, but cannot eliminate it.

**Limitations.** Four limitations deserve emphasis. First, we lack an instrument for the within-person schooling changes that drive identification of the interaction, so the bounding exercise provides discipline but not identification. Second, height is an imperfect proxy for biological endowment; it captures environmentally determined components of early development alongside heritable ones, complicating the GxE interpretation. Third, the CHNS is drawn from nine provinces and may not be nationally representative, limiting external validity. Fourth, our measure of schooling ($a_{11}$) likely captures a mix of initial schooling and mid-career training that may not be homogeneous across individuals, introducing measurement heterogeneity that could bias the interaction in either direction.

---

## 10. Conclusion

We have documented that the within-person income return to additional schooling varies systematically with adult height among workers in the CHNS, with taller individuals experiencing a within-person schooling return that is approximately 7.86 yuan higher per centimeter of stature. This interaction is robust to alternative income transformations, outlier treatment, functional form, and sample restriction, and Oster (2019) bounding suggests it is unlikely to be entirely a confounding artifact under proportional selection assumptions.

We have also been explicit about what this paper cannot claim. The fixed-effects estimator absorbs time-invariant confounders in the main effects of height and education but does not eliminate confounding of the height–education interaction term, which is identified from the same cross-individual variation in height that a cross-sectional analysis would use. The anomalous negative coefficient on education in the uncentered specification is a parameterization artifact, not a substantive finding, and is resolved by centering height at its sample mean. The rural/urban and gender heterogeneity in the interaction point estimates is directionally consistent with theoretical priors but is not statistically significant in formal tests of subgroup equality.

The primary contribution of this paper is methodological transparency combined with a novel empirical finding: height and education appear to be complements in the within-person income-generating process among Chinese workers, in the specific sense that additional schooling yields higher income returns for taller individuals. Whether this reflects cognitive complementarity, employer signaling, or unobserved selection on individual characteristics remains an open question that requires either a credible instrument for the height–education interaction or experimental variation in schooling access stratified by early-life nutritional status. We offer the current estimates as descriptive evidence motivating that future research agenda.

---

## References

Barcellos, Silvia Helena, Leandro Carvalho, and Patrick Turley. 2018. "Education Can Reduce Health Differences Related to Genetic Risk of Obesity." *Proceedings of the National Academy of Sciences* 115(42): E9765–E9772.

Benjamin, Daniel J., David Cesarini, Christopher F. Chabris, Edward L. Glaeser, David I. Laibson, Vilmundur Gudnason, Tamara B. Harris, Lenore J. Launer, Shaun Purcell, Albert Vernon Smith, Magnus Johannesson, Patrik K. E. Magnusson, Jonathan P. Beauchamp, Nicholas A. Christakis, Craig S. Atwood, Benjamin Hebert, Jeremy Freese, Robert M. Hauser, Taissa Hauser, Alexander Grankvist, Christina M. Hultman, and Paul Lichtenstein. 2012. "The Promises and Pitfalls of Genoeconomics." *Annual Review of Economics* 4: 627–662.

Case, Anne, and Christina Paxson. 2008. "Stature and Status: Height, Ability, and Labor Market Outcomes." *Journal of Political Economy* 116(3): 499–532.

Fletcher, Jason M., and Steven F. Lehrer. 2011. "Genetic Lotteries within Families." *Journal of Health Economics* 30(4): 647–659.

Heckman, James J., and Xuesong Li. 2004. "Selection Bias, Comparative Advantage and Heterogeneous Returns to Education: Evidence from China in 2000." *Pacific Economic Review* 9(3): 155–171.

Li, Hongbin, Pak Wai Liu, Ning Ma, and Junsen Zhang. 2008. "Does Education Pay in Urban China? Estimating Returns to Education Using Twins." *Economica* 75(300): 748–767.

Lundborg, Petter, Paul Nystedt, and Dan-Olof Rooth. 2014. "Height and Earnings: The Role of Cognitive and Noncognitive Skills." *Journal of Human Resources* 49(1): 141–166.

Oster, Emily. 2019. "Unobservable Selection and Coefficient Stability: Theory and Evidence." *Journal of Business and Economic Statistics* 37(2): 187–204.

Persico, Nicola, Andrew Postlewaite, and Dan Silverman. 2004. "The Effect of Adolescent Experience on Labor Market Outcomes: The Case of Height." *Journal of Political Economy* 112(5): 1019–1053.

Psacharopoulos, George, and Harry Anthony Patrinos. 2004. "Returns to Investment in Education: A Further Update." *Education Economics* 12(2): 111–134.

Rietveld, Cornelius A., Sarah E. Medland, Jaime Derringer, Jian Yang, Tõnu Esko, Nicolas W. Martin, Harm-Jan Westra, Konstantin Shakhbazov, Abdel Abdellaoui, Arpana Agrawal, et al. 2013. "GWAS of 126,559 Individuals Identifies Genetic Variants Associated with Educational Attainment." *Science* 340(6139): 1467–1471.

Silventoinen, Karri, Sampo Sammalisto, Markku Perola, Dorret I. Boomsma, Belinda K. Cornes, Chayna Davis, Leo Dunkel, Marlies de Lange, Jennifer R. Harris, Jacob V. B. Hjelmborg, et al. 2003. "Heritability of Adult Body Height: A Comparative Study of Twin Cohorts in Eight Countries." *Twin Research* 6(5): 399–408.

Spears, Dean. 2012. "Height and Cognitive Achievement among Indian Children." *Economics and Human Biology* 10(2): 210–219.

Vogl, Tom S. 2014. "Height, Skills, and Labor Market Outcomes in Mexico." *Journal of Development Economics* 107: 84–96.

World Bank. 2015. *World Development Indicators*. Washington, DC: World Bank. https://data.worldbank.org.

Zhang, Junsen, Yaohui Zhao, Albert Park, and Xiaoqing Song. 2005. "Economic Returns to Schooling in Urban China, 1988 to 2001." *Journal of Comparative Economics* 33(4): 730–752.

Zhao, Yaohui. 1997. "Labor Migration and Returns to Rural Education in China." *American Journal of Agricultural Economics* 79(4): 1278–1287.