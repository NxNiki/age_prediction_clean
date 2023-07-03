# multidimensional_age_prediction

1. run quadratic regression on brain features with age, age^2, sex, age*sex, and age^2*sex
2. run cluster analysis based on the coefficients in the regression model.
3. build the age prediction model for each cluster identified in the previous stage.
4. examine how the predicted age (brain age) and brain age gap (chronological age - brain age) are associated with behavioral performance and disorder

For details, see our publication:

Xin Niu, Alexei Taylor, Russell T Shinohara, John Kounios, Fengqing Zhang, Multidimensional Brain-Age Prediction Reveals Altered Brain Developmental Trajectory in Psychiatric Disorders, Cerebral Cortex, 2022;, bhab530, https://doi.org/10.1093/cercor/bhab530

We run cluster analysis on the coefficients of Huber regression models for each feature. Thus identify four clusters with divergent developmental trajectories.
![image](https://github.com/NxNiki/age_prediction_clean/assets/4017256/7e094992-58e3-45d9-a97d-63df14e3529d)

Then we predict the age using features in each cluster and compared the brain age gap between healthy controls and each disorder group:
![image](https://github.com/NxNiki/age_prediction_clean/assets/4017256/bf17b489-7582-49f5-84ca-a99ab5b8f246)

Our results indicate the brain is composed of systems with divergent developmental trajectories and shows different alteration patterns in psychiatric disorders.

