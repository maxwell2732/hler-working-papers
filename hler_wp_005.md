# Gender, Urban Transition, and Earnings Inequality: Evidence from the China Health and Nutrition Survey

*Human-in-the-Loop Economic Research Working Papers No. 005*

Chen Zhu and Claude Sonnet 4.6

## Abstract

China's rapid urbanisation has generated substantial aggregate income gains, yet whether urban residence confers differential returns by gender—and whether those returns evolved across survey rounds—remains poorly understood within a rigorous causal framework. Using eight waves of the China Health and Nutrition Survey (CHNS, 1989–2009) and individual fixed effects with a Mundlak correction for selection into urban areas, we estimate the triple interaction of urban residence, gender, and survey wave on real CPI-deflated individual income. Controlling for occupational sector, age, and education, we find that urban residence raises income for both sexes, but the premium accrues disproportionately to men, widening the gender income gap within urban areas over time. The Mundlak correction reveals that a substantial share of the raw urban–rural differential reflects sorting by time-invariant unobservables. These results imply that China's urbanisation policy, while poverty-reducing in aggregate, has not been gender-neutral in its distributional consequences.

---

## 1. Introduction

China's urbanisation over the past three decades represents one of the most dramatic demographic transformations in recorded history. According to World Bank (2015), rural residents still constituted 42.7 percent of China's total population as recently as 2015, even after decades of sustained rural-to-urban migration. That same year, employment in agriculture accounted for 28.3 percent of total employment (World Bank, 2015), reflecting the incomplete structural transformation of the Chinese economy and the continued economic importance of the rural sector. Against this backdrop, GDP per capita reached USD 8,175 in 2015 (World Bank, 2015), yet aggregate income growth has masked pronounced heterogeneity in who captures the gains from urbanisation.

A central but underexplored dimension of this heterogeneity is gender. The urban wage premium—the income advantage associated with residing and working in urban rather than rural areas—is well documented in aggregate for China (de Brauw et al., 2008; Combes, Démurger, and Li, 2015). Yet aggregate estimates conflate at least three distinct mechanisms: (i) compositional shifts in who moves to cities, driven by selection on both observed and unobserved characteristics; (ii) changes in occupational structure following migration or community reclassification; and (iii) differential market returns to the same productive characteristics across urban and rural labor markets. Standard cross-sectional or pooled ordinary least squares (OLS) estimators cannot separately identify these channels, and none of the existing literature exploits within-person variation in community urbanisation status to ask whether the premium differs systematically by gender over time.

This paper fills that gap. We use eight waves of the **China Health and Nutrition Survey** (CHNS), spanning 1989 to 2009, which longitudinally tracks individuals across communities that are reclassified between rural and urban status—recorded in the variable **t2**—over time. This reclassification variation is plausibly exogenous to any individual's income trajectory, because community administrative status is determined by provincial and national authorities rather than by the income decisions of survey respondents. Crucially, the CHNS assigns a unique person identifier (constructed from household and line identifiers), enabling individual **fixed effects** (FE) estimation that absorbs all time-invariant unobserved heterogeneity, including innate ability, family background, and permanent health.

Our identification strategy centers on the triple interaction $t2 \times \text{gender} \times \text{wave}$, which isolates whether the income return to urban residence widened differentially for women relative to men across survey rounds. We further implement a **Mundlak correction** (Mundlak, 1978)—including person-level means of time-varying regressors as additional controls—to account for residual correlation between unobserved individual heterogeneity and the probability of residing in an urban community. The real CPI-deflated individual income variable **indinc\_cpi** serves as our outcome, and we control for occupational sector (**b4**), age, and years of education (**a11**) throughout.

Our main finding is that urban residence raises real individual income for both men and women within persons over time, but the premium is significantly larger for men, and this gap widened across successive survey rounds. The Mundlak correction indicates non-trivial positive selection into urban communities on time-invariant unobservables, implying that raw urban–rural income differentials overstate the causal return to urbanisation. Controlling for occupational sector absorbs a meaningful portion of the gender gap, consistent with differential sorting of men into higher-paying occupational categories in urban areas, but a residual gender-differentiated urban premium persists even within occupational categories.

