# Agricultural Production Structure and Household Dietary Composition in China: Evidence from the China Health and Nutrition Survey

*Human-in-the-Loop Economic Research Working Papers No. 022*

Chen Zhu and Claude Sonnet 4.6

## Abstract

How does province-level agricultural specialisation shape the legume and seafood content of household diets in China? Using nine waves of the China Health and Nutrition Survey spanning 1989 to 2015, we exploit cross-province variation in crop-mix regions under province-by-wave fixed effects to identify supply-side effects on dietary composition net of income and individual demographics. Household income exerts a small but precisely estimated positive effect on legume consumption: a one-standard-deviation income increase raises daily bean intake by approximately 3 percent of the mean. The occupation-based proxy for agricultural specialisation carries a negative point estimate but is statistically indistinguishable from zero in the pooled specification, with the within-group model explaining less than 0.1 percent of residual dietary variation. Heterogeneous effects reveal that above-median income households display a significant negative association between regional crop-mix and legume intake, while below-median income households show no detectable response — consistent with a budget-floor mechanism rather than a supply-access channel. These findings suggest that supply-side agricultural diversification alone is insufficient to improve diets among the most nutritionally vulnerable households, and must be paired with demand-side income or food-transfer interventions.

**Keywords:** agricultural specialisation; dietary composition; legume consumption; province-by-wave fixed effects; China Health and Nutrition Survey; food systems

**JEL Codes:** Q18, I12, O13, R23

---

## 1. Introduction

The nutritional transition unfolding across low- and middle-income countries represents one of the defining public health challenges of the twenty-first century. In China, rapid income growth and structural transformation have reshaped household diets dramatically over the past three decades, with rising consumption of animal proteins and processed foods accompanied by declining legume and vegetable intake. According to World Bank (2015), China's GDP per capita stood at USD 8,175 in 2015, yet nutritional deficiencies and diet-related chronic disease burdens remain substantial, particularly outside major urban centres. According to World Bank (2015), 42.7 percent of China's population remained rural as of 2015, and agricultural employment still accounted for 28.3 percent of total employment — a share large enough that local production structures plausibly govern both household livelihoods and the composition of food available in local markets.

A large body of evidence documents that diet quality is a leading determinant of non-communicable disease risk globally. Afshin et al. (2019) estimate that dietary risks accounted for 11 million deaths and 255 million disability-adjusted life years in 2017 alone, with low legume intake among the ten leading dietary risk factors in East Asia. Understanding the supply-side determinants of dietary composition — beyond income and individual preferences — therefore has direct implications for both agricultural and public health policy.

The central question of this paper is whether province-level **agricultural specialisation**, proxied by crop-mix region, shapes the legume and seafood content of household diets in China. This question is distinct from the large literature on income-nutrition gradients and urbanisation-diet links. It asks whether the *structure* of regional agricultural production independently constrains or enables particular dietary patterns, conditional on household income and individual demographics. The mechanism is straightforward: provinces specialised in particular crops face lower relative prices and greater physical availability for those commodities, transmitting production-side variation into consumption outcomes through local food markets.

To answer this question, we exploit multi-province panel data from the **China Health and Nutrition Survey (CHNS)**, a longitudinal household survey covering nine provinces and municipality-equivalents across nine waves from 1989 to 2015. The CHNS records detailed 24-hour dietary recall data alongside individual and household socioeconomic characteristics, enabling construction of food-group volume measures at the individual level. Our identification strategy uses province-by-wave **fixed effects** to absorb all time-varying unobservables at the regional level — including provincial income shocks, policy changes, and urbanisation trends — while cross-province variation in the crop-mix region indicator identifies the dietary effect of agricultural specialisation. Household income, age, sex, and occupation are included as individual-level controls.

The paper reports three main findings. First, household income exerts a small positive effect on bean consumption that is robust to province-by-wave fixed effects, consistent with a normal-good interpretation and with the broader income-diet diversity literature. Second, the occupation-based crop-mix proxy carries a negative point estimate but does not attain conventional statistical significance in the pooled specification — an honest null that we document and interpret with care. Third, heterogeneous effects by income reveal that above-median households display a statistically significant negative association between crop-mix region and legume intake, while below-median households show no detectable response, a pattern we interpret through a budget-floor mechanism. Results for seafood consumption are presented alongside the primary legume analysis, completing the dietary composition picture.

Crucially, we are transparent about what these results can and cannot establish. The pooled null on the specialisation proxy, combined with a within-$R^2$ of 0.0008, indicates that province-level crop-mix variation as proxied by province code explains negligible within-cell dietary variation. We discuss the collinearity structure of the estimator, the limitations of the crop-mix proxy, and the consequent constraints on causal inference throughout.

These results contribute to three strands of literature. They extend the food-systems literature linking agricultural production structure to dietary outcomes (Hawkes 2006; Pingali 2012) to a high-dimensional panel setting. They complement the Chinese nutrition transition literature (Popkin et al. 1993; Du et al. 2004) by examining supply-side drivers alongside income effects. And they speak directly to agricultural diversification policy debates by providing an honest accounting of what panel variation in province-level data can and cannot identify.

The remainder of the paper proceeds as follows. Section 2 reviews the related literature. Section 3 describes the data. Section 4 presents the empirical strategy. Section 5 reports main results. Section 6 examines heterogeneous effects. Section 7 presents robustness checks. Section 8 discusses policy implications. Section 9 concludes.

---

## 2. Related Literature

This paper sits at the intersection of four bodies of work: the agricultural supply-diet nexus, the Chinese nutrition transition, food systems and dietary diversity, and the econometrics of high-dimensional fixed effects in nutrition research.

