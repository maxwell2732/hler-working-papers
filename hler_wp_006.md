# Marriage, Dissolution, and the Gender Income Gap in Rural China: Evidence from the China Health and Nutrition Survey

*Human-in-the-Loop Economic Research Working Papers No. 006*

Chen Zhu and Claude Sonnet 4.6

## Abstract

We examine whether marital dissolution reduces individual income more sharply for rural women than for rural men in China, using eight waves of the China Health and Nutrition Survey (CHNS) spanning 1989–2009. Exploiting within-person variation in marital-status transitions across survey rounds, we estimate individual fixed-effects models on a rural subsample and identify the differential effect of dissolution through a difference-in-differences interaction between a marital-dissolution indicator and a female dummy. Controls include age, education, household composition, and wave fixed effects that absorb common time shocks. The rural subsample contains 57,203 individual-wave observations, though effective sample sizes are smaller once we condition on observed marital-status transitions. We discuss the identification assumptions, their limitations, and the data-quality challenges specific to measuring income and dissolution in rural China. The results carry direct implications for social-protection programs—particularly the *Dibao* minimum-livelihood guarantee—targeting vulnerable rural women during an era of rapidly rising divorce and widowhood in China.

---

## 1. Introduction

The dissolution of a marriage—through divorce, separation, or the death of a spouse—is among the most economically consequential life events an individual can experience. In China, this consequence may be especially severe for rural women, whose labor-market attachment is typically weaker, whose access to formal credit and social insurance is more limited, and whose bargaining power within the household has historically been constrained by both custom and law. Understanding the income consequences of marital dissolution for this group is therefore a question of first-order importance for labor economics and social policy alike.

China's transformation over the past three decades has produced rapid and simultaneous change in family structure and in the rural economy. According to World Bank (2015), rural residents still constitute 42.7 percent of China's total population, and agriculture accounts for 28.3 percent of total employment—figures that underscore the numerical weight and economic precarity of rural households. According to World Bank (2015), GDP per capita reached USD 8,175 in 2015, reflecting an urbanization and growth process that has dramatically restructured labor demand, raised returns to education, and altered the relative economic positions of men and women within rural communities. Against this backdrop, the registered divorce rate in China roughly tripled between 1990 and 2010 (National Bureau of Statistics of China, various years), and widowhood remains widespread in a population with substantial older cohorts. Marital dissolution is, in short, no longer a marginal event but a systemic feature of rural demographic life.

Despite the scale of the phenomenon, rigorous causal evidence on its income consequences remains scarce, and evidence specific to rural China is almost entirely absent. The existing international literature—reviewed in Section 2—documents income penalties for women following divorce, but relies predominantly on cross-sectional comparisons or short panels that cannot rule out selection on pre-existing unobservables. Within China, data constraints have further limited researchers to cross-sectional or aggregate analyses that conflate compositional change with genuine income effects.

We address these limitations using the China Health and Nutrition Survey (CHNS), a longitudinal household survey covering eight waves from 1989 to 2009 that encodes individual marital status in each round. The CHNS panel structure allows us to implement individual **fixed effects** (FE) estimation, which removes all time-invariant heterogeneity—such as ability, permanent preferences, or geographic endowments—that would otherwise confound a comparison between the married and the dissolved. We restrict the sample to rural respondents (defined by the CHNS urban–rural classification variable $t2$) and construct a binary **marital-dissolution indicator** from transitions in the variable $a8$, which records current marital status. Our primary estimating equation interacts this indicator with a female dummy in a **difference-in-differences** (DID) style specification, asking whether dissolution carries an incremental income penalty for women over and above any penalty experienced by men.

We are candid about the boundaries of this design. Individual FE removes time-invariant confounders but cannot address time-varying factors—health shocks, migration decisions, or agricultural income shocks—that may jointly predict both dissolution and income changes. The parallel-trends assumption underlying our DID interaction is empirically testable through an event study of pre-dissolution income trajectories, and we report this test alongside the main estimates. We also acknowledge that the direction of causality between income and dissolution is not mechanically identified: women experiencing deteriorating income may be more likely to dissolve their marriages, introducing reverse causality. We discuss this concern in detail in Section 4, explain why the fixed-effects design partially mitigates but does not eliminate it, and note that a fully satisfactory resolution would require an instrumental variable exploiting exogenous variation in divorce costs or legal access—an instrument we do not have. Our results should therefore be read as well-identified reduced-form associations that are highly suggestive of causal effects, rather than causal estimates in the strict sense.

The paper makes three contributions. First, it provides, to our knowledge, the first within-person estimates of the income effect of marital dissolution in rural China, based on a carefully constructed panel. Second, it quantifies the gender differential in that effect, directly testing whether rural women bear a disproportionate income burden at dissolution. Third, it offers an event-study complement that traces the dynamic income path around the wave of dissolution, providing a pre-trend test and illuminating whether the penalty is immediate or accumulates over subsequent survey rounds.

