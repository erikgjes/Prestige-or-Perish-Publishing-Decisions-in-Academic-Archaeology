# Introduction

This markdown document presents the R code for the analysis of responses from the Publication Decisions in Archaeology (PDIA) survey of carried out by Drs. Jess Beck, Erik Gjesfjeld, and Stephen Chrisomalis. The data presented here was derived from a survey that was taken by respondents through the Qualtrics platform with details provided in the manuscript and supplemental information.

# Data Sources

The analysis preformed in this research is broadly comprised of six sources of data. These include:

1. Demographic information for each respondent (PDIA_Cleaned.csv)
2. List of Journal names given by each respondent (PDIA_Cleaned.csv)
3. Ranking of prestige factors given by each respondent (PDIA_Cleaned.csv)
4. Comments provided by respondents (PDIA_Comments.csv)
5. Scientific journal rankings (SJRs) as listed by Scimago (Journals_SJR_Ulrichs.csv)
6. Additional Journal metadata as provided Ulrich's database (Journals_SJR_Ulrichs.csv)


# Data cleaning

Data used in this work was initially cleaned by Dr. J. Beck and provided with further cleaning was performed by Dr. E. Gjesfjeld. The cleaning process broadly included the following:  
 - Removal of timestamp information for respondents  
 -  Standardization of journal names (i.e. removing journal abbreviations) to coincide with Ulrich's journal names  
 -  Summarizing comments  

# Data Analysis

The organization and analysis of the data is performed using R and these related packages, which can be loaded into your R environment using the following. (Note: For beginning R users, these packages must first be installed using the install.packages() function) As a note, a majority of the code presented uses "tidy" syntax and commands. If users are not familiar with the tidyverse (Wickham et al. 2019), please see the many great online tutorials and cheat sheets.   
