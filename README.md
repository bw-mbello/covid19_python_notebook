# covid19_python_notebook

## covid19_update_global.ipynb
+ after 2020-03-23 presents the data countries only. Stats for states and counties are not available

## SIR Model_simplified.ipynb
+ A notebook with some theoretical background on use of the exponential function for data fitting

Note: Predictions make sense only if the underlying behavior does not change. If new policies are introduced than predictions will be an overestimates. Predictions are based on the best fit of $\exp(\alpha t)$ to the data corresponding to n (configurable) previous days

## covid19_update.ipynb - deprecated 2020-03-23 because of the data format change by the data source (no recovered stats, no counties)
+  is a Jupyter Notebook to visualize covid19 stats and make predictions by yourself
+ Pulls data from https://github.com/CSSEGISandData/COVID-19/tree/master/archived_data from John Hopkins University
+ Allows to select the country and visualize counts, log, derivative and log derivative for the confirmed cases, deaths and recovery
+ Makes predictions based on a best fit to exponential function 
+ Make work_dir setup to something suitable. It is setup to r'c:\tmp' in the notebook 


