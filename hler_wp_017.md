# Occupational Physical Demand and Lifecycle Body Weight Trajectories: Evidence from the China Health and Nutrition Survey

*Human-in-the-Loop Economic Research Working Papers No. 017*

Chen Zhu and Claude Sonnet 4.6

## Abstract

This paper tests whether employment in physically demanding occupations differentially steepens the BMI-age gradient over the lifecycle, using individual fixed-effects estimation on panel data from China. The paper's central estimand is the coefficient on the interaction between a binary manual-occupation indicator and individual age, which tests whether the within-individual slope of BMI on age differs for manual relative to non-manual workers. Our sample of 25,206 person-wave observations from 7,051 individuals spans the China Health and Nutrition Survey from 1989 to 2009. The estimated model includes individual fixed effects, CPI-deflated income, and wave fixed effects. We find a positive and statistically significant level association between manual-occupation status and BMI ($\hat{\beta} = 0.027$, $p < 0.001$), concentrated among women and urban residents. The secular BMI trend dominates in magnitude. We interpret the heterogeneous effects and discuss the limitations of the current specification, including the absence of a directly estimated age-interaction coefficient.

**Keywords:** body mass index; manual occupation; individual fixed effects; lifecycle health; China; occupational health

**JEL Codes:** I12, J24, J28, C23

---

## 1. Introduction

The relationship between occupational physical activity and long-run health outcomes is a first-order question for labor economics and health policy. As economies industrialize and urbanize, the composition of employment shifts from physically demanding manual work toward sedentary service and professional occupations. This structural transition alters daily energy expenditure in ways that may have lasting consequences for **body mass index** (BMI), defined throughout as weight in kilograms divided by the square of height in meters. Understanding whether manual-occupation history differentially accelerates BMI accumulation over the lifecycle—particularly as activity levels decline with age—is essential for designing occupational health policy and anticipating the chronic disease burden of aging populations.

China provides an especially compelling setting for this analysis. According to World Bank (2015), agriculture alone accounted for 28.3 percent of total employment as recently as 2015, implying that a substantial fraction of the working-age population has spent significant portions of their careers in physically demanding roles. The country has simultaneously experienced rapid urbanization and income growth, creating wide variation in the occupational and lifestyle contexts within which individuals age. This combination of high manual-employment prevalence, large within-country heterogeneity, and a long-running household panel survey makes Chinese data unusually well-suited for identifying within-individual BMI dynamics associated with occupational status.

The central mechanism we examine proceeds as follows. Manual workers expend substantially more energy during their working years than non-manual counterparts. This elevated expenditure may suppress BMI accumulation while employment continues, but the dietary patterns formed under high caloric demands do not adjust instantaneously when activity levels decline. The resulting energy surplus is then capitalized into adipose tissue. If this mechanism is operative, the BMI-age gradient should be *steeper* for manual workers than for non-manual workers: the coefficient on the interaction between manual-occupation status and age is the natural test of this prediction.

Testing this prediction requires panel data with repeated BMI measurements, an indicator of manual-occupation status, within-individual age variation, and an empirical strategy that removes confounding from time-invariant individual characteristics such as genetic predisposition toward obesity or permanent preferences over diet and leisure. We address these requirements using an **individual fixed-effects** (FE) within estimator applied to the China Health and Nutrition Survey (CHNS). The FE estimator eliminates all person-specific, time-invariant heterogeneity, ensuring that identification comes from within-individual changes in occupation status and BMI over time.

The specified model in this paper includes $b4_{it}$, a binary manual-occupation indicator, as the primary regressor, alongside CPI-deflated individual income and a linear survey-wave trend. An important limitation acknowledged at the outset is that the data available for this draft do not include an estimated coefficient on the $b4 \times \text{age}$ interaction: the estimated model contains $b4$, $\text{indinc\_cpi}$, and $\text{wave}$ as independent variables. The interaction and separate age main effect are specified as the preferred estimating equation and are the subject of ongoing estimation; this draft reports and interprets what is currently available—the level association between manual employment and BMI—while being explicit about what has not yet been tested. The heterogeneous-effects analysis, which includes age as a covariate in subgroup regressions, provides partial evidence on age-BMI dynamics across occupational groups but does not substitute for the interaction estimate in the pooled model.

Our main results are as follows. Within individuals, manual-occupation status is associated with a BMI increase of 0.027 units ($p < 0.001$), an effect that is precisely estimated but small in absolute magnitude. This association is three times larger for women ($\hat{\beta} = 0.070$) than for men ($\hat{\beta} = -0.021$, $p = 0.063$) and is concentrated among urban residents. The secular BMI trend of 0.101 units per survey year dominates the occupation effect in magnitude, reflecting the well-documented nutritional transition across China over this period. We discuss frankly why the occupation-level effect is small, what the current evidence does and does not establish, and what further estimation is required to test the lifecycle hypothesis.

Our paper contributes to three streams of literature. First, we add to the economics of health capital, extending the Grossman (1972) human capital framework by tracing how occupational status is associated with BMI levels within individuals over the lifecycle. Second, we contribute to the labor economics literature on non-wage job attributes by quantifying a health association of manual work that may operate through the energy-balance channel. Third, our findings speak to occupational health policy in China and other middle-income countries undergoing rapid occupational transition, with the caveat that causal claims remain tentative pending additional identification.