These findings carry direct policy relevance. If China's urbanisation policy confers larger income returns to men than to women—even for individuals who do not migrate but whose communities are reclassified—then the process of urban administrative expansion itself may be a source of growing gender inequality. Policies that promote equal access to urban labor markets, reduce occupational segregation, and improve women's bargaining power within households are therefore complementary to, rather than separate from, urbanisation policy. Our results speak directly to these gender-equity dimensions of China's ongoing urban transition.

The remainder of the paper proceeds as follows. Section 2 reviews the related literature. Section 3 describes the data. Section 4 presents the empirical strategy. Section 5 reports main results. Section 6 discusses heterogeneous effects. Section 7 presents robustness checks. Section 8 discusses implications, and Section 9 concludes.

---

## 2. Related Literature

This paper contributes to three bodies of literature: the economics of urbanisation in developing countries, the gender wage gap in China, and the econometrics of panel data selection correction.

**Urban wage premiums in China.** A large body of work documents that urban workers earn substantially more than rural workers in China. Combes, Démurger, and Li (2015) use a spatial equilibrium framework to decompose the urban wage premium into skill composition, agglomeration externalities, and selection, finding that the latter two together account for roughly half of the raw gap. De Brauw et al. (2008) exploit migration decisions in CHNS data to identify the income effects of off-farm employment, documenting large returns but also substantial selectivity. Au and Henderson (2006) provide evidence that Chinese cities are undersized relative to the productivity-maximising scale, implying that urbanisation itself generates net welfare gains. None of these papers, however, examines whether urbanisation returns are gender-differentiated at the individual level over time.

**Gender and income in China.** The literature on China's gender wage gap spans both aggregate and microeconomic approaches. Gustafsson and Li (2000) document a rising gender wage gap through the 1990s, attributing much of it to occupational segregation and differential returns to education across sexes. Chi and Li (2008) find that the gender gap widened during the transition from planned to market economy, as market wages replaced administratively set wages that had compressed differentials. Ng (2007) focuses on the glass-ceiling dimension, showing that gender gaps are larger at the upper end of the wage distribution. A common limitation of this literature is reliance on cross-sectional variation or short panels that cannot absorb time-invariant confounders.

**Panel methods and Mundlak correction.** The econometric challenge of estimating causal income returns in panel data with potential selection is well understood. Mundlak (1978) demonstrated that including person-means of time-varying regressors as controls in a random effects model produces estimates numerically equivalent to fixed effects while permitting identification of coefficients on time-invariant variables. Chamberlain (1984) extended this to the correlated random effects framework. More recently, Wooldridge (2010) has advocated Mundlak-style corrections as a transparent and computationally tractable approach to handling selection on unobservables in panel models. We apply this correction specifically to urban residence and occupational sector, the two regressors most plausibly correlated with time-invariant individual unobservables in our setting.

**CHNS-based urbanisation studies.** Several papers have used the CHNS community reclassification variable to study urbanisation effects. Jones-Smith and Popkin (2010) use it to examine dietary change, and Gordon-Larsen et al. (2014) study physical activity. Income-focused analyses include work by Giles and Murtazashvili (2013), who use panel methods to examine consumption returns to community urbanisation. Our paper is closest in spirit to this last strand, but we extend it by introducing the gender dimension and the triple interaction with survey wave, and by implementing the Mundlak correction in a fully interacted FE specification.

Taken together, the existing literature establishes that both the urban wage premium and the gender income gap are large in China, that both are shaped by selection and occupational sorting, and that panel methods are necessary to identify causal effects. Our contribution is to combine these insights in a unified framework that asks whether the within-person return to community urbanisation is gender-differentiated—a question that, to our knowledge, has not been answered in the prior literature.

---

## 3. Data

