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

### Article 2: Crowd-sourcing the smart city: Using big geosocial media metrics in urban governance.
**Major argument:**
- In the field of computer ethics, it is very common to encounter policy vacuums due to the constant advancement of computer technology. Therefore, it is important to establish protocols for formulating policies to guide actions.
- Core principles of research ethics: minimizing harm (including physical harm, psychological distress, social and reputational disadvantages), obtaining informed consent, and protecting subject privacy and confidentiality.
- Definetion of private information: First, it is that which subjects reasonably expect is not normally monitored or collected. Second, it is that which subjects reasonably expect is not normally publicly available. When research potentially includes the collection of private information, ethics requires the development of protocols with sufficient safeguards to protect subject privacy and maintain confidentiality of research data.
- In today's academic environment, it is rather easy to obtain large data sets, often outside any institutional supervision or authority. However, there is a deficiency regarding teaching research ethics to students and researchers across disciplines, and especially in the domain of big data research, students from this field are not exposed to rigorous training on research ethics.
  
**Reflection on the project environment and future:**
- When acquiring research data, it is important to know what are the regulations and management protocols. Researchers should be aware of the potential harm that data misconduct can cause. It is crucial to deal with data responsibly and ethically.
- Our dataset about traffic, although highly anonymized, requires careful handling. We should only store limited attributes that are highly relevant to our research. Extensive operations on irrelevant parts of the dataset should be avoided to maintain data integrity and privacy.
- As science students, we must learn more about privacy and research ethics. It is important to communicate the significance of handling data responsibly with fellow students. If we do not raise our awareness of these issues, the consequences could be detrimental, influencing not only the academic environment but also all components of human society.
  
### Article 3: The dynamics of big data and human rights: The case of scientific research.
**Major argument:**

**Reflection on the project environment and future:**

## Conclusion and discussion
As a nature sciences major, ethics and data privacy could be distant for me at first, but after finishing this learning goal by reading relevant articles and intertwining it with our group project, I realize how important it is to educate myself with knowledge in this field. It can not only make me a scientist that is good in research, but also a scientist that is more responsible and can actively think about the consequences of the research results.

After this course, I also came to realize the ethics and privacy issues are everywhere in the academic world, and it made me think about what is the ultimate goal of doing research. As students in an ivory tower, it is very easy for us to lose the view of the complete picture after digging in a specific field for a long time. Therefore, this learning process made me realize the original goal of research is to make the society a better place.

In our group project, a lot of existing issues are also caused by miscommunication between stakeholders and lack of transparency in decision making (nitrogen crisis in the Netherlands). I think by educating more people about how doing research can influence people's lives, the next generation of researchers in the Netherlands will have more social awareness and make good use of their research work.

On the other hand, doing group work in a short timespan also made me realize that technology development can be a two-sided sword. While we as students and researchers would like to use new technology like AI to help us, it is important to see how harmful it could be. In the project setting, using too many tools like AI for coding and text generating could be detrimental for material understanding. Therefore, we should really use it wisely, as the thing that matters is the learning process rather than the results.

## Reference articles (details can be find in folder: /EthicsArticles)
**-Article 1:** Zook, M., Barocas, S., Boyd, D., Crawford, K., Keller, E., Gangadharan, S. P., ... & Pasquale, F. (2017). Ten simple rules for responsible big data research. PLoS computational biology, 13(3), e1005399.

**-Article 2:** Zook, Matthew. "Crowd-sourcing the smart city: Using big geosocial media metrics in urban governance." Big Data & Society 4.1 (2017): 2053951717694384.

**-Article 3:** Vayena, E., & Tasioulas, J. (2016). The dynamics of big data and human rights: The case of scientific research. Philosophical Transactions of the Royal Society A: Mathematical, Physical and Engineering Sciences, 374(2083), 20160129.