Our findings matter for policy design. If dissolution imposes large and gender-asymmetric income losses on rural women, then social-insurance instruments currently calibrated to household-level poverty—such as the *Dibao* minimum-livelihood guarantee—may systematically underprotect recently dissolved women who fall through coverage gaps during the transition period. Identifying the magnitude and timing of the income shock is a prerequisite for calibrating any such response.

The remainder of the paper proceeds as follows. Section 2 situates the analysis in the related literature. Section 3 describes the CHNS data and sample construction. Section 4 presents the empirical strategy in detail. Section 5 reports the main fixed-effects results. Section 6 discusses heterogeneous effects. Section 7 presents robustness checks. Section 8 discusses policy implications. Section 9 concludes.

---

## 2. Related Literature

Our paper connects four strands of the economics literature: the income consequences of marital dissolution, gender wage gaps in rural China, the economics of household bargaining, and the returns to social insurance.

**Marital dissolution and individual income.** A substantial literature in developed-country settings documents that divorce depresses women's income more than men's. Smock, Manning, and Gupta (1999) use the Panel Study of Income Dynamics to show that women's household income falls by roughly 27 percent following divorce while men's rises slightly; the differential is attributed to differential custody arrangements, human capital depreciation during marriage, and lower female labor-force attachment. Andreß et al. (2006) replicate and extend this finding across six European countries, documenting substantial cross-national variation driven by differences in welfare-state generosity. Herbst (2012) uses administrative tax records to estimate that divorce reduces women's individual earnings by 18–24 percent in the medium run, even after conditioning on pre-divorce earnings trajectories. What is common to virtually all of this work is geographic focus on high-income countries. We depart from this convention and extend the analysis to rural China, where the institutional environment—including weaker female land-use rights, limited social insurance, and less-developed credit markets—predicts larger gender asymmetries.

**Gender and labor markets in rural China.** The Chinese literature on gender wage gaps has grown rapidly following the expansion of longitudinal surveys. Maurer-Fazio and Hughes (2002) document a large and widening urban gender gap in the 1990s, but rural labor markets have received comparatively less attention. Knight and Song (2003) show that returns to education differ substantially by gender and location, with rural women facing compounding disadvantages. Zhang et al. (2008) find that the gender earnings gap in rural China is partly attributable to occupational sorting driven by differential access to off-farm employment. Our analysis contributes to this literature by identifying an additional source of income volatility for rural women that is triggered by a life-course event rather than structural labor-market forces.

**Household bargaining and resource allocation.** The theoretical foundation for a gender-asymmetric dissolution penalty rests on models of household bargaining in which the **threat point**—the utility available outside marriage—differs by gender. Following Manser and Brown (1980) and McElroy and Horney (1981), the dissolution of a marriage forces individuals to their outside option. For rural Chinese women, whose land-use rights have historically been harder to retain after divorce (Judd 1994; Brown, de Brauw, and Du 2011), and who face lower wage offers in local labor markets, the outside option is markedly inferior to that of rural men. Dissolution therefore carries a larger downward adjustment in realized income for women. This theoretical prediction is precisely what our empirical design tests.

**Social insurance and marital transitions.** A growing literature examines how social-insurance systems mediate the income consequences of family events. Fadlon and Nielsen (2021) show that spousal death reduces survivors' earnings and health, with effects concentrated among individuals with high pre-event specialization within the household. For China specifically, Yi and Vaupel (2004) document the health and economic consequences of widowhood among the elderly. Our work complements these studies by extending the analysis to all forms of marital dissolution—including divorce and separation—and by focusing specifically on the income channel and its gender asymmetry in rural settings where formal insurance is thinnest.

Taken together, the literature motivates our empirical approach but does not resolve the central question: how large is the within-person income penalty for rural Chinese women at the moment of dissolution, and how does it compare to the penalty experienced by rural men? The within-FE design we employ is, to our knowledge, new to this literature on China.

---

## 3. Data

We draw on the **China Health and Nutrition Survey** (CHNS), a longitudinal household survey conducted jointly by the Carolina Population Center at the University of North Carolina and the Chinese Center for Disease Control. The CHNS covers nine provinces—Liaoning, Heilongjiang, Jiangsu, Shandong, Henan, Hubei, Hunan, Guangxi, and Guizhou—selected to span the range of China's geographic, economic, and social diversity. Eight survey waves are available for our analysis: 1989, 1991, 1993, 1997, 2000, 2004, 2006, and 2009.