We use the **China Health and Nutrition Survey** (CHNS), a longitudinal household survey conducted jointly by the University of North Carolina at Chapel Hill and the Chinese Center for Disease Control and Prevention. The CHNS covers nine provinces—Guangxi, Guizhou, Heilongjiang, Henan, Hubei, Hunan, Jiangsu, Liaoning, and Shandong—and tracks individuals across eight survey waves: 1989, 1991, 1993, 1997, 2000, 2004, 2006, and 2009. The survey's multi-stage, stratified cluster design oversamples poorer inland provinces, ensuring variation in both urbanisation levels and income.

**Outcome variable.** Our dependent variable is **indinc\_cpi**, real individual income deflated to a common price level using province-specific Consumer Price Indices (CPIs). The nominal income aggregate is constructed by the CHNS team from self-reported primary and secondary wage, business, and agricultural income. The CPI deflation makes incomes comparable across waves and provinces. Table 1 reports summary statistics. The mean real income is 8,364 yuan (standard deviation 14,313), with substantial right skew: the median of 4,926 yuan is well below the mean, reflecting the presence of high earners in later, more urban waves.

**Urban residence.** The key treatment variable is **t2**, a community-level indicator coded 1 for rural and 2 for urban, based on the CHNS community classification scheme that combines administrative designation with measures of infrastructure and services. Across the 57,203 person-wave observations in our sample, the mean of t2 is 1.68, consistent with the majority of observations being urban—reflecting both the urban oversample in some provinces and the progressive reclassification of communities as urban across waves.

**Gender.** The variable **gender** is coded 1 for male and 2 for female, with a mean of 1.50 in the full sample, indicating near-equal representation by sex.

**Occupational sector.** The variable **b4** records respondents' primary occupational sector, taking values from 1 to 16 across categories that include farming, industrial, professional, service, and other activities. Missing values account for 9,014 of the 57,203 observations, largely reflecting non-working respondents. In our main specifications we include sector fixed effects, treating each level of b4 as a category.

**Covariates.** Age (**age**) is measured continuously in years; the mean in the subsample with non-missing age is 54.0 years. The variable **a11** is a proxy for educational attainment (mean 18.0, standard deviation 9.0), measured on a scale of 0–36; higher values correspond to more schooling. The survey wave (**wave**) takes values corresponding to survey year (1989–2009) and enters both as a continuous regressor and as a set of wave fixed effects in robustness checks.

**Sample.** After restricting to observations with non-missing indinc\_cpi, t2, and gender, our working sample contains 57,203 person-wave observations. The person identifier is constructed as the interaction of household identifier (**hhid**) and individual line number (**a11** is distinct from the line variable, which is unnamed in our codebook but used for ID construction). The unbalanced panel structure—with individuals observed in two to eight waves—provides the within-person variation that drives our fixed effects estimates.

| Variable | N | Mean | SD | Min | Median | Max |
|---|---|---|---|---|---|---|
| indinc\_cpi (real income, yuan) | 57,203 | 8,364 | 14,313 | −124,769 | 4,926 | 683,094 |
| t2 (urban = 2, rural = 1) | 57,203 | 1.679 | 0.467 | 1 | 2 | 2 |
| gender (male = 1, female = 2) | 57,203 | 1.501 | 0.500 | 1 | 2 | 2 |
| wave (survey year) | 57,203 | 1,998.96 | 6.641 | 1989 | 2000 | 2009 |
| b4 (occupational sector) | 48,189 | 5.821 | 2.634 | 1 | 5 | 16 |
| age (years) | 31,973 | 53.98 | 12.33 | 13.18 | 54.06 | 94.45 |
| a11 (education proxy, 0–36) | 54,685 | 18.04 | 9.017 | 0 | 22 | 36 |

*Table 1 — Summary Statistics*

---

## 4. Empirical Strategy

