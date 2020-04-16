# Web Design Homework - Web Visualization Dashboard (Latitude)

## Latitude - Latitude Analysis Dashboard with Attitude

For this challenge, I created a visualization dashboard website using visualizations created in another challenge. Specifically, plotting [weather data](Resources/cities.csv).

In building this dashboard, I created individual pages for each plot and the means to navigate between them. These pages contain the visualizations and their corresponding explanations. There is also a landing page where we can see a comparison of all of the plots, and another page to view the data used to build them.

### Requirements

The website must consist of 7 pages total, including:

* A landing page containing:
  * An explanation of the project.
  * Links to each visualizations page.
* Four visualization pages, each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A "Comparisons" page that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a bootstrap grid for the visualizations.
    * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A "Data" page that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table must be a bootstrap table component.
    * The data must come from exporting the `.csv` file as HTML, or converting it to HTML.

The website must, at the top of every page, have a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown on the right of the navbar named "Plots" which provides links to each individual visualization page.
* Provides two more links on the right: "Comparisons" which links to the comparisons page, and "Data" which links to the data page.
* Is responsive (using media queries). The nav must include color-changing elements.

Finally, the website must be deployed to GitHub pages.

### Copyright

Trilogy Education Services © 2019. All Rights Reserved.