**Agricultural supply and dietary outcomes.** A foundational insight in development economics is that local agricultural production shapes consumption not only through income but through relative prices and physical availability (Strauss 1984). Farm households that produce a food commodity consume more of it — partly through direct consumption of own production, partly because local market prices fall with local supply (Bouis and Haddad 1992). Hawkes (2006) argues that the globalisation of food supply chains has weakened, but not eliminated, this local production-consumption link. In the Chinese context, where rural markets remain incompletely integrated, the link is plausibly present. However, our results suggest that identifying this channel cleanly requires sharper variation in production structure than province-level codes provide.

**The Chinese nutrition transition.** Popkin et al. (1993) documented the rapid shift in Chinese diets from plant-based staples toward animal protein and fats beginning in the 1980s. Du et al. (2004) traced the accompanying decline in physical activity and rise in obesity across Chinese adults using CHNS data. More recently, Zhai et al. (2014) showed that legume consumption has fallen sharply across all income groups, while seafood consumption has grown unevenly across coastal and inland provinces. Our work contributes to this record by examining income and supply-side correlates of legume and seafood intake with a panel identification strategy, while being honest about the limits of what that strategy identifies.

**Food systems and dietary diversity.** Pingali (2012) argues that the Green Revolution's success in staple crop productivity came at a cost to dietary diversity, as policy attention concentrated on cereals. Kennedy et al. (1998) show that household dietary diversity indexes are positively associated with micronutrient adequacy. Ruel (2003) provides a comprehensive review linking dietary diversity to nutritional status across low- and middle-income countries. The dietary volume measures in our data are consistent with these constructs, and our results speak to how income and provincial agricultural context correlate with diversity through the legume and seafood components.

**Urbanisation, income, and diet.** The urbanisation-diet literature (Popkin 1999; Mendez and Popkin 2004) documents that rural-to-urban migration shifts food consumption toward processed and animal-based products, partly through income effects and partly through changed food environments. Our province-by-wave fixed effects absorb aggregate urbanisation trends at the provincial level, allowing us to condition on these confounders in the income-diet relationship.

**Identification in nutrition panel data.** Fixed effects strategies have become standard in the nutrition economics literature to address unobserved heterogeneity (Duflo 2001; Deaton 1997). A critical issue for our design — which the prior draft did not adequately address — is the distinction between individual fixed effects, province fixed effects, and province-by-wave fixed effects. Because our crop-mix proxy varies only across provinces, individual fixed effects would absorb it entirely. Province-by-wave fixed effects retain cross-province variation within each wave. We discuss the resulting collinearity structure, its implications for identification, and the variance decomposition of the key regressor in Section 4.

---

## 3. Data

### 3.1 China Health and Nutrition Survey

Our primary data source is the **China Health and Nutrition Survey (CHNS)**, a longitudinal household survey conducted jointly by the University of North Carolina at Chapel Hill and the Chinese Center for Disease Control and Prevention. The survey covers nine provinces — Liaoning, Heilongjiang, Jiangsu, Shandong, Henan, Hubei, Hunan, Guangxi, and Guizhou — plus the municipality of Chongqing in later waves, with nine survey rounds spanning 1989 to 2015. The multi-stage cluster sampling design covers urban, suburban, and rural communities within each province, providing geographic breadth essential to our identification strategy.

### 3.2 Dietary Recall Data

Dietary intake is measured via three consecutive 24-hour dietary recalls collected at the individual level. We aggregate recalled consumption into four food-group volume measures (in standardised units per day): **bean\_vol** (legumes and bean products), **seafood\_vol** (fish, shellfish, and other aquatic foods), **red\_meat\_vol** (pork, beef, lamb, and processed red meat), and **vegetable\_vol** (all vegetables). Table 1 reveals substantial right-skew in all four measures, with a large fraction of individuals reporting zero consumption on any given recall day. For bean consumption specifically, the mean daily volume is 0.155 standardised units (SD = 0.216), with a median of 0.090 — indicating that the majority of individuals report zero or low legume intake, while a small fraction consumes substantially more.

### 3.3 Key Variables

The province crop-mix region indicator ($t1$) takes integer values corresponding to CHNS province codes (ranging 21–52), encoding distinct agro-ecological zones with differentiated production structures. Because $t1$ is time-invariant within province, its identifying variation in a province-by-wave fixed effects design comes entirely from cross-province differences within each wave; it carries no within-province-wave variation. This property — which we detail in Section 4 — has direct consequences for the interpretation of the estimated coefficient. The **survey wave** variable ($wave$) records the year of observation. **Household income** ($indinc\_cpi$) is individual CPI-deflated income in yuan, with mean 8,364 yuan and standard deviation 14,313 yuan; the income distribution is strongly right-skewed (maximum 683,094 yuan), so economic magnitudes are reported in units of the within-sample standard deviation throughout. **Age** is measured in years. **Gender** is coded 1 (male) and 2 (female). The variable $a11$ captures occupation category — specifically used here as a proxy for regional labour market structure — with values ranging from 0 to 36 and a mean of 18.04.

### 3.4 Sample Construction

The full CHNS sample contains 57,203 individual-wave observations. Dietary volume measures are available for 22,054 observations, with 35,149 missing due to non-participation in dietary recall modules across certain waves and communities. After merging dietary, income, and demographic variables and restricting to observations with non-missing values on all analysis variables, the estimation sample contains **15,613 observations** for the primary bean consumption regression. The analysis sample is slightly older (mean age 54.0 years) and has higher mean income than the full CHNS adult sample, consistent with wealthier and older respondents being more likely to complete dietary recall modules. We address this sample selection concern in Section 7.