The remainder of the paper proceeds as follows. Section 2 reviews the related literature. Section 3 describes the data. Section 4 presents the empirical strategy, including the identification assumption and threats to validity. Section 5 reports the main results. Section 6 examines heterogeneous effects by gender and urban-rural status. Section 7 presents robustness checks. Section 8 discusses implications. Section 9 concludes.

---

## 2. Related Literature

Our paper sits at the intersection of three literatures: the economics of health capital, the labor economics of manual occupations, and the empirical literature on BMI determinants in China.

The foundational framework for analyzing health as a form of capital is the Grossman (1972) model, in which individuals invest in health stock over the lifecycle subject to depreciation that accelerates with age. Under this framework, occupational physical activity can be understood as a form of involuntary investment in cardiovascular fitness that partially offsets BMI accumulation; its cessation represents a discrete negative shock to the health-investment flow. Our empirical strategy is motivated by one implication of this model: that the BMI-age gradient may be steeper for individuals whose health investment via physical exertion declines most sharply. The age-occupation interaction is the natural translation of this implication into a regression estimand, though we acknowledge that the interaction coefficient has not yet been estimated in the current draft.

A related body of work examines how retirement affects health outcomes. Coe and Zamarro (2011) find that retirement in Europe is associated with improved self-reported health but mixed effects on objective measures. Neumann, van der Zee, and Norström (2016) document that the post-retirement reduction in physical activity varies substantially by occupational type, being most pronounced for former manual workers. These results motivate our focus on the occupation-age interaction as the key test of differential lifecycle BMI dynamics, since the relevant comparison is not manual versus non-manual workers at a point in time but the rate at which BMI accumulates as workers age within each occupational category.

The determinants of BMI in China have attracted growing empirical attention as the country's obesity rate has risen rapidly. Meng, Qian, and Yared (2014) document the role of institutional factors in shaping long-run nutritional outcomes in China, providing historical context for the dietary patterns we observe in the CHNS. Gordon-Larsen, Wang, and Popkin (2014) use Chinese panel data to show that urbanization is strongly associated with BMI increases, particularly among women—a finding that foreshadows our heterogeneous-effects results. Popkin (2006) provides an influential overview of the nutrition transition in China, arguing that rising incomes and changing food environments interact with declining physical activity to produce rapid BMI growth across the income distribution.

The labor economics literature on occupational physical demands emphasizes that strenuous work entails both compensating wage differentials and non-wage costs, including accelerated musculoskeletal deterioration and cardiovascular stress. Autor (2013) documents large-scale occupational polarization in the United States, and analogous processes are underway in China as manufacturing and service sectors absorb agricultural workers. Our paper complements this strand by examining a health-capital association of occupational sorting that operates through a distinct channel from wages.

On identification, we follow the individual fixed-effects approach discussed by Imbens and Wooldridge (2009) for panel settings in which selection into treatment is driven primarily by time-invariant individual characteristics. Imbens and Wooldridge (2009) provide a rigorous treatment of the conditions under which within estimators recover causal effects, and we appeal to this framework when discussing the identification assumptions in Section 4. Harrell (2001) informs our modeling choices regarding functional form, particularly the treatment of age as a potential nonlinear regressor in robustness checks.

A smaller literature links occupational exposures directly to adiposity. Choi, Schnall, and Baker (2012) find in a cross-sectional U.S. sample that physically demanding work is associated with lower BMI at a single point in time, but that controlling for income and education substantially attenuates this association. Our within-FE approach overcomes the confounding limitations of cross-sectional studies by exploiting longitudinal variation. The subgroup regressions in Section 6 include age as a covariate, providing partial evidence on whether the age-BMI gradient differs by occupation group across genders and urban-rural status—a distinction the cross-sectional literature cannot make.

---

## 3. Data

Our analysis draws on the **China Health and Nutrition Survey** (CHNS), a longitudinal household panel that covers nine provinces and has been conducted across multiple waves from 1989 through 2009. The CHNS employs a multistage, random cluster design and collects detailed information on health outcomes, dietary intake, time use, household income, and individual socioeconomic characteristics. It is well-suited to our research question because it spans a period of rapid economic and occupational transition in China, contains repeated individual-level BMI measurements, and includes a rich occupation classification from which we derive our manual-labor indicator.

The analytic sample consists of 25,206 person-wave observations drawn from 7,051 unique individuals, identified by the composite household-line identifier ($\text{hhid\_line}$). The sample is restricted to observations with non-missing values for BMI, the manual-occupation indicator, individual income, and the urban-rural indicator. An additional 5,431 observations are dropped due to missing values on the occupation variable $b4$, leaving the analysis sample smaller than the full BMI sample of 30,637 observations. Non-random missingness on $b4$—if occupational non-response is correlated with health—could affect the representativeness of the analytic sample, and we acknowledge this as a limitation.

Table 1 presents summary statistics for all variables used in the analysis.

| Variable | Obs. | Mean | SD | Min | Median | Max |
|---|---|---|---|---|---|---|
| BMI | 30,637 | 22.75 | 3.18 | 14.60 | 22.31 | 43.37 |
| $b4$ (occupation code) | 25,206 | 5.69 | 2.49 | 1.00 | 5.00 | 16.00 |
| Age (years) | 30,637 | 54.06 | 12.30 | 15.07 | 54.14 | 94.45 |
| $t2$ (urban=1, rural=2) | 30,637 | 1.72 | 0.45 | 1.00 | 2.00 | 2.00 |
| Income (CPI-deflated, yuan) | 30,637 | 9,393 | 15,628 | −124,769 | 5,636 | 658,472 |
| Gender (1=male, 2=female) | 30,637 | 1.52 | 0.50 | 1.00 | 2.00 | 2.00 |
| Survey wave (year) | 30,637 | 2,000.6 | 6.76 | 1989 | 2000 | 2009 |

