## World Population Visualization using GeoPandas

This repository contains a Jupyter Notebook that visualizes world population data using geopandas and matplotlib. It provides a choropleth map to display population estimates for each country, with options for applying logarithmic normalization to enhance data representation.

**Table of Contents**

* **Overview**
* **Features**
* **Requirements**
* **Installation**
* **Usage**
* **Project Structure**
* **Contributing**

**Overview**

The goal of this project is to visually represent global population distribution, using color to indicate relative population sizes of countries. By leveraging the geopandas dataset and color maps, we create a clear representation of population density across different regions.

**Features**

* Loads country boundary and population data using geopandas.
* Filters non-positive population values to improve visualization accuracy.
* Applies a logarithmic color scale for effective representation of diverse population sizes.
* Customizable color maps for aesthetic and informative visual effects.

**Requirements**

* Python 3.x
* Jupyter Notebook
* Libraries:
  * geopandas
  * matplotlib
  * pandas (if additional data processing is required)
    
**Installation**

*1. Clone this repository:

     git clone https://github.com/yourusername/world-population-geopandas.git
  
     cd world-population-geopandas

*2.Install the required libraries:

     pip install geopandas matplotlib pandas
  
*3. Open the Jupyter Notebook:

    jupyter notebook World_population_using_geopandas.ipynb
  
**Usage**

Run each cell in the notebook to:

   * Load the country boundary data.
   * Filter and normalize the population data.
   * Generate a world map with population density visualization.


![Population Per Country](https://github.com/user-attachments/assets/1047b053-32e1-461d-9121-118c8986dcce)

**Project Structure**

.
├── World_population_using_geopandas.ipynb  # Main notebook for visualization

├── README.md                              # Project documentation

└── example_map.png                         # Example output image (if available)

**Contributing**

Contributions are welcome! Please open an issue or submit a pull request if you'd like to improve this project.

**Contact :**

For any questions or collaborations, reach out via:

•	Email: rsgis.sudin@gmail.com

•	LinkedIn: https://www.linkedin.com/in/sudin-giri-6814b74a/