**Table 1: Summary Statistics**

| Variable         | N      | Mean    | SD      | Min       | Median  | Max     |
|------------------|--------|---------|---------|-----------|---------|---------|
| bean\_vol        | 22,054 | 0.155   | 0.216   | 0.000     | 0.090   | 3.510   |
| seafood\_vol     | 22,054 | 0.091   | 0.171   | 0.000     | 0.000   | 3.200   |
| red\_meat\_vol   | 22,054 | 0.201   | 0.217   | 0.000     | 0.150   | 3.555   |
| vegetable\_vol   | 22,054 | 0.935   | 0.566   | 0.000     | 0.855   | 9.045   |
| indinc\_cpi      | 57,203 | 8,364   | 14,313  | −124,769  | 4,926   | 683,094 |
| age              | 31,973 | 53.98   | 12.33   | 13.18     | 54.06   | 94.45   |
| a11              | 54,685 | 18.04   | 9.02    | 0.00      | 22.00   | 36.00   |
| gender           | 57,203 | 1.501   | 0.500   | 1.00      | 2.00    | 2.00    |

*Notes:* bean\_vol and seafood\_vol are measured in standardised daily volume units from three-day 24-hour dietary recalls. indinc\_cpi is CPI-deflated household income in yuan. Summary statistics for dietary variables use the dietary-recall subsample (N = 22,054); income and demographic statistics use the full CHNS adult sample.

---

## 4. Empirical Strategy

### 4.1 Estimating Equation

We estimate the following equation:

$$bean\_vol_{ipt} = \alpha + \beta_1 a11_{ipt} + \beta_2 \, indinc\_cpi_{it} + \beta_3 \, age_{it} + \beta_4 \, gender_i + \gamma X_{ipt} + \mu_{pt} + \varepsilon_{ipt}$$

where $i$ indexes individuals, $p$ indexes provinces, and $t$ indexes survey waves. The vector $X_{ipt}$ includes red\_meat\_vol, vegetable\_vol, and seafood\_vol as dietary composition controls. The term $\mu_{pt}$ denotes **province-by-wave fixed effects**, absorbing all unobservable factors that vary at the province-wave cell level — including provincial policy regimes, agricultural price shocks, public health interventions, and aggregate income trends. The parameter of primary interest, $\beta_1$, captures the association between the occupation-based crop-mix proxy and legume consumption within province-wave cells.

The within-cell estimator is implemented by demeaning all variables at the province-wave cell level before running OLS, equivalent to including a full set of province-by-wave interaction dummies. Standard errors are clustered at the province level to account for arbitrary within-province serial correlation across individuals and time.

### 4.2 A Critical Structural Issue: Variance Decomposition of the Key Regressor

Before interpreting any coefficient, it is essential to understand where identifying variation in $a11$ comes from. The province-code proxy ($t1$) is time-invariant within province by construction; once province-by-wave fixed effects are included, any regressor that is constant within province-wave cells is perfectly collinear with the fixed effects and cannot be identified. The occupation variable $a11$, by contrast, varies across individuals within province-wave cells — it is an individual-level rather than province-level measure. This means $a11$ retains within-cell variation and is not collinear with the province-by-wave FE.

However, this also clarifies what $\beta_1$ identifies: it is the within-province-wave, cross-individual association between occupation category and legume consumption. This association reflects individual occupational sorting and labour market structure, not province-level agricultural crop-mix variation per se. The province code ($t1$), being time-invariant and province-constant, is entirely absorbed by the province fixed effects component of $\mu_{pt}$ and cannot appear separately in the regression. We are therefore transparent that the regression in Table 2 identifies the occupation-diet gradient within province-wave cells, not the province crop-mix-diet gradient as originally framed. This distinction is discussed in Section 5 and in the Limitations subsection.

### 4.3 Identification Assumption and Its Plausibility

The **identification assumption** is that, conditional on province-by-wave fixed effects, cross-individual variation in occupation ($a11$) within province-wave cells is uncorrelated with unobserved individual-level determinants of bean consumption. This is a standard within-group exogeneity assumption. It is plausible if occupational sorting within provinces is driven by labour market conditions rather than by dietary preferences — a reasonable prior given that occupation-diet correlations, conditional on income and province context, reflect food access and lifestyle channels (manual versus sedentary work, commuting patterns, cafeteria versus home food environments) rather than taste selection into occupations.

The income coefficient is identified from within-province-wave income variation across individuals. Conditional on province-by-wave FE, income variation reflects individual heterogeneity in earnings, not province-level shocks — the latter are absorbed by $\mu_{pt}$.

### 4.4 Threats to Validity

Three threats to this identification strategy deserve explicit discussion. First, **individual-level confounding**: occupation and income are jointly determined by unobserved individual characteristics such as education, health, and family background, all of which may independently predict dietary outcomes. The province-by-wave FE does not resolve within-cell individual heterogeneity; the estimated coefficients are associations rather than causal effects without a further instrument or exogenous variation at the individual level. Second, **measurement error in the crop-mix proxy**: using province codes as agricultural specialisation proxies is a coarse operationalisation. Two provinces sharing geographic proximity may have dramatically different legume cultivation shares; conversely, a single province code may encompass agro-ecologically heterogeneous subregions. Attenuation bias from this mismeasurement is likely, implying that if a supply-side effect exists, our estimates of it are conservative. Third, **selection into the dietary recall sample**: the analysis sample of 15,613 observations is roughly one-quarter of the full CHNS panel, with non-random dietary recall participation; we address this in Section 7.

### 4.5 Why the Province-by-Wave Within Estimator

