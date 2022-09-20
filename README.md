# Web-Design-Challenge
#### In our Module 11 Challenge, we were asked to build a website using data that was generated during on of our previous challenges.  Over 500 random latitude and longitude data points were generated during a succession of API calls. This data was saved to a CSV file (cities.csv).  The csv file is then loaded into a Pandas dataframe and converted to HTML using to_html function, after which the data is then used to create plots of latitude versus X pages where X is: max temperature, humidity, cloudiness, and wind speed and a comparison page. 

### Requirements for the website are as follows: 

#### A landing page containing the following elements:
* An explanation of the project
* Links to each visualizations page. 
* Sidebar containing preview images of each plot
* Clickable image  that takse the user to that visualization.

#### Four visualization pages, stored in the visualizations folder, each having the following elements:
* A descriptive title and heading tag.
* Plot or visualization for the selected comparison 
* latitude vs: 
    ###### * max temperature
    ###### * humidity 
    ###### * cloudiness
    ###### * wind speed
* Images displayed on these pages should be stored in the assets/images folder.
* A paragraph describing the plot and its significance.
* A "Comparisons" page that does the following:
* Contains all of the visualizations on the same page so they can easily be compared with each other.
* Uses a Bootstrap grid for the visualizations.
* A grid must having two visualizations across medium and large screens, and it must be one visualization across on extra-small or small screens.
* A "Data" page that displays a responsive table containing the data used in the visualizations.
* The table must be a Bootstrap table component. Refer to the Bootstrap documentation for how to use responsive tables.
* Use to_html function in pandas dataframe to convert file from CSV to HTML file as HTML
* Website navigation at the top of every page with a menu having following elements:
* Name of the site on the left of the navigation bar, allowing users to return to the landing page from any page.
* Dropdown menu on the right of the navigation bar, named "Plots," to provide links to each individual visualization page.
* Two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Responsive (using media queries). 
* Navigation bar must be similar to the screenshots in the "Navigation Menu" section.
* Wwebsite must be deployed to GitHub Pages.
* Use Bootstrap navbar component for the header on every page, the Bootstrap table component for the data page
* Bootstrap grid for responsiveness on the comparison page.
##### Deploy website to GitHub Pages,  publicly accessible URL

## References

OpenWeatherMap.org Сurrent weather and forecast. Retrieved from [https://openweathermap.org/](https://openweathermap.org/)

