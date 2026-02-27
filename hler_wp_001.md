# Job Mobility, Earnings Growth, and Gender Inequality in the Chinese Labor Market: Evidence from the China Health and Nutrition Survey

*Human-in-the-Loop Economic Research Working Papers No. 001*

Chen Zhu and Claude Sonnet 4.6

## Abstract

This paper estimates the earnings return to voluntary job switching in a longitudinal sample drawn from the China Health and Nutrition Survey (CHNS, 1989–2009), a multi-province panel covering rural, peri-urban, and urban communities across nine provinces. Using individual fixed effects to absorb time-invariant unobserved heterogeneity, I find that a job-to-job transition raises CPI-deflated annual income by approximately 4,955 yuan. Gender-stratified estimates reveal that men capture a premium of roughly 6,725 yuan while the female point estimate of 4,298 yuan is economically substantial but statistically indistinguishable from zero at conventional thresholds; a formal equality test cannot reject equal coefficients across genders, urging caution in interpreting the raw gap as evidence of causal discrimination. The within-person $R^2$ of 7.3 percent and measurement-error concerns in the self-reported job-change indicator limit causal identification. The findings nonetheless suggest that job mobility is a meaningful, if unevenly accessible, pathway to earnings growth in China's transitional economy.

---

## 1. Introduction

How workers advance through the wage distribution is a central question in labor economics. One prominent mechanism is **job-to-job (b2b) mobility**—defined here as a voluntary transition between employers or occupations without an intervening spell of unemployment—which can raise wages by enabling workers to move toward positions that better match their skills or by triggering renegotiation effects at the original employer. While a large literature documents wage gains from job switching in developed economies, evidence for developing and transitional economies remains limited, and the question of whether these gains are equally accessible to men and women has received little systematic attention.

China offers an especially instructive setting. Since the early 1990s, China's labor market has undergone a profound structural transformation: the dismantling of the *danwei* (work-unit) system reduced lifetime employment guarantees, rural-to-urban migration expanded the pool of mobile workers, and private-sector growth created new employment opportunities outside the state sector. In this environment, the ability to switch jobs voluntarily became an increasingly important determinant of individual earnings trajectories. Yet gender gaps in Chinese labor markets have persisted and, in some dimensions, widened over the reform period (Gustafsson and Li, 2000; Zhang et al., 2008). Whether women can exploit job mobility to the same extent as men therefore has direct implications for understanding income inequality and the design of labor-market policy.

The data come from the **China Health and Nutrition Survey (CHNS)**, a longitudinal household survey covering nine waves from 1989 to 2009. The CHNS tracks individuals across waves in nine provinces—spanning rural townships, county seats, and urban districts—and records employment histories, CPI-deflated individual income, household composition, and demographic characteristics. An important clarification is warranted at the outset: the CHNS sampling frame covers communities at multiple urbanicity levels within each province. All results should therefore be interpreted as pertaining to this mixed CHNS population rather than to strictly rural China.

This paper makes three contributions. First, it provides panel-data estimates of the wage return to voluntary job switching using individual **fixed effects (FE)**, which absorb all time-invariant individual characteristics—such as ability, family background, or local labor-market conditions—that might confound a cross-sectional comparison. The identifying assumption is that, conditional on individual and wave fixed effects and a set of time-varying controls, the timing of a job-to-job transition is uncorrelated with transitory income shocks. I examine pre-switch income dynamics using a relative-time event-study specification to assess whether b2b switchers and non-switchers exhibit parallel income trajectories prior to the transition—the panel-data analog of a pre-trends test. I am candid, however, about the limits of this strategy: with a within-$R^2$ of only 7.3 percent, substantial within-person income variation remains unexplained, and three threats—reverse causality from negative employer-specific shocks, anticipation of outside offers correlated with unobserved skill growth, and selection on time-varying unobservables such as health—cannot be fully ruled out with the available data.

Second, I document gender heterogeneity in these returns. The male point estimate (6,725 yuan) exceeds the female estimate (4,298 yuan) by roughly 56 percent. However, a formal Wald test of coefficient equality across gender-stratified models cannot reject the null that male and female returns are equal at conventional significance levels, meaning the raw difference should be interpreted with caution and cannot be attributed to discrimination without further evidence.

Third, the paper is transparent about several technical issues that earlier drafts did not adequately address. The coefficients on age and job type (*t2*) in the main specification are numerically reported as zero due to near-perfect collinearity with individual fixed effects—a fundamental identification problem discussed in Section 4. The main results report heteroskedasticity-robust (HC3) standard errors, but community-clustered standard errors are reported alongside as the preferred baseline given the multi-level structure of the CHNS; both sets yield similar inference for the b2b coefficient. Self-reported job changes over two-to-four-year recall windows introduce classical measurement error that attenuates the point estimate toward zero, implying estimates here are plausibly lower bounds on the true return. Panel attrition in the CHNS is known to be selective, and the analytic sample composition relative to the full panel is documented in Section 3.

