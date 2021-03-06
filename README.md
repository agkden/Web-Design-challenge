# Web-Design-challenge

## Web Visualization Dashboard

For this project we'll be creating a visualization dashboard website using visualizations we've created in the past WeatherPy project. 

In building this dashboard, we'll create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

The Bootstrap, HTML, and CSS will be used for the project.

### Website Requirements

The website must consist of 7 pages total, including:

* A **landing page** containing:
  * An explanation of the project.
  * Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.
* Four **visualization pages**, each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A **Comparisons** page that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
    * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A **Data** page that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table must be a bootstrap table component.
    * The data must come from converting the `.csv` file to HTML by using Pandas.

The website must, at the top of every page, have a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* The navbar needs to be responsive and collapses when window is shrunk. The toggle button should make the navbar reappear.
* The nav should have behavior of changing the background color of active dropdown item.

Finally, the website must be deployed to GitHub pages.

