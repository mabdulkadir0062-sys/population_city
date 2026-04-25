# population_city

## 📊 Project Overview

### This project analyzes global city population data to identify largest urban centers, population distribution patterns, and geographic concentration of people

## 🎯 Business Problem

### Urban population data is critical for governments, urban planners, and businesses. However, raw data alone doesn’t answer key questions:

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
  
