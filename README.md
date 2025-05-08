# Dissertation Quantitative Data Analysis

## Step 1: Association between User Engagement and Probability of Ephemerality 
_**RQ 1.1** What content characteristics (i.e., a video's user engagement metrics and audio, visual, and linguistic elements) are associated with the ephemerality of nonsuicidal self-injury information on TikTok?_
<br/>
<br/> 
**Analysis:** Stepwise logistic regression
<br/>
**Script:** step1.01.Rmd
<br/>
<br/>
**Description:** To determine whether user engagement metrics were associated with the probability of ephemerality of NSSI content on TikTok, a stepwise logistic regression was conducted using view count, like count, comment count, and share count as predictors of ephemerality. 

## Step 2: Compare User Engagement between Ephemeral and Non-Ephemeral Content
_**RQ 1.1** What content characteristics (i.e., a video's user engagement metrics and audio, visual, and linguistic elements) are associated with the ephemerality of nonsuicidal self-injury information on TikTok?_
<br/>
<br/>
**Analysis:** Mann-Whitney U
<br/>
**Script:** step2.01.Rmd
<br/>
<br/>
**Description:** To compare user engagement between ephemeral and non-ephemeral NSSI content, a Mann-Whitney U test was conducted for four user engagement metrics: view count, like count, comment count, and share count. To account for multiple comparisons, a Bonferroni correction was applied to adjust the significance threshold.
 

## Step 3: Characterize Content Characteristics of Ephemeral and Non-Ephemeral Content
_**RQ 1.1** What content characteristics (i.e., a video's user engagement metrics and audio, visual, and linguistic elements) are associated with the ephemerality of nonsuicidal self-injury information on TikTok?_
<br/>
<br/>
**Analysis:** Content analysis
<br/>
<br/>
**Description:** A content analysis of both ephemeral and non-ephemeral videos was conducted to characterize the content characteristics (i.e., a video’s user engagement metrics and audio, visual, and linguistic elements) of each. Analysis resulted in six high-level categories: addiction language, algospeak, signaling, visible scars, explicit NSSI language, and the presence of trigger warnings. A total of 24 child codes was organized under these categories: three for addiction language, six for algospeak, four for explicit language, four for visible scars, and seven for signaling. Each characteristic was coded as present (1) or absent (0) in Excel.


## Step 4: Association between Content Characteristics and Probability of Ephemerality
_**RQ 1.1** What content characteristics (i.e., a video's user engagement metrics and audio, visual, and linguistic elements) are associated with the ephemerality of nonsuicidal self-injury information on TikTok?_
<br/>
<br/>
**Analysis:** Stepwise logistic regression
<br/>
**Script:** step4.01.Rmd
<br/>
<br/>
**Description:** A stepwise logistic regression was conducted to examine whether the presence of six high-level content characteristics (i.e., addiction language, algospeak, signaling, visible scars, explicit NSSI language, and trigger warnings) were associated with the probability that NSSI content would become ephemeral. The stepwise procedure used Akaike Information Criterion (AIC) to iteratively remove variables that did not improve model fit.
<br/>
<br/>
_Note: Double check this analysis - Shouldn't the results be inversed?_
<br/>
<br/>
**Analysis:** Stepwise logistic regression
<br/>
**Script:** step4.02.Rmd
<br/>
<br/>
**Description:** To determine whether specific content elements were associated with the probability NSSI content becoming ephemeral, a stepwise logistic regression was conducted using 24 child content characteristics as predictors. The dependent variable was ephemerality. The model selection process used Akaike Information Criterion (AIC) to iteratively retain predictors that improved model fit.
<br/>
<br/>
_Note: Double check this analysis - Some of the results seem like they should be inversed._


## Step 5: Association between Key Content Characteristics and Probability of Ephemerality while Factoring in User Engagement _(to determine if user engagement is a confounding variable)_
_**RQ 1.1** What content characteristics (i.e., a video's user engagement metrics and audio, visual, and linguistic elements) are associated with the ephemerality of nonsuicidal self-injury information on TikTok?_
<br/>
<br/>
**Analysis:** Stepwise logistic regression
<br/>
**Script:** step5.01.Rmd
<br/>
<br/>
**Description:** To assess whether user engagement confounded the relationship between content characteristics and video ephemerality, a stepwise logistic regression was conducted using seven content-related predictors alongside four user engagement metrics (i.e., view count, like count, comment count, and share count). The model selection process used Akaike Information Criterion (AIC) to iteratively retain only the predictors that improved model fit, allowing for an assessment of whether the previously observed content-based associations with ephemerality remained significant when user engagement was taken into account.

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
### Stepwise Logistic Regression
Script: 