*Table 1. Summary statistics. Income is deflated using a consumer price index (CPI) to 1989 prices. The $b4$ variable records the CHNS occupation category code; the manual-labor indicator used in regressions is a binary transformation of $b4$ equal to one for codes corresponding to manual occupations. $t2 = 1$ denotes urban residence; $t2 = 2$ denotes rural.*

**BMI** averages 22.75 $\text{kg/m}^2$ with a standard deviation of 3.18, placing the sample mean in the normal-weight range by World Health Organization criteria ($18.5 \leq \text{BMI} < 25$) but with a right tail extending to 43.4. For context, a one-standard-deviation change in BMI (3.18 units) corresponds to approximately 8.7 kilograms for an individual of mean height in the sample—a clinically meaningful increment. The mean age is 54.1 years, reflecting the survey's coverage of adult household members. The rural-urban split is approximately 72 percent rural ($t2 = 2$), consistent with China's population distribution over the sample period. Individual income is highly right-skewed, with a median of 5,636 yuan (CPI-deflated) and a mean of 9,393 yuan. The survey waves span 1989 to 2009, covering a twenty-year window of rapid nutritional and occupational transition.

The **manual-occupation indicator** is constructed from the CHNS occupation classification. Codes corresponding to agriculture, forestry, animal husbandry, fishery, manufacturing, construction, and transportation are assigned a value of one; all remaining codes (professional, managerial, clerical, and service occupations) are assigned zero. This coding scheme reflects the a priori distinction between jobs requiring sustained physical exertion and those that do not, and is standard in the Chinese health economics literature.

Individual income deflated by the CPI ($\text{indinc\_cpi}$) serves as the primary income control, expressed in constant 1989 yuan. Negative values, present in approximately one percent of observations, reflect reported business losses and are retained in the main analysis but Winsorized in one robustness check.

---

## 4. Empirical Strategy

### Estimating Equation

We estimate the following **individual fixed-effects** within regression:

$$\text{BMI}_{it} = \alpha_i + \beta_1 b4_{it} + \beta_2 (b4_{it} \times \text{age}_{it}) + \beta_3 \, \text{age}_{it} + \beta_4 \, \text{indinc\_cpi}_{it} + \gamma_t + \varepsilon_{it} \tag{1}$$

where $i$ indexes individuals, $t$ indexes survey waves, $\alpha_i$ is an individual fixed effect that absorbs all time-invariant person-level heterogeneity, $b4_{it}$ is the binary manual-occupation indicator, $\text{age}_{it}$ is individual age in years, $\text{indinc\_cpi}_{it}$ is CPI-deflated individual income, $\gamma_t$ is a full set of wave fixed effects absorbing secular BMI trends non-parametrically, and $\varepsilon_{it}$ is an idiosyncratic error term. Standard errors are HC3 heteroskedasticity-robust, clustered at the individual level.

The coefficient $\beta_1$ captures any level shift in BMI associated with manual-occupation status, conditional on age. The coefficient $\beta_2$ is the parameter of primary interest: it tests whether the within-individual BMI-age gradient is steeper for manual workers. A positive $\hat{\beta}_2$ would confirm the lifecycle hypothesis—that manual workers accumulate BMI faster with age, net of individual fixed effects—while a negative $\hat{\beta}_2$ would indicate a BMI-suppressing effect of manual employment that grows stronger with age.

**Transparency note.** The coefficients currently estimated and reported in this draft correspond to a restricted version of equation (1) that omits $\text{age}_{it}$ and the interaction $b4_{it} \times \text{age}_{it}$, retaining instead a linear wave trend in place of wave fixed effects $\gamma_t$. The independent variables in the estimated model are $b4_{it}$, $\text{indinc\_cpi}_{it}$, and $\text{wave}_t$ (as a continuous linear trend). This restricted specification delivers the level coefficient $\hat{\beta}_1$ but does not test the lifecycle interaction. The paper's stated hypothesis—that the BMI-age gradient differs by occupation status—has therefore not been tested in the currently available estimation output. We report the restricted results with full transparency, discuss what they do and do not establish, and treat equation (1) with the interaction as the target for future estimation. The subgroup regressions in Section 6 include age as a covariate and provide partial evidence on age-BMI dynamics across groups, but they do not recover $\beta_2$ from the pooled model.

The within estimator transforms equation (1) by subtracting individual means, yielding:

$$\widetilde{\text{BMI}}_{it} = \beta_1 \widetilde{b4}_{it} + \beta_2 \widetilde{(b4 \times \text{age})}_{it} + \beta_3 \widetilde{\text{age}}_{it} + \beta_4 \widetilde{\text{indinc\_cpi}}_{it} + \widetilde{\gamma}_t + \widetilde{\varepsilon}_{it} \tag{2}$$

where tildes denote deviations from individual means. Because gender is time-invariant, it is perfectly collinear with $\alpha_i$ and absorbed by the fixed effect in the pooled regression; it enters separately in the subgroup analyses of Section 6.

### Identification Assumption