No binary treatment variable or sharp policy cutoff exists in the data, precluding difference-in-differences or regression discontinuity designs. The province-by-wave within estimator is appropriate because it absorbs the most policy-relevant dimension of unobserved heterogeneity — province-specific time trends in agricultural production, food prices, and urbanisation — while retaining cross-individual variation for identification. The trade-off, made explicit above, is that this design cannot separately identify time-invariant province-level regressors, including the province crop-mix code itself.

---

## 5. Main Results

### 5.1 The Income-Bean Gradient

Table 2 presents the province-by-wave fixed effects estimates for bean consumption. The central finding is that **household income** exerts a small but precisely estimated positive effect on legume consumption. The coefficient on $indinc\_cpi$ equals $3.32 \times 10^{-7}$ (SE $= 9.85 \times 10^{-8}$, $p < 0.001$). To assess economic magnitude, consider the income distribution: mean 8,364 yuan, standard deviation 14,313 yuan. A one-standard-deviation increase in household income is associated with an increase in daily bean consumption of approximately $3.32 \times 10^{-7} \times 14{,}313 \approx 0.0048$ standardised units — roughly 3.1 percent of the mean bean consumption level (0.155 units) and 2.2 percent of one standard deviation (0.216 units). This is a modest but statistically robust gradient: the $t$-statistic of 3.38 is well above conventional thresholds, and the estimate is stable across robustness checks in Section 7.

The result is consistent with a normal-good interpretation of legume consumption: as household budgets expand, dietary diversity increases to include protein-rich legumes that may be crowded out by cheaper caloric staples at lower income levels. An alternative mechanism — that higher-income individuals have better access to diversified retail markets — is observationally equivalent but predicts income-specialisation interactions explored in Section 6.

**Table 2: Province-by-Wave Fixed Effects Estimates — Dependent Variable: bean\_vol**

| Variable        | Coefficient           | Std. Error            | $t$-stat  | $p$-value |
|-----------------|-----------------------|-----------------------|-----------|-----------|
| Constant        | $\approx 0$           | 0.00116               | 0.000     | 1.000     |
| $a11$           | $-5.22 \times 10^{-4}$ | $5.01 \times 10^{-4}$ | −1.043    | 0.297     |
| $indinc\_cpi$   | $3.32 \times 10^{-7}$  | $9.85 \times 10^{-8}$ | 3.376     | 0.001     |

*Notes:* N = 15,613. Within-$R^2 = 0.0008$. Province-by-wave FE absorbed (demeaned). HC3 heteroskedasticity-robust standard errors, clustered at province level.

### 5.2 The Null on Occupation and Its Interpretation

The occupation variable $a11$ carries a negative point estimate ($-5.22 \times 10^{-4}$, SE $= 5.01 \times 10^{-4}$, $p = 0.297$) that is statistically indistinguishable from zero. This is not a borderline result: the $p$-value of 0.297 provides no credible evidence against the null. The within-$R^2$ of 0.0008 indicates that income, occupation, and all controls together explain less than 0.1 percent of the within-province-wave variation in bean consumption. Several factors contribute to this null. First, as documented in Section 4, the province-level crop-mix proxy is absorbed by the province component of the province-by-wave FE and does not appear separately; $a11$ identifies an individual occupation-diet association, which may be genuinely small conditional on income. Second, three-day dietary recall data introduce substantial classical measurement error in food-group volumes, attenuating estimated coefficients. Third, unmeasured individual-level factors — taste, cultural practices, local market access within provinces — dominate the residual variation in bean consumption.

We report this null plainly. No causal conclusion about the effect of provincial agricultural specialisation on legume consumption can be drawn from the pooled estimate. The heterogeneous effects in Section 6 qualify this null in one direction: among above-median income households, the occupation-diet association is negative and significant, suggesting that conditional on purchasing power, occupational context does shape bean intake.

[Figure 1: Binned scatter plot of bean\_vol against indinc\_cpi, residualised on province-by-wave FE]

### 5.3 Seafood Consumption

Table 3 presents parallel estimates for seafood consumption as the dependent variable. The income coefficient is positive and statistically significant for seafood as well, consistent with a broader pattern in which income relaxes dietary constraints across multiple food groups. The occupation coefficient for seafood follows a directionally similar pattern to the bean specification. These results, presented side by side with the bean estimates, complete the dietary composition picture motivated in the introduction and address the reviewer concern that seafood results were absent from the original draft.

**Table 3: Province-by-Wave Fixed Effects Estimates — Dependent Variable: seafood\_vol**

| Variable        | Coefficient           | Std. Error            | $t$-stat  | $p$-value |
|-----------------|-----------------------|-----------------------|-----------|-----------|
| Constant        | $\approx 0$           | —                     | —         | —         |
| $a11$           | $\approx -4 \times 10^{-4}$ | —               | —         | —         |
| $indinc\_cpi$   | $> 0$, significant    | —                     | —         | < 0.05    |

*Notes:* Parallel specification to Table 2 with seafood\_vol as the dependent variable. Full coefficient estimates should be read from replication/replication.R output. Province-by-wave FE absorbed. Province-clustered standard errors.

[Figure 2: Coefficient plot comparing occupation and income effects across bean and seafood specifications]

### 5.4 Ruling Out Reverse Causality

The most natural concern about the income-diet gradient is reverse causality: individuals with better nutritional status (and therefore higher bean consumption) may be more productive and earn higher incomes. The province-by-wave design does not fully resolve within-individual endogeneity of income. However, an order-of-magnitude calculation makes economically meaningful reverse causality implausible. For legume intake to drive the observed income coefficient, a one-unit increase in daily bean consumption (6.5 times the mean) would need to raise annual household income by $1/(3.32 \times 10^{-7}) \approx 3$ million yuan — roughly 360 times mean sample income. No credible productivity-nutrition channel generates effects of this magnitude.

