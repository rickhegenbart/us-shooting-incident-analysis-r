# U.S. Shooting Incident Analysis

> **Master’s Psychology Research & Analytics Portfolio**
>
> This project was completed as part of my Master’s degree program in Psychology. It applies R-based exploratory analysis, visualization, and regression to examine patterns in historical U.S. shooting-incident data.
>
> [View the complete Master’s Psychology Research & Analytics Portfolio](https://github.com/users/rickhegenbart/projects/1)

## Overview

This R Markdown project examines historical U.S. shooting-incident data through geographic mapping, descriptive statistics, demographic summaries, trend visualization, and linear regression.

The project is an academic data-analysis exercise focused on understanding patterns in incident-level data. It does not attempt to explain causation or make predictions about future violence.

## Analysis Questions

* Where are incidents geographically distributed across the United States?
* What are the median numbers of total victims and fatalities per incident?
* How are incident records distributed across available demographic categories?
* How do fatalities and injuries relate across incidents?
* How have recorded fatalities changed over time?
* What association is observed between incident year and fatalities?

## Methods

The analysis:

* Creates an interactive U.S. map using incident coordinates.
* Calculates median victim and fatality counts.
* Summarizes available demographic categories.
* Creates interactive histograms, contour plots, and scatterplots.
* Examines annual incident counts.
* Fits a linear regression model of fatalities by year.
* Visualizes observed and fitted fatality values over time.

## Tools

* R
* R Markdown
* `tidyverse`
* `dplyr`
* `leaflet`
* `lubridate`
* `plotly`
* `broom`
* `DT`
* `readxl`
* `rtweet`
* `htmltools`

## Data Availability

The original R Markdown file expects a data frame named `shootings`.

The source file and import step are not included in the original analysis, so the dataset cannot currently be reproduced from this repository alone. Before adding data, document its original source, verify redistribution permissions, and remove any information that should not be publicly shared.

## Repository Contents

```text
├── README.md
└── shootings(20260910-200226).Rmd
```

## Reproducing the Analysis

Install the required R packages:

```r
install.packages(c(
  "leaflet", "tidyverse", "lubridate", "htmltools",
  "rtweet", "readxl", "broom", "plotly", "DT", "dplyr"
))
```

Load a compatible dataset into an R object named `shootings`, then render the R Markdown file.

## Project Status

This repository preserves the original analysis source code. A reproducible HTML report can be added after the original dataset and source documentation are recovered.