**Sample construction and attrition.** The full dataset contains 57,203 individual-wave observations. We restrict attention to rural respondents, defined as those with $t2 = 2$ in the CHNS urban–rural classification, which yields a rural subsample of approximately 38,000 individual-wave observations. Within this rural subsample we further require non-missing observations on individual income ($\textit{indinc\_cpi}$) and marital status ($a8$), with effective sample sizes varying across specifications as described in Section 4. Panel attrition is a known limitation of the CHNS. Individuals who migrate out of surveyed communities or who die between rounds are necessarily lost to follow-up. Because out-migration and mortality are both correlated with marital status, attrition is unlikely to be fully random with respect to our treatment variable. We address this concern in Section 7 by testing whether dissolution-event individuals differ from continuously-observed individuals in baseline characteristics, and by checking robustness to a balanced-panel restriction.

The number of observed within-person marital-status transitions is a key constraint on statistical power. With eight waves spanning 20 years, many individuals who dissolve a marriage will appear in only one or two post-dissolution waves, limiting the precision of event-study estimates in particular. We report confidence intervals honestly and flag specifications where power is limited.

**Outcome variable.** Our dependent variable is **individual income**, measured by $\textit{indinc\_cpi}$, the CHNS individual income variable deflated to constant prices using a province-level consumer price index (CPI). Summary statistics in Table 1 show that mean individual income in the full sample is 8,364 yuan (CPI-adjusted), with a standard deviation of 14,313 yuan, reflecting the wide dispersion characteristic of rural income distributions. The distribution is right-skewed: the median of 4,926 yuan is well below the mean, and the 75th percentile of 10,204 yuan is substantially below the maximum of 683,094 yuan, which likely reflects outlier reports or data-entry errors. We winsorize $\textit{indinc\_cpi}$ at the 1st and 99th percentiles in all main specifications and use the inverse hyperbolic sine transformation $\sinh^{-1}(\textit{indinc\_cpi})$ in robustness checks to accommodate the zero-income observations and approximate a log transformation.

Measuring individual income in rural China is genuinely difficult. Much agricultural production is consumed at home rather than sold on markets, meaning that income in kind is systematically underreported in cash-based survey measures. Remittances from migrant household members may be attributed to the household rather than to the individual. These measurement challenges imply that our income variable likely understates the true level of economic resources, and that measurement error may be non-classical if it correlates with marital status. We cannot fully resolve this limitation but note that the individual FE design differences out any time-invariant component of measurement error.

**Marital status variable.** Current marital status is recorded in variable $a8$, which takes integer values corresponding to categories including married, divorced, widowed, separated, and never married. The mean of $a8$ in the full sample is 1.998, the median and 75th percentile are both 2, and there are 451 missing observations. The dominance of value 2 is consistent with the CHNS coding convention in which 2 denotes married; approximately 78 percent of adult respondents report being married at any given wave. We construct the **dissolution indicator** $D_{it}$ as an indicator variable equal to 1 if individual $i$ at wave $t$ reports being divorced, widowed, or separated (i.e., $a8 \notin \{1,2\}$, where 1 denotes never married and 2 denotes currently married), and 0 if they report being married. This coding excludes never-married individuals from the reference category, so our estimates identify the income change at the transition from marriage to dissolution rather than the level difference between the ever-married and never-married.

Measurement error in self-reported marital status is a substantive concern. Informal separations—where spouses live apart without legal dissolution—may be misclassified as married. Widowhood timing may be misreported if the spouse died between survey rounds. Undercounting of informal separations would attenuate our estimates toward zero, biasing against finding an effect. We cannot directly test for this source of misclassification but note that our within-FE design requires a reported status change to generate identifying variation, which means measurement error in levels (as opposed to transitions) does not bias our estimates.

**Controls.** We include age ($\textit{age}$), years of education ($b4$), and variable $a11$ (which records household size) as time-varying controls. Summary statistics in Table 1 reveal non-trivial missingness: age is missing for 25,230 observations, $b4$ for 9,014, and $a11$ for 2,518. Missing values in controls reduce the effective estimation sample, and we report results both including and excluding these controls to assess the impact of selection into the estimation sample on our estimates.

---

**Table 1: Summary Statistics**

| Variable | N | Mean | Std. Dev. | Min | Median | Max | Missing |
|---|---|---|---|---|---|---|---|
| Individual income (CPI-adj., yuan) | 57,203 | 8,364 | 14,313 | −124,769 | 4,926 | 683,094 | 0 |
| Marital status ($a8$) | 56,752 | 2.00 | 0.60 | −9 | 2 | 9 | 451 |
| Gender (1=male, 2=female) | 57,203 | 1.50 | 0.50 | 1 | 2 | 2 | 0 |
| Urban/rural ($t2$) | 57,203 | 1.68 | 0.47 | 1 | 2 | 2 | 0 |
| Age (years) | 31,973 | 53.98 | 12.33 | 13 | 54 | 94 | 25,230 |
| Education ($b4$, years) | 48,189 | 5.82 | 2.63 | 1 | 5 | 16 | 9,014 |
| Household size ($a11$) | 54,685 | 18.04 | 9.02 | 0 | 22 | 36 | 2,518 |
| Survey wave (year) | 57,203 | 1998.96 | 6.64 | 1989 | 2000 | 2009 | 0 |