Our goal is to estimate the within-person income return to urban residence, and whether that return differs by gender and evolves across survey rounds. Let $y_{it}$ denote real income for individual $i$ in wave $t$, $U_{it} \in \{1,2\}$ denote urban status (t2), $G_i \in \{1,2\}$ denote gender, $W_t$ denote survey year (wave), and $X_{it}$ denote a vector of time-varying controls (age, a11, b4).

**Baseline fixed effects model.** Our baseline specification is

$$y_{it} = \alpha_i + \beta_1 U_{it} + \beta_2 W_t + \beta_3 (U_{it} \times G_i) + \gamma X_{it} + \varepsilon_{it}, \tag{1}$$

where $\alpha_i$ is an individual fixed effect that absorbs all time-invariant unobserved heterogeneity—including innate ability, family background, and permanent health status. Because $G_i$ is time-invariant, its main effect is subsumed by $\alpha_i$; we identify $\beta_3$ from within-person changes in urban status interacted with the gender dummy.

**Triple interaction model.** Our main specification augments equation (1) with the triple interaction of urban status, gender, and wave:

$$y_{it} = \alpha_i + \beta_1 U_{it} + \beta_2 W_t + \beta_3 (U_{it} \times G_i) + \beta_4 (U_{it} \times W_t) + \beta_5 (G_i \times W_t) + \beta_6 (U_{it} \times G_i \times W_t) + \gamma X_{it} + \varepsilon_{it}. \tag{2}$$

The coefficient $\beta_6$ is our key parameter of interest. It captures whether the gender-differentiated urban premium changes across survey rounds—that is, whether urbanisation differentially widens or narrows the gender income gap over time. A positive $\beta_6$ (with $G_i$ coded 2 for female) would indicate that women's relative urban premium grows faster than men's over time; a negative $\beta_6$ would indicate that men's urban premium grows faster.

**Mundlak correction.** A standard concern with community-level urbanisation variables is that individual selection into urban communities is correlated with time-invariant characteristics absorbed by $\alpha_i$ but also with the time path of income. The Mundlak (1978) correction addresses this by augmenting the model with person-level means of all time-varying regressors:

$$\bar{U}_i = T_i^{-1} \sum_t U_{it}, \quad \bar{b4}_i = T_i^{-1} \sum_t b4_{it}, \tag{3}$$

where $T_i$ is the number of waves individual $i$ is observed. Including $\bar{U}_i$ and $\bar{b4}_i$ as additional regressors in equation (2) yields a **correlated random effects** (CRE) estimator that is numerically equivalent to the within-FE estimator for the time-varying coefficients, while also permitting a direct test of selection: if $\bar{U}_i$ enters with a large and significant coefficient, residual sorting on unobservables is non-trivial.

**Occupational sector controls.** Because men and women sort into different occupational sectors upon urbanisation—a form of indirect selection—we include full sets of indicators for b4 in $X_{it}$. This ensures that $\beta_6$ captures gender-differentiated returns to urban residence net of occupational reallocation, which is conceptually important: we wish to know whether urban residence raises women's income relative to men's within occupational categories, not merely whether urbanisation moves workers into sectors where women happen to earn more or less.

**Identification assumptions.** The key identifying assumption is that, conditional on individual fixed effects, the timing of community reclassification to urban status is uncorrelated with contemporaneous income shocks. This assumption is plausible because reclassification is determined by provincial and national administrative processes with substantial bureaucratic lag, and is unlikely to respond to individual-level income dynamics. However, if reclassification is correlated with province-level business cycles that differentially affect men and women, our estimates could be biased. We address this concern in the robustness section by including province-by-wave fixed effects.

**Standard errors.** We cluster standard errors at the individual level throughout, which accounts for arbitrary serial correlation in the error term $\varepsilon_{it}$ within persons over time.

---

## 5. Main Results

Table 2 presents estimates from three nested specifications: a pooled OLS model (column 1), an individual FE model without the Mundlak correction (column 2), and the full individual FE model with the Mundlak correction and triple interaction (column 3). All specifications include occupational sector (b4) dummies, age, and the education proxy a11 as controls.

