# Web Visualization Dashboard



### Objective

The purpose of this project is to create a visualization dashboard website using visualizations created for the [Weather Model](https://github.com/zunicd/Weather-Model) project.

The dashboard can be viewed at: https://zunicd.github.io/Web-Design-Challenge/index.html

The website consists of 7 pages total, including:

- A **landing page** containing:
  - An explanation of the project.
  - Links to each visualization page.
- Four visualization pages, **Max Temperature**, **Humidity**, **Cloudiness**, **Wind Speed**, each with:
  - A descriptive title and heading tag
  - The plot/visualization itself for the selected comparison.
  - A description of the plot and its significance.
- A **Comparisons** page that:
  - Contains all of the visualizations on the same page so we can easily visually compare them.
- A **Data** page that:
  - Displays a responsive table containing the data used in the visualizations. Pandas' method called `to_html` was used to generate a HTML table from a pandas dataframe. 



The website has at the top of every page a navigation menu that:

- Has the name of the site on the left which allows users to return to the landing page from any page.
- Contains a dropdown on the right of the navbar named **Plots** which provides links to each individual visualization page.
- Provides two more links on the right: **Comparisons** which links to the comparisons page, and **Data** which links to the data page.



### Tools / Techniques Used:

- HTML5

- CSS

- Bootstrap4

- Pandas

  
