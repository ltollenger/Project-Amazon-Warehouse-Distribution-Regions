# Project-Amazon-Warehouse-Distribution-Regions

## Project Background
The goal of this project is to create a map visual for the purpose of having a starting place for analyzing if Amazon warehouses are too close to each other.

Before coding, I needed to gather the following items:
<ul>
  <li>Come up with a region to analyze; then convert this region into a json file</li>
  <li>Find a dataset of all US ZIP codes</li>
  <li>Gather a sample of Amazon warehouse locations</li>
</ul>

After acquiring the prerequisites, I was able to start the project.  I followed these steps to make the project deliverable:
<ul>
  <li>Perform exploratory data analysis on datasets and install python packages</li>
  <li>Create a shapely Polygon object to define the distribution region</li>
  <li>Filter the US ZIP codes dataframe to only include ZIP codes that reside within the defined distribution region</li>
  <li>Find the distance between each warehouse to each ZIP code, and only keep the records that corresponded with the closest warehouse and ZIP code combinations</li>
  <li>Then, using plotly and the distirbution region coordinates dataframe, to create the map visual</li>
</ul>

## Next Steps
Potential next steps after generating the plotly map:
<ul>
  <li>Determine if warehouses were located close to each other to distribute storage capacity across locations to better serve a common region or not.</li>
  <li>Assuming existing warehouses are all strategically located, what customers should we focus on serving next?</li>
</ul>
