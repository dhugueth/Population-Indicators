# Population and Indicators 

To access the report [click here](https://app.powerbi.com/view?r=eyJrIjoiZWNkN2NkNjctZmU0ZC00YWEzLWI5NGYtZjkxMzJkMWZhZGVjIiwidCI6ImJhYjBiNjc5LWJkNWYtNGZlOC1iNTE2LWM2YjhiMzE3Yzc4MiIsImMiOjR9)

## What was used? 

The project was developed and published using Power BI, one of the top leader in business Intelligence.

### Data

_The data used was provided for educational purposes by Power BI - Data Analysis and Business Intelligence course on the Udemy platform._

**First Part**
- [Population.xlsx](https://github.com/dhugueth/Poblacion-e-Indicadores/files/7532797/Population.xlsx)
- [Countries.xlsx](https://github.com/dhugueth/Poblacion-e-Indicadores/files/7532795/Countries.xlsx)
- [Paises.xlsx](https://github.com/dhugueth/Poblacion-e-Indicadores/files/7532796/Paises.xlsx)

**Second Part**
- [Infant death rate.xlsx](https://github.com/dhugueth/Poblacion-e-Indicadores/files/7532798/Infant%2Bdeath%2Brate.xlsx)
- [Life expectancy.xlsx](https://github.com/dhugueth/Poblacion-e-Indicadores/files/7532799/Life%2Bexpectancy.xlsx)


### Data Preparation

Modifications were made to the original data using the Power Query editor to be able to use them appropriately. 

The modifications were: 

- In some cases it was necessary to use the "Use First Row as Headers" option to accommodate the imported data.
- A conditional column was created to add a new category called "Cantidad Poblacional" 
- A conditional column was created to add a new category called "Mortalidad Infantil (Muertes cada 1000 niños)"
- A conditional column was created to add a new category called "Esperanza de Vida (Años promedio)"

## Data Modeling

It was required to relate common data between the files:

- The data named "Country" from the file Population and Countries were related. 
- The data named "Country code" from the file Population, and data named "Codigo pais" from the file Countries were related.
- The data named "Country" from the file Countries and Infant death rate were related.
- The data named "Country" from the file Countries and Life Expectancy were related.

![relacion de datos](https://user-images.githubusercontent.com/93662295/141716274-a53ea1b4-eb37-432b-9bae-6981036d5769.png)

## Description

This is an interactive report divided into two parts. **The first** is an analysis of the population quantity seen by countries and continents. **The second** relies on the first part with additional information from the world indicators of infant death rate and life expectancy.

Different types of visualizations were used to represent the behavior of the data, such as maps, treemaps, tables, and scatter charts.

In the first part, the visualizations with the data of continent and population size make easy different forms of analysis. Below you can see a snapshot from the first part of the report:

![Poblacion_parte1](https://user-images.githubusercontent.com/93662295/141862170-76783c22-2bec-4195-8160-ccc8b5a30cb1.png)

In the second part, the data of continent, population size, average of life expectancy and average of infant death rate make easy different forms of analysis. In the report, it is possible to analyze correlations between the data on infant death rate and life expectancy. Below you can see a snapshot from the second part of the report:

![Poblacion_parte2](https://user-images.githubusercontent.com/93662295/141862840-fb0084d7-a825-4881-85b9-2f4a6d8982ff.png)



