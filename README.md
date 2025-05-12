# Survival Prediction of Lung Cancer Patients Based on Different Feature Selection Methods Using DeepSurv Models
Although many studies have been conducted on survival prediction, most of them have focused on the diversity of models, and few have compared the performance using various feature selection techniques.
In this study, we aimed to predict the survival rate of lung cancer patients by applying various feature selection methods, including a variance-based univariate method, specific gene selection, KEGG pathway-based selection, and the Cascaded Wx algorithm.
We then compared their impact on the model's predictive performance.
Based on the experimental results, we found that when the goal is to achieve stable performance across diverse datasets rather than the highest accuracy on a specific dataset, it is preferable to use generalized feature selection methods such as the variance-based approach or the Cascaded Wx algorithm.

## The cancer dataset used
- LUAD - Lung Adenocarcinoma
- LUSC - Lung Squamous Cell Carcinoma

## Feature selection
- Variance-based univariate selection
- Specific gene selection
- KEGG pathway selection - small cell lung cancer
- KEGG pathway selection - cancer
- KEGG pathway selection - wnt signaling
- Cascaded Wx
