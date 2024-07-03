# **Replication and Extension of "Anti-Immigrant Rhetoric and ICE Reporting Interest: Evidence from a Large-Scale Study of Web Search Data"**
---
**Overview**
This project aims to replicate and expand upon the findings of the study titled [Anti-Immigrant Rhetoric and ICE Reporting Interest: Evidence from a Large-Scale Study of Web Search Data](https://www.cambridge.org/core/journals/british-journal-of-political-science/article/abs/antiimmigrant-rhetoric-and-ice-reporting-interest-evidence-from-a-largescale-study-of-web-search-data/AF982680AEC49AE65CACFD73352A44AD). The original study utilized Google Trends and Bing search data, in addition to content analysis of cable news transcripts, to investigate the correlation between media cues and public interest in immigration-related topics, specifically focusing on crime, welfare, and reporting across different political periods.

**Extension Ideas:** 
In our extension research, our aim was to investigate the relationship between political events and policies on the significant search trends related to immigration topics. We applied thresholds to identify topics displaying notable wave patterns and conducted regression analyses to assess the statistical significance of selected topics.

**Replication Study and Extension Research Results:**

1.  Setup Instructions:
Install necessary R libraries.
Ensure all required data sources are accessible.

2.  View Results:
Run the file trends.Rmd to see detailed results of the replication study and extension research.
Alternatively, view the results directly through [this link](https://htmlpreview.github.io/?https://github.com/msr-ds3/immigrant-news-2024-group-4/blob/main/trends.html) without running the code

**Data Sources:**
crime.csv contains the original google search data for "immigrant + crime" searches used in the paper
report.csv contains the original google search data for "immigrant + report" searches used in the paper
welfare.csv contains the original google search data for "immigrant + welfare" searches used in the paper
TopicModel.RData contains the topic model used in the original paper
zero_tolerance_policy.csv contains the google search data for zero tolerance policy data used in the extension research
ICEdeportation.csv contains the google search data for ICE deportation data used in the extension research




