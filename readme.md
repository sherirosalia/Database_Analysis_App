## Analysis of surf reports from Hawaii 
### SQLite, SQLAlchemy & Flask

### About
Hawaii surf reports extracted from CSV files using SQLite and, using Python's version of 
SQL "SQLAlchemy" in Pandas, data analyzed.

Localhost deployment of app with Flask provides user interface

### Frameworks
 Python Pandas
 SQLAlchemy
 Flask
 Jupyter Notebooks
 
### File Structure
All csv files in root folder.
Deploy flask app by typing python -m app.py in bash
Jupyter notebook file called "climate_analysis" is the precursor to the flask app.
The file named "refactor_sqlite_analysis" is a notebook duplicating SQLAlchemy scripts with both "regular" Python
and Python Pandas.

### Avg Temp
![Average Temps](../master/resources/trip_avg_temp.png)

### Temperature range
![Temp Range](../master/resources/temp_ranges.png)


### Rain
![Histogram](../master/resources/year_rain.png)