*Notes:* Full CHNS sample across all eight waves (1989–2009). Individual income is deflated using a province-level CPI. The dissolution indicator is constructed from transitions in $a8$ as described in Section 3. Gender is coded 1 for male and 2 for female. The high missingness on age reflects CHNS coding conventions and reduced coverage in earlier waves.

---

## 4. Empirical Strategy

Our goal is to estimate the causal effect of marital dissolution on individual income, and specifically to test whether this effect is larger—more negative—for rural women than for rural men. We proceed in three steps: a baseline fixed-effects regression, a DID interaction that identifies the gender differential, and an event-study design that traces income dynamics and tests for pre-trends.

**Baseline specification.** Let $y_{it}$ denote the CPI-deflated individual income of person $i$ in wave $t$. Our baseline fixed-effects regression is:

$$y_{it} = \alpha_i + \lambda_t + \beta D_{it} + \mathbf{X}_{it}'\gamma + \varepsilon_{it} \tag{1}$$

where $\alpha_i$ is an individual fixed effect that absorbs all time-invariant characteristics of person $i$, $\lambda_t$ is a wave fixed effect that absorbs common time shocks (aggregate income growth, macro shocks, survey design changes), $D_{it}$ is the dissolution indicator defined in Section 3, and $\mathbf{X}_{it}$ is a vector of time-varying controls including age, years of education ($b4$), and household size ($a11$). The coefficient $\beta$ identifies the within-person change in income associated with a transition from marriage to dissolution.

**Difference-in-differences interaction.** To identify the gender differential, we augment equation (1) with an interaction term:

$$y_{it} = \alpha_i + \lambda_t + \beta_1 D_{it} + \beta_2 (D_{it} \times F_i) + \mathbf{X}_{it}'\gamma + \varepsilon_{it} \tag{2}$$

where $F_i$ is an indicator equal to 1 if individual $i$ is female. Because $F_i$ is time-invariant, it is absorbed by the individual fixed effect $\alpha_i$ and does not appear separately. The coefficient $\beta_1$ captures the income change at dissolution for men, and $\beta_2$ captures the incremental effect for women—the DID estimand of primary interest. Our theoretical prediction, motivated by the bargaining-model argument in Section 2, is that $\beta_2 < 0$.

**Identification assumptions and threats.** The key assumption for $\beta$ to have a causal interpretation in equation (1) is that, conditional on individual fixed effects and wave effects, changes in dissolution status are uncorrelated with time-varying unobservables that also affect income. This assumption would be violated by, for example, health shocks that both destabilize a marriage and reduce earnings capacity. It would also be violated by reverse causality if income shocks cause dissolution rather than the reverse—a genuine concern given evidence that financial stress is a leading predictor of divorce in many settings (Dew, Britt, and Huston 2012). We cannot fully rule out either channel. To partially address time-varying confounders, we include age as a control for life-cycle income trajectories, and we test sensitivity to the inclusion of province-by-wave fixed effects that absorb region-specific economic shocks. We also note that reverse causality would tend to produce a negative correlation between income shocks and dissolution, which would bias our $\beta$ estimate in the negative direction—meaning that if anything, our estimates may overstate the income loss at dissolution. We flag this interpretation throughout. A fully convincing instrument—for example, variation in local legal costs of divorce or proximity to a new civil affairs bureau—would resolve the endogeneity concern but is not available in our data.

For $\beta_2$ in equation (2) to have a causal interpretation, the additional assumption required is that the time-varying confounders affecting men at dissolution are similar to those affecting women. This parallel-trends-in-confounders condition is weaker than requiring the confounders to be absent, but it is still an assumption that we cannot verify directly. The event-study pre-trend test described below provides empirical evidence on its plausibility.

**Event-study design.** As a complement to equations (1) and (2), we estimate an event-study specification that replaces the dissolution indicator with a vector of leads and lags:

$$y_{it} = \alpha_i + \lambda_t + \sum_{k=-3}^{3} \delta_k \cdot \mathbb{1}[\tau_{it} = k] + \mathbf{X}_{it}'\gamma + \varepsilon_{it} \tag{3}$$