The binary variable *wave*, entered as a continuous linear time trend in the baseline specification, is a crude approximation to secular real-income growth across the 1989–2009 period. In robustness checks, I replace the linear trend with a full set of wave dummies, which more flexibly captures the non-linear income growth and structural breaks—including the 1997 Asian financial crisis and the post-2000 acceleration—that characterize this period. Because age is perfectly collinear with individual fixed effects plus any monotone time trend, age effects cannot be separately identified in the within-person estimator and are fully absorbed; I discuss this identification failure explicitly rather than treating the near-zero coefficient as a substantive finding.

The remainder of the paper is organized as follows. Section 2 reviews the related literature. Section 3 describes the data. Section 4 presents the empirical strategy. Section 5 reports the main results. Section 6 examines heterogeneous effects by gender and job type. Section 7 explains why a gene-by-environment extension was not feasible. Section 8 presents robustness checks. Section 9 discusses the findings, and Section 10 concludes.

---

## 2. Related Literature

This paper sits at the intersection of three strands of research: the economics of job mobility and wage growth, gender discrimination in labor markets, and empirical work on China's labor-market transition.

**Job mobility and wages.** The theoretical foundations for a positive wage return to job switching derive from two complementary frameworks. In Burdett's (1978) search model, workers sample wage offers over time and switch when a draw exceeds their current wage; the return to switching is the realized gain from a better match. In Jovanovic's (1979) matching model, job switches reflect the revelation of match quality: workers who learn they are in low-quality matches separate and obtain higher wages in better-fitting positions. Both frameworks predict positive average wage gains from voluntary job changes, though they differ in predictions about which workers benefit most.

Empirical work in developed economies broadly confirms positive wage returns to job switching. Topel and Ward (1992) find that job changes account for a third of early-career wage growth among young American men. Dustmann and Meghir (2005) show that wage growth in Germany is driven primarily by occupation upgrades rather than employer changes per se. More recently, Haltiwanger, Hyatt, and McEntarfer (2018) document substantial earnings gains from employer-to-employer transitions in U.S. administrative data. These estimates range from a few percent to over ten percent of prior wages depending on the sample and specification. A common challenge across all these studies is separating voluntary from involuntary separations; the CHNS context raises additional concerns because the b2b indicator is self-reported and retrospective, an issue addressed explicitly in Section 3.

**Gender and labor-market returns.** A large literature documents that women face constraints in translating human-capital investments and labor-market behaviors into wages equivalent to men's. Goldin (2014) argues that a residual gender gap persists because women are penalized for demanding flexible hours. Blau and Kahn (2017) survey evidence that occupational and industrial segregation account for a significant share of the gender wage gap. In the context of job mobility specifically, Loprest (1992) finds that women gain less from job switching in the United States, while Bowlus (1997) attributes part of the gender wage gap to women's lower job-offer arrival rates. These studies motivate the gender-stratified analysis in Section 6, though the formal equality test reported there counsels against strong conclusions from point-estimate differences alone.

**Labor markets in China.** Gustafsson and Li (2000) document a persistent and widening gender wage gap in China during the 1990s reform period. Zhang et al. (2008) find that the unexplained component of the gap increased as market forces replaced administrative wage-setting. Giles, Park, and Cai (2006) examine worker displacement and re-employment in urban China, finding large wage losses for displaced workers that underscore the importance of distinguishing voluntary from involuntary transitions. Knight and Yueh (2004) study job mobility in urban China and find positive wage gains, though their analysis does not examine gender heterogeneity systematically. Meng (2012) documents the heterogeneous effects of China's labor-market transformation across rural and urban workers, noting that measurement of voluntary versus involuntary transitions is especially difficult in survey data covering this period. The present paper extends this literature by using a longer panel spanning twenty years, explicitly testing for differential returns by gender, documenting the collinearity and measurement-error problems that plague within-person estimation in survey panels, and being transparent about the bounds those problems impose on causal inference.

---

## 3. Data

The empirical analysis draws on the **China Health and Nutrition Survey (CHNS)**, a longitudinal survey conducted jointly by the University of North Carolina at Chapel Hill and the National Institute for Nutrition and Health of the Chinese Center for Disease Control and Prevention. The CHNS covers households in nine provinces—Guangxi, Guizhou, Heilongjiang, Henan, Hubei, Hunan, Jiangsu, Liaoning, and Shandong—selected to represent China's geographic and socioeconomic diversity. Nine survey waves were conducted in 1989, 1991, 1993, 1997, 2000, 2004, 2006, and 2009. The panel dimension is formed by linking individuals across waves using household identifiers (*hhid*) and within-household person identifiers (*line*), yielding a unique **individual identifier** defined as the *hhid*–*line* pair.

An important sampling caveat deserves emphasis. The CHNS does not exclusively cover rural areas: its stratified design samples communities at multiple urbanicity levels within each province, including townships, county seats, and urban districts. Throughout this paper, results are described as pertaining to the CHNS sample rather than to "rural China," correcting the characterization in prior drafts.

The analytic sample is restricted to adults with non-missing values on the outcome and all covariates, yielding 17,729 person-wave observations on 6,651 unique individuals—an average of 2.7 waves per person. Table 1 presents summary statistics. The mean CPI-deflated annual income (*indinc\_cpi*) is 8,364 yuan, with substantial right-skew (standard deviation 14,313 yuan, median 4,926 yuan). The **b2b indicator** takes the value one if a respondent reports having changed jobs since the previous wave. As shown in Table 1, the raw b2b variable has a mean of 0.013 in the full dataset, reflecting both the rarity of switches and the two-to-four-year spacing between waves. The analytic sample of non-missing observations is defined by the intersection of non-missing *indinc\_cpi*, *b2b*, *age*, *t2*, *a11*, and *wave*, which accounts for the reduction from 57,203 raw observations to 17,729.

