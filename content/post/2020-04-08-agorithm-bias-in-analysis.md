---
title: Agorithm Bias in Analysis
author: 'Bryan '
date: '2019-02-03'
slug: agorithm-bias-in-analysis
categories:
  - Statistical Methods
tags:
  - Bias
---

&nbsp;&nbsp;&nbsp;&nbsp;The term "bias" concerning an analysis of population data concerning machine learning and predictive analytic algorithms can result in bias, and that would be a bit more in-depth for this discussion. According to Bruce and Bruce (2017), the bias seen in statistical measurement or sampling errors is likely due to the process of measurement and sampling methods. Bias may be observable or invisible and detected by referencing or benchmarking values. The authors say the algorithm has been misspecified or a critical variable(s) left out (p. 47). Delgado-Rodriquez & Llorca (2004) surmise bias as the "lack of internal validity" or an improper analysis of the relationship between one thing and the outcome in a data population in which the estimated or proposed statistic that does not equal the actual value. The Delgado-Rodriquez & Llorca also mention categorization of the biases by the stage of research the bias occurs. "The most important biases are those produced in the definition and selection of the study population" (p.635). The important take away is distinguishing biases from random error or lack of precision. 

&nbsp;&nbsp;&nbsp;&nbsp;Goldstone & Partan (2018) learned about an example in healthcare data where Asian patients, in a study, produced a higher error rate indicating high bias or discrimination of that population. Chen, the data scientist in the research, was aware of the "discrimination" and looked into it further and discovered that Asians were only three percent of the total data. The white population was much higher at sixty percent of the population (biased). The algorithm indicated that the Asian patients were not at risk of death, and the hospital did not need to allocate resources to that population. In reality, there could have been Asians with a high risk of death and ended up dying because the hospital's algorithm didn't indicate a need to increase resources in that area (Goldstone & Partan, 2018).  

&nbsp;&nbsp;&nbsp;&nbsp;Chen, Johansson, & Sontag (2018) performed a study and found machine learning algorithms used in healthcare create concerns of fairness and bias. The authors say there is a "balance between fairness and accuracy" (p. 1), and there is a give and take between fairness and accuracy, which can lead to prediction errors and adverse outcomes. The paradox is the algorithms intended to increase algorithm accuracy and to remove human bias; however, the authors discovered data quality and model selection could produce unintended bias (Chen, Johansson, & Sontag, 2018). The authors stress accuracy can be lacking when taking insufficient or skewed sample data, given a set of specific variables available. Chen, Johansson, & Sontag found in their study that gathering more samples in the data will improve fairness, and there are other ways to reduce discrimination without losing accuracy in the models (2018).  


Bruce, A., Bruce, P.(2017). Practical statistics for data scientists – 50 essential concepts. (3rd ed.). Sebastopol, CA: O’Reilly Media. (46-47).

Chen, I., Johansson, F., & Sontag, D. (2018). Why is my classifier discriminatory? (1-18). Retrieved from: https://arxiv.org/pdf/1805.12002.pdf

Delgado-Rodríguez, M., & Llorca, J. (2004). Bias. Journal of Epidemiology and Community Health, 58(8), (635-641). https://doi: 10.1136/jech.2003.008466