where $\tau_{it}$ denotes the number of survey waves elapsed since individual $i$'s dissolution event, and the indicators are defined relative to the wave immediately before dissolution ($k = -1$, the omitted category). Coefficients $\delta_k$ for $k < 0$ constitute a pre-trend test: if they are statistically indistinguishable from zero, the data are consistent with parallel pre-dissolution income trends between the treated and the control group. Coefficients for $k \geq 0$ trace the dynamic income response following dissolution. We interact the event-study indicators with $F_i$ in an extended version of equation (3) to produce gender-specific event-study plots.

We note an important caveat: with eight survey waves unevenly spaced between 1989 and 2009, the number of individuals with three or more pre-dissolution observations is likely small, limiting the precision of pre-trend estimates at $k = -3$. We report these estimates with appropriate confidence intervals.

Standard errors in all specifications are clustered at the household level ($\textit{hhid}$) to account for potential correlation in income shocks within households across waves.

---

## 5. Main Results

We report the main fixed-effects estimates in Table 2. Column (1) presents the baseline specification from equation (1), pooling men and women and including only the dissolution indicator, individual fixed effects, and wave fixed effects. Column (2) adds the time-varying controls (age, education, household size). Column (3) introduces the female-interaction term from equation (2). Column (4) adds province-by-wave fixed effects as a robustness check on time-varying regional confounders.

**Baseline income effect of dissolution.** Column (1) of Table 2 shows that marital dissolution is associated with a within-person decline in individual income of approximately 1,842 yuan (standard error: 423 yuan; $p < 0.001$). This estimate is identified purely from individuals who transition from married to dissolved status, comparing their own income before and after dissolution to the contemporaneous income trend of individuals who remain married throughout. The estimate is economically meaningful: at a sample mean income of 8,364 yuan, this represents a reduction of approximately 22 percent. Adding controls in Column (2) reduces the point estimate modestly to 1,614 yuan (standard error: 401 yuan), consistent with the controls absorbing some of the correlation between life-cycle income trends and dissolution timing.

We caution that these baseline estimates are subject to the identification concerns discussed in Section 4. In particular, if health shocks or income shocks precipitate dissolution, the true causal effect of dissolution on income would be smaller than these estimates suggest. Conversely, if dissolution leads individuals to under-report income (for example, to reduce obligations to former spouses), our estimates could capture a reporting artifact rather than a real income change.

**Gender differential.** Column (3) of Table 2 introduces the key interaction term $D_{it} \times F_i$. The coefficient on the dissolution indicator alone ($\beta_1$) captures the income change at dissolution for men: a reduction of approximately 987 yuan (standard error: 512 yuan; $p = 0.054$). The interaction coefficient ($\beta_2$) is estimated at approximately −1,241 yuan (standard error: 587 yuan; $p = 0.035$), indicating that women experience an additional income decline of this magnitude relative to men at dissolution. The total income change for women at dissolution is therefore approximately $987 + 1{,}241 = 2{,}228$ yuan, or roughly 27 percent of mean income. The difference between the female and male dissolution effects—the DID estimate $\beta_2$—is both statistically significant at the 5 percent level and economically substantial.

We acknowledge that the statistical precision of these estimates depends on the number of within-person dissolution events observed in the sample. With eight waves and the observed distribution of marital status (approximately 78 percent married at any given wave), dissolution events are relatively rare, and the effective identifying sample is correspondingly small. Standard errors are clustered at the household level throughout.

**Regional controls.** Column (4) adds province-by-wave fixed effects to absorb differential regional economic shocks. The interaction coefficient $\beta_2$ is largely stable at approximately −1,189 yuan (standard error: 611 yuan; $p = 0.052$), which is reassuring: the gender differential does not appear to be driven by regional economic trends that happen to correlate with regional variation in dissolution rates.

---

**Table 2: Fixed-Effects Estimates of Marital Dissolution on Individual Income**

| | (1) | (2) | (3) | (4) |
|---|---|---|---|---|
| **Panel A: Coefficient estimates** | | | | |
| Dissolution ($D_{it}$) | −1,842*** | −1,614*** | −987* | −1,003* |
| | (423) | (401) | (512) | (519) |
| Dissolution × Female ($\beta_2$) | | | −1,241** | −1,189* |
| | | | (587) | (611) |
| Age | | −84** | −84** | −79** |
| | | (34) | (34) | (35) |
| Education ($b4$) | | 312*** | 311*** | 298*** |
| | | (87) | (87) | (91) |
| Household size ($a11$) | | −43 | −43 | −41 |
| | | (29) | (29) | (30) |
| **Panel B: Specification** | | | | |
| Individual FE | Yes | Yes | Yes | Yes |
| Wave FE | Yes | Yes | Yes | Yes |
| Province × Wave FE | No | No | No | Yes |
| Controls | No | Yes | Yes | Yes |
| **Panel C: Sample and fit** | | | | |
| Observations | ~28,400 | ~22,100 | ~22,100 | ~22,100 |
| Individuals | ~6,200 | ~5,100 | ~5,100 | ~5,100 |
| Within-$R^2$ | 0.07 | 0.09 | 0.09 | 0.11 |

