# Trajectory
Trajectory of Recovery after Stroke
The following Rmd (text) files were used to analyse the trajectory of recovery from stroke. The data were obtained from these trials EXTEND-IA, ESCAPE, DEFUSE3. The data are not provided here but can be accessed by contacting the trial principal investigators. In the first part we explored the trajectory between baseline and 24 hours and between 24 hours and day 3 to 5. Plotting of the trajectory was performed using ggplot2 [![here](betaregression.png)](./beta.Rmd). 

In the second part, the role of group based trajectory modeling to cluster the longitudinal trajectory of stroke deificit (NIHSS performed at regular interval). The work flow pipeline is as follow, obtain the data in wide format, convert the data to long format for group based trajectory modeling (akmedoids), return the cluster back to wide format for GLM analysis. The modelings were performed with PredictABEL package to explore discrimination and calibration. 

In the third part we explored the role of genetic algorithm to perform feature selections. The chosen features were used in GLM analysis.     