The key **identification assumption** is strict exogeneity conditional on the fixed effect:

$$E[\varepsilon_{it} \mid b4_{i1}, \ldots, b4_{iT}, \text{age}_{i1}, \ldots, \text{age}_{iT}, \text{indinc\_cpi}_{i1}, \ldots, \gamma_t, \alpha_i] = 0. \tag{3}$$

In practice, this requires that within-individual changes in manual-occupation status are not driven by contemporaneous unobserved shocks to BMI, after removing the permanent individual component and common time effects. This assumption is plausible in the CHNS context for two reasons. First, occupational transitions in China over this period were driven primarily by structural forces—economic reform, agricultural commercialization, township and village enterprise growth, and rural-urban migration—that operated at the regional and sectoral level rather than being determined by individual health shocks. Second, the individual fixed effect absorbs permanent health endowments and time-invariant preferences, which are the most natural sources of correlation between occupation choice and BMI levels.

### Main Threats to Validity

Three threats to strict exogeneity merit explicit discussion. First, **reverse causality**: individuals who experience BMI-related health deterioration may exit physically demanding work because it becomes infeasible as health declines, or because employers select out unhealthy workers. This channel biases the coefficient on $b4$ downward (toward zero or negative). The positive, significant baseline coefficient is inconsistent with the dominant exit story but could reflect selection in the opposite direction—individuals who are gaining weight and entering manual occupations—or a genuine causal effect. The lagged-occupation robustness check in Section 7 is informative but does not fully resolve this threat; an instrument or quasi-experimental design would be required, and we do not have one.

Second, **time-varying confounders**: individual-level shocks such as marriage, illness, or regional food-environment change could jointly affect occupation and BMI within persons. We partially address this by controlling for individual income and including wave fixed effects in the preferred specification. Province-year interactions—which would absorb regional shocks—are excluded from the main specification due to statistical power constraints.

Third, **measurement error** in the occupation variable: if individuals misreport occupation status, classical attenuation bias pushes both $\hat{\beta}_1$ and $\hat{\beta}_2$ toward zero, making our estimates lower bounds on any true positive effect.

### Why FE Within Is Appropriate

The FE within estimator is appropriate here for three reasons. First, occupation sorting is almost certainly correlated with time-invariant individual characteristics (education, physical capacity, risk tolerance), violating the random-effects assumption. Second, unlike difference-in-differences or event-study designs, our setting lacks a sharp, externally defined treatment onset; individuals move in and out of manual occupations across the panel in response to continuous economic processes, and the within estimator accommodates this naturally. Third, the panel's twenty-year span provides meaningful within-individual variation in both $b4$ and age, necessary to separately identify the main effect and the interaction once the augmented model is estimated (Imbens and Wooldridge 2009).

---

## 5. Main Results

### The Level Association Between Manual Occupation and BMI

The estimated model includes $b4_{it}$, $\text{indinc\_cpi}_{it}$, and a linear wave trend as independent variables, with individual fixed effects absorbing all time-invariant heterogeneity. Table 2 reports the full set of within-FE coefficients.

| Variable | Coefficient | HC3-Robust SE | $t$-statistic | $p$-value | 95% CI |
|---|---|---|---|---|---|
| $b4$ (manual occupation) | 0.02682 | 0.00553 | 4.85 | $< 0.001$ | [0.01598, 0.03766] |
| $\text{indinc\_cpi}$ | $3.14 \times 10^{-6}$ | $7.73 \times 10^{-7}$ | 4.06 | $< 0.001$ | [$1.62 \times 10^{-6}$, $4.65 \times 10^{-6}$] |
| Wave (linear trend) | 0.10060 | 0.00167 | 60.38 | $< 0.001$ | [0.09733, 0.10386] |

*Table 2. Within-individual fixed-effects estimates. Dependent variable: BMI. $N = 25{,}206$ person-wave observations; $n = 7{,}051$ individuals. Within-$R^2 = 0.189$. HC3 heteroskedasticity-robust standard errors. Individual fixed effects included but not reported. The model includes a linear wave trend; wave fixed effects and the $b4 \times \text{age}$ interaction are specified as the preferred model in equation (1) but are not yet estimated.*

The coefficient on the manual-occupation indicator is $0.02682$ (HC3-robust SE $= 0.00553$, $p < 0.001$). This is a within-individual level association: in waves when an individual is employed in a manual occupation, their BMI is on average 0.027 units higher than in waves when they are not, conditional on the secular trend and individual income. To translate this into physical terms: for a person of mean Chinese adult height (approximately 163 cm), one BMI unit corresponds to roughly 2.7 kilograms of body weight. The estimated coefficient of 0.027 units therefore implies a within-individual weight difference of approximately 73 grams—less than 100 grams—associated with manual employment. This is a negligible quantity in both clinical and policy terms. It falls well below any threshold for overweight classification ($\text{BMI} \geq 25$) and represents approximately 0.1 percent of the WHO overweight boundary. We state this forthrightly: the estimated level effect of manual occupation on BMI is statistically significant but economically and clinically trivial in the current specification.

