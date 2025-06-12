# KAAN Dataset: Building Projects Across the Netherlands

## Overview

The KAAN dataset includes architectural data corresponding to more than 800 apartment units related to four building projects across the climatic context of the Netherlands. The projects spread over the cities of Amsterdam, Rotterdam, and Eindhoven over three different provinces of North Holland, South Holland, demonstrating variety in development and city context. The data is sourced from commercial clients of KAAN Architecten, a Rotterdam-based architectural firm that combines academic knowledge with practical application in architecture, urbanism, and the built environment.

## Data Format

Each project contains four data types organized in separate folders:

- **General_csv/**: CSV files with detailed IFC element data including ExpressId, GlobalId, Class, coordinates, materials, and quantification properties
- **Graphs/**: Network graph representations stored as pickle files
- **Embeddings/**: Compressed embedding data (zip format) for machine learning applications  
- **BatchPlan_output/**: Automated building plan outputs generated using [BatchPlan](https://github.com/byildiz/BatchPlan)

## Projects

| Project Name | Location | Status | Use Configuration | Design Duration | Gross Floor Area (m2) | Number of Storeys | Project Description |
|--------------|----------|--------|-------------------|-----------------|----------------------|-------------------|-------------------|
| **SPOT** | Southeast Amsterdam | Construction | 390 apartment units | 2017 - 2021 | 40,000 | 35 | It contains varying towers and lower building blocks. |
| **Lumiere** | Center of Rotterdam | Design | 263 apartments, hotel with 160 rooms, shopping, working, and recreation spaces | 2018 - present | 50,000 | 46 | It promotes the high-rise vision of the city and involves a tower among lower level building volumes. |
| **The Stack** | North Amsterdam | Built | 120 apartments with a communal garden in between | 2017 - 2019 | 11,400 | 9 | It consists of two separate buildings and Apartment units are positioned such a way that they are oriented towards the sun as much as possible. |
| **Matchbox** | Strijp-S area of Eindhoven | Construction | offices on the ground floor and apartment units on upper levels surrounding an inner courtyard | 2018 - 2023 | 4,800 | 7 | wooden construction, usage of bio-based materials, integrated solar panels, rain water collection system, and natural cross ventilation contribute to the sustainable design aspect of the project. |