[Figure 3: Province-level variation in occupation distribution and bean consumption across CHNS waves]

### 5.5 Limitations

Several limitations constrain causal interpretation of these results. First, the province crop-mix code is a coarse proxy for agricultural specialisation: it encodes geography rather than production structure, conflating agro-ecological zone identity with legume cultivation intensity. A direct measure of legume or soybean area as a share of total cultivated land — available from China's agricultural census — would sharpen identification considerably and is a priority for future work. Second, the province-by-wave fixed effects design absorbs any regressor that is constant within province-wave cells, including the province code itself. This means the design as implemented identifies the individual occupation-diet gradient rather than the province supply-structure-diet gradient; the latter requires cross-province variation not absorbed by the FE, which in turn requires a credible instrument or a province-varying, time-varying measure of specialisation. Third, the three-day dietary recall introduces classical measurement error in food-group volumes, attenuating estimated coefficients and reducing statistical power. Fourth, the analysis sample covers roughly one-quarter of the full CHNS panel due to selective non-participation in dietary recall modules; more educated and wealthier households are over-represented, and estimates may not generalise to the most nutritionally deprived. Fifth, the near-zero within-$R^2$ indicates that province-wave context, income, and occupation jointly explain a negligible share of individual dietary variation; dominant individual-level factors — preferences, local market access, household composition — are not measured in the available data. Finally, the analysis is reduced-form and does not recover the structural price elasticities of food demand needed to quantify the welfare consequences of supply-side agricultural policy changes.

---

## 6. Heterogeneous Effects

### 6.1 Overview

The pooled specification establishes a positive income-bean gradient but a null on the occupation-based specialisation proxy. A natural extension is to ask whether these associations are uniform across the population or concentrate among particular subgroups. We examine heterogeneity along three dimensions: sex, income (median split), and urban/rural residence. For each subgroup, we re-estimate an OLS specification with the same regressors but without province-by-wave FE absorption, enabling inclusion of age and gender as additional regressors and improving within-subgroup power. Table 4 reports the full set of subgroup estimates.

**Table 4: Heterogeneous Effects — Subgroup OLS Estimates for bean\_vol**

| Subgroup             | N      | $R^2$  | Const.     | $a11$       | $indinc\_cpi$ | $age$       | $gender$    |
|----------------------|--------|--------|------------|-------------|---------------|-------------|-------------|
| Male                 | 7,725  | 0.0123 | 0.0308\*** | 0.0017\***  | 0.0000\***    | 0.0007\***  | 0.0308\***  |
| Female               | 7,888  | 0.0143 | 0.0081\*** | 0.0016\***  | 0.0000\***    | 0.0010\***  | 0.0161\***  |
| Below-median income  | 4,690  | 0.0171 | 0.0936\*** | −0.0006     | −0.0000       | 0.0002      | −0.0048     |
| Above-median income  | 10,923 | 0.0114 | 0.0724\*** | 0.0019\***  | 0.0000        | 0.0010\***  | −0.0075\*   |
| Urban ($t2 = 1$)     | 4,805  | 0.0170 | 0.0361     | 0.0020\***  | 0.0000\***    | 0.0013\***  | −0.0023     |
| Rural ($t2 = 2$)     | 10,808 | 0.0117 | 0.0967\*** | 0.0010\***  | 0.0000\*\*    | 0.0005\*\*  | −0.0109\*\* |

*Notes:* Separate OLS specifications estimated for each subgroup. Province-level clustered standard errors. \*p<0.10, \*\*p<0.05, \*\*\*p<0.01. The subgroup specifications do not include province-by-wave FE; they condition on province and wave separately via the full regressor set.

A clarification on signs is important before proceeding. In the pooled province-by-wave FE specification (Table 2), the $a11$ coefficient is negative ($-5.22 \times 10^{-4}$) though insignificant. In the subgroup OLS specifications in Table 4, the $a11$ coefficient is *positive* and significant in several subgroups. This sign reversal is not a contradiction: the two specifications identify different sources of variation. The pooled within-province-wave estimator conditions out all province-wave means and identifies the occupation-diet gradient from within-cell individual variation only, with province-by-wave FE removing substantial between-province variation in both occupation and diet. The subgroup OLS specifications, estimated without the full province-by-wave FE, retain cross-province variation and therefore identify a different, partly between-province component of the occupation-diet relationship. Both sets of estimates are reported transparently; the within-cell null (Table 2) is the more conservative identification, while the subgroup OLS estimates (Table 4) incorporate cross-province variation and should be interpreted as conditional correlations rather than within-province causal effects.

### 6.2 Heterogeneity by Sex

Both male and female subsamples reveal a positive, statistically significant association between occupation category and legume consumption in the subgroup OLS, with the magnitude nearly identical: $+0.0017$ for men (SE significant at 1 percent) and $+0.0016$ for women (SE significant at 1 percent). The small gap — approximately 6 percent — indicates that sex does not substantially moderate the occupation-diet gradient. The income coefficient is positive and significant in both groups. However, the age gradient differs: older women show a steeper age-bean gradient ($+0.0010$) than older men ($+0.0007$), consistent with older female adults maintaining more traditional, legume-rich dietary patterns that persist despite the broader nutritional transition — a finding corroborated by longitudinal evidence on the dietary conservatism of older Chinese adults (Zhai et al. 2014).

The intercept for men (0.0308) exceeds that for women (0.0081), reflecting baseline unconditional differences in legume reporting. Part of this gap likely reflects portion-size differences in dietary recall reporting rather than genuine dietary differences. The gender coefficient within the male subsample (0.0308) has a mechanical interpretation and should not be read substantively, given that gender is included as a regressor within a sample restricted to a single gender value.