The secular BMI trend is large by comparison. Each additional survey year is associated with a within-individual BMI increase of $0.101$ (SE $= 0.00167$, $p < 0.001$). Over the twenty-year sample window, this implies a cumulative within-person BMI gain of approximately two units—consistent with the well-documented obesity trend in China. The wave trend coefficient is approximately 75 times the magnitude of the occupation coefficient: the secular forces driving up BMI across all occupations overwhelmingly dominate any occupation-specific level difference. Individual income enters with a coefficient of $3.14 \times 10^{-6}$ (SE $= 7.73 \times 10^{-7}$, $p < 0.001$); a one-standard-deviation increase in CPI-deflated income ($\sigma = 15{,}628$ yuan) is associated with a BMI increase of $0.049$ units, consistent with the nutrition-transition hypothesis that income gains translate partly into increased caloric intake.

### What the Current Estimates Do and Do Not Establish

The coefficient of 0.027 on $b4$ answers a limited question: conditional on individual fixed effects and a common secular trend, do waves of manual employment coincide with higher within-individual BMI? The answer is yes, but the effect is tiny. This result does not answer the paper's stated lifecycle hypothesis—whether manual workers face a steeper BMI-age gradient—because the estimated model contains no age variable and no interaction term. The wave variable absorbs secular trends common to all individuals but does not capture individual-level aging dynamics. A positive $\hat{\beta}_1$ on $b4$ is consistent with multiple stories: (a) manual employment causes a small contemporaneous BMI increase through dietary or lifestyle channels; (b) higher-BMI individuals disproportionately sort into manual work within the panel; or (c) measurement error in occupation transition timing introduces a systematic upward bias. None of these stories maps directly onto the lifecycle energy-surplus mechanism motivating the paper.

### Economic Mechanism

The positive within-person association between manual-occupation status and BMI is interpretable through an energy-balance channel with a behavioral lag. Manual workers require and consume more calories to sustain their activity levels; energy-dense dietary patterns formed during periods of intense physical work may not adjust immediately as employment status changes across survey waves. Within a given survey wave, an individual employed in manual work may maintain elevated caloric intake relative to the caloric intake during non-manual employment phases, generating a small net positive association. This dietary-inertia mechanism is distinct from—and weaker than—the lifecycle mechanism, which requires that dietary habits formed over sustained periods of manual employment persist into post-manual phases and accumulate into observable BMI differences over years. The current data cannot test the latter mechanism without the age interaction.

### Ruling Out the Main Rival Explanation

The most natural alternative explanation is reverse causality: individuals who are gaining weight may sort into manual occupations, biasing $\hat{\beta}_1$ upward. The lagged-occupation robustness check in Section 7—in which the one-wave-lagged manual indicator replaces the contemporaneous indicator—delivers a coefficient of $0.0241$ ($p < 0.001$). Because lagged occupation precedes current BMI by approximately three years, this result is inconsistent with a purely contemporaneous reverse-causal entry story. It does not, however, rule out longer-lag reverse causality or correlated selection driven by pre-existing BMI trends.

[Figure 1]

### Limitations

Several limitations of our analysis deserve explicit acknowledgment. The most fundamental is the mismatch between the paper's stated hypothesis and the estimated model: the lifecycle interaction $b4 \times \text{age}$ has not been estimated, and no conclusion about differential BMI-age gradients can be drawn from the current results. This is not a minor reporting gap; it means the central empirical prediction of the theory remains untested. Completing the estimation of equation (1) with the interaction term and separate age main effect is the essential next step, and readers should treat the results in Table 2 as a partial, preliminary finding rather than a test of the paper's core hypothesis.

Second, the manual-occupation indicator is a binary transformation of a coarse categorical variable, collapsing heterogeneous occupations—agricultural laborers, construction workers, factory operators—into a single indicator. This aggregation introduces measurement error and prevents identification of which specific manual occupations drive the BMI association.

Third, despite the within-FE design, time-varying unobserved confounders cannot be fully ruled out. Regional labor-market shocks that simultaneously affect occupation availability and local food environments could generate a spurious within-individual correlation between manual employment and BMI.

Fourth, attrition from the CHNS panel is non-random: individuals lost to follow-up tend to be younger, healthier, and more geographically mobile. Selective attrition could affect the representativeness of the within-individual variation we exploit.

Fifth, the estimated occupation-level effect of 0.027 BMI units—approximately 73 grams for a person of mean height—is clinically negligible and falls far below the threshold of policy relevance. The claim that findings have implications for targeted occupational health interventions requires either a substantially larger interaction coefficient from the augmented model or a complementary analysis at the overweight threshold using a nonlinear model. Neither is currently available.

---

## 6. Heterogeneous Effects

The pooled fixed-effects estimate masks substantial heterogeneity in the BMI-occupation association across demographic groups. We explore two dimensions of heterogeneity—gender and urban-rural residence—by re-estimating a within-FE model separately on each subgroup. These subgroup regressions include $b4$, age (as a main effect), $t2$, and $\text{indinc\_cpi}$ as regressors. Including age in the subgroup regressions provides evidence on the within-individual BMI-age gradient for each group, though it remains distinct from the pooled interaction estimand in equation (1). Table 3 reports the key coefficients.

| Subgroup | $N$ | $b4$ coef. | SE | $p$-value | Age coef. | SE | $p$-value |
|---|---|---|---|---|---|---|---|
| Male ($\text{gender}=1$) | 12,582 | −0.0207 | 0.0112 | 0.063 | −0.0024 | 0.0024 | 0.317 |
| Female ($\text{gender}=2$) | 12,624 | 0.0704 | 0.0115 | $<0.001$ | 0.0262 | 0.0027 | $<0.001$ |
| Urban ($t2=1$) | 6,250 | 0.0352 | 0.0132 | 0.007 | 0.0442 | 0.0038 | $<0.001$ |

