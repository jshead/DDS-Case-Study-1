# DDS-Case-Study-1

# Doing Data Science Case Study 1 Budweiser Beers and Breweries 

## Overview
This repository contains the analysis of beer data, focused on uncovering insights into Alcohol By Volume (ABV) and International Bitterness Units (IBU) across various beer styles. It aims to understand consumer preferences and inform strategic decisions for product development and marketing.

## Project Contents
- `data_visualizations/`: Directory with R scripts and images for visual data analysis, including distribution of ABV and IBU.
- `presentation_materials/`: Contains slides and materials prepared for the executive presentation at Budweiser.

## Key Findings
- IPAs tend to have a higher ABV and IBU than Pale Ales, indicating a preference for stronger and more bitter beers in this market segment.
- The data suggest distinct taste preferences for IPA and Pale Ale consumers, potentially guiding targeted product innovation.

## Contributing
We welcome contributions and suggestions! Please open an issue or pull request for any improvements you wish to make.



# Codebook for Case Study 1 Beer Data Analysis Project

## Introduction
This codebook documents the datasets, code, and presentation materials used in the beer data analysis project. It aims to provide clarity on the variables, the data structure, and the analytical processes undertaken throughout the project.

## Datasets
### Beers.csv
- **Columns**:
  - `Name`: Name of the beer.
  - `ABV`: Alcohol by volume as a percentage.
  - `IBU`: International Bitterness Units, a measure of the beer's bitterness.
  - `Style`: The style of the beer (e.g., IPA, Stout).
  - Additional columns describing characteristics and metrics of each beer.
- **Preprocessing Steps**:
  - Removed entries with missing ABV values.
  - Normalized text fields to capitalize the beer styles.
- **Source**: Provided by Budweiser's database.

### Breweries.csv
- **Columns**:
  - `Brewery_ID`: Unique identifier for each brewery.
  - `Name`: Name of the brewery.
  - `City`: City where the brewery is located.
  - `State`: State where the brewery is located.
- **Preprocessing Steps**:
  - Merged with Beers.csv on `Brewery_ID` to associate beers with breweries.
- **Source**: Provided by Budweiser's database.

## Code Files
### Case Study 1 Markdown.Rmd
- **Description**: R Markdown file containing the analysis scripts, comments, and narrative for the project.
- **Contents**:
  - Exploratory data analysis
  - Statistical tests (t-tests)
  - Data visualization (ggplot2)
- **Dependencies**: Requires R and the following libraries: dplyr, ggplot2, tidyr.

## Presentation Materials
- **Slide Decks**: Presentations summarizing the findings and insights from the data analysis.
- **Charts and Graphs**: Visual aids created from the analysis to support the presentation.

## Usage
Refer to the README.md for instructions on how to use the materials in this repository.

## Notes
- Confidential data has been anonymized or removed as per Budweiser's data policy.
- Analysis was conducted with R version 4.0.2.

## Contact
For questions or further information, please contact [Jaren Shead](jshead@smu.edu).
