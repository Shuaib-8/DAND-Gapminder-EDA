### Date created for project and README Files
Created the project file on: ```27/06/19```
<br>
created the README file on: ```17/07/19```

### Project Title
**Investigate a dataset: Gapminder**

### Description
I used python's data analysis libraries (pandas; numpy; matplotlib) to analyse the Gapminder data set which contains economic and development indicators for which I communicated my findings around.
Going through the data analysis process gave me insight into the data wrangling, cleaning and visualisation stages.
I utilised my analysis entirely around descriptive rather than inferential statistics.

#### Datasets
I choose datasets that expressed the following indicators (latest up to 2017):
* `GDP per capita (income_pc)` - dependent variable
* `Life expectancy (life_exp)` - independent variable
* `Exports (% of GDP)` - independent variable
* `Investment (% of GDP)` - independent variable

Before any cleaning, they arrived in this format:

Country | Year 1 | Year 2 | Year 3 | .... |
------------ | ------------- | ------------- | ------------- | ---------
country 1| indicator value* | * | * | ....

The years studied in this Exploratory Data Analysis (EDA) were 1960-2017.

After cleaning - the final outcome made this dataset functional for EDA and viewing:

Country | Year | income_pc | life_exp | export | investment
------------ | ------------- | ------------- | ------------- | ------------| ------------ |
country 1| year 1 | income_pc value | life_exp value | export value| investment value

#### Case studies and findings
I chose to find trends for countries categorised under the **BRIC** - regarded among the fastest-growing emerging economies in recent times:
- Brazil
- China
- India

*Questions*:

**Q1** Have certain regions of the world been growing in terms of income per capita better than others? - cases of Brazil, China and India

> Mainly capturing the countries that grew the fastest in the sample, also uncovering the distribution of income (percentiles) in each case, utilising line plots, bar charts, box plots and histograms

**Q2** Are there trends that can be observed between the selected metrics? - cases of Brazil, China and India

> Finding associated trends between the selected variables for each country using correlation heatmaps and scatterplots.

### Files used

If you want to see the original files from Gapminder, they can be accessed under ```List of indicators in Gapminder Tools (✅data currently used)```:

[Gapminder](https://www.gapminder.org/data/) - {.csv or .xlsx format}

### References

Beyond my Udacity mentor, peers and lectures, I consulted a number of resources including:

* [DataCamp](https://www.datacamp.com/courses/cleaning-data-in-python) - Cleaning Data in Python
* [Youtube - Data School](https://www.youtube.com/user/dataschool)
* [McKinney (2017)](https://www.oreilly.com/library/view/python-for-data/9781491957653/) - chapters 7 (Data Cleaning and Preparation) and 8 (Data Wrangling: Join, Combine, Reshape)
* [stackoverflow](https://stackoverflow.com/)
