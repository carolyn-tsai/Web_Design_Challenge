# Web_Design_Challenge

For this project, I created a visualization dashboard website using visualizations created from past projects. Specifically, I created plots and graphs using weather data.


In building this dashboard, I created individual pages for each plot and a means by which I can navigate between them. These pages will contain the visualizations and their corresponding explanations. There is also a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Website Structure:

The website consists of 7 pages total:
1. A landing page containing:- An explanation of the project
    - Links to each visualizations page
2. Four visualization pages, each with:
    - A descriptive title and heading tag
    - The plot/visualization itself for the selected comparison
    - A paragraph describing the plot and its significance
3. A "Comparisons" page that:
    - Contains all of the visualizations on the same page so quick comparisons can be made
    - Has a Bootstrap grid for the visualizations
          - The grid has two visualizations across on screens medium and larger, and 1 across on extra-small and small screens
4. A "Data" page that:
    - Displays a responsive table containing the data used in the visualizations
    - The table includes a bootstrap table component
    - The HTML table was created using Pandas

At the top of every page, there is a navigation menu that:
- Has the name of the site on the left of the nav which allows users to return to the landing page from any page
- Contains a dropdown on the right of the navbar named "Plots" which provides links to each individual visualization page
- Provides two more links on the right: "Comparisons" which links to the comparisons page, and "Data" which links to the data page
- Is responsive (using media queries)

### Tools used: 
- HTML
- CSS
- Pandas
- Python
- API

### Dataset:
The weather dataset of over 500 cities was created using the OpenWeatherMap API (https://openweathermap.org/api)

---------------------------------------------------------------


### Resources used:

- https://www.quackit.com/css/css_color_codes.cfm
- https://pythonexamples.org/pandas-render-dataframe-as-html-table/
- https://www.w3schools.com/default.asp
- https://pandas.pydata.org/pandas-docs/version/0.17.0/generated/pandas.DataFrame.to_html.html
