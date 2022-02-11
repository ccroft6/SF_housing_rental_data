# San Francisco Housing Rental Data
This is an analysis of the housing rental market in San Francisco between 2010-2016. A proptech company wants to offer an instant, one-click service for people to buy properties and then rent them to others. This analysis combines the use of interactive visualizations, aggregation, and geospatial analysis to find properties in the San Francisco market that are viable investment opportunities. 

---
## Technologies
This project uses Jupyter Notebook (within [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/)) and the standard Python 3.8 libraries. In addition, this project requires the following libraries and/or dependencies:

* [Pandas](https://pandas.pydata.org/) - a software library designed for open source data analysis and manipulation
* [Pathlib](https://docs.python.org/3/library/pathlib.html) - a Python module which provides an object API for working with files and directories
* [hvplot](https://hvplot.holoviz.org/) - interactive plotting API that supports panning, zooming, hovering, and clickable/selectable legends
* [geoviews](https://geoviews.org/) - makes it easy to explore and visualize geographical, meteorological, and oceanographic datasets. It is built on the HoloViews library for building flexible visualizations of multidimensional data

---

## Installation Guide
Before running the application, first install the following dependencies:
```
Install Anaconda Package
Pip install Jupyter
conda install -c pyviz hvplot geoviews
```

Verify the installations:
```
conda list hvplot
conda list geoviews
```

---
## Usage
To determine the new housing rental investment options:
1. Clone the repository 
`git clone https://github.com/ccroft6/SF_housing_rental_data.git`
2. Open terminal at this repository location. Activate the environment and launch jupyter lab:

```
conda activate dev
jupyter lab 
```
*Jupyter lab should launch in a web browser. If it doesn't launch, select one of the hyperlinks that it provides, copy it, and paste it into a web browser.* 

---

## Methods
The following steps were completed:
1. Calculate and plot the housing units per year
2. Calculate and plot the average sales prices per square foot
3. Compare the average sale prices by neighborhood
4. Build an interactive neighborhood map

---

## Results
The interactive neighborhood map helps visualize the neighborhoods where the sale price per square foot is low and the gross rent is high. For those who are interested in buying properties and then renting them to others, this map helps identify viable investment opportunities. 

---

## Contributors
Catherine Croft

Email: catherinecroft1014@gmail.com

LinkedIn: [catherine-croft](https://www.linkedin.com/in/catherine-croft-4715481aa/)

---

## License 

MIT