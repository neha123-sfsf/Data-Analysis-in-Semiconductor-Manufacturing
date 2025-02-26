# Data-Analysis-in-Semiconductor-Manufacturing
In this study we propose machine learning techniques to automatically generate an accurate predictive model to predict equipment faults.
Data Analysis in Semiconductor Manufacturing
Semiconductor manufacturing is one of the most technologically and highly complicated manufacturing processes. Traditional machine learning algorithms such as uni-variate and multivariate analyses have long been deployed as a tool for creating predictive model to detect faults. In the past decade major collaborative research projects have been undertaken between fab industries and academia in the areas of predictive modeling. In this study we propose machine learning techniques to automatically generate an accurate predictive model to predict equipment faults during the wafer fabrication process of the semiconductor industries. Aim at constructing a decision model to help detecting as quickly as possible any equipment faults in order to maintain high process yields in manufacturing.

Data Set Information:
A complex modern semi-conductor manufacturing process is normally under consistent surveillance via the monitoring of signals/variables collected from sensors and or process measurement points. However, not all of these signals are equally valuable in a specific monitoring system. The measured signals contain a combination of useful information, irrelevant information as well as noise. It is often the case that useful information is buried in the latter two. Engineers typically have a much larger number of signals than are actually required. If we consider each type of signal as a feature, then feature selection may be applied to identify the most relevant signals. The Process Engineers may then use these signals to determine key factors contributing to yield excursions downstream in the process. This will enable an increase in process throughput, decreased time to learning and reduce the per unit production costs.

To enhance current business improvement techniques the application of feature selection as an intelligent systems technique is being investigated.

The dataset presented in this case represents a selection of such features where each example represents a single production entity with associated measured features and the labels represent a simple pass/fail yield for in house line testing, figure 2, and associated date time stamp. Where –1 corresponds to a pass and 1 corresponds to a fail and the data time stamp is for that specific test point.

Using feature selection techniques it is desired to rank features according to their impact on the overall yield for the product, causal relationships may also be considered with a view to identifying the key features.

Results may be submitted in terms of feature relevance for predictability using error rates as our evaluation metrics. It is suggested that cross validation be applied to generate these results. Some baseline results are shown below for basic feature selection techniques using a simple kernel ridge classifier and 10 fold cross validation.

Baseline Results: Pre-processing objects were applied to the dataset simply to standardize the data and remove the constant features and then a number of different feature selection objects selecting 40 highest ranked features were applied with a simple classifier to achieve some initial results. 10 fold cross validation was used and the balanced error rate (*BER) generated as our initial performance metric to help investigate this dataset.

SECOM Dataset: 1567 examples 591 features, 104 fails
