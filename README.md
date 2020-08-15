# National Health Examination Survey 2007-2008 

This data was obtained from the following [study](https://www.icpsr.umich.edu/web/ICPSR/studies/25505/datadocumentation). It includes a large set of tables but the ones utilized in this project are included in this repository. 
The goal of the project was to predict one of the survey responses ("Health Status") and use this prediction as a preemptive action tool for medical plan treatment. The health status was recoded to crudely represent Healthy (1) 
and Unhealthy status (0) and a number of machine learning algorithms was applied to achieve applicable results. 

Some of the approcahes taken to achieving the goals of classification incldued: 

1. Imputation with [MICE package](https://cran.r-project.org/web/packages/mice/mice.pdf)  - application of Multivariate Imputation by Chained Equations. 
2. Balancing unbalanced class representation with [ROSE library](https://cran.r-project.org/web/packages/ROSE/ROSE.pdf) to perform random oversampling. 
3. Following classification algorithms were utilized: 

- Logistic Regression 
- Support vector machines 
- Neural Network 
- Rules classification with C5.0