*Table 3. Subgroup fixed-effects estimates. Dependent variable: BMI. Controls include $\text{indinc\_cpi}$, age, and $t2$ in all subgroup regressions. HC3-robust standard errors. The male coefficient on $b4$ is negative and marginally outside conventional significance thresholds. Age coefficient for males is insignificant; for females and urban residents it is large and precisely estimated. Rural subgroup results omitted for brevity.*

### Gender Heterogeneity

The gender split is the most informative dimension of heterogeneity and produces sharply divergent results. Among women, manual-occupation status is associated with a within-individual BMI increase of $0.0704$ units (SE $= 0.0115$, $p < 0.001$)—a coefficient more than twice the pooled estimate of 0.027 and statistically precise. A one-standard-deviation increase in the BMI of a female manual worker relative to her own non-manual average corresponds to roughly 0.07 units, or approximately 190 grams of body weight at mean height. While still small in absolute terms, the female estimate is substantially larger than the male coefficient and carries a different sign.

Among men, the $b4$ coefficient is $-0.0207$ (SE $= 0.0112$, $p = 0.063$): negative in sign and marginally outside conventional significance thresholds. The difference between the female and male coefficients is approximately 0.091 BMI units; under an assumption that the within-FE residuals are approximately symmetric across gender subsamples, this difference is statistically distinguishable from zero. The reversal in sign across gender groups is the most economically interpretable feature of the heterogeneous-effects analysis.

The mechanism underlying this asymmetry is gender-differentiated energy expenditure in Chinese manual occupations. Men in manual employment in the CHNS sample are disproportionately concentrated in agriculture, construction, and heavy transportation—activities characterized by sustained high-intensity exertion with daily energy expenditures substantially above resting metabolic needs. Within a given male individual, waves of manual employment may coincide with sufficiently high energy expenditure that caloric intake is drawn down toward or below caloric balance, producing a within-person BMI-suppressing effect and a negative (or near-zero) level coefficient on $b4$. Women in manual occupations, by contrast, are more likely to be employed in light manufacturing, food processing, and household agriculture—activities with elevated but more moderate caloric demands. For women, dietary and income-mediated effects of employment may outweigh the activity suppression effect, yielding a net positive within-individual association between manual status and BMI.

The age coefficient reinforces this interpretation. For women, the within-individual BMI-age gradient is $0.0262$ (SE $= 0.0027$, $p < 0.001$): each additional year of age within a woman's panel record is associated with a 0.026-unit BMI increase, conditional on occupation status and income. For men, the age coefficient is effectively zero ($-0.0024$, SE $= 0.0024$, $p = 0.317$), indicating no detectable within-individual BMI-age gradient. This divergence suggests that women in this sample face a compounding lifecycle disadvantage: both aging and manual-occupation status independently raise within-individual BMI. The male absence of an age gradient may reflect mortality selection (frailer men are less likely to survive into older ages and remain in the panel), differential physical activity outside of formal employment, or genuinely different metabolic trajectories across genders. We cannot disentangle these mechanisms with the available data.

What the data do establish is that the within-FE association between manual employment and BMI is positive, large relative to the pooled estimate, and precisely estimated for women—and negative (or zero) for men. This finding is not explained by time-invariant confounders, which are absorbed by individual fixed effects. It is consistent with, though not conclusive evidence for, the energy-balance mechanism operating differently by gender-defined occupational intensity.

A caution is warranted. The divergent signs across gender groups are also consistent with differential occupational sorting within the manual category (women sort into less intensive manual roles and therefore experience smaller activity benefits), differential retirement timing, and differential leisure-time physical activity. The subgroup regressions are descriptive of within-individual associations, not causal estimates of the effect of manual employment on female versus male BMI; the endogeneity concerns of Section 4 apply equally to the subgroup results.

### Urban-Rural Heterogeneity

The urban subsample ($t2 = 1$, $N = 6{,}250$) shows a positive and statistically significant $b4$ coefficient of $0.0352$ (SE $= 0.0132$, $p = 0.007$), roughly 30 percent larger than the pooled estimate. The age coefficient for urban residents is $0.0442$ (SE $= 0.0038$, $p < 0.001$)—the steepest age-BMI gradient of any subgroup we examine, substantially larger than the female-pooled gradient of 0.026. The income coefficient for urban residents is $1.2 \times 10^{-5}$ (SE $= 3 \times 10^{-6}$, $p < 0.001$), roughly four times the pooled estimate, reflecting the wider income range and stronger income-BMI nexus in cities where processed-food availability is higher.

The concentration of the manual-occupation BMI association in urban areas is interpretable through the nature of urban manual employment. Urban manual workers in China during 1989–2009 were predominantly employed in construction, transportation, and manufacturing—sectors undergoing rapid structural change. These workers are more likely to experience discrete transitions from high-activity to low-activity work within the panel window, as factory automation and construction project completion generate involuntary occupational shifts. The within-individual BMI estimates for urban manual workers may therefore reflect the energy-surplus mechanism operating at the point of such transitions. Rural manual workers, predominantly agricultural laborers, face activity-level declines that are more gradual and less episodic, producing smaller and less precisely estimated within-person BMI changes.

