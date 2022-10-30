# Workflow

## Topic Selection

- Search for articles and databases of interest
- Find articles with common research directions

## Extraction

- Extract data from the article
- Analyze the information and content of the article

## Modeling

- Install the required libraries

- Import all data into rstudio
- Calculate the SD\mean\N of the data
- Unify all data in one format and combine them in one dataset
- Calculate effect sizes using the dataset
- Analyze models using fixed effects and random effects meta-analysis
- Calculate heterogeneity, confidence intervals
- Make funnel plots, forest plots, time lag plots
- Calculate annual fixed-effects meta-analysis models
- Calculate inverted sample variance meta-regression analysis model

## Analysis

- Discuss potential publication bias
- Discuss the causes and effects of publication bias





# Meta-data

The data used are a total of 92 meta-analysis articles consisting of data on the control effects of seawater acidification on the activity values of different fish species.



# File structure

文件结构可以从data文件夹中的（meta-data_ocean_meta.csv）文件看到，如下表所示。

| **Column heading**                           | **Description**                                              |
| -------------------------------------------- | ------------------------------------------------------------ |
| **Study**                                    | Code for each individual study                               |
| **Authors**                                  | Authors of each paper                                        |
| **Year (online)**                            | Year the final paper was made available online               |
| **Year (print)**                             | Year the final paper was included in a journal volume/issue  |
| **Title**                                    | Title of each paper                                          |
| **Journal**                                  | Journal the paper was published in                           |
| **Pub year IF**                              | The journal impact factor for the year the paper was published; obtained from InCites Journal Citation Reports |
| **2017 IF**                                  | The journal impact factor for 2017 (i.e., most recent journal impact factor); obtained from InCites Journal Citation Reports |
| **Average n**                                | Average sample size for the study; average of indiviudal sample sizes for the contol and experimental groups |
| **Effect type**                              | The type of effect concluded by the study regarding the effect of OA on behaviour; strong, weak, or no effect (see Supplementary Methods for details) |
| **Species**                                  | The species used in each individual experiment               |
| **Climate (FishBase)**                       | Climatic region for each species; obtained from FishBase     |
| **Env cue/stimulus?**                        | Whether or not the experiment included a cue or stimulus in the experiment (olfactory, visual, auditory, or physical) |
| **Cue/stimulus type**                        | The type of cue or stimulus used                             |
| **Behavioural metric**                       | The specific measure of behaviour tested                     |
| **Life stage**                               | Life stage of the fish tested                                |
| **ctrl.n**                                   | Sample size of the control group                             |
| **ctrl.mean**                                | Mean of the control group                                    |
| **ctrl.var**                                 | Measured variance of the control group                       |
| **ctrl.vartype**                             | The metric of variance used for the control group (standared deviation, standard error, 95% confidence interval, or inter-quartile range |
| **ctrl.sd**                                  | The standard deviation of the control group, calculated from ctrl.vartype |
| **oa.n**                                     | Sample size of the experimental group                        |
| **oa.mean**                                  | Mean of the experimental group                               |
| **oa.var**                                   | Measured variance of the experimental group                  |
| **oa.vartype**                               | The metric of variance used for the experimental group (standared deviation, standard error, 95% confidence interval, or inter-quartile range |
| **oa.sd**                                    | The standard deviation of the experimental group, calculated from ctrl.vartype |
| **lnRR**                                     | Raw effect size (natural log transformed response ratio)     |
| **\|lnRR\|**                                 | Absolute effect size (natural log transformed response ratio) |
| **Weighted mean \|lnRR\|**                   | The mean effect size for each study computed as the average of \|lnRR\| measurements for a given study |
| **Notes**                                    | General notes regarding the nature of the data; includes rationale for omissions and other alterations to the data |
| **JS check**                                 | Data checked by Josefin Sundin; X = yes                      |
| **JCC final check**                          | Data final checked by Jeff Clements; X = yes                 |
| **Precise sample size description in text?** | Whether or not the study adequately described sample sizes in the text of the paper |
| **Sample size source**                       | How the sample size for each group in each study was derived |
