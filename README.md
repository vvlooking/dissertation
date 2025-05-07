# Dissertation Quantitative Data Analysis

## Step 1: Association between User Engagement and Probability of Ephemerality 
_**RQ 1.1** What content characteristics (i.e., a video's user engagement metrics and audio, visual, and linguistic elements) are associated with the moderation of nonsuicidal self-injury information on TikTok?_
<br/>
<br/> 
**Analysis:** Stepwise logistic regression
<br/>
**Script:** step1.01.Rmd
<br/>
<br/>
**Description:** To determine whether user engagement metrics were associated with the probability of ephemerality of NSSI content on TikTok, a stepwise logistic regression was conducted using view count, like count, comment count, and share count as predictors of ephemerality. 

## Step 2: Compare User Engagement between Ephemeral and Non-Ephemeral Content
_**RQ 1.1** What content characteristics (i.e., a video's user engagement metrics and audio, visual, and linguistic elements) are associated with the moderation of nonsuicidal self-injury information on TikTok?_
<br/>
<br/>
**Analysis:** Mann-Whitney U
<br/>
**Script:** step2.01.Rmd
<br/>
<br/>
**Description:** To compare user engagement between ephemeral and non-ephemeral NSSI content, a Mann-Whitney U test was conducted for four user engagement metrics: view count, like count, comment count, and share count. To account for multiple comparisons, a Bonferroni correction was applied to adjust the significance threshold.
 

## Step 3: Characterize Content Characteristics of Ephemeral and Non-Ephemeral Content
_**RQ 1.1** What content characteristics (i.e., a video's user engagement metrics and audio, visual, and linguistic elements) are associated with the moderation of nonsuicidal self-injury information on TikTok?_
<br/>
<br/>
**Analysis:** Content analysis
<br/>
<br/>
**Description:** A content analysis of both ephemeral and non-ephemeral videos was conducted to characterize the content characteristics (i.e., a video’s user engagement metrics and audio, visual, and linguistic elements) of each. Analysis resulted in six high-level categories: addiction language, algospeak, signaling, visible scars, explicit NSSI language, and the presence of trigger warnings. A total of 24 child codes was organized under these categories: three for addiction language, six for algospeak, four for explicit language, four for visible scars, and seven for signaling. Each characteristic was coded as present (1) or absent (0) in Excel.


## Step 4: Association between Content Characteristics and Probability of Ephemerality
_**RQ 1.1** What content characteristics (i.e., a video's user engagement metrics and audio, visual, and linguistic elements) are associated with the moderation of nonsuicidal self-injury information on TikTok?_
<br/>
<br/>
**Analysis:** Stepwise logistic regression
**Script:** step4.01.Rmd
<br/>
<br/>
**Description:** A stepwise logistic regression was conducted to examine whether the presence of six high-level content characteristics (i.e., addiction language, algospeak, signaling, visible scars, explicit NSSI language, and trigger warnings) were associated with the probability that NSSI content would become ephemeral. The stepwise procedure used Akaike Information Criterion (AIC) to iteratively remove variables that did not improve model fit.
<br/>
<br/>
_Note: Double check this analysis - Shouldn't the results be inversed?_


## Step 5: Association between Key Content Characteristics and Probability of Ephemerality while Factoring in User Engagement _(to determine if user engagement is a confounding variable)_
_**RQ 1.1** What content characteristics (i.e., a video's user engagement metrics and audio, visual, and linguistic elements) are associated with the moderation of nonsuicidal self-injury information on TikTok?_
### Stepwise Logistic Regression
Script:

## Step 6: Association between Interactions of Content Characteristics and Probability of Ephemerality _(to determine if content characteristics operate independently or synergistically)_
_**RQ 1.1** What content characteristics (i.e., a video's user engagement metrics and audio, visual, and linguistic elements) are associated with the moderation of nonsuicidal self-injury information on TikTok?_
### Stepwise Logistic Regression
Script: 

## Step 7: Association between User Profile Characteristics and Probability of Ephemerality
_**RQ 1.2.** What user profile characteristics (i.e., total number of videos, total number of likes across videos, total number of followers, total number of accounts followed, and verification status) are associated with the moderation of nonsuicidal self-injury information on TikTok?_
### Stepwise Logistic Regression
Script: 
