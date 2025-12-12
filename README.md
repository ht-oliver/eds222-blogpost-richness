# "Modeling Precipitation as a Predictor for Fish Species Richness In US Northwest"
##### Author: Henry Oliver, UCSB Bren School of Environmental Science and Management.
##### Date Published: December 11, 2025


# Purpose
This repository houses the contents of the final blog post related to EDS 222 Final Project. This analysis seeks to identify a relationship between precipitation and fish species richness in US Northwest streams and rivers.

# Background
Freshwater fish presence and species richness is a vital metric for stream health. Stream health is intrinsically tied to water quality, water availability, agriculture and industrial processes, making it incredibly important to local economies. Moreover, stream health is a major part of the recreation and tourism economies for stream-rich states like Montana, Wyoming, Idaho and the Dakotas. As global heating trends cause decreases in snowfall and increases in air temperature, these streams are at risk, and so are the fish that swim in them. In order to protect stream life, it's important that we research the relationships between biotic factors and their environment. Precipitation is a key driver of stream conditions, controlling water volume, flow rates, turbidity, and temperature—factors that determine which fish species can thrive in a given stream. By identifying direct relationships between precipitation and species richness, we can build a better idea of how we can expect or freshwater ecological landscape to change in the coming years; and ideally how we can preserve our freshwater resources for future generations.

# Contents
```
├── blogpost.qmd # Rendering this document produces analysis
├── data
│   └── StreamSpeciesDataset_v1_1_3_edited.csv
├── eds222-blogpost-richness.Rproj
├── images
│   ├── big_hole.jpeg
│   ├── data-1.png
│   ├── data-2.png
│   └── study_area.png
└── README.md
```

# Data Access
The data used in the this analysis is the The University of Wyoming Stream Species Dataset[1]. This multi-generational composition is a species presence dataset containing presence locations for 116 freshwater fish species in Wyoming, Montana, and the surrounding states dating back to the year 1900. It contains data from 40,490 unique sample events (location, month, year), and was compiled by combining data from agency databases, the Global Biodiversity Information Facility, university theses, peer-reviewed literature, grey-literature reports, and unpublished data from the University of Wyoming. Please note that absence (0) values only indicate that a species was not recorded by observers and should not be used as true absences in analyses. Data is present in the `data` folder in the repository.

# References

[1]Clancy, N. (2024). Dataset of species presence locations for 116 freshwater fish species in Wyoming, Montana, and the surrounding states from 1800–2022 (U.S. Geological Survey data release). U.S. Geological Survey. https://doi.org/10.5066/P13OGUSE

