# Visualizing FEMA NRI and ACS Data

This repository contains visualizations summarizing NRI ([National Risk Index](https://www.fema.gov/flood-maps/products-tools/national-risk-index)) and ([ACS](https://www.census.gov/programs-surveys/acs/about.html)) data for the 50 U.S. states. This analysis was completed for homework assignments 2 and 3 for MEDS course EDS240: Data Visualization & Communication. The first (HW2.qmd) is an exploration of California's NRI compared to other U.S. states, and the second (HW3.qmd) visualizes how NRI varies across different racial/ethnic groups in California.

As of January 28, 2026, only [Homework 2](https://eds-240-data-viz.github.io/course-materials/assignments/HW2.html) has been completed.

As of February 10, 2026, both Homework 2 and [Homework 3](https://eds-240-data-viz.github.io/course-materials/assignments/HW3.html) have been completed.

## Data Access

**NRI:** FEMA ([Federal Emergency Management Agency](https://www.fema.gov/about)) has maintained National Risk Index (NRI) data since 2021. The index “provides information for communities most at risk to 18 different natural hazards. It offers a baseline risk measurement for expected annual loss, social vulnerability and community resilience at the Census tract or county level. The data helps to validate, measure and better understand your community’s natural hazard risk.” Risk is defined as the potential for negative impacts resulting from natural hazards. This analysis uses NRI composite scores, which adds together the risk from all 18 hazard types. 

Data can be downloaded from FEMA's [Resilience Analysis and Planning Tool](https://experience.arcgis.com/experience/0a317e8998534c30a9b2d3861c814d42/).

**ACS:** The American Community Survey (ACS) is an ongoing survey that provides yearly information about the United States, including social, economic, housing, and demographic data. It differs from the Decennial Census in that it is only sent to a sample of addresses (about 3.5 million) in the 50 states, District of Columbia, and Puerto Rico, every month of every year. The Decennial Census provides population data for every 10 years, but the ACS provides estimates on 1-year and 5-year intervals.

Data can be downloaded using the [tidycensus](https://walker-data.com/tidycensus/) package, which is completed in the HW3.qmd.

Data information sourced from the [Homework 2 assignment](https://eds-240-data-viz.github.io/course-materials/assignments/HW2.html) description.

## Repository Structure
```
├── HW2.qmd
├── HW3.qmd
└── README.md
```
## Course Information

-   **Course Title:** [EDS 240 - Data Visualization & Communication](https://eds-240-data-viz.github.io/)
-   **Term:** Winter 2026
-   **Program:** [UCSB Masters in Environmental Data Science](https://bren.ucsb.edu/masters-programs/master-environmental-data-science).

Teaching Team:

-   **Instructor:** [Sam Shanny-Csik](https://github.com/samanthacsik)
-   **Co-Instructor:** [Annie Adams](https://github.com/annieradams)

Complete materials for this homeowork assignment can be found on the [course website](https://eds-240-data-viz.github.io/course-materials/assignments/HW1.html).

*This README was adapted from the README template provided in EDS220; see course details and original repository [here](https://github.com/sofiasarak/eds220-2025-in-class).*
