# Web-Design-Challenge

## Web Visualisation Dashboard

The Aim of this Assignment is to create a dashboard featuring the Analysis that was done on the Python API Challenge to showcase the Image results of the Weather Plots to demonstrate the relationship between the Distance from Latitude and the Maximum Temperature, Humidity, Cloudiness and Wind Speed of the Cities.


### Website Design

The website consists of seven pages in total, including:

#### Landing Page
A landing page containing the following elements:


An explanation of the project


Links to each visualisation page. A a sidebar containing preview images of each plot. Clicking an image takes the user to that visualisation.



#### Visualisation Pages
Four visualisation pages, stored in the visualisations folder, each with the following elements:


A descriptive title and heading tag.


The plot or visualisation for the selected comparison (latitude vs: max temperature, humidity, cloudiness, or wind speed). The images displayed on these pages are stored in the assets/images folder.


A paragraph describing the plot and its significance.



#### Comparison Page
A "Comparisons" page that does the following:


Contains all of the visualisations on the same page so they can easily be compared with each other.


Uses a Bootstrap grid for the visualisations.

The grid is two visualisations across medium and large screens, and is one visualisation across on extra-small or small screens.




#### Data Page
A "Data" page that displays a responsive table containing the data used in the visualisations.


The table is a Bootstrap table component.


The data is derived by converting it to HTMLby using Pandas method, called to_html, that allows user to generate an HTML table from a Pandas DataFrame. 