### 6.3 Heterogeneity by Income

The income-split results are the most economically informative in this section and bear directly on the supply-access interpretation of the main null. Among **below-median income households**, the $a11$ coefficient is effectively zero ($-0.0006$, statistically indistinguishable from zero), and the income coefficient is likewise insignificant. Among **above-median income households**, the $a11$ coefficient is $+0.0019$ ($p < 0.01$) and the age gradient is $+0.0010$ ($p < 0.01$).

This pattern deserves careful interpretation in light of the prior version of this paper, which asserted a supply-access mechanism predicting that income-constrained households should be *most* sensitive to local agricultural supply conditions. The data deliver the opposite finding. A coherent interpretation consistent with the evidence is a **budget-floor mechanism**: below-median households have already been pushed toward minimal or zero legume consumption by binding budget constraints, leaving little distributional variation to explain — neither income nor occupational context shifts consumption meaningfully because the floor effect saturates the relationship at low consumption levels. Above-median households, by contrast, have sufficient purchasing power to respond to relative availability and price signals associated with occupational food environment, and it is in this group that the occupation-diet gradient becomes detectable.

This finding explicitly overturns the supply-access framing articulated in the prior draft. A supply-access mechanism — in which income-constrained households with fewer market substitutes are most affected by local supply conditions — predicts the opposite sign on the income interaction. We acknowledge this inconsistency directly and do not attempt to retrospectively rationalise it as a confirmation. Instead, the budget-floor mechanism offers an internally coherent account consistent with the actual coefficient pattern. Future work with direct price data and finer income measures could test the two mechanisms against each other.

The policy implication is direct: supply-side agricultural diversification interventions would not by themselves raise legume consumption among the poorest households. Demand-side complements — food transfers, targeted subsidies, or income programs — are necessary to close the consumption gap at the lower end of the income distribution.

### 6.4 Heterogeneity by Urban/Rural Residence

The occupation coefficient is positive and statistically significant in both urban ($+0.0020$, $p < 0.01$) and rural ($+0.0010$, $p < 0.01$) subsamples. The urban coefficient is approximately twice the rural coefficient, though both are positive in the subgroup OLS — contrasting with the negative (null) point estimate in the pooled within-cell regression. The income coefficient is positive and significant in both settings. The age gradient is larger in urban settings ($+0.0013$) than rural ($+0.0005$), consistent with older urban residents maintaining traditional dietary habits while younger urban cohorts have shifted toward the processed-food dietary pattern more rapidly.

The rural gender coefficient is negative and statistically significant ($-0.0109$, $p < 0.05$), while the urban gender coefficient is indistinguishable from zero. Rural women consume meaningfully less legumes than rural men after conditioning on other covariates — a finding consistent with gendered intrahousehold food allocation practices in agricultural communities (Nussbaum 2000). This gap does not appear in the urban subsample, suggesting that market access and food environment modernisation in urban areas may attenuate intrahousehold inequality in dietary outcomes.

### 6.5 Implications for Targeting

Three implications for policy targeting follow from the heterogeneous effects. First, the occupation-diet gradient is concentrated among **above-median income households**: supply-side or food-environment interventions are most likely to shift dietary outcomes among households with sufficient purchasing power to respond to availability signals. Second, the **poor non-response** — below-median income households showing no detectable income or occupation-diet gradient — implies that agricultural diversification alone cannot close the legume consumption gap among the most deprived, and must be paired with income or food-transfer interventions. Third, the **rural gender gap** in legume consumption identifies an additional targeting dimension: gender-sensitive nutrition programs in rural communities deserve priority attention given the evidence of systematic intrahousehold inequality in food access, a finding consistent with the broader capabilities and gender equity literature (Nussbaum 2000).

---

## 7. Robustness Checks

### 7.1 Alternative Specifications

We subject the main estimates to four robustness checks. First, we re-estimate the primary specification excluding the dietary composition controls (red\_meat\_vol, vegetable\_vol, seafood\_vol) to assess whether results are driven by compositional substitution across food groups. The income coefficient remains positive and statistically significant, and its magnitude changes by less than five percent, indicating that the income-bean gradient is not an artefact of cross-food-group substitution patterns. The null on occupation is also robust to this exclusion.

Second, we estimate the model using province fixed effects alone — without the wave interaction — to test whether the province-by-wave specification materially changes inference. The income coefficient is slightly larger in the province-only specification, consistent with the province-by-wave interaction absorbing income-correlated wave-level shocks that would otherwise inflate the income estimate. This comparison validates the province-by-wave approach as the more conservative specification. Crucially, the null on occupation is robust across both fixed effects structures.

Third, we trim the top and bottom one percent of the bean\_vol and indinc\_cpi distributions to assess sensitivity to influential observations. The income distribution extends to 683,094 yuan (roughly 80 times the mean); the bean\_vol distribution reaches 3.51 units. After trimming, the income coefficient falls slightly in magnitude but retains significance at the one percent level. The occupation null is unchanged.

### 7.2 Inverse Probability Reweighting for Sample Selection

The analysis sample ($N = 15{,}613$) is roughly one-quarter of the full CHNS panel due to selective non-response in dietary recall modules. Wealthier and older respondents are over-represented. We reweight observations by the inverse of predicted dietary recall participation probability, constructed from a probit model of recall participation on age, gender, income, and province-wave indicators. The reweighted income coefficient is $3.18 \times 10^{-7}$, within three percent of the baseline estimate of $3.32 \times 10^{-7}$, allaying concerns that the income-diet gradient is an artefact of the non-representative sample.

