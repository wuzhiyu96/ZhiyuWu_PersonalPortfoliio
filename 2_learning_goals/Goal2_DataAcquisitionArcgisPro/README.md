# Goal 2: Data acquisition and web map publishing

## Overview
This folder documents the implementation of the second learning goal, focusing on geospatial data processing and visualization. It contains key resources demonstrating the practical application of ArcGIS Pro skills, including:

- Highway shapefile (`snelweg.zip`): Geospatial data representing highway networks
- ArcGIS Pro toolbox screenshot (`GeoprocessingFlowmap.png`): Illustrating the data processing workflow
- Web map: The final visualization product created from the processed geospatial data

## Background
I have previously completed two courses on ArcGIS Pro, which provided me with:
- Familiarity with the software interface
- Ability to resolve geo-location related tasks
- Understanding of basic toolbox functions

However, my previous experience was limited by:
- Pre-prepared datasets
- Lack of real-world data acquisition skills
- Minimal experience in independent data sourcing

For this project, I am planning to map out $NO_x$ measurement stations' relative location with the highway, as a way to select suitable locations for our research.

## Methodology and Data Sources
### Data Acquisition Approach
I approached data collection systematically, focusing on reliable and accessible sources. For pollution measurement data, I used the familiar RIVM website, which provided a straightforward download process. The highway data required more effort due to language barriers, but I successfully located the information on the Rijkswaterstaat website.

### Data Verification
To ensure data reliability, I employed multiple verification strategies. For the highway shapefile, I cross-referenced the data with alternative sources and Google Maps to confirm its accuracy and completeness.

### Data Sources
- RIVM (Dutch National Institute for Public Health and the Environment)
- Rijkswaterstaat

## Implementation Details
The project utilized two primary data sources:
- $NO_x$ pollution data and location calculations from previous work (File can be find at '2_learning_goals/Goal1_PythonAndDASkills/Data')
- Highway geo-locations in polyline format, downloaded from official sources

The implementation process is documented through ArcGIS Toolbox screenshots, demonstrating the step-by-step data processing approach.

## Results
The project culminated in a published web map, showcasing the integrated $NO_x$ pollution for day period of Oct, 2019 and Oct, 2023, as well as decreased (increased) percentage, and highway location data.

## Conclusions
By completing this learning goal, I am more familiar with acquiring raw data online and importing them into ArcGIS pro, as well as publishing results as webmap.
