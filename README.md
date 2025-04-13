# Energy Data Visualization Project

## Overview
This project is part of a university course on **Visualization**, focused on gaining hands-on experience working with real-world datasets and presenting data both interactively and non-interactively. The dataset used for this project is related to **global energy consumption and production**, sourced from **Our World in Data** and **OWID Energy Data** repositories. The analysis focuses on the evolution of energy production, consumption, and efficiency across different countries over decades, exploring various energy sources such as renewables (e.g., solar, wind) and non-renewables (e.g., coal, oil, natural gas).

![Visualization](/assets/visualization.jpeg)

## Dataset Overview

**Dataset**: [Our World in Data - Energy](https://ourworldindata.org/energy), [OWID Energy Data](https://github.com/owid/energy-data/tree/master)

The dataset we chose is from Our World in Data, a research organization that provides free access to data on various global issues. There we searched for interesting topics and found the energy dataset which stood out to us. The dataset contains extensive data on various energy related metrics for countries around the world over several decades. It includes various attributes, such as the energy consumption (primary energy, per capita, and growth rates), energy mix, electricity mix and other relevant metrics.

We chose this dataset in particular, since it not only contains data over a large timespan, but also contains data for many different countries. Furthermore, the question of sustainability and energy consumption is more pressing than ever. Therefore, we thought it would be interesting to investigate how energy related metrics change over time for different countries. Observing the differences in effectiveness of certain policies is key in understanding what works and what doesn’t.

## Tasks and Hypotheses

**Hypothesis**: There is a positive correlation between time and the sustainable energy ratio over a specified year range.

**Hypothesis**: There is a positive correlation between GDP per capita and energy consumption per capita over the years. This trend is expected to be stronger in developed countries.

**Task**: Determine the share of renewable and non-renewable energy sources in the total electricity generation of countries worldwide during certain time interval.
There is a map, where each country is colored in a shade of a specific color, which determines the degree of dependence on a selected energy source. 
The colors should be interpreted as follows: The darker the color, the more dependent the country is on the energy source, and the lighter the color, the less dependent the country is on the energy source.

**Hypothesis**: Looking at specified timeframe, some countries are getting more energy efficient with regard to GDP growth, i.e., 
there is less additional energy consumption needed to increase GDP now compared e.g. to the 90s and 2000s. Since different countries place a different priority on becoming more energy efficient, 
comparing the gains in energy efficiency should reflect the differences in economic and ecological politics.
