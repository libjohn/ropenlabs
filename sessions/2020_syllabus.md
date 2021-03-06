Traversing the Tidyverse
================
John Little
2020-02-10

An [ROpenLabs](https://rfun.library.duke.edu/portfolio/r_open_labs/)
tiered training tutorial

<!-- README.md is generated from README.Rmd. Please edit that file -->

The following outline is based on Garrett Grolemund’s [*Matering the
Tidyverse*](https://github.com/rstudio/master-the-tidyverse) workshop
plus the [R Studio Primmers](https://rstudio.cloud/learn/primers).

## Intro to R / RStudio / Tidyverse (January 13, 2020)

1.  Download the Master the Tidyverse Repository from GitHub
    
      - <https://github.com/rstudio/master-the-tidyverse>

2.  Slides (PDFs):
    
      - 000 PreClass
      - 00 Introduction
      - 01 Visualization

Topics

    - R / Packages (Tidyverse ; Base R)
    - IDE
    - R Notebook   (Literate Coding ; R Markdown ; Report Rendering)
    - dplyr        (Data Transformations)
    - pipes        (Conjunctions)
    - assignment   (Object permanence)
    - import data  (Import Data Wizard)
    - simple Viz   (Example Bargraph)

3.  **FOLLOW-UP** – Your work outside of the ROpenLab
    
      - R Primers
        
          - Visuazliation Basics -
            <https://rstudio.cloud/learn/primers/1.1>
          - Visualizing Data - <https://rstudio.cloud/learn/primers/3>

## Visualization (Feb 03)

1.  Slides (PDFs):
    
      - 01 Visuzlizaton

2.  **FOLLOW-UP** – Your work outside of the ROpenLab
    
      - R Primers
        
          - Visualizing Data - <https://rstudio.cloud/learn/primers/3>

## Transform data, i.e. dplyr (Feb 10)

  - 00 Reintroduction
  - 02 Transform Data (dplyr)

**FOLLOW-UP**: [Working with
data](https://rstudio.cloud/learn/primers/2)

## Reshape: pivot & join (Feb 17)

  - 03 Tidy: pivot & join

<!-- end list -->

``` r
tidyr::table4a %>% pivot_longer(2:3, names_to = "year", values_to = "population")

tidyr::table2 %>% pivot_wider(names_from = "type", values_from = count)
```

[join](https://github.com/libjohn/intro2r-code/blob/master/02_join-skim-eda.Rmd)

**FOLLOW-UP**: [Tidy your data](https://rstudio.cloud/learn/primers/4)

## Iterate & Functions (Feb 24)

  - Iteration / Functions: purrr::map

## Models (March 02)

  - Models with Evan Wyse