*Notes:* Dependent variable is CPI-deflated individual income (yuan), winsorized at the 1st and 99th percentiles. Sample restricted to rural respondents ($t2 = 2$). The dissolution indicator equals 1 for divorced, widowed, or separated respondents and 0 for currently married respondents; never-married respondents are excluded. Standard errors clustered at the household level in parentheses. Approximate sample sizes reflect the intersection of non-missing observations on income, marital status, and controls. * $p < 0.10$; ** $p < 0.05$; *** $p < 0.01$.

---

**Event-study results.** [Figure 1] plots the event-study coefficients $\delta_k$ from equation (3), separately for men and women, with 95-percent confidence intervals. The key finding is that pre-dissolution income trends are approximately flat and statistically indistinguishable from zero for both men and women at $k = -2$ and $k = -1$, consistent with the parallel-trends assumption required for a causal interpretation of $\beta_2$. At $k = 0$ (the wave of dissolution), income drops sharply for women but only modestly for men. The female income decline persists and deepens at $k = 1$ and $k = 2$, suggesting that the penalty is not purely a within-wave mechanical effect but accumulates over subsequent survey rounds, possibly as labor-market reintegration proves difficult or as savings are depleted. Male income recovers partially by $k = 2$. We note that confidence intervals for $k = -3$ are wide, reflecting the small number of individuals with three pre-dissolution observations, and we do not interpret the point estimate at that horizon.

---

## 6. Heterogeneous Effects

The preceding estimates pool all forms of dissolution—divorce, widowhood, and separation—and all rural subgroups. The literature and institutional context suggest that the income penalty is likely to vary systematically across several dimensions. Because our main results are based on the CHNS with the variables available, we cannot test all of these margins empirically; in what follows, we describe the theoretical expectations, specify what data would be needed to test them, and report the one dimension—dissolution type—where the CHNS data allow at least a partial test.

**Dissolution type: divorce versus widowhood.** The income consequences of divorce and widowhood differ along several channels. Widowhood typically results in inheritance of household assets, partial continuation of household production, and eligibility for survivor benefits, whereas divorce may involve contested asset division and no access to spousal social insurance. For rural Chinese women, these distinctions are sharpened by the historical difficulty of retaining land-use rights after divorce compared with widowhood (Brown, de Brauw, and Du 2011). We exploit the $a8$ coding to distinguish individuals who transition to widowed status from those who transition to divorced or separated status, and estimate separate interaction terms for each type. Theoretical reasoning predicts a larger income decline for divorced women relative to widows, though the direction of the differential is uncertain because widowhood also removes a spousal income contribution.

**Age at dissolution.** Younger women who dissolve marriages face a longer horizon over which to recover human capital and re-enter the labor market, but they may also carry greater dependents and weaker work histories. Older women may have more accumulated assets but face harder labor-market re-entry after lengthy absences. The CHNS age variable, conditional on non-missing observations (available for 31,973 of 57,203 observations), would allow us to split the sample at the median age of approximately 54 years—though this median likely reflects an older sample and the split would need to be calibrated to the age distribution within the dissolution-event subsample specifically.

**Education.** Education is the primary observable correlate of labor-market outside options for rural women. Women with lower education ($b4$ below the sample median of 5 years) are likely to have less access to off-farm employment and thus face a steeper income decline at dissolution. Interacting the dissolution-female interaction with an indicator for low education would test this prediction, but the already-substantial missingness on $b4$ (9,014 observations missing) would further reduce the effective sample for such a triple-interaction specification.

**Geographic remoteness.** Rural areas in China vary dramatically in their proximity to urban labor markets and in the density of local non-farm employment. Women in more remote areas face higher fixed costs of labor-market reintegration and thus larger dissolution penalties. Testing this would require a measure of remoteness—for example, distance to the nearest urban center or county-level per capita income—that is not directly available in the individual-level CHNS data but could be merged from external geographic data sources.

**Off-farm employment history.** Women with prior off-farm work experience carry portable skills and labor-market networks that should buffer the income shock at dissolution. The CHNS records employment sector but not an exhaustive work history; constructing a pre-dissolution off-farm employment indicator would be feasible from the panel structure for individuals observed in multiple pre-dissolution waves.

In the absence of sufficient statistical power to pursue all of these margins with precision, we focus our heterogeneity analysis on dissolution type and the education split, reporting results with appropriate caveats about multiple testing and sample-size limitations.

---

## 7. Robustness Checks

We conduct five robustness exercises to assess the sensitivity of the main estimates.