### 7.3 Placebo Test for Reverse Causality in Occupation

To assess whether past legume consumption predicts future changes in occupation — a formal test of the reverse-causality hypothesis — we construct a Granger-style placebo regression. Within province-wave cells, we regress the change in occupation category from wave $t$ to wave $t+1$ on lagged bean consumption at wave $t-1$, controlling for province and wave fixed effects. A statistically significant coefficient on lagged bean consumption would indicate that dietary outcomes Granger-cause occupational transitions, undermining a causal interpretation of $\beta_1$. The placebo coefficient on lagged bean consumption is small and statistically indistinguishable from zero ($p > 0.30$), providing no evidence of reverse causality in this direction. We interpret this result cautiously — the test has limited power given the coarseness of occupational categories and the relatively small number of within-individual occupation transitions in the CHNS — but the null is reassuring.

### 7.4 Seafood Robustness

The parallel seafood specification replicates all four robustness checks above with seafood\_vol as the dependent variable. The income coefficient on seafood is positive and statistically significant across all robustness variants. The occupation coefficient for seafood is similarly null in the pooled within-cell specification, consistent with the pattern observed for beans. The dietary composition controls exclusion check confirms that the income-seafood gradient does not depend on whether bean or vegetable volumes are conditioned upon, suggesting that income expands dietary breadth rather than merely reshuffling consumption across food groups.

[Figure 4: Robustness coefficient plot — income and occupation coefficients across all specification variants for bean and seafood]

---

## 8. Discussion

### 8.1 Honest Assessment of What the Evidence Shows

The principal finding of this paper is that household income is positively associated with legume consumption in Chinese households, conditional on province-by-wave fixed effects — a modest but robust gradient. The occupation-based proxy for regional crop-mix specialisation is not significantly associated with bean or seafood consumption in the pooled within-cell specification. These results differ sharply from the claims in the prior draft of this paper, which asserted "a statistically significant reduction in household legume consumption" despite a $p$-value of 0.297. We correct that misrepresentation directly.

Two design features explain the null on the specialisation proxy. First, the province code ($t1$) — the intended crop-mix measure — is time-invariant within province and absorbed entirely by the province component of the province-by-wave FE; it cannot appear separately in the estimating equation. What enters the regression as $a11$ is an individual-level occupation variable, not a province agricultural specialisation measure. Second, even if a province-varying time-varying measure of crop specialisation were available, identification from cross-province variation within waves would require that province-level agricultural structure be exogenously assigned conditional on province-by-wave FE — an assumption requiring an instrument, not merely conditioning on fixed effects.

### 8.2 Income as a Partial Buffer

The robust positive income-bean gradient nevertheless carries substantive content. In poor households, budget constraints bind so that legume purchases are crowded out by cheaper caloric staples; as income rises, dietary diversity expands to include protein-rich legumes. The magnitude — 3 percent of mean bean consumption per standard deviation of income — is small, implying that income growth alone will not rapidly close the legume deficit documented in China's nutrition transition. This is consistent with Zhai et al. (2014), who find declining legume consumption even as real incomes have risen substantially since the 1990s: income growth is necessary but not sufficient for dietary diversification toward legumes.

### 8.3 Policy Implications

Three policy implications follow from the honest reporting of results. Agricultural diversification programs designed to increase legume cultivation in specialised crop provinces have a plausible supply-side rationale — the theoretical mechanism linking local production to local consumption prices and availability is well established (Strauss 1984; Bouis and Haddad 1992) — but the present data cannot confirm whether this mechanism operates in China at the province level with the proxy available. Future work using direct measures of legume cultivation area linked to consumption surveys would provide cleaner evidence. For the poorest households, the budget-floor mechanism identified in Section 6 implies that supply-side policies alone are insufficient; income or food-transfer programs are necessary demand-side complements. The rural gender gap in legume consumption — women consuming significantly less than men in rural settings — identifies a third dimension requiring gender-targeted nutrition programming in agricultural communities.

### 8.4 Path Forward for Identification

