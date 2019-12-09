

# Leaf Green Footprints
<p>Our goal is to address the environmental habits and concerns of the communities that comprise Prince George's County by enlightening residences of better littering practices. We hope to bring litter awareness to the residences by showing them real-life data on their current recycling and trash habits, along with the amount of trash that they compile on a weekly basis. Environmental awareness is an important aspect of encouraging conservation efforts, and it is important we work together as a community to address this issue.</p>

## Heroku Instance
<https://green-leaf-footprints.herokuapp.com/>

## Target Browsers
<p> Our ideal browsers are Chrome on a desktop and iOS. Potential users might use Chrome to browse a larger version of our map. For instance, someone who is looking to peruse our heat map of litter may choose to use Chrome on a desktop. Our mobile users would likely have iOS devices. These users would be interested in searching our map of waste disposal areas. Someone searching for these areas is likely working somewhere in which a desktop computer may not be readily available. Therefore, they would need to use some sort of mobile device. We believe iOS is the most likely in this case. </p>

## User Manual
<https://github.com/lanavdove/green-leaf-footprints/blob/master/docs/user.md>

## Developer Manual

### Installation
* go to the root repository that has the package.json
* npm i to install all dependencies for the application

### Running the Application on a Server
### Tests
No tests have currently been made for the application.
### The API
The data for this project came from an API pull from https://data.princegeorgescountymd.gov/Environment/LitterTRAK/9tsa-iner/data
-- Please insert the GET, POST, PATCH endpoints --

### Known Bugs and Future Development
The heatmap made through Tableau does not appear on the right corner of the Project page when deployed through Heroku. We anticipate having ocassional problems with Heroku such as load time. Some of our interactive visuals have a lot of data to display and therefore sometimes take a long time to load as well. Future development will take place with integrating Tableau better with Heroku as well as including future visuals that show different facets of the LiterTrak dataset. Involvement with Prince George's County is a possibility in the future to increase website accessibility.

## Contributing
* Lana Dove
* Lauren Thomas 
* Camden Kelley
* Diego Hagans

## Documentation
Leaflet was used to create an interactive map to identify locations to dispose of waste.
Tableau was used to create a heat map of areas of high litter concentrations.
Glob is a supporting library that allows for easy file bundling. We used this to bundle our files smoothly and efficiently based on relevance.
Babel is a Javascript compiler for es6 and above through plain JS across browsers. This allows our application to be accessible on multiple browsers.
Webpack is a module bundler that takes modules with dependencies and generates static assets representing those modules.

## License
* <a href="https://opensource.org/licenses/mit-license.php"> MIT License </a>
* Copyright 2019 © LeafGreenTeam

## Acknowledgements
W3 Schools Online Web Tutorials for guidance and inspiration and Leaflet for providing easy to follow tutorials and documentation.