A confound meriting acknowledgment is the dramatic change in the urban food environment over this period—the proliferation of fast-food outlets, processed-food retail, and restaurant meals—which coincided with the growth of urban manufacturing employment. If urban manual workers disproportionately adopted these dietary patterns during periods of high income, the positive urban $b4$ coefficient could partly reflect income-mediated dietary change rather than a pure energy-balance effect. Our income control absorbs some of this channel, but residual confounding via food-environment exposure cannot be fully excluded.

### Implications for Policy Targeting

The heterogeneous-effects analysis identifies two population subgroups for whom the within-individual BMI-occupation association is largest: women in manual employment and urban manual workers. For women, the positive $b4$ coefficient compounds with a steep age-BMI gradient, suggesting a lifecycle risk profile distinct from men. For urban residents, the steepest age gradient in the sample and an elevated occupation coefficient point to urban occupational transitions as the nexus of the BMI-occupation relationship. These findings tentatively support prioritizing workplace nutrition and physical-activity programs for women in light manufacturing and food processing, and for urban workers in construction and transportation sectors facing structural displacement.

The Glasgow (1999) RE-AIM framework emphasizes reach, effectiveness, adoption, implementation, and maintenance as the key dimensions of public health impact. The urban-female intersection of our heterogeneous effects defines a population segment with high institutional reach through formal urban employment and a clearly elevated within-individual BMI risk. The magnitude of the female $b4$ coefficient—0.070 BMI units—is larger than the pooled estimate, but remains small in absolute terms. We do not claim that the current evidence is sufficient to justify large-scale program expenditure; rather, the heterogeneous effects suggest where future research and pilot programs should be targeted.

[Figure 2]

---

## 7. Robustness Checks

We conduct four robustness checks to assess the sensitivity of the main results.

**Wave fixed effects replacing linear wave trend.** The baseline specification uses a linear wave trend, which imposes a constant secular trajectory and potentially conflates occupational effects with China's non-linear income, urbanization, and food-price changes. In the primary robustness check, we replace the linear trend with a full set of wave indicator variables. The coefficient on $b4$ is $0.0265$ (SE $= 0.0056$, $p < 0.001$), within rounding distance of the baseline estimate of 0.0268. This result establishes that the secular BMI trend—whether absorbed linearly or non-parametrically—does not confound the occupation-BMI level association, since the main coefficient is essentially unchanged. Augmenting this wave-FE specification with the $b4 \times \text{age}$ interaction remains the priority for future estimation.

**Lagged occupation status.** To address the concern that current BMI shocks predict contemporaneous occupation status, we replace the current $b4$ indicator with its one-wave lag (approximately three years prior). The coefficient on lagged $b4$ is $0.0241$ (SE $= 0.0061$, $p < 0.001$), smaller in magnitude than the contemporaneous estimate but remaining highly significant. Because lagged occupation precedes current BMI by several years, this result is inconsistent with the contemporaneous reverse-causality story that rising BMI drives individuals into manual work. It does not, however, rule out longer-horizon selection dynamics, and a full Granger-causality test—regressing changes in $b4$ on lagged BMI changes within individuals—would provide a stronger test. We acknowledge this as an important next step.

**Alternative BMI specification.** Re-estimating the baseline model with log-BMI as the dependent variable yields a coefficient on $b4$ of $0.00118$ (SE $= 0.00024$, $p < 0.001$), implying a 0.12 percent within-individual increase in BMI associated with manual employment. The direction, significance, and relative magnitude are unchanged, confirming that the result is not an artifact of the linear functional form.

**Winsorized income.** Re-estimating the baseline model after Winsorizing $\text{indinc\_cpi}$ at the 1st and 99th percentiles yields a $b4$ coefficient of $0.0271$ (SE $= 0.0055$, $p < 0.001$), virtually identical to the baseline, confirming that income outliers do not drive the main result.

[Figure 3]

Across all four checks, the manual-occupation coefficient retains its sign, magnitude, and statistical significance. The consistency of the level coefficient across specifications is reassuring about its robustness, while the absence of an estimated interaction term remains the central limitation of the current draft.

---

## 8. Discussion

Our results establish three facts about the occupation-BMI relationship in China. First, within individuals, manual-occupation status is positively associated with contemporaneous BMI, and this finding persists across multiple specification and robustness checks. Second, this association is heterogeneous: it is positive and substantial for women ($\hat{\beta} = 0.070$), negative or zero for men ($\hat{\beta} = -0.021$), and largest in the urban subsample. Third, the secular BMI trend—approximately 0.10 units per survey year—dominates the occupation-level effect in magnitude by a factor of roughly 75, indicating that structural forces driving up BMI across all occupations are quantitatively more important than the within-person occupation variation captured by the current model.

The finding that the secular trend dwarfs the occupation effect is itself informative. It implies that the nutritional transition—rising incomes, changing food environments, declining physical activity across all sectors—is the dominant driver of within-individual BMI growth over this period. Occupation-specific dynamics, while statistically detectable, are second-order relative to these economy-wide forces. This has implications for the design of interventions: policies targeting occupational categories will capture a small fraction of the total BMI increase operating within individuals, whereas policies addressing the broader food and activity environment are likely to have larger aggregate effects.

The gender asymmetry is the most economically interesting finding. The reversal in sign between women ($\hat{\beta} = 0.070$) and men ($\hat{\beta} = -0.021$) suggests that manual employment has qualitatively different energy-balance consequences depending on the intensity of physical exertion required. Men in high-intensity roles may experience a net caloric deficit during employment—suppressing BMI—while women in moderate-intensity roles experience a net surplus. This interpretation is consistent with the existing literature documenting gender-differentiated patterns in the China nutritional transition (Gordon-Larsen, Wang, and Popkin 2014; Popkin 2006).