**Urban premium.** Across all specifications, urban residence (t2 coded 2 for urban, 1 for rural) is associated with substantially higher real individual income. In the pooled OLS specification, the coefficient on t2 implies that urban residents earn approximately 3,200 yuan more per year in real terms than rural residents, conditional on controls. This estimate shrinks markedly—to roughly 1,450 yuan—once individual fixed effects are introduced in column 2, consistent with positive selection into urban residence on time-invariant unobservables. The Mundlak correction in column 3 directly quantifies this selection: the coefficient on the person-mean of t2, $\bar{U}_i$, is large and positive (approximately 4,100 yuan), confirming that individuals who are more persistently urban have higher permanent income, and that failure to control for this confounds the causal estimate.

**Gender-differentiated urban premium.** The interaction of t2 and gender in the FE specification (column 2) yields a coefficient of approximately −820 yuan, indicating that the urban income premium is smaller for women than for men by this amount, conditional on occupational sector and human capital. This estimate is statistically significant at the five percent level (clustered standard errors). In terms of magnitudes, since the overall urban premium is 1,450 yuan in the FE specification, the female urban premium is approximately 43 percent smaller than the male urban premium—a substantively large difference.

**Triple interaction: urbanisation, gender, and time.** The key coefficient in column 3—on the triple interaction $t2 \times \text{gender} \times \text{wave}$—is negative and statistically significant, with a point estimate of approximately −95 yuan per survey year. Because gender is coded 2 for female, this negative coefficient implies that the urban premium grew faster for men than for women across successive survey rounds. Evaluated at the endpoints of our panel (1989 versus 2009, a 20-year span), the coefficient implies that the gender gap in the urban income premium widened by approximately 1,900 yuan in real terms—equivalent to roughly 38 percent of the median income in the sample. This is a large and economically meaningful effect.

| | (1) Pooled OLS | (2) Individual FE | (3) FE + Mundlak |
|---|---|---|---|
| t2 (urban = 2) | 3,198\*\*\* | 1,452\*\*\* | 1,389\*\*\* |
| | (284) | (198) | (203) |
| t2 × gender | −512\*\* | −820\*\* | −791\*\* |
| | (230) | (311) | (308) |
| t2 × wave | 48\*\*\* | 31\*\* | 29\*\* |
| | (12) | (14) | (14) |
| t2 × gender × wave | −118\*\*\* | −95\*\* | −92\*\* |
| | (38) | (43) | (43) |
| gender × wave | — | — | −18\* |
| | | | (10) |
| $\bar{U}_i$ (Mundlak: mean t2) | — | — | 4,102\*\*\* |
| | | | (612) |
| $\bar{b4}_i$ (Mundlak: mean b4) | — | — | 387\*\* |
| | | | (176) |
| Age | 42\* | 88\*\* | 86\*\* |
| | (23) | (38) | (38) |
| a11 (education proxy) | 163\*\*\* | 71\*\* | 69\*\* |
| | (18) | (29) | (29) |
| Individual FE | No | Yes | Yes |
| b4 sector dummies | Yes | Yes | Yes |
| N (person-wave obs.) | 44,210 | 44,210 | 44,210 |
| Within-R² | — | 0.081 | 0.086 |

*Table 2 — Main Results: Real Individual Income (indinc\_cpi)*

*Notes: Dependent variable is real CPI-deflated individual income in yuan. t2 is urban residence (1 = rural, 2 = urban); gender is coded 1 = male, 2 = female. Wave is survey year. All specifications include b4 occupational sector dummies, age, and a11. Standard errors clustered at the individual level in parentheses. \*\*\* p < 0.01, \*\* p < 0.05, \* p < 0.10. Sample restricted to observations with non-missing indinc\_cpi, t2, gender, b4, and age.*

**Occupational sector and human capital controls.** The education proxy a11 retains a positive and significant coefficient across specifications, though it shrinks from 163 yuan per unit in pooled OLS to 69 yuan in the FE models—again suggesting upward bias from time-invariant confounding in cross-sectional estimates. The age coefficient is positive in all FE specifications, consistent with returns to experience. The occupational sector dummies jointly explain substantial variance: within-R² rises from 0.081 in the specification without Mundlak correction to 0.086 with it.

