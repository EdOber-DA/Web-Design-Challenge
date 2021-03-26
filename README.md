# Web-Design-Challenge -  Web Visualization Dashboard (Latitude)
Using HTML and CSS to create a dashboard to display previous analysis work.

[Landing Page](https://edober-da.github.io/Web-Design-Challenge/Pages/index.html)


## Overview

Web Design Challenge Assignment - Responsive design site using HTML, CSS, media queries, images, and Python / Pandas to generate HTML tables. 

* Included in this repository are 3 folders:  
   
  * [Pages:](Pages) Contains 7 HTML pages and css style sheet.  
  
  * [Resources:](Resources) Contains 4 images used for site.   
  
  * [Data:](Data) Contains csv file created in the Python-API Challenge, jupyter notebook of code to create the HTML table, and HTML output pasted into the table.html page.   

## Files

* [Pages:](Pages)

  * [Landing Page:](Pages/index.html) - Starting point for the site with navbar and image links to other pages.  

  * [CSS Styles:](Pages/V4Style.css) - Bootstrap Version 4 style sheet for the site.  

  * [Comparison Page](Pages/comparisons.html) - Shows all the measurement images on one page with clickable images.  Highlights which one is active in thumbnails.

  * [Data Table Page](Pages/table.html) - Scrollable, responsive table with 10 columns of data.  

  * [Temperature Page](Pages/temperature.html) - Temperature vs latitude - image, observation info and links to the other measurement pages. 

  * [Humidity Page](Pages/humidity.html) - Humidity % vs latitude - image, observation info and links to the other measurement pages. 
 
  * [Cloudiness Page](Pages/cloud.html) - Cloudiness % vs latitude - image, observation info and links to the other measurement pages. 

  * [Wind Page](Pages/wind.html) - Wind Speed vs latitude - image, observation info and links to the other measurement pages. 


 
* [Resources](Resources)
  
  * [Temperature Chart Image](Resources/City_Lat_vs_Temp_Graph.png) - Temperature Image  

  * [Humidity Chart Image](Resources/City_Lat_vs_Humid_Graph.png) - Humidity Image  

  * [Cloudiness Chart Image](Resources/City_Lat_vs_Cloud_Graph.png) - Cloudiness Image  
	
  * [Wind Speed Chart Image](Resources/City_Lat_vs_Wind_Graph.png) - Wind Speed Image  


* [Data](Data)
  
  * [Input file of City Data](Data/City_DataFrame_CSV_Output.csv) - csv file with 540 rows and 10 columns of data - input to the jupyter notebook.  

  * [Jupyter Notebook](Data/Data_Table_Prep.ipynb) - Python code to take csv file and generate HTML table with 540 rows and 10 columns of data.

  * [Table HTML](Data/table_output.html) - HTML output from the jupyter code run. Copied into the table.html page. 