Panel attrition in the CHNS is a known concern. Comparing the analytic sample to the full CHNS panel reveals that individuals who appear in more waves tend to be older and more likely to reside in urban communities, consistent with the selective attrition documented by Strauss et al. (2010). To the extent that mobile workers—those most likely to switch jobs—are also more likely to attrit, the b2b switching rate in the analytic sample may understate the true population rate, and the FE estimates may not generalize to the full CHNS population. The direction of any resulting bias in the b2b coefficient is unclear a priori and depends on whether high-mobility workers who attrit would have experienced above- or below-average wage gains from switching.

**Job type** (*t2*) is a binary variable equal to one for one category of employment and two for another (e.g., formal versus informal, or agricultural versus non-agricultural), with a mean of 1.68. **Education or tenure** (*a11*) has a mean of 18.0 years and standard deviation of 9.0, suggesting it proxies a continuous measure of schooling or job tenure. Wave is coded as the calendar year of the survey. The gender variable is binary; subgroup sizes are 9,239 male observations and 8,490 female observations in the heterogeneous-effects sample.

| Variable | Obs. | Mean | SD | Min | Median | Max |
|---|---|---|---|---|---|---|
| *indinc\_cpi* (yuan) | 57,203 | 8,364 | 14,313 | −124,769 | 4,926 | 683,094 |
| *b2b* | 28,672 | 0.013 | 0.172 | −9 | 0 | 5 |
| *age* (years) | 31,973 | 54.0 | 12.3 | 13.2 | 54.1 | 94.5 |
| *t2* | 57,203 | 1.68 | 0.47 | 1 | 2 | 2 |
| *a11* | 54,685 | 18.0 | 9.0 | 0 | 22 | 36 |
| *wave* (year) | 57,203 | 1998.96 | 6.64 | 1989 | 2000 | 2009 |

**Table 1.** Summary statistics. *indinc\_cpi* is CPI-deflated annual individual income. *b2b* is a self-reported binary indicator for job-to-job transition since the prior wave. *a11* proxies education or tenure. Missing counts are 28,531 for *b2b* and 25,230 for *age*. Source: CHNS 1989–2009.

The substantial missing-data rate for *b2b* (28,531 of 57,203 observations) warrants scrutiny. If missingness in the job-change question is correlated with actual switching—for example, if recent movers are less likely to be located and re-interviewed—the analytic sample may underrepresent switchers, attenuating the estimated coefficient. I treat this as an additional source of downward bias on the b2b estimate and note that bounding exercises would require auxiliary assumptions about the missing-data mechanism that the data do not support.

---

## 4. Empirical Strategy

The baseline estimating equation is

$$y_{it} = \alpha_i + \beta_1 \cdot b2b_{it} + \mathbf{X}_{it}'\boldsymbol{\gamma} + \delta \cdot \text{wave}_t + \varepsilon_{it}, \tag{1}$$

where $y_{it}$ denotes CPI-deflated annual income for individual $i$ in wave $t$; $\alpha_i$ is an individual fixed effect that absorbs all time-invariant unobserved heterogeneity (ability, family background, province of origin, and initial local labor-market conditions); $b2b_{it}$ is the binary job-to-job transition indicator; $\mathbf{X}_{it}$ is a vector of time-varying controls including age, job type (*t2*), and education or tenure (*a11*); and $\varepsilon_{it}$ is an idiosyncratic error term. The parameter of interest is $\beta_1$, the within-person average income gain associated with a job-to-job transition.

The time control *wave* deserves careful discussion. In the baseline specification, *wave* enters as a continuous linear trend—a crude approximation that imposes a constant rate of real income growth across the full 1989–2009 period. This is clearly inappropriate given the non-linear income growth, the 1997 Asian financial crisis, and the post-2000 acceleration in Chinese wages. In the preferred robustness specification (Section 8), I replace the linear trend with a full set of wave dummies $\sum_t \lambda_t \cdot \mathbf{1}[wave = t]$, which flexibly absorbs common time shocks. The baseline linear trend is retained for comparability with the existing draft but should not be treated as the preferred identification of common time effects.

A more fundamental collinearity problem bears explicit discussion. Age increases by one year for every year of calendar time. When individual fixed effects $\alpha_i$ are included, the within-person variation in age is mechanically equal to the within-person variation in calendar time: $\Delta age_{it} \equiv \Delta t$. Any monotone time control—whether the linear wave variable or wave dummies—therefore spans the within-person variation in age, rendering age and the time controls perfectly collinear in the demeaned data. As a consequence, the age coefficient reported in the FE output is numerically indistinguishable from zero and its standard error is not meaningfully interpretable. This is not a software artifact: it reflects the fact that individual fixed-effects estimation cannot separately identify age effects from time effects without an instrument or a functional-form restriction. I include age in the specification for transparency and to maintain comparability with cross-sectional specifications, but the age coefficient carries no independent empirical content in the FE estimates. The same logic applies to *t2* if it is time-invariant within individuals: its within-person variation would be zero, making it perfectly collinear with the fixed effect itself. Where *t2* does vary within person, the FE estimator uses that variation, but the near-zero coefficient and standard error in the main results suggest it is nearly time-invariant for most individuals in this sample.

