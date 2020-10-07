<!---Project Logo -->
<br />
<p align="center">
  <h3 align="center">Weather Visualisation Dashboard</h3>
  <p align="center">
    A HTML, CSS and Bootstrap Project
    <br />
</p>
</p>


<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Website Specifications](#website-specifications)
  * [Considerations](#considerations)
  * [Built With](#built-with)
* [Usage](#usage)
* [Results](#results)
  

<!-- ABOUT THE PROJECT -->
## About The Project
## Latitude - Latitude Analysis Dashboard with Attitude

For this project I created a visualization dashboard website using visualizations I've created in a past project. Specifically, I plotted [weather data](Resources/cities.csv).

In building this dashboard, I created individual pages for each plot and a means by which one can navigate between them. These pages contain the visualizations and their corresponding explanations. There is also a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Website specifications:

The website consists of 7 pages total, including:

* A landing page containing:
  * An explanation of the project.
  * Links to each visualizations page. There is a sidebar containing preview images of each plot, and clicking an image takes the user to that visualization.
* Four visualization pages, each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A "Comparisons" page that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
    * The grid is two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A "Data" page that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table is a bootstrap table component. 
    * The data comes from exporting the `.csv` file as HTML, or converting it to HTML. I used pandas to convert csv to HTML. Pandas has a nifty method approprately called `to_html` that allows you to generate a HTML table from a pandas dataframe. 

The website has a navigation menu that at the top of every page:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive (using media queries). The nav has similar behavior. 


### Considerations

* I used the weather data (inside resources folder in the repo).
* Bootstrap `navbar` component is used for the header on every page, the bootstrap table component for the data page, and the Bootstrap grid for responsiveness on the comparison page.
* Used a CSS media query for the navigation menu.
* The website works at all window widths/sizes.

### Built With
* [Python](https://www.python.org/about/)
  * [Pandas](https://pandas.pydata.org/pandas-docs/stable/getting_started/index.html)
* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS#:~:text=Cascading%20Style%20Sheets%20%28CSS%29%20is%20a%20stylesheet%20language,on%20paper%2C%20in%20speech%2C%20or%20on%20other%20media.)
* [Bootstrap](https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css)

### Results
The website is deployed to GitHub pages. <a href="https://susovd.github.io/Web-Design-Challenge/WebVisualizations/index.html" alt="Weather Visualisation Dashboard"> Weather Visualisation Dashboard</a>


**Additional reference materials:**

_Best-README-Template_ Retrieved from: [https://github.com/othneildrew/Best-README-Template](https://github.com/othneildrew/Best-README-Template)