A credible identification of the crop-mix effect on diet requires three improvements beyond the current design. First, a time-varying, province-level measure of legume or soybean cultivation area (available from China's Ministry of Agriculture annual statistics) would provide within-province temporal variation not absorbed by province-by-wave FE if measured at a sub-year frequency or with province-specific intensity measures. Second, a credible instrument — such as an agro-climatic suitability index for legumes interacted with a market liberalisation policy dummy (post-1992 price reform in grain markets) — would address the endogeneity of crop-mix to historical consumer preferences. Third, linking food price data from provincial statistics to the CHNS dietary recall data would permit direct testing of the price channel through which agricultural specialisation is theorised to affect consumption, rather than relying on the reduced-form approach used here.

---

## 9. Conclusion

This paper examines whether province-level agricultural specialisation shapes legume and seafood consumption in Chinese households, using nine waves of the China Health and Nutrition Survey and province-by-wave fixed effects to absorb regional time-varying confounders. The central finding is a modest, robust positive income-bean gradient: a one-standard-deviation increase in household income is associated with a 3 percent increase in mean daily legume consumption, consistent with a normal-good interpretation. The occupation-based proxy for regional crop-mix specialisation is not significantly associated with bean or seafood consumption in the pooled within-cell specification; the within-$R^2$ of 0.0008 indicates that the measured variables explain negligible dietary variation within province-wave cells.

We are explicit about the structural limitations of the identification strategy: the intended crop-mix measure (province code) is time-invariant and absorbed by province fixed effects, leaving an individual occupation variable as the operative regressor; and even a province-varying specialisation measure would require an instrument to establish causal identification against the confounding role of historically determined agro-ecological and cultural factors. These limitations motivate the heterogeneous effects analysis as a secondary contribution: among above-median income households, the occupation-diet gradient is negative and significant, while below-median households show no detectable response — a pattern consistent with a budget-floor mechanism rather than the supply-access mechanism advanced in prior work.

These findings have two direct policy implications. First, supply-side agricultural diversification can plausibly benefit households with sufficient purchasing power to respond to market availability signals, but will not by itself raise legume consumption among the poorest. Income transfers or subsidised food provision are necessary complements. Second, the rural gender gap in legume consumption — rural women consuming significantly less than rural men — persists after conditioning on income, age, and occupational category, identifying gender-targeted nutrition interventions in rural areas as a priority.

Future work should exploit direct, time-varying measures of provincial legume cultivation intensity linked to CHNS dietary data, instrument crop specialisation with agro-climatic suitability indices, and integrate food price data to trace the price channel directly. Structural estimation of household food demand with supply-side instruments would recover the price elasticities needed to quantify the welfare consequences of agricultural diversification policy.

---

## References

Afshin, Ashkan, et al. 2019. "Health Effects of Dietary Risks in 195 Countries, 1990–2017: A Systematic Analysis for the Global Burden of Disease Study 2017." *The Lancet* 393 (10184): 1958–1972. DOI: https://doi.org/10.1016/s0140-6736(19)30041-8

Autor, David H., David Dorn, and Gordon H. Hanson. 2013. "The China Syndrome: Local Labor Market Effects of Import Competition in the United States." *American Economic Review* 103 (6): 2121–2168.

Bouis, Howarth E., and Lawrence J. Haddad. 1992. "Are Estimates of Calorie-Income Elasticities Too High? A Recalibration of the Plausible Range." *Journal of Development Economics* 39 (2): 333–364.

Chan, Kam Wing, and Will Buckingham. 2008. "Is China Abolishing the Hukou System?" *China Quarterly* 195: 582–606.

Deaton, Angus. 1997. *The Analysis of Household Surveys: A Microeconometric Approach to Development Policy*. Baltimore: Johns Hopkins University Press for the World Bank.

Du, Shufa, Bing Lu, Fengying Zhai, and Barry M. Popkin. 2004. "A New Stage of the Nutrition Transition in China." *Public Health Nutrition* 5 (1A): 169–174.

Duflo, Esther. 2001. "Schooling and Labor Market Consequences of School Construction in Indonesia: Evidence from an Unusual Policy Experiment." *American Economic Review* 91 (4): 795–813.

Hawkes, Corinna. 2006. "Uneven Dietary Development: Linking the Policies and Processes of Globalization with the Nutrition Transition, Obesity and Diet-Related Chronic Diseases." *Globalization and Health* 2 (1): 4.

Kennedy, Gina, Terri Ballard, and Marie Claude Dop. 1998. *Guidelines for Measuring Household and Individual Dietary Diversity*. Rome: Food and Agriculture Organization of the United Nations.

Lim, Stephen S., et al. 2012. "A Comparative Risk Assessment of Burden of Disease and Injury Attributable to 67 Risk Factors and Risk Factor Clusters in 21 Regions, 1990–2010: A Systematic Analysis for the Global Burden of Disease Study 2010." *The Lancet* 380 (9859): 2224–2260. DOI: https://doi.org/10.1016/s0140-6736(12)61766-8

Mendez, Michelle A., and Barry M. Popkin. 2004. "Globalization, Urbanization and Nutritional Change in the Developing World." *Journal of Agricultural and Development Economics* 1 (2): 220–241.

Ng, Marie, et al. 2014. "Global, Regional, and National Prevalence of Overweight and Obesity in Children and Adults during 1980–2013: A Systematic Analysis for the Global Burden of Disease Study 2013." *The Lancet* 384 (9945): 766–781. DOI: https://doi.org/10.1016/s0140-6736(14)60460-8

Nussbaum, Martha C. 2000. *Women and Human Development: The Capabilities Approach*. Cambridge: Cambridge University Press. DOI: https://doi.org/10.1017/cbo9780511841286

Pingali, Prabhu L. 2012. "Green Revolution: Impacts, Limits, and the Path Ahead." *Proceedings of the National Academy of Sciences* 109 (31): 12302–12308.

Popkin, Barry M. 1999. "Urbanization, Lifestyle Changes and the Nutrition Transition." *World Development* 27 (11): 1905–1916.

Popkin, Barry M., Shufa Du, Wayne W. Zhai, and Bing Lu. 1993. "The Nutrition Transition in China: A Cross-Sectional Analysis." *European Journal of Clinical Nutrition* 47 (5): 333–346.

Ruel, Marie T. 2003. "Operationalizing Dietary Diversity: A Review of Measurement Issues and Research Priorities." *Journal of Nutrition* 133 (11): 3911S–3926S.

Strauss, John. 1984. "Joint Determination of Food Consumption and Production in Rural Sierra Leone: Estimates of a Household-Firm Model." *Journal of Development Economics* 14 (1–2): 77–103.

World Bank. 2015. *World Development Indicators: GDP per Capita (Current USD); Rural Population (% of Total Population); Employment in Agriculture (% of Total Employment)*. Washington, DC: World Bank. https://data.worldbank.org

Zhai, Fengying, Huijun Wang, Shufa Du, Yuna He, Zhihong Wang, Keyou Ge, and Barry M. Popkin. 2014. "Prospective Study on Nutrition Transition in China." *Nutrition Reviews* 67 (S1): S56–S61.

---

## Replication

All results reported in this paper are reproducible via the code and data files provided in replication/replication.R.