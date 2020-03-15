# covid19_python_notebook
+ Jupyter Notebook to visualize covid19 stats and make predictions by yourself
+ Pulls data from https://github.com/CSSEGISandData/COVID-19/tree/master/archived_data from John Hopkins University
+ Allows to select the country and visualize counts, log, derivative and log derivative for the confirmed cases, deaths and recovery
+ Makes predictions based on a best fit to exponential function 
+ Make work_dir setup to something suitable. It is setup to r'c:\tmp' in the notebook 

Note: Predictions make sense only if the underlying behavior does not change. If new policies are introduced than predictions will be an overestimates. Predictions are based on the best fit of $\exp(\alpha t)$ to the data corresponding to the 7 (configurable) previous days