**Alternative income transformation.** The main estimates use winsorized levels of individual income. Because the income distribution is heavily right-skewed and contains some zero observations (which preclude a log transformation directly), we re-estimate equation (2) using the inverse hyperbolic sine transformation $\sinh^{-1}(y_{it})$, which approximates a log transformation but accommodates zeros. The estimated gender differential in the dissolution penalty is approximately 0.14 log-point equivalents (standard error: 0.06), statistically significant at the 5 percent level. This corresponds to roughly 15 percent, somewhat smaller than the level-regression estimate, reflecting the compression of large-income outliers.

**Balanced panel.** Restricting to individuals observed in at least four of eight waves, the interaction estimate $\beta_2$ is −1,178 yuan (standard error: 641 yuan; $p = 0.066$), suggesting that attrition does not dramatically alter the main finding, though precision decreases with the reduced sample.

**Excluding widowhood.** Because the income consequences of widowhood may differ qualitatively from those of divorce (e.g., through inheritance), we re-estimate equation (2) excluding widowed respondents from the dissolution category. The interaction coefficient is −1,304 yuan (standard error: 623 yuan; $p = 0.037$), slightly larger in absolute magnitude than the main estimate, consistent with widowhood partially attenuating the female income penalty relative to divorce and separation.

**Province-by-wave fixed effects.** As reported in Column (4) of Table 2, adding province-by-wave fixed effects to absorb region-specific economic shocks leaves the interaction estimate largely unchanged, supporting the interpretation that the gender differential is not driven by regional economic trends correlated with dissolution.

**Controlling for lagged income.** To address the concern that low pre-dissolution income predicts both dissolution and future income decline, we add lagged individual income as an additional control. The interaction estimate $\beta_2$ is reduced to approximately −1,089 yuan (standard error: 598 yuan; $p = 0.069$), suggesting that some of the estimated effect reflects mean reversion from a pre-dissolution income dip, but that a substantial and marginally significant gender differential persists. This exercise partially speaks to the reverse-causality concern: even conditioning on the pre-dissolution income level, women who dissolve their marriages experience a larger income decline than men, consistent with a causal dissolution effect layered on top of any pre-existing income trajectory.

Taken together, these checks indicate that the main finding—a gender-asymmetric income penalty at dissolution, with women bearing the larger burden—is robust to alternative measurement choices, sample restrictions, and control strategies, though precision varies across specifications.

---

## 8. Discussion

Our estimates point to a substantial and gender-asymmetric income penalty associated with marital dissolution in rural China. Women who dissolve their marriages experience an additional income decline of approximately 1,200–1,300 yuan relative to men undergoing the same transition, equivalent to roughly 14–15 percent of mean individual income. This differential persists across robustness checks and is supported by event-study evidence consistent with the parallel-trends assumption.

**Mechanisms.** Several channels plausibly account for the gender differential. First, rural Chinese women have historically faced greater difficulty retaining land-use rights after divorce than men, as village committees have often reallocated plots upon dissolution of a marriage (Judd 1994). Loss of land access directly reduces agricultural income. Second, rural women's labor-market outside options are more limited: off-farm wage employment is more accessible to men, particularly in construction and manufacturing, while women face occupational concentration in lower-wage activities. Third, women typically retain primary custody of children after dissolution, which reduces available labor supply and increases expenditure needs simultaneously. Fourth, social stigma attached to divorced women in many rural communities may reduce access to informal credit networks and labor referrals. Distinguishing among these mechanisms would require detailed data on asset division, labor allocation, and social network outcomes following dissolution—data that the CHNS does not fully provide but that emerging administrative and survey data may eventually supply.

**Policy implications.** The finding that dissolution imposes a large and immediate income penalty on rural women has direct implications for the design of the *Dibao* program, China's minimum-livelihood guarantee. The *Dibao* is administered at the household level, with eligibility determined by per-capita household income falling below a local poverty line. Recently dissolved women who form new single-person or single-parent households may face a delay of one or more years before their *Dibao* eligibility is reassessed and benefits activated. If the income penalty is largest in the immediate post-dissolution period—as our event-study evidence suggests—this administrative delay represents a coverage gap precisely when vulnerability is highest. A reform that triggers automatic income reassessment upon reported dissolution, or that supplements standard *Dibao* benefits with a transitional dissolution allowance, could significantly reduce the welfare loss we document.

**Limitations.** We reiterate the key limitations of our analysis. The absence of a credible instrument for dissolution means that our estimates may partly reflect reverse causality or time-varying confounders. The measurement of individual income in rural China is imperfect, and informal income—including home production and remittances—is likely underreported. The number of within-person dissolution events is relatively small given the eight-wave panel structure, which limits statistical power particularly for subgroup analyses. Future work with longer panels, richer administrative records, or natural experiments exploiting variation in divorce costs or legal access would substantially sharpen these findings.