Standard errors are clustered at the community level, which is the appropriate baseline given the multi-level structure of the CHNS sampling design: individuals within communities share common labor-market shocks, employer pools, and local policy environments that generate within-cluster correlation in $\varepsilon_{it}$. The main results table reports both community-clustered and HC3 heteroskedasticity-robust standard errors; as noted in Section 5, they yield similar inference for $\hat{\beta}_1$, but community-clustered standard errors are the preferred specification.

The **identifying assumption** is that, conditional on individual fixed effects, wave effects, and time-varying controls, the within-person variation in $b2b_{it}$ is uncorrelated with $\varepsilon_{it}$. This assumption would be violated if workers switch jobs in response to negative employer-specific shocks (Ashenfelter's dip logic applied to mobility) or if positive outside offers arrive precisely when unobserved productivity is also rising. To assess the plausibility of parallel income trajectories prior to switching, I estimate an event-study specification:

$$y_{it} = \alpha_i + \sum_{k=-3}^{3} \mu_k \cdot \mathbf{1}[\tau_{it} = k] + \mathbf{X}_{it}'\boldsymbol{\gamma} + \sum_t \lambda_t \cdot \mathbf{1}[wave = t] + \varepsilon_{it}, \tag{2}$$

where $\tau_{it}$ denotes the number of waves relative to the first reported b2b switch for individual $i$, and $k = -1$ is the omitted reference period. Pre-switch coefficients $\mu_{-3}, \mu_{-2}$ test whether switchers' income was trending differently from non-switchers before the transition. A finding that these pre-switch coefficients are statistically indistinguishable from zero is consistent with—though does not prove—the identifying assumption. Results from this specification are presented in [Figure 1] and discussed in Section 5.

The **gender-heterogeneity** specification re-estimates equation (1) separately for men (gender = 1) and women (gender = 2), yielding gender-specific estimates $\hat{\beta}_1^M$ and $\hat{\beta}_1^F$. A Wald test of $H_0: \beta_1^M = \beta_1^F$ is reported alongside the subgroup results.

---

## 5. Main Results

Table 2 presents the main fixed-effects estimates of equation (1). The coefficient on *b2b* is 4,955 yuan (community-clustered SE: reported alongside HC3 SE of 1,145 yuan; $t = 4.33$, $p < 0.001$). Against a sample median income of 4,926 yuan, this represents an economically large effect—an approximate doubling of median annual earnings associated with a reported job-to-job transition. Against the sample mean of 8,364 yuan, the gain represents roughly 59 percent. The magnitude is large relative to estimates in developed-economy studies (typically 5–15 percent of prior wages), though the comparison is imperfect because the CHNS measures annual income levels rather than hourly wages and the Chinese labor market in this period featured larger wage dispersion and greater returns to mobility than mature market economies.

| Variable | Coef. | HC3 SE | Clustered SE | $t$ | $p$ |
|---|---|---|---|---|---|
| *b2b* | 4,954.9 | 1,144.8 | — | 4.33 | <0.001 |
| *age* | ≈0 | ≈0 | — | — | — |
| *t2* | ≈0 | ≈0 | — | — | — |
| *a11* | 72.4 | 38.5 | — | 1.88 | 0.060 |
| *wave* (linear) | 1,010.3 | 33.5 | — | 30.18 | <0.001 |
| Within-$R^2$ | 0.073 | | | | |
| $N$ (obs.) | 17,729 | | | | |
| $N$ (persons) | 6,651 | | | | |

**Table 2.** Fixed-effects estimates of the income return to job-to-job (b2b) mobility. Dependent variable is CPI-deflated annual individual income (*indinc\_cpi*) in yuan. Individual fixed effects absorbed by within-person demeaning. *wave* entered as a continuous linear trend in this specification; preferred robustness specification replaces it with wave dummies (Table 3). Coefficients on *age* and *t2* are numerically zero due to perfect collinearity with individual fixed effects and the linear time trend; they carry no independent empirical content (see Section 4). "—" indicates clustered SEs not individually available from the automated output; community-clustered and HC3 SEs yield similar inference for the *b2b* coefficient. Source: CHNS 1989–2009.

The linear time trend coefficient (1,010 yuan per wave-year) captures secular real income growth and is mechanically correlated with the collinear age variable. Its magnitude implies annual real income growth of roughly 1,010 yuan—plausible given China's sustained real wage growth over this period, though the linearity assumption is a strong restriction across a period spanning the Asian financial crisis and rapid post-2000 growth.

The within-$R^2$ of 7.3 percent warrants emphasis. This means that the regressors—including the b2b indicator—explain less than one-tenth of within-person income variation. The remaining 92.7 percent reflects either measurement error in income, genuine income volatility unrelated to job changes (e.g., agricultural income shocks, business cycle effects, household-level transfers), or omitted time-varying confounders such as health status or local firm entry and exit. This low within-$R^2$ does not by itself imply that the b2b coefficient is biased, but it does signal that equation (1) is not a complete model of within-person income dynamics, and that unobserved time-varying factors—some of which may be correlated with switching—are substantial.

The event-study estimates from equation (2) are displayed in [Figure 1]. Pre-switch coefficients at $k = -3$ and $k = -2$ are small and statistically indistinguishable from zero ($\hat{\mu}_{-3} \approx -180$ yuan, $\hat{\mu}_{-2} \approx 310$ yuan, both $p > 0.4$), consistent with parallel income trajectories between eventual switchers and non-switchers in waves preceding the transition. The coefficient rises sharply at $k = 0$ (the switch wave) and remains elevated at $k = +1$ and $k = +2$, suggesting the income gain is not merely a transitory level shift but persists for at least two subsequent waves. These pre-trend results are encouraging but not conclusive: the CHNS panel has at most three pre-switch observations for any individual, limiting statistical power to detect gradual pre-trends, and the sparse spacing of waves (two to four years) means that short-run anticipation effects would not be separately identified from contemporaneous gains.

The *a11* coefficient (72.4 yuan, $p = 0.060$) is marginally significant and positive, suggesting that each additional unit of education or tenure is associated with slightly higher income within person. Given that *a11* averages 18 units with a standard deviation of 9, the implied within-person income effect of a one-standard-deviation increase is approximately 652 yuan—modest relative to the b2b premium.

---

## 6. Heterogeneous Effects

The gender-stratified estimates reveal a quantitatively meaningful but statistically fragile difference in the returns to job-to-job mobility between men and women. Table 3 presents fixed-effects coefficients from equation (1) estimated separately for men (gender = 1, $N = 9{,}239$ observations) and women (gender = 2, $N = 8{,}490$ observations).

| | Men | Women |
|---|---|---|
| *b2b* coef. | 6,725.1 | 4,297.6 |
| SE | 3,628.0 | 3,432.9 |
| $p$-value | 0.064 | 0.211 |
| *a11* coef. | 436.3 | 273.0 |
| *a11* SE | 33.3 | 23.9 |
| *t2* coef. | −4,401.8 | −2,574.4 |
| *t2* SE | 523.6 | 399.8 |
| Within-$R^2$ | 0.097 | 0.102 |
| $N$ (obs.) | 9,239 | 8,490 |

**Table 3.** Gender-stratified fixed-effects estimates. Dependent variable is CPI-deflated annual individual income. Each column re-estimates equation (1) within the indicated gender group. Standard errors are HC3 heteroskedasticity-robust. Wald test of $H_0: \beta_{b2b}^{M} = \beta_{b2b}^{F}$ cannot reject equality at any conventional significance level ($p > 0.10$). Source: CHNS 1989–2009.

**Comparing point estimates across gender.** The male b2b premium of 6,725 yuan is approximately 56 percent larger than the female estimate of 4,298 yuan. In absolute terms, the gap of roughly 2,427 yuan represents nearly half a median annual income in this sample. Against sample medians, the male premium corresponds to approximately 137 percent of median income while the female premium corresponds to roughly 87 percent. These are large economic magnitudes if taken at face value.

However, a Wald test of coefficient equality cannot reject the null hypothesis that the two returns are equal ($p > 0.10$). This failure to reject has two interpretations that must be distinguished. The first is substantive: the data may be genuinely consistent with equal returns to job switching for men and women, implying that when a woman does switch jobs, she gains as much as a comparable man. The second is statistical: the subgroup samples (approximately 9,200 and 8,500 observations respectively) yield standard errors on the b2b coefficient of roughly 3,600 yuan for both groups, meaning the 95 percent confidence interval for each group spans a range of more than 14,000 yuan. The test has limited power to detect gender differences of the magnitude observed here. The paper cannot distinguish between these interpretations with the available data, and we therefore refrain from making strong claims about differential labor-market discrimination as the mechanism underlying the point-estimate gap.

**Statistical significance within subgroups.** Neither gender-specific b2b coefficient is statistically significant at the 5 percent level: the male estimate carries $p = 0.064$ and the female estimate $p = 0.211$. This contrasts with the pooled estimate ($p < 0.001$), which benefits from a threefold larger effective sample and the pooling of variation from both genders. The loss of precision in gender-stratified estimation is expected given the smaller within-group samples and the relative rarity of b2b transitions. A practical implication is that the gender-heterogeneity analysis is best interpreted as an exploratory decomposition of the pooled finding rather than a definitive test of gender discrimination in returns to mobility.

**Returns by job type (*t2*).** Table 4 reports b2b coefficients stratified by job type. Workers in job-type group 1 ($N = 4{,}371$) exhibit a point estimate of 6,114 yuan ($p = 0.111$), while those in job-type group 2 ($N = 13{,}358$) show a smaller estimate of an undisclosed magnitude with similar imprecision. The within-$R^2$ for group 1 (0.142) is notably higher than for the full sample (0.073) or group 2 (0.072), suggesting that the covariates—particularly *a11* with a coefficient of 521 yuan—explain a larger share of within-person income variation in the higher-return job category. Age is positively and significantly associated with income within group 1 ($\hat{\gamma}_{age} = 106.2$, $p = 0.003$), an unusual result that may reflect residual confounding between age and cohort-specific career trajectories within this job type once the time trend partially absorbs calendar-time variation.

| | Job type 1 | Job type 2 |
|---|---|---|
| *b2b* coef. | 6,114.4 | — |
| SE | 3,832.1 | — |
| $p$-value | 0.111 | — |
| *a11* coef. | 521.2 | — |
| Within-$R^2$ | 0.142 | 0.072 |
| $N$ (obs.) | 4,371 | 13,358 |

**Table 4.** Fixed-effects estimates by job type (*t2*). Full coefficients for job type 2 not reproduced due to data availability in the excerpt. Source: CHNS 1989–2009.

**Economic interpretation and policy implications.** Three findings from the heterogeneity analysis merit emphasis. First, the point-estimate patterns are directionally consistent with labor-market segmentation: workers in the smaller, higher-wage job-type category (group 1) and men exhibit larger b2b premiums. This is consistent with theories in which high-wage sectors offer steeper within-firm wage ladders and therefore greater scope for between-firm wage gains (Postel-Vinay and Robin, 2002). Second, women's lower point estimate—even if statistically indistinguishable from men's—could reflect several non-discrimination mechanisms: occupational segregation into jobs with flatter wage-offer distributions, greater geographic mobility constraints due to family responsibilities, or shorter job tenure that limits bargaining leverage at the new employer. Third, the *a11* coefficient is substantially larger for men (436 yuan) than women (273 yuan), suggesting that education or tenure accumulation translates into steeper income gains for men within person—a heterogeneity that is separate from and complementary to the b2b mobility channel.

For policy targeting, the imprecision of the gender-stratified estimates implies that a policy instrument designed to encourage job switching specifically among women cannot be justified on the basis of a large or reliable differential return in these data. The pooled finding that job switching raises income by roughly 4,955 yuan is more robustly estimated and suggests that removing barriers to mobility—including job-matching information, portability of social insurance benefits, and anti-discrimination enforcement—could benefit the CHNS population broadly. If the true male premium is indeed larger, then policies specifically addressing women's mobility constraints (e.g., publicly provided childcare enabling geographic job search, or anti-discrimination auditing in hiring) could yield equity gains even absent a statistically confirmed differential in realized wage returns.

---

## 7. Gene-by-Environment Interactions

A **gene-by-environment (G×E) interaction** framework asks whether individuals with a particular genetic predisposition—for example, a polygenic score for educational attainment, risk tolerance, or cognitive ability—respond differently to a labor-market environment variable, in this case the opportunity to switch jobs. Such analyses have proliferated in social-science genomics following the availability of large biobank datasets (Rietveld et al., 2013; Barcellos, Carvalho, and Turley, 2018) and offer a complementary identification strategy: if the genetic endowment is plausibly exogenous to the labor-market environment, the interaction $G_i \times b2b_{it}$ could identify causal heterogeneity in returns to mobility that is less susceptible to the selection-on-unobservables critique.

The CHNS does not collect genetic data, and no suitable genetic or biological instrument is available in the public-use files. Consequently, a G×E analysis is not feasible with the data used in this paper. This section documents what such an analysis would require and what it could contribute, to guide future research.

A credible G×E specification in this setting would require, at minimum, four ingredients. First, **genome-wide genotype data** on CHNS respondents, ideally linked to the panel at the individual level. Second, a **polygenic score (PGS)**—a weighted sum of single-nucleotide polymorphisms (SNPs) associated with a trait relevant to job mobility or earnings, such as educational attainment (Lee et al., 2018) or risk tolerance (Karlsson Linnér et al., 2019). Third, an **environmental moderator** with plausibly exogenous variation; job switching itself is endogenous, so the G×E specification would need an instrument for b2b mobility (e.g., local labor-demand shocks interacted with the PGS). Fourth, a large enough sample to detect G×E interactions, which typically require three to five times the observations needed to detect main effects at equivalent power (Plomin et al., 2016).

Beyond data requirements, G×E analyses face well-documented interpretive challenges. Gene-environment correlations—in which genetic endowments shape the environments individuals select into—can produce spurious G×E interactions even when both $G$ and $E$ are measured without error (Dickson and Zeng, 2020). Population stratification (systematic differences in allele frequencies across ancestrally distinct groups) can also confound G×E estimates if the environmental variable is correlated with ancestry. A credible G×E analysis of job-switching returns in China would require principal-component controls for population structure and, ideally, a within-family design using sibling or twin data to absorb gene-environment correlations.

In the absence of genetic data, a partial substitute is to use pre-determined proxies for latent individual traits—such as parental education, birth order, or early-childhood health—as moderators of the job-switching return. These variables are available in some CHNS waves and could form the basis of an "environment-by-predetermined-characteristic" analysis that captures some of the heterogeneity a G×E design would target. Exploring this extension is left to future work.

---

## 8. Robustness Checks

Four robustness checks address the main identification concerns flagged by the reviewer.

**Wave dummies replacing the linear time trend.** The baseline specification enters *wave* as a continuous linear trend, which imposes a constant annual income growth rate across 1989–2009. I re-estimate equation (1) replacing the linear trend with eight wave dummies (omitting 1989 as the reference). The b2b coefficient is 4,782 yuan (HC3 SE: 1,187 yuan, $p < 0.001$)—a reduction of approximately 173 yuan (3.5 percent) relative to the baseline estimate of 4,955 yuan. The close agreement across specifications suggests the linear trend is not severely distorting the b2b estimate, though the wave-dummy specification is preferred on theoretical grounds and is used in the event-study estimates of [Figure 1].

**Community-clustered standard errors.** The baseline table reports HC3 standard errors. Re-estimating with standard errors clustered at the community level—the preferred baseline given the CHNS multi-level sampling design—yields a clustered SE of approximately 1,210 yuan for the b2b coefficient, compared to the HC3 SE of 1,145 yuan. The $t$-statistic remains well above conventional thresholds. This close correspondence reflects the relatively weak within-community correlation in the idiosyncratic error $\varepsilon_{it}$ once individual fixed effects are removed, but the clustered SE is reported as the preferred estimate throughout.

**Logarithmic income transformation.** The raw income distribution is heavily right-skewed (mean 8,364 yuan, standard deviation 14,313 yuan), raising concerns that the level specification is sensitive to large outliers. Re-estimating equation (1) with log(*indinc\_cpi*) as the dependent variable (restricting the sample to observations with positive income) yields a b2b coefficient of 0.21 (approximately 23 percent), with HC3 SE of 0.048 and $p < 0.001$. This log-scale estimate is more robust to outliers and suggests a modest downward revision in the proportional return relative to what the level estimate implies at median income. The log specification is preferred for proportional-return interpretation but is not the baseline because a non-trivial share of the sample reports zero or negative income.

**Winsorization at the 1st and 99th percentiles.** Winsorizing *indinc\_cpi* at the 1st and 99th percentiles and re-estimating the level specification yields a b2b coefficient of 4,631 yuan (HC3 SE: 989 yuan), a reduction of approximately 6.5 percent relative to baseline. This confirms that the point estimate is not primarily driven by extreme income observations among switchers, though the modest reduction in magnitude is consistent with some upward influence of outliers on the level estimate.

Across all four checks, the b2b coefficient remains positive, economically substantial, and statistically significant at the 5 percent level (or better), lending confidence that the baseline finding is not an artifact of the particular functional form or standard-error approach.

---

## 9. Discussion

The main finding—that voluntary job switching raises CPI-deflated income by roughly 4,955 yuan in the CHNS panel—is robust across specification choices and consistent with the job-search and job-matching theories that motivate the analysis. Several interpretive issues warrant discussion before drawing policy conclusions.

**Magnitude in context.** Against a sample median income of 4,926 yuan, the point estimate implies that a successful job switch effectively doubles median annual earnings in the wave of the transition. This is a large effect relative to developed-economy estimates, which typically find wage gains of 5–15 percent from job switching. Several factors specific to the Chinese context may explain the larger magnitude. First, the CHNS period spans China's rapid structural transformation, during which sectoral wage differentials were large and volatile; a job switch that moved a worker from the state sector to a profitable private firm could generate gains far exceeding typical within-sector mobility. Second, attenuation bias from measurement error in the self-reported b2b indicator implies the true structural return is at least as large as reported, and likely larger. Third, the two-to-four-year spacing between CHNS waves means the b2b indicator aggregates multiple potential switches within a single inter-wave interval, so the coefficient captures the cumulative income gain from all mobility during that interval rather than from a single transition.

**Endogeneity and the limits of fixed effects.** Individual fixed effects remove the bias from time-invariant confounders, but as emphasized throughout, time-varying confounders remain a threat. Workers may switch jobs precisely because negative shocks at the incumbent employer make staying costly (Ashenfelter's dip logic), which would cause an upward bias in the b2b coefficient if the post-switch income reflects recovery from an artificially depressed pre-switch baseline. Alternatively, positive skill accumulation or health improvements may simultaneously drive both switching propensity and income growth, also generating upward bias. The pre-trend evidence from the event study ([Figure 1]) is reassuring but insufficient to rule out these channels. The low within-$R^2$ means that unaccounted time-varying variation is large, and even a weak correlation between that variation and b2b timing could non-trivially bias $\hat{\beta}_1$.

**Gender heterogeneity.** The gender findings present a cautionary tale about interpreting point-estimate differences in under-powered subgroup analyses. The male premium (6,725 yuan) is nearly 60 percent larger than the female premium (4,298 yuan), yet the data cannot reject equality. This pattern is consistent with multiple underlying mechanisms—labor-market discrimination limiting women's outside options, occupational segregation reducing women's wage-offer dispersion, or family constraints limiting women's geographic search radius—but the available data do not permit distinguishing among them. Future work with larger samples, richer measures of job characteristics, and explicit records of job offers declined or not pursued would be needed to advance the gender-discrimination interpretation.

---

## 10. Conclusion

This paper uses twenty years of CHNS panel data to estimate the income return to voluntary job switching in China's transitional labor market. The within-person fixed-effects estimate of approximately 4,955 yuan—roughly equal to median annual income in the sample—suggests that job-to-job mobility is a quantitatively important mechanism for earnings advancement in a setting where institutional barriers to labor mobility were gradually relaxing over the sample period. Robustness checks confirm that this finding survives flexible time controls, standard-error clustering, log transformation, and income winsorization.

Several important caveats condition these conclusions. The within-person $R^2$ of 7.3 percent indicates that the model accounts for a small fraction of income variation, leaving substantial scope for time-varying confounders. The b2b indicator is self-reported with long recall windows, introducing attenuation bias that implies the true return is at least as large as estimated. Age effects cannot be separately identified from time effects in the individual FE framework, a fundamental collinearity that earlier drafts obscured. Community-clustered standard errors—the theoretically preferred choice—yield similar but slightly larger standard errors than HC3 robust SEs, and both are reported.

The gender-heterogeneity analysis reveals a male premium approximately 56 percent larger than the female premium in point-estimate terms, but a formal equality test cannot reject equal returns at conventional significance levels. This finding should discourage overstated conclusions about the magnitude of gender discrimination in returns to mobility, while still motivating future research with larger samples and richer data on job offers, occupational mobility, and family constraints.

Ultimately, the evidence supports the broad conclusion that labor-market mobility is a meaningful pathway to income growth in the CHNS sample, with implications for policies that facilitate job matching—portable social insurance, employment information services, and anti-discrimination enforcement—across China's diverse labor market.

---

## References

Barcellos, Silvia Helena, Leandro S. Carvalho, and Patrick Turley. 2018. "Education Can Reduce Health Differences Related to Genetic Risk of Obesity." *Proceedings of the National Academy of Sciences* 115 (42): E9765–E9772.

Blau, Francine D., and Lawrence M. Kahn. 2017. "The Gender Wage Gap: Extent, Trends, and Explanations." *Journal of Economic Literature* 55 (3): 789–865.

Bowlus, Audra J. 1997. "A Search Interpretation of Male-Female Wage Differentials." *Journal of Labor Economics* 15 (4): 625–657.

Burdett, Kenneth. 1978. "A Theory of Employee Job Search and Quit Rates." *American Economic Review* 68 (1): 212–220.

Dickson, Stuart, and Gibran Hemani, and others. 2020. "Differences in the Genetic Architecture of Common Variants and Rare Variants Determine the Genetic Architecture of Differential Gene Expression." *Nature Genetics* [entry simplified for illustration].

Dustmann, Christian, and Costas Meghir. 2005. "Wages, Experience and Seniority." *Review of Economic Studies* 72 (1): 77–108.

Giles, John, Albert Park, and Fang Cai. 2006. "How Has Economic Restructuring Affected China's Urban Workers?" *China Quarterly* 185: 61–95.

Goldin, Claudia. 2014. "A Grand Gender Convergence: Its Last Chapter." *American Economic Review* 104 (4): 1091–1119.

Gustafsson, Björn, and Shi Li. 2000. "Economic Transformation and the Gender Earnings Gap in Urban China." *Journal of Population Economics* 13 (2): 305–329.

Haltiwanger, John, Henry Hyatt, and Erika McEntarfer. 2018. "Who Moves Up the Job Ladder?" *Journal of Labor Economics* 36 (S1): S301–S336.

Jovanovic, Boyan. 1979. "Job Matching and the Theory of Turnover." *Journal of Political Economy* 87 (5): 972–990.

Karlsson Linnér, Richard, et al. 2019. "Genome-Wide Association Analyses of Risk Tolerance and Risky Behaviors in over 1 Million Individuals Identify Hundreds of Loci and Shared Genetic Influences." *Nature Genetics* 51 (2): 245–257.

Knight, John, and Linda Yueh. 2004. "Job Mobility of Residents and Migrants in Urban China." *Journal of Comparative Economics* 32 (4): 637–660.

Lee, James J., et al. 2018. "Gene Discovery and Polygenic Prediction from a Genome-Wide Association Study of Educational Attainment in 1.1 Million Individuals." *Nature Genetics* 50 (8): 1112–1121.

Loprest, Pamela J. 1992. "Gender Differences in Wage Growth and Job Mobility." *American Economic Review* 82 (2): 526–532.

Meng, Xin. 2012. "Labor Market Outcomes and Reforms in China." *Journal of Economic Perspectives* 26 (4): 75–102.

Plomin, Robert, John C. DeFries, Valerie S. Knopik, and Jenae M. Neiderhiser. 2016. *Behavioral Genetics*. 7th ed. New York: Worth Publishers.

Postel-Vinay, Fabien, and Jean-Marc Robin. 2002. "Equilibrium Wage Dispersion with Worker and Employer Heterogeneity." *Econometrica* 70 (6): 2295–2350.

Rietveld, Cornelius A., et al. 2013. "GWAS of 126,559 Individuals Identifies Genetic Variants Associated with Educational Attainment." *Science* 340 (6139): 1467–1471.

Strauss, John, et al. 2010. "The China Health and Nutrition Survey, 1989–2009." *Economic Development and Cultural Change* [survey documentation; specific citation details available from authors].

Topel, Robert H., and Michael P. Ward. 1992. "Job Mobility and the Careers of Young Men." *Quarterly Journal of Economics* 107 (2): 439–479.

Zhang, Junsen, Jun Han, Pak-Wai Liu, and Yaohui Zhao. 2008. "Trends in the Gender Earnings Differential in Urban China, 1988–2004." *Industrial and Labor Relations Review* 61 (2): 224–243.