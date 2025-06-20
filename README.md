# 5512assignment4
## Author and Publishing Date

Author: Ruyu Li
Published: June 16, 2025

## Data Origin

Source: United Kingdom Office for National Statistics (ONS) – local area statistics

Original File: datadownload.ods, an OpenDocument Spreadsheet containing multiple sheets of data

Tables Used:
Table 5: Modelled unemployment rate (percentage) for years 2017–2023
Table 61: Average life satisfaction score (scale 0–10) for years 2017–2023

Data Characteristics: These indicators are derived from ONS’s regularly published sample-based data and modelled estimates. 
License: All data is published under the Open Government Licence v3.0 (OGL), allowing free use with attribution.

Contains public sector information licensed under the Open Government Licence v3.0. © Crown copyright 2017-2022, Office for National Statistics.

<a href="https://www.nationalarchives.gov.uk/doc/open-government-licence/"><img src="/ogl-symbol-41px-retina-black.png" alt="Open Government Licence logo"/></a>

Additionally, spatial data used for mapping was retrieved using the **giscoR** R package. This package provides access to Geographic Information System of the Commission (GISCO) datasets maintained by Eurostat. The data is open and publicly available, and the package is licensed under **GPL-3**. For more details, see: https://ropengov.github.io/giscoR/

## File Structure of This Dataset

assignment4_template_34795596/
├── assignment4_template_RUYULI.qmd        -> Quarto (.qmd) document containing all data wrangling, analysis, and visualization code (no separate scripts needed)
├── assignment4_template_RUYULI.html       -> Rendered HTML output (generated from the .qmd; no separate image files saved)
├── data
│   └── datadownload.ods    -> Primary dataset file (OpenDocument Spreadsheet format)
├── README.md                              -> Project documentation (this file)
└── assignment4_template_34795596.Rproj    -> RStudio project file (for opening the project in RStudio)
