## Data analysis on seismic data from coal mines

A simple study on the classification of hazard (hazardous or not hazardous) in coal mines using seismic data.

### Data source

Sikora M., Wrobel L.: Application of rule induction algorithms for analysis of data collected by seismic hazard monitoring systems in coal mines. Archives of Mining Sciences, 55(1), 2010, 91-114.

### Run

Please follow the analysis in the notebook.

### Dependencies

Please see the imports in the notebook.

### Analysis

The analysis includes the following:

-   simple EDA to identify data attributes
-   build machine learning model with regularization
-   use ensemble technique to boost the performance

The original dataset contains three classification methods that rely on expert knowledge and seismic theories. A logistic model is built in this analysis and the final classification results are from the votes of the four methods.
