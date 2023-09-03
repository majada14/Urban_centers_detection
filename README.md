# Urban_centers_detection
The current projectwas developed for the Computational Social Science's course.  
The objective is to detect urban centers inside cities using machine learning algorithms. More specifically, the DBSCAN and the OPTICS models, both clustering techniques, were implemented to identify clusters, and so urban centers, inside the city of Trento.  

It is possible to adapt the current implementation to other cities, changing the following variables:
* city_coordinates in the data_extraction.ipynb
* suggested_radius in the data_extraction.ipynb
* n_districts in the data_analysis_dbscan.ipynb
* n_districts in the data_analysis_optics.ipynb  

## DATA EXTRACTION
In the file data_extraction.ipynb is available the code to retrieve nodes from OpenStreetMap's API.  

## DATA ANALYSIS
In the file data_analysis_dbscan.ipynb is available the code to perform the DBSCAN model on the dataset.
In the file data_analysis_optics.ipynb is available the code to perform the OPTICS model on the dataset.  

## DATA VISUALIZATION
In the file data_visualization.ipynb is available the code to see the visualization of the best results for both algorithms.  

**Note**: since GitHub repositories do not support the display of interactive maps it is suggested to copy the path of the current repository and past it on nbviewer to see all the plots available.
