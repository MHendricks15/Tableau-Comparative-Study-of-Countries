# Tableau-Comparative-Study-of-Countries
Project Tableau Dashboard [Tableau Public Link](https://public.tableau.com/app/profile/marcus.hendricks/viz/ComparativeStudyofCountriesbyMarcusHendricks/ComparativeStudyofCountries?publish=yes)

# Project Description
  * Created a dashboard to compare parameters such as income, life insurance share, market share, penetration, ratio of reinsurance accepted, and retention ratio for different countries, to strategize market penetration and to target new customers.

# Process
Primary Dataset – Insurance Sample Dataset

Secondary Dataset – Global Financial Development Database

  * Created a geographic map showing the countries' fields. Colored the map based on the income column from the secondary dataset

    * Included income group filter in the dashboard.
  * Included a webpage to show data from the wikipedia website driven by an URL action from the geography graph

    * The country names in the map acts as the trigger
  * Created a KPI Table to show the comparison between the selected period and the period prior to the selected one

    * Created two parameters for Year Selection and Category Selection

    * Category parameter includes life insurance share, market share, penetration, ratio of reinsurance accepted, and retention ratio

    * Created a calculated field to calculate the Growth %

    * Created a table to show these values

    * Title updates based on the category selection

  * Created Growth Indicator Shapes based on the Growth %

    * Growth indicator displays Negative, No Change, and Positive as values and corresponding shapes against it
  * Created a trend line to show the selected category values

    * The line shows a rhombus at the last mark
  * Created a dashboard filter for income group to be applied for all charts with the filter action enabled in the map as well
