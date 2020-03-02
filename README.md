# Weather Visualization Dashboard 
The goal of this project was for me  to utilize HTML and CSS and create a visualization dashboard website that displays visualizations created for the analysis of weather data. 

## Latitude Analysis Dashboard 
To build the dashboard I created individual pages for each plot - a means by which the user can navigate between them. These pages contain the visualizations and their corresponding explanations. There is a landing page, a page where comparison of all of the plots can be seen , and another page where the data used to build them can be viewed.

## Website Specifics
I constructed the website to consist of 7 pages total, including:
### •	A landing page containing:
o	An explanation of the project.
o	Links to each visualizations page.
### •	Four visualization pages, each with:
o	A descriptive title and heading tag.
o	The plot/visualization itself for the selected comparison.
o	A paragraph describing the plot and its significance.

![dashboard]("/assets/images/Fig1.png")

### •	A "Comparisons" page that:
o	Contains all of the visualizations on the same page so visual comparison  can be easy.
o	Uses a bootstrap grid for the visualizations.
	The grid has  two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
### •	A "Data" page that:
o	Displays a responsive table containing the data used in the visualizations.
	The table is a bootstrap table component.
	The data came from exporting the .csv file as HTML. 

## The website  at the top of every page, has a navigation menu that:
 I built a navigation bar to have the following features:
•	Has the name of the site on the left of the navbar which allows users to return to the landing page from any page.
•	Contains a dropdown on the right of the navbar named "Plots" which provides links to each individual visualization page.
•	Provides two more links on the right: "Comparisons" which links to the comparisons page, and "Data" which links to the data page.
•	Is responsive (using media queries).



