# ppmi-preprocess
The project is about how to preprocess the raw Parkinson's Progression Markers Initiative (PPMI) clinical data. The tables can be categorized as demographics, motor, non-motor, biospecimen, neuroimaging, and medication features. Due to the required permissions of the Michael J. Fox Foundation (MJFF), we are not going to provide the [data](http://www.ppmi-info.org/). Our aim is to make the preprocess easier.

The project currently includes file reading, feature concatenation, and imputation. The generated ".pkl" files includes sequential features for each patient and her/his associated labels (PD or control, Hoehn & Yahr stage, or cognitive impairment scale). The things you only need to do is to copy the corresponding ".csv" files into the folder "data" according to the "filename" lists under the folders.
