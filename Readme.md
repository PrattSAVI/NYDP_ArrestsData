### Filtering & Visualizing NYPD historic arrests data
Notebook creates a very simple dashboard using Altair library in [Jupyter Notebook](https://github.com/PrattSAVI/NYDP_ArrestsData/blob/master/NYPD%20Historic%20Arrests%20Data%20Dashboard.ipynb).

Dashboard filters and visualizes data based on Location, Etnicity, Age, Weekday and Arrest Description. Selection filters currently work left to right. 


Original Data can be accessed through [Open Data NYC](https://data.cityofnewyork.us/Public-Safety/NYPD-Arrests-Data-Historic-/8h9b-rp9u)  
I will add accesing the up-to-date data programatically through Socrata at some point.

Tools Required:
* Jupyter Notebook (notebook in the repo)
* Pandas
* Altair

Dashboard can be viewed [here](https://prattsavi.github.io/NYDP_ArrestsData/)

Altair is not the best library for creating geographic plots, that is why the code utilizes the scatter plot function. Not the best practice.
