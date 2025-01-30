# Goal 4: Social and Privacy Aspects

## Overview
This folder contains materials related to the fourth learning goal, there is a folder (/EthicPosters_Traffic1) containing the ethics poster of Group Traffic 1 (among which I contributed most on the dystopia poster and the reflection poster, I got a lot of inspiration from Article 1: Ten simple rules for responsible big data research), a folder (/EthicsArticles) containing three articles about ethics and data privacy I read for this course, and in the following part of this document, I write down main takeaways from the three articles, as well as lectures and workshops during the course.

## Background
Since I come from a scientific background and completed my Bachelor’s degree in another country, the topics of data privacy and conducting research ethically are relatively new to me. While I have read some articles about these issues in my personal time, I have not yet applied them in an academic setting. Additionally, I am curious about potential underlying issues associated with using public data, which often seems prevalent and harmless at first glance.

## Implementation
- Critical literature review: three academic articles on data ethics, summarize key arguments and insights
- Systematic analysis of ethical considerations
- Reflection on the group project using public traffic data and further professional implications
- Contribute to group poster presentation: Dystopia and reflection part

## Results: Key Ethical Insights from Articles
### Article 1: Ten simple rules for responsible big data research

This article lists some simple principles for data scientists.

**Major argument:**
- The most important thing to remember is that most data represent or impact people. While this is obvious for some datasets, it is less apparent for others. Even seemingly neutral data can lead to social inequities.
- Good intentions by researchers do not necessarily ensure the protection of personal information. Data misuse can occur long after the current research concludes. Therefore, researchers should work to reduce the risk of data reidentification.
- Sharing data is essential for verifying research, but it should be done under specific protocols. Researchers should also proactively consider how to manage data responsibly.
- Acknowledge the flaws in your datasets. To produce meaningful results, data scientists often employ various data cleaning methods. However, these processes can sometimes be perceived as data manipulation. It is crucial to meticulously document the evolution of your data throughout this process and to highlight how these methods might affect the data's credibility.

**Reflection on the project environment and future:**
- In our course project, most of data comes from public accessible datasets. We did not collect any data by ourselves. The datasets also do not include anything personal. (e.g.: vehicle data do not include license numbers nor vehicle color, only length was included.) However, we should be aware that with some other datasets, it is still possible to reveal personal information from these data. Our research results could also leads to shift in government policies that can influence citizens' living environment and health.
- To reduce the risks of reidentification of the data, the processed datasets will be editted to limit any personal information, they will only be stored in the server for 12 months, and people outside of the group can access by request.
- Always document the processes of averaging data, removing outliers, and other modifications within the datasets. Share this information with your team and include it in the final report.

### Article 2: Crowd-Sourcing the Smart City
- Challenges in establishing ethical guidelines for emerging technologies
- Core principles of research ethics
- Defining and protecting private information
- Gaps in ethical training for data researchers

### Article 3: Locating Ethics in Data Science
- Responsibility in global knowledge production
- Accountability in distributed research systems

## Conclusions
### Goal Accomplishment
- Developed comprehensive understanding of data ethics
- Learned protocols for responsible data management
- Identified potential ethical challenges in research

### Technical Conclusions
- Importance of data anonymization
- Need for transparent research practices
- Risks of unintentional personal information exposure

### Personal Development
- Enhanced critical thinking about data ethics
- Improved ability to evaluate research methodologies
- Developed a responsible approach to data science

## Reference articles (details can be find in folder: /EthicsArticles)
**-Article 1:** Zook, M., Barocas, S., Boyd, D., Crawford, K., Keller, E., Gangadharan, S. P., ... & Pasquale, F. (2017). Ten simple rules for responsible big data research. PLoS computational biology, 13(3), e1005399.

**-Article 2:** Zook, Matthew. "Crowd-sourcing the smart city: Using big geosocial media metrics in urban governance." Big Data & Society 4.1 (2017): 2053951717694384.

**-Article 3:** Vayena, E., & Tasioulas, J. (2016). The dynamics of big data and human rights: The case of scientific research. Philosophical Transactions of the Royal Society A: Mathematical, Physical and Engineering Sciences, 374(2083), 20160129.
