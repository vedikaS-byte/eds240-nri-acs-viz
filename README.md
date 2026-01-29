# Homework #2 (Visualizing FEMA NRI Data)

\*The full assignment description is available on the [course website](https://eds-240-data-viz.github.io/course-materials/assignments/HW2.html).

## Description

This repository contains the code used to explore and visualize [FEMA’s National Risk Index (NRI)](https://hazards.fema.gov/nri/) data for U.S. counties. The analysis focuses on analyzing how counties differ in their susceptibility to natural hazards by comparing risk levels both within and across states. The workflow includes data cleaning and wrangling to ensure suitability for visualization, as well as utilizing R and `ggplot2` to create an effective and accessible visualization.

The graph produced in this analysis is designed to quantify and highlight patterns in natural disaster risk, such as comparing California counties to those in other states based on an assigned composite (overall) score at the county-level. This visualization aims to support insights into community vulnerability and resilience, as well as clearly convey data driven messages about natural hazard risk in California compared to other states.

## Contents

This repository is organized as follows and contains:

-   `README.md`: Markdown file detailing repository description, content, structure, data access, and references.

-   `eds-240-hw-2.qmd`: File containing the code relevant to the analysis of county-level FEMA NRI scores.

-   `eds-240-hw-2.qmd`: Rendered PDF of `eds-240-hw-2.qmd`.

-   `.gitignore`: File containing shortcut to ignore pushing large data files.

```         
├── eds240-nri-acs-viz.Rproj
├── eds-240-hw-2.pdf
├── eds-240-hw-2.qmd
├── README.md
└── .gitignore
```

## Data Access

\*The data utilized in this analysis is not housed in this repository.

The data used in this project is obtained from FEMA’s [National Risk Index (NRI)](https://www.fema.gov/flood-maps/products-tools/national-risk-index) for natural hazards. The NRI provides open-access information on expected annual loss, social vulnerability, and community resilience for U.S. counties. It includes both hazard specific and composite risk scores, along with qualitative risk ratings ranging from “Very Low” to “Very High.” The dataset is publicly available through FEMA’s [Resilience Analysis and Planning Tool (RAPT)](https://hazards.fema.gov/nri/).

## Contributors

This repository is maintained by Vedika Shirtekar as part of the Master of Environmental Data Science program at UC Santa Barbara. This work was completed for the **EDS 240: Data Visualization and Communication** course at the Bren School of Environmental Science and Management, which provided data access and documentation practices, as well as assignment instructions.

## References

[1] EDS 240. (n.d.). *Data Visualization & Communication*. Bren School of Environmental Science and Management. Accessed January 27, 2026, from <https://eds-240-data-viz.github.io/>

[2] Resilience Analysis and Planning Tool (RAPT). (2025). Federal Emergency Management Agency. Accessed January 27, 2026, from <https://www.fema.gov/emergency-managers/practitioners/resilience-analysis-and-planning-tool>
