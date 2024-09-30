# School Analysis and Visualization in Calgary
This project demonstrates data analytics and data visualization skills using a dataset of schools in Calgary, Canada. The goal is to provide an interactive map displaying school locations with relevant details and a geographic analysis of travel times using isochrones.

## Project Overview
The primary objective of this project is to visualize the locations of 49 schools in Calgary, Canada, and analyze their accessibility based on driving times. The analysis was conducted using R libraries like leaflet and mapdeck to create interactive maps and add spatial layers to provide useful insights.

## Key Features
  * **Data Collection:** The dataset includes the names, coordinates (latitude and longitude), levels (High School, Middle, Elementary), and maximum grade for each school.
  * **Interactive Leaflet Map:** Schools are marked on a map, with a pop-up that displays details such as the name of the school, level, and grade.
  * **Isochrone Calculation:** Isochrones show areas reachable within a 3-minute drive from each school, giving users insights into accessibility for students and parents.

## Tools and Libraries
The project was created using R and the following libraries:
  * **leaflet:** For interactive maps
  * **mapdeck:** For isochrone calculation and polygon mapping
  * **ggplot2:** For data visualization
  * **sf:** For handling spatial data
  * **RColorBrewer:** For color schemes
  * **mapboxapi:** For accessing Mapbox APIs (including isochrones)

## Steps and Methodology
1. **Data Preparation:**
  * A dataset containing the names, latitudes, longitudes, levels, and grades of schools in Calgary was created.
  * The data was used to plot points on a map representing the locations of the schools.

2. **Map Creation:**
  * A leaflet map was created with each school represented by a point.
  * Pop-ups were added to display the name, city, level, and grade of each school when clicked.

3. **Isochrone Generation:**
  * For each school, a 3-minute driving isochrone was calculated using the Mapbox API.
  * Isochrone polygons were added to the map to visualize the areas accessible within a 3-minute drive.

4. **Layer Control:**
  * A control was added to allow users to toggle the visibility of the isochrones, making the map more interactive.
