# Web Design Challenge _ Web Visualisation Dashboard

## Introduction
In this challenge a visualosation dashboard of the weather data generatated during the previous Python API Challenge will be created.

In building this dashboard, individual pages for each plot and a means by which allows for navigation between each of them will be created. These pages will contain the visualisations and their corresponding explanations. A landing page which contains a comparison of all of the plots, and another page where the data used to build them can be viewed is also part of this dashboard.

### Website Requirements

The website consists of 7 pages total, including:

* A [landing page](#landing-page) containing:
  * An explanation of the project.
  * Links to each visualisations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualisation.
* Four [visualisation pages](#visualisation-pages), each with:
  * A descriptive title and heading tag.
  * The plot/visualisation itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A ["Comparisons" page](#comparisons-page) that:
  * Contains all of the visualisations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualisations.
    * The grid must be two visualisations across on screens medium and larger, and 1 across on extra-small and small screens.
* A ["Data" page](#data-page) that:
  * Displays a responsive table containing the data used in the visualisations.
    * The table must be a bootstrap table component. [Hint](https://getbootstrap.com/docs/4.3/content/tables/#responsive-tables)
    * The data must come from exporting the `.csv` file as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method appropriately called `to_html` that allows you to generate a HTML table from a pandas dataframe. See the documentation [here](https://pandas.pydata.org/pandas-docs/version/0.17.0/generated/pandas.DataFrame.to_html.html)

The website must, at the top of every page, have a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualisation page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive (using media queries). The nav must have similar behaviour as the screenshots ["Navigation Menu" section](#navigation-menu) (notice the background color change).

Finally, the website must be deployed to GitHub pages.

When finished, submit to BootcampSpot the links to 1) the deployed app and 2) the GitHub repository.

## Contents

* WebVisualisations - contains all required pages
* Resources - contains cities.csv database
* Assets - contains  pngs of graphs

### Output for Web Design Challenge

https://alinehornoff.github.io/Web_Design_Challenge/
