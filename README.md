# Problem Statement:
* Create a dashboard to do a comparative study on various parameters of different countries using the sample insurance dataset and world development indicators dataset

* Primary Dataset – Insurance Sample Dataset
* Secondary Dataset – Global Financial Development Database

## Tools Used:
* Tableau

## Dashboard Description

The dashboard is equiped with the following:

* A geographic map showing countries field. The map is coloured on the basis of Income from the secondary dataset.
* The dashboard has a **filter** of income group.
* The dashboard includes a webpage to show data from world bank webpage driven by a URL **action** from geography graph. The country names in the map will act as the trigger  https://data.worldbank.org/country/<country>?view=chart
* The dashboard has a KPI Table to show the comparison between the selected period and the prior period to the selected one.
* The dashboard has 2 **parameters** for Year Selection and Category Selection.
* The Category Parameter  has options of Life Insurance Share, Market Share, Penetration, Ratio of Reinsurance Accepted & Retention Ratio
* The dashboard consists of a **calculated field** to calculate the Growth %.
* The **title** of the KPI table updates based on the category selection
* The dashboards has Create Growth Indicator Shapes based on the Growth %. Growth indicator to display Negative, No Change and Positive as values and corresponding shapes against it.
* The dashboard has a trend line which shows the selected category values. 
* The dashboard filter for income group applies to all charts with the filter action enabled in the map as well.


 
