# Leaf Green Footprints
## Team Members
Lana Dove

Camden Kelley

Diego Hagans

Lauren Thomas
## Link
https://green-leaf-footprints.herokuapp.com/
## Information Problem
<p> To address the environmental habits of Prince George's County through real-life data on current recycling and weekly trash disposal habits </p>

## Stakeholders 
* Environmental Health Division and Environmental Education in Prince George’s County

* Communities that comprise Prince George’s

## Data
* LiterTRAK for Prince George's County -
https://data.princegeorgescountymd.gov/Environment/LitterTRAK/9tsa-iner/data

* Waste and recylcing center information -
https://www.princegeorgescountymd.gov/612/Facilities
## Technical System Decision Rationale
*  **Leaflet**- good tool for users trying to find trash dumping locations on a map and utilizes javascript

* **Tableau**- has attractive heatmap tool to visualize amount of trash in Prince George's County. This gave us the ability to create a visualization that highlighted areas of high illegal dumping and trash concentration. 

* **Glob** - Supporting library that allows for easy bundling of multiple files by pattern. This allowed bundling for our files smoothly and efficiently based off their relevances.

* **Babel** - Javascript compiler for es6 and above down to plain js across multiple browsers. This allows our application to be accessible across multiple broswers.

* **Webpack** - module bundler that takes modules with dependencies and generates static assets representing those modules.

## Final Project Analysis
  <p>We learned through the project that instead of plainly showing the liter data to inspire others to take action against littering, we would want to show locations on where to dump trash in order to reduce litter instead. This is more of an information solution that can change behavior. We display waste and recylcing centers on an interactive map based upon the users location in order to give users the closest locations to dump their garbage. </p>
     <p>One of our challenges in our information project was data cleaning. Public data is generally messy and there were data entries that were irrelevant to the type of litter and related information. Columns of data were mislabeled such as Latitude and Longitude being switched. Another challenge was switching direction to solve our information problem. We had to refocus on how we visually were going to represent our problem through graphs and the site layout. With our graphs, we learned that leaflet would not be an ideal tool for heatmaps and decided Tableau would function better. </p>
    <p> Some of the next steps to take for our project would be to possibly improve data collection by making data entries more standard and descriptive. More maps on different aspects of the data could be utilized to show different factors of the litering problem. With our leaflet map, we could also introduce a search bar to search for trash drop-off locations by name and location, as well as a filtering option for users to filter trash drop-off options based on location distance and type of trash they wish to get rid of. We could also contact the Environmental Health Division and Environmental Education Department in Prince George's County to give our web application more traction. In the near future, we also hope to offer the community relevant articles on better littering practices and ways be more environmentally aware, as well as give users information on upcoming events to participate in making our community a greener and healthier place. </p>