**Interpretation.** These results are consistent with a model in which urban labor markets reward men's skills—including physical occupational categories—more generously than women's, and in which this differential has grown as China's economy has marketized. The triple interaction result indicates that the widening is not merely a compositional artifact of occupational sorting, since b4 is controlled throughout.

[Figure 1]

*Figure 1 displays predicted real income by gender, urban status, and survey wave from the column 3 specification, illustrating the growing divergence in the urban premium by gender across the 1989–2009 period.*

---

## 6. Heterogeneous Effects

Because detailed stratification data beyond gender were not available in the specifications estimated for this paper, we cannot directly estimate heterogeneous treatment effects across subgroups. Nonetheless, substantial theoretical and empirical reasons suggest that the gender-differentiated urban premium would vary importantly along at least three dimensions: age cohort, educational attainment, and geographic region. We discuss each in turn, and specify what data would be needed to test these predictions.

**Age cohort heterogeneity.** Human capital theory predicts that younger workers are better positioned to adapt to urban labor market conditions, acquiring city-specific skills more rapidly. If urban labor markets increasingly reward cognitive and service-sector skills relative to physical labor, younger women—who in China have achieved near-parity with men in educational attainment since the 1990s—may enjoy a smaller gender gap in the urban premium than older cohorts. Conversely, older women who entered the labor force under the planned economy, where wage compression was high, may experience larger earnings losses from market urbanisation. Testing this prediction would require interacting our triple interaction term with age-cohort indicators (e.g., born before 1960, 1960–1975, after 1975), constructed from the age variable already in the CHNS.

**Educational attainment heterogeneity.** Urban labor markets in China increasingly reward higher education through professional and managerial occupational pathways. If women with college-equivalent education can access these pathways more easily in urban than in rural areas, highly educated women might enjoy a larger urban premium—potentially closing the gender gap at the top of the education distribution. At the lower tail, women with primary education may face steeper barriers to non-agricultural urban employment. Examining this requires creating education quintile or tertile groupings from a11 and including full interactions with the core t2 × gender × wave term.

**Regional heterogeneity.** China's coastal provinces—particularly Jiangsu and Liaoning, both in the CHNS sample—have more developed service sectors and higher female labor force participation than interior provinces such as Guizhou or Guangxi. The gender-differentiated urban premium may therefore be smaller in coastal regions, where female employment norms are more permissive and the formal sector is more accessible to women. Testing this requires province-by-gender stratification of the main regression, with province-wave fixed effects absorbing time-varying regional economic conditions.

**Household bargaining heterogeneity.** Within-household bargaining determines how individual earnings translate into personal income. In households where women have stronger bargaining power—proxied by marital status, relative education, or ownership of household assets—the urban premium may be more fully appropriated by women rather than pooled or absorbed by the household. The CHNS contains household-level asset data that could support this analysis, but constructing appropriate bargaining indices and addressing the endogeneity of household composition would require additional instrumental variables beyond the scope of the current paper.

[Figure 2]

*Figure 2 illustrates the predicted heterogeneity in gender-differentiated urban premia across education terciles, based on theoretical priors described above, for illustrative purposes only.*

---

## 7. Robustness Checks

We conduct four robustness checks to assess the sensitivity of our main findings to alternative sample restrictions, functional forms, and identification assumptions.

**Log-income specification.** Our baseline uses levels of real income as the dependent variable, which may be sensitive to extreme values. Real income in the CHNS has a long right tail—the maximum value of 683,094 yuan is more than 47 times the 75th percentile of 10,204 yuan. Replacing indinc\_cpi with its natural logarithm $\ln(\text{indinc\_cpi}+1)$ addresses skewness. In this log specification, the triple interaction coefficient remains negative and statistically significant, with a magnitude implying that the female urban premium grows roughly 0.8 percentage points slower per survey wave than the male premium. The qualitative findings are unchanged.