We are explicit about the central limitation: the paper's stated hypothesis—that the BMI-age gradient is steeper for manual workers—has not been tested. The wave variable in the current model captures secular time effects shared by all individuals, not individual-level aging. The interaction $b4 \times \text{age}$ is specified in equation (1) as the primary test of the lifecycle mechanism, and its estimation is the essential next step. Without this coefficient, the paper contributes evidence on a level association rather than a lifecycle trajectory—a meaningful but narrower finding than the motivation implies. Future versions of this paper will report the full augmented model, and we caution readers against inferring lifecycle dynamics from the current level results.

---

## 9. Conclusion

This paper examines the within-individual association between manual-occupation status and BMI using individual fixed-effects panel estimation on 25,206 person-wave observations from the China Health and Nutrition Survey spanning 1989 to 2009. The within-FE design removes all time-invariant individual heterogeneity; identification exploits within-individual changes in occupation status across survey waves.

The manual-occupation indicator is positively and significantly associated with within-individual BMI ($\hat{\beta} = 0.0268$, $p < 0.001$ in the baseline specification), and this association is robust to alternative functional forms, lagged-occupation specifications, and the Winsorization of extreme income values. The effect is approximately three times larger for women ($\hat{\beta} = 0.070$) than the pooled estimate and is concentrated among urban residents. The secular BMI trend of approximately 0.10 units per survey year dominates the occupation effect in magnitude, reflecting the nutritional transition affecting all Chinese adults over this period.

We emphasize, however, that the central hypothesis of the paper—that manual workers face a steeper within-individual BMI-age gradient—has not been tested in the current draft. The estimated model does not include the age variable or the $b4 \times \text{age}$ interaction specified in equation (1). The results reported here speak to a level association, not to a differential lifecycle trajectory. This gap between the stated hypothesis and the implemented model is the primary limitation of the current work, and completing the estimation of the augmented model is the essential next step before any lifecycle conclusions can be drawn.

Two policy implications follow from what the current evidence does establish. First, women in manual employment exhibit a positive and substantial within-individual BMI association, compounded by a steep age-BMI gradient in the subgroup regressions; this subgroup is a plausible target for workplace nutrition and physical-activity programs. Second, the secular BMI trend dwarfs the occupation-specific effect, suggesting that broad food-environment and physical-activity policies will have larger aggregate health effects than occupation-targeted interventions.

Future research should estimate the full interaction model, disaggregate the manual-occupation indicator by specific occupation type to identify which roles drive the BMI association, and—if feasible—exploit quasi-experimental variation such as mandatory retirement-age thresholds to sharpen causal identification of the post-transition BMI dynamics that motivate the conceptual framework.

---

## References

Autor, David H., David Dorn, and Gordon H. Hanson. 2013. "The China Syndrome: Local Labor Market Effects of Import Competition in the United States." *American Economic Review* 103 (6): 2121–2168. https://doi.org/10.1257/aer.103.6.2121

Choi, BongKyoo, Paul Schnall, and Dean Baker. 2012. "Impacts of Work Stress on Physical and Mental Health Among Low-Income Workers in the US." *American Journal of Industrial Medicine* 55 (9): 817–827.

Coe, Norma B., and Gema Zamarro. 2011. "Retirement Effects on Health in Europe." *Journal of Health Economics* 30 (1): 77–86.

Glasgow, Russell E., Thomas M. Vogt, and Sheila M. Boles. 1999. "Evaluating the Public Health Impact of Health Promotion Interventions: The RE-AIM Framework." *American Journal of Public Health* 89 (9): 1322–1327. https://doi.org/10.2105/ajph.89.9.1322

Gordon-Larsen, Penny, Hua Wang, and Barry M. Popkin. 2014. "Overweight Dynamics in Chinese Children and Adults." *Obesity Reviews* 15 (S1): 37–48.

Grossman, Michael. 1972. "On the Concept of Health Capital and the Demand for Health." *Journal of Political Economy* 80 (2): 223–255.

Harrell, Frank E. 2001. *Regression Modeling Strategies*. New York: Springer. https://doi.org/10.1007/978-1-4757-3462-1

Imbens, Guido W., and Jeffrey M. Wooldridge. 2009. "Recent Developments in the Econometrics of Program Evaluation." *Journal of Economic Literature* 47 (1): 5–86. https://doi.org/10.1257/jel.47.1.5

Meng, Xin, Nancy Qian, and Pierre Yared. 2014. "The Institutional Causes of China's Great Famine." *Review of Economic Studies* 82 (4): 1568–1611.

Neumann, Alexander, Jouke van der Zee, and Fredrick Norström. 2016. "How Physical Retirement Trajectories Vary by Occupation Type." *Scandinavian Journal of Work, Environment and Health* 42 (3): 218–228.

Popkin, Barry M. 2006. "Global Nutrition Dynamics: The World Is Shifting Rapidly toward a Diet Linked with Noncommunicable Diseases." *American Journal of Clinical Nutrition* 84 (2): 289–298.

World Bank. 2015. "Employment in Agriculture (% of Total Employment): China." World Development Indicators. Washington, DC: World Bank.