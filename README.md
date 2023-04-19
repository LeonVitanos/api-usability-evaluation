# Evaluating API Usability using Complexity Metrics

Based on the research model presented in the notebook, our main research objective in this study was to focus on design complexity metrics for evaluating API usability, as they have been found to have a positive correlation. We conducted analysis on six APIs using srcML, cloc, and various Python modules. The three metrics chosen for our study were operation argument complexity, interface size, and interaction level, which were used with the k-means algorithm to group the APIs into two clusters, differentiating between low and high complexity APIs.

There are several potential directions for extending this research study. Firstly, other design metrics proposed in literature could be compared to the three design complexity metrics studied in this research to evaluate their effectiveness in assessing API usability. These new metrics could also take into account the object-oriented paradigm to enhance the approach. Secondly, we could continue expanding our API database by investigating additional APIs for a more comprehensive analysis. Lastly, we could consider analyzing only the classes that are necessary to implement a particular service within an API, rather than the entire API, as this would indicate ease of use. To achieve this, code research engines could be employed to identify methods of API usage and evaluate only those methods in terms of API complexity.

These potential research directions could further enhance the findings and contribute to a more comprehensive understanding of API usability evaluation using design complexity metrics.

![alt text](https://github.com/LeonVitanos/api_complexity/blob/master/images/plot.png?raw=true)
