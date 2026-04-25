# population_city

## 📊 Project Overview

### This project analyzes global city population data to identify largest urban centers, population distribution patterns and geographic

concentration of people

## 🎯 Business Problem

### Urban population data is critical for governments, urban planners, and businesses However raw data alone doesn’t answer key questions:

. Which cities have the largest populations?

. How is population distributed across continents?

. Are populations concentrated in a few mega-cities?

## 🧹 Data Cleaning & Preparation

### Before analysis, the dataset required preprocessing to ensure accuracy:

. Loaded dataset using Polars

. Inspected data using:

- head()

- describe()

- null_count()

. Casted "Population" from str to int
  
   . Exported a cleaned version of the dataset for reproducibility

   ## 📊 Visualizations

 ### Top 10 Cities by Population
   
. Bar chart ranking largest cities
. Color-coded by country

### Population Distribution

. Histogram showing distribution of city populations

. Segmented by continent

### Population Hierarchy

. Hierarchical visualization

. Size based on population

## 🧠 Skills Demonstrated

### theese skills are :

. Data cleaning and transformation

. Group-by aggregation analysis

. Interactive data visualization

. Casting data types 

. End-to-end analytics workflow

## 📊 Key Insighst

### 1. Top 10 Cities by Population

. The bar chart highlights Tokyo’s massive lead as the world's most populous city being 62% larger than New York City 

. It reveals a highly competitive top tier where Delhi and Jakarta maintain nearly identical population levels

### 2. Distribution of City Populations

​. The chart reveals a heavy concentration of cities in the lower population bracket with the vast majority falling below 10M residents

Asia dominates every population tier consistently outnumbering all other continents and representing the only region with cities exceeding

the 25M mark

### Hierarchchical View of Population by Country and City

. The treemap shifts focus to national scale showing that China dominates the landscape with three cities totaling over 30% of the entire
list's population It visually isolates the United States as the sole non-Asian representative in this global ranking of extreme urban 
density







  
