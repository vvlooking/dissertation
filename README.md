# Dissertation Quantitative Data Analysis
## Step 1: Descriptive Analysis
**Analysis:** Descriptive statistics
<br/>
**Script:** step1.02.Rmd (Folder: Step 1)
<br/>
<br/>
**Description:** Before conducting inferential statistical analyses, I performed descriptive analysis to gain an initial understanding of the dataset and ensure data quality. This step allowed me to summarize the distributions and relationships among key variables, as well as to inform subsequent regression modeling.
<br/>
<br/> 
## Step 2: Compare User Engagement between Ephemeral and Non-Ephemeral Content
_**RQ 1.1** What content characteristics (i.e., a video's user engagement metrics and audio, visual, and linguistic elements) are associated with the ephemerality of nonsuicidal self-injury information on TikTok?_
<br/>
<br/>
**Analysis:** Mann-Whitney U
<br/>
**Script:** step2.02.Rmd (Folder 2)
<br/>
<br/>
**Description:** To compare user engagement between ephemeral and non-ephemeral NSSI content, a Mann-Whitney U test was conducted for four user engagement metrics: view count, like count, comment count, and share count. To account for multiple comparisons, a Bonferroni correction was applied to adjust the significance threshold.
<br/>
<br/> 
**Analysis:** Stepwise logistic regression
<br/>
**Script:** step2.02.Rmd (Folder 2)
<br/>
<br/>
**Description:** To determine whether user engagement metrics were associated with ephemerality of NSSI content on TikTok, a stepwise logistic regression was conducted using view count, like count, comment count, and share count as predictors of ephemerality. 
 

## Step 3: Characterize Content Characteristics of Ephemeral and Non-Ephemeral Content
_**RQ 1.1** What content characteristics (i.e., a video's user engagement metrics and audio, visual, and linguistic elements) are associated with the ephemerality of nonsuicidal self-injury information on TikTok?_
<br/>
<br/>
**Analysis:** Content analysis
<br/>
<br/>
**Description:** A content analysis of both ephemeral and non-ephemeral videos was conducted to characterize the content characteristics (i.e., a video’s user engagement metrics and audio, visual, and linguistic elements) of each. Analysis resulted in six high-level categories: addiction language, algospeak, signaling, visible scars, explicit NSSI language, and the presence of trigger warnings. A total of 24 child codes was organized under these categories: three for addiction language, six for algospeak, four for explicit language, four for visible scars, and seven for signaling. Each characteristic was coded as present (1) or absent (0) in Excel.
<br/>
<br/>
**Analysis:** Descriptive analysis
<br/>
**Script:** step3.02.Rmd


## Step 4: Association between Content Characteristics and Probability of Ephemerality
_**RQ 1.1** What content characteristics (i.e., a video's user engagement metrics and audio, visual, and linguistic elements) are associated with the ephemerality of nonsuicidal self-injury information on TikTok?_
<br/>
<br/>
**Analysis:** Chi-Square
<br/>
**Script:** step4.03.Rmd
<br/>
<br/>
**Description:** To examine the relationship between specific content characteristics and ephemerality, we conducted a series of chi-square tests of independence (Table 6). For each variable, we constructed 2x2 contingency tables comparing the frequency of the characteristic across ephemeral and non-ephemeral videos. We calculated Chi-square statistics and associated p-values to assess whether observed distributions differed significantly from what would be expected by chance. We also computed descriptive frequencies (counts and percentages) of each characteristic within both groups to contextualize the statistical results.
<br/>
<br/>
**Analysis:** Stepwise logistic regression
<br/>
**Script:** step4.03.Rmd
<br/>
<br/>
**Description:** Following the Chi-square tests, we conducted a stepwise logistic regression analysis (Table 7) to identify which content characteristics were most strongly associated with ephemerality.  The dependent variable was ephemerality, while independent variables included binary indicators of specific content characteristics derived from our codebook. We used a bidirectional stepwise selection procedure based on Akaike Information Criterion (AIC) to iteratively add or remove predictors, optimizing model fit. The final model included only those variables that contributed significantly to explaining variation in ephemerality. For each retained predictor, we reported estimated coefficients, standard errors, z-values, p-values, odds ratios, and 95% confidence intervals.
<br/>
<br/>
## Step 5: Association between Key Content Characteristics and Probability of Ephemerality while Factoring in User Engagement _(to determine if user engagement is a confounding variable)_
_**RQ 1.1** What content characteristics (i.e., a video's user engagement metrics and audio, visual, and linguistic elements) are associated with the ephemerality of nonsuicidal self-injury information on TikTok?_
<br/>
<br/>
**Analysis:** Stepwise logistic regression
<br/>
**Script:** step5.02.Rmd
<br/>
<br/>
**Description:** To evaluate whether user engagement confounded the relationship between content characteristics and ephemerality, we conducted a stepwise logistic regression that included both sets of predictors. We entered content characteristics that we found to be significantly associated with ephemerality in previous analyses into the stepwise logistic regression model alongside four user engagement metrics: views, likes, comments, and shares. Using Akaike Information Criterion (AIC), the stepwise procedure iteratively selected the combination of predictors that best explained the outcome while minimizing model complexity. This approach allowed us to assess whether the associations between content characteristics and ephemerality persisted after adjusting for user engagement levels.


## Step 6: Association between Interactions of Content Characteristics and Probability of Ephemerality _(to determine if content characteristics operate independently or synergistically)_
_**RQ 1.1** What content characteristics (i.e., a video's user engagement metrics and audio, visual, and linguistic elements) are associated with the ephemerality of nonsuicidal self-injury information on TikTok?_
<br/>
<br/>
**Analysis:** Stepwise logistic regression
<br/>
**Script:** step6.01.Rmd 
<br/>
<br/>
**Description:** To assess whether content characteristics operated independently or synergistically in predicting ephemerality, a stepwise logistic regression was conducted that included all two-way interactions between seven key (child) content codes identified in earlier models. The model began with all main effects and interaction terms and used Akaike Information Criterion (AIC) to iteratively remove non-contributing variables. This approach allowed for the identification of not only direct associations but also whether specific combinations of content features increased or decreased the probability of a video becoming ephemeral.

## Step 7: Association between User Profile Characteristics and Probability of Ephemerality
_**RQ 1.2.** What user profile characteristics (i.e., total number of videos, total number of likes across videos, total number of followers, total number of accounts followed, and verification status) are associated with the ephemerality of nonsuicidal self-injury information on TikTok?_
<br/>
<br/>
**Analysis:** Stepwise logistic regression
<br/>
**Script:** step7.01.Rmd
<br/>
<br/>
**Description:** To determine whether user profile characteristics were associated with the probability of ephemerality, a stepwise logistic regression was conducted. Predictor variables included total likes, total video count, follower count, following count, and verification status. Due to skewed distributions, all count-based variables were log-transformed prior to modeling. Verification status was excluded during model selection, and the final model retained four log-transformed user profile predictors.