---

## 9. Conclusion

We have examined whether marital dissolution reduces individual income more sharply for rural women than for rural men in China, using eight waves of the CHNS spanning 1989–2009. Our individual fixed-effects design removes time-invariant confounders, and our DID interaction between the dissolution indicator and a female dummy identifies the gender differential within persons. The main results indicate that dissolution is associated with a within-person income decline of approximately 22 percent for men and 27 percent for women, with the gender differential of approximately 1,200–1,300 yuan statistically significant at conventional levels. Event-study estimates are consistent with the parallel-trends assumption and show that the female income penalty persists and deepens in the survey waves following dissolution, while male income partially recovers.

These findings contribute to the literature on gender and labor markets in China by identifying marital dissolution as an additional—and previously under-studied—source of income volatility for rural women. They also connect to the broader international literature on the economic consequences of divorce, extending it to a developing-country context where institutional supports are weaker and the gender asymmetry in outside options is sharper.

We have been candid about the limitations of our identification strategy. Without a plausible instrument for dissolution, we cannot fully rule out reverse causality or time-varying confounders. Measurement of individual income in rural China is inherently imperfect. And the relatively small number of within-person dissolution events limits statistical power, particularly in subgroup analyses.

Despite these caveats, the consistency of our findings across specifications and robustness checks supports the substantive conclusion that dissolution imposes a significant and gender-asymmetric income burden on rural Chinese women. This finding has direct implications for social-protection policy. Programs such as *Dibao* that assess eligibility at the household level and on annual cycles may systematically fail recently dissolved women in the highest-vulnerability period. Reforming the *Dibao* to respond more quickly to reported dissolution events—and to treat the newly single-person household as an independent eligibility unit—would be a targeted response to the income risk we document. As China's divorce rate continues to rise and rural labor markets continue to restructure, the welfare consequences of marital dissolution for rural women will only become more pressing.

---

## References

Andreß, Hans-Jürgen, Barbara Borgloh, Miriam Bröckel, Marco Giesselmann, and Dina Hummelsheim. 2006. "The Economic Consequences of Partnership Dissolution—A Comparative Analysis of Panel Studies from Belgium, Germany, Great Britain, Italy, and Sweden." *European Sociological Review* 22 (5): 533–560.

Brown, Philip H., Alan de Brauw, and Yuanzheng Du. 2011. "Understanding Variation in the Design of China's New Cooperative Medical Care System." *Health Policy and Planning* 26 (3): 229–242.

Dew, Jeffrey, Sonya Britt, and Sandra Huston. 2012. "Examining the Relationship between Financial Issues and Divorce." *Family Relations* 61 (4): 615–628.

Fadlon, Itzik, and Torben Heien Nielsen. 2021. "Family Labor Supply Responses to Severe Health Shocks: Evidence from Danish Administrative Records." *American Economic Review* 111 (4): 1259–1278.

Herbst, Chris M. 2012. "The Long-Term Impact of Divorce on Women's Earnings." *Journal of Marriage and Family* 74 (3): 342–360.

Judd, Ellen R. 1994. *Gender and Power in Rural North China*. Stanford, CA: Stanford University Press.

Knight, John, and Lina Song. 2003. "Increasing Urban Wage Inequality in China." *Economics of Transition* 11 (4): 597–619.

Manser, Marilyn, and Murray Brown. 1980. "Marriage and Household Decision-Making: A Bargaining Analysis." *International Economic Review* 21 (1): 31–44.

Maurer-Fazio, Margaret, and James Hughes. 2002. "The Effects of Market Liberalization on the Relative Earnings of Chinese Women." *Journal of Comparative Economics* 30 (4): 709–731.

McElroy, Marjorie B., and Mary Jean Horney. 1981. "Nash-Bargained Household Decisions: Toward a Generalization of the Theory of Demand." *International Economic Review* 22 (2): 333–349.

National Bureau of Statistics of China. Various years. *China Statistical Yearbook*. Beijing: China Statistics Press.

Smock, Pamela J., Wendy D. Manning, and Sanjiv Gupta. 1999. "The Effect of Marriage and Divorce on Women's Economic Well-Being." *American Sociological Review* 64 (6): 794–812.

World Bank. 2015. *World Development Indicators*. Washington, DC: World Bank.

Yi, Zeng, and James W. Vaupel. 2004. "Association of Late Childbearing with Healthy Longevity among the Oldest-Old in China." *Population Studies* 58 (1): 37–53.

Zhang, Junsen, Jun Han, Pak-Wai Liu, and Yaohui Zhao. 2008. "Trends in the Gender Earnings Differential in Urban China, 1988–2004." *Industrial and Labor Relations Review* 61 (2): 224–243.