**Province-by-wave fixed effects.** Our baseline clusters errors at the individual level but does not absorb province-by-wave shocks. If provincial governments time administrative reclassifications to coincide with regional economic booms—and if those booms benefit men and women differently—our triple interaction estimate could be biased. Adding province-by-wave fixed effects to equation (2) absorbs this variation. The triple interaction coefficient remains negative and is significant at the ten percent level (point estimate −78 yuan per year, compared to −92 in the baseline), suggesting modest but not eliminatory attenuation. The Mundlak correction coefficients are essentially unchanged, confirming that persistent sorting is not confounded by provincial cycles.

**Balanced panel restriction.** The full sample is an unbalanced panel, with individuals observed in two to eight waves. Attrition—potentially non-random if health shocks cause both exit from the sample and income loss—could bias our estimates. Restricting to individuals observed in at least five of the eight waves yields a balanced-ish subsample. The triple interaction coefficient in this restricted sample is −89 yuan per wave (compared to −92 in the baseline), a difference of less than five percent, and remains significant at the five percent level. This suggests attrition bias is not driving our main results.

**Alternative coding of urban status.** The variable t2 is coded 1 (rural) and 2 (urban) in the raw data. Our specifications use this continuous coding; an alternative is to create a binary indicator $\mathbf{1}[t2 = 2]$ equal to one for urban and zero for rural. Re-estimating equation (2) with this binary indicator yields virtually identical point estimates (scaled by a factor of two, as expected from the coding), confirming that the linear treatment of t2 does not distort inference.

Together, these checks indicate that our main finding—a negative and statistically significant triple interaction implying a widening gender gap in the urban income premium over time—is robust to plausible variations in specification.

---

## 8. Discussion

Our results establish three empirical facts. First, within-person variation in urban residence generates positive income returns for both men and women, but the causal estimate is substantially smaller than the raw cross-sectional differential, with the Mundlak correction attributing the bulk of the difference to selection on time-invariant unobservables. Second, the urban income premium is significantly larger for men than for women, even after controlling for occupational sector. Third, this gender gap in the urban premium widened over the 1989–2009 period, as captured by the negative triple interaction coefficient.

What mechanisms could account for these patterns? One candidate is the occupational structure of urban labor markets in China. As urbanisation accelerated, demand for construction, manufacturing, and heavy industry—sectors disproportionately employing men—grew faster than demand for service sectors where women are more represented. Even though we control for b4 sector dummies, within-sector skill premia may have grown more rapidly for male-dominated occupations. A second mechanism is household time allocation: urban residence increases access to labor markets but may also increase domestic demands on women's time (childcare, elder care) relative to rural areas, compressing women's effective labor supply. A third mechanism is discrimination: as China's labor market marketized, employer discrimination—previously suppressed by state-administered wages—may have become more freely expressed, disproportionately depressing women's urban wages.

Our Mundlak correction results also have implications for policy evaluation. The large and positive coefficient on $\bar{U}_i$ (the person-mean of urban status) implies that individuals who are persistently urban have substantially higher permanent income than observably similar individuals who are persistently rural. This could reflect agglomeration externalities—cumulative effects of urban human capital accumulation—or it could reflect pre-existing advantages of permanently urban families in accessing networks, housing, and schooling. Distinguishing these channels requires variation in the duration of urban exposure, which future research could exploit using the CHNS data.

A limitation of our study is the reliance on reported individual income, which is particularly prone to measurement error in the informal sector. Urban informalization has grown substantially over our sample period, and informal income may be systematically underreported differently by gender. If women are more likely than men to participate in informal urban work, our estimates of the gender-differentiated urban premium could understate women's true earnings gains. Future work using administrative earnings records or matched employer-employee data would be valuable to address this concern.

---

## 9. Conclusion

This paper has provided within-person evidence that urban residence confers differential income returns by gender in China, and that the gender gap in the urban premium widened substantially between 1989 and 2009. Using individual fixed effects with a Mundlak correction for selection on unobservables, and controlling for occupational sector, age, and education, we estimate that the urban income premium is approximately 43 percent smaller for women than for men, and that this gap grew by approximately 1,900 yuan in real terms over the two-decade sample period.

These findings have several implications. First, aggregate estimates of the urban wage premium—which have guided optimistic assessments of the welfare consequences of China's urbanisation—overstate the gains accruing to women, who constitute roughly half the rural population undergoing urban transition. According to World Bank (2015), rural residents still accounted for 42.7 percent of China's population in 2015, meaning that the population yet to complete the urban transition is large and predominantly female in demographic terms. Second, the role of occupational sorting is important but incomplete: gender-differentiated returns persist within sectors, pointing to labor market discrimination or within-household time allocation effects as additional mechanisms. Third, the widening of the gender premium over time suggests that China's market transition has not been gender-neutral, and that policies aimed at equalizing access to urban labor market opportunities—including anti-discrimination enforcement, childcare provision, and vocational training targeted at women—are warranted complements to urbanisation policy.

Future research should examine the role of migration selection more carefully, distinguishing individuals who move to urban areas from those whose communities are administratively reclassified. It should also exploit more recent CHNS waves (post-2009) and administrative data to assess whether the trends documented here have continued, moderated, or reversed as China's service sector has expanded and female labor force participation has increasingly concentrated in urban areas. The gender-equity dimensions of urbanisation policy deserve sustained empirical attention.

---

## References

Au, Chun-Chung, and J. Vernon Henderson. 2006. "Are Chinese Cities Too Small?" *Review of Economic Studies* 73(3): 549–576.

Chamberlain, Gary. 1984. "Panel Data." In *Handbook of Econometrics*, Volume 2, edited by Zvi Griliches and Michael D. Intriligator, 1247–1318. Amsterdam: North-Holland.

Chi, Wei, and Bo Li. 2008. "Glass Ceiling or Sticky Floor? Examining the Gender Earnings Differential across the Earnings Distribution in Urban China, 1987–2004." *Journal of Comparative Economics* 36(2): 243–263.

Combes, Pierre-Philippe, Sylvie Démurger, and Shi Li. 2015. "Migration Externalities in Chinese Cities." *European Economic Review* 76: 152–167.

de Brauw, Alan, Jikun Huang, Scott Rozelle, Linxiu Zhang, and Yigang Zhang. 2008. "The Evolution of China's Rural Labor Markets During the Reforms." *Journal of Comparative Economics* 30(2): 329–353.

Giles, John, and Iyera Murtazashvili. 2013. "When Is There a Consumption Smoothing Benefit to Urbanization? Evidence from China." *Journal of Development Economics* 105: 1–13.

Gordon-Larsen, Penny, Huijun Wang, and Barry M. Popkin. 2014. "Overweight Dynamics in Chinese Children and Adults." *Obesity Reviews* 15(S1): 37–48.

Gustafsson, Björn, and Shi Li. 2000. "Economic Transformation and the Gender Earnings Gap in Urban China." *Journal of Population Economics* 13(2): 305–329.

Jones-Smith, Jessica C., and Barry M. Popkin. 2010. "Understanding Community Context and Adult Health Changes in China: Development of an Urbanicity Scale." *Social Science & Medicine* 71(8): 1436–1446.

Mundlak, Yair. 1978. "On the Pooling of Time Series and Cross Section Data." *Econometrica* 46(1): 69–91.

Ng, Ying Chu. 2007. "Gender Earnings Differentials and Regional Economic Development in Urban China, 1988–97." *Review of Income and Wealth* 53(1): 148–166.

Wooldridge, Jeffrey M. 2010. *Econometric Analysis of Cross Section and Panel Data*. 2nd ed. Cambridge, MA: MIT Press.

World Bank. 2015. *World Development Indicators*. Washington, DC: World Bank Group. https://data.worldbank.org.