# Empirical Model for Categorical Athletic Expenditures on NCAA Men’s Basketball
Jason Guo, Michael Oh-Yang, Matthew Sherman, Jiale Zheng \
Georgia Institute of Technology, College of Computing \
CS 4641 Machine Learning \
Dr. Mahdi Roozbahani
<br />

## Introduction
It’s easy to throw money at a problem, but where should you invest it to maximize the likelihood of winning a national championship? To answer this question, we analyzed two large datasets to discover correlation(s) between NCAA Men’s Basketball game performance and the amount each university allocates into specific athletic expenditures. A prior study examined the “impact of athletic expenditure on athletic performance” among NCAA Division I Institutions (Beaudin, 2017). With expenses increasing annually, it’s more important now, than ever, for universities to best distribute athletic funding to best improve performance. Essentially, there exists a positive feedback loop of “spending leads to athletic success which in turn leads to institutional benefits” (Suggs, 2003).

## Problem
Division I universities invest millions each year into their men’s basketball teams, with spending ranging from updating facilities to bidding for athletes with scholarships. Annual athletic expenditures are created to maximize the likelihood of winning a national championship, but there’s no definite answer as to where investments will make the largest impact. Through understanding the relationship between expenditure categories and team performance, we can better inform teams on where to best invest their money to have the greatest return on investment.

## Methods
We will use unsupervised learning methods, specifically clustering, in order to discover significant trends in our data. We will categorize and filter the datasets and for look core features that we believe are categories for classification. We can utilize K-mean clustering (or GMM) for categorization in the datasets and then plot the datas on the graph to visualize the distribution.  We will analyze the aggregated data and find meaningful information to validate against ground truth.
Additionally, we will use supervised learning in order to develop predictive tools that map expenditure to athletic performance. We expect to use 80% of the data for training purposes and 20% for testing purposes. 


## Potential Results
Our results will consist of a statistical analysis of the correlation between financial factors we’ve identified and indicators of athletic performance in our data. In addition, our results will include a predictive model for this relationship. The goal of the analysis from the aggregated results is to inform universities of future athletic expenditure.

## References 
- Beaudin, L. (2017, April 20). Examining the relationship between athletic program expenditures. Sage Journals - Journal of Sport Economics. Retrieved February 21, 2022, from https://journals.sagepub.com/doi/full/10.1177/1527002517702423 
- Humphrey, B. (2006). Financing Intercollegiate Athletics: The Role of Monitoring and Enforcing NCAA Recruiting Regulations. International Journal of Sport Finance. Retrieved February 21, 2022, from http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.606.5182&amp;rep=rep1&amp;type=pdf 
- Suggs, W. (2003, May 2). Sports as the University’s ‘Front Porch’? The Public Is Skeptical. The Chronicle of Higher Education. Retrieved February 21, 2022, from https://www.chronicle.com/article/sports-as-the-universitys-front-porch-the-public-is-skeptical/ 




