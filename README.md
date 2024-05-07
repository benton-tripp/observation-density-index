# Cross-Species Observation Density Index for Managing Observation Bias in Species Distribution Models

## Overview

This project develops an Observation Density Index (ODI) to correct 
observation biases in species distribution models using citizen science 
data, like [eBird](https://ebird.org/home) observations. The index 
aims to standardize observation efforts and provide a more accurate 
reflection of species distributions by accounting for varying densities 
of data submissions.

## Objectives

- **Develop a Baseline Density Map**: Aggregate observation data across 
  multiple species to establish baseline observer effort.
- **Correct Bias in Species-Specific Models**: Use the baseline density 
  map to correct for observation bias in models of individual species, 
  leading to more accurate predictions.

## Methodology

- **Data Aggregation**: Compile observation data from multiple species to 
  create a comprehensive map of observation densities.
- **Index Calculation**: Calculate the Observation Density Index by 
  comparing species-specific observation frequencies to the baseline map.
- **Model Integration**: Integrate the ODI into existing species distribution 
  models to adjust for localized biases in observation data.

## Expected Outcomes

- **Enhanced Model Accuracy**: Improved accuracy of species distribution 
  models by correcting for the over- or under-sampling inherent in citizen 
  science data.
- **Broader Applicability**: A methodological framework that can be applied 
  to various taxa and geographic regions.
  
## Applied Example

In a practical application of the Observation Density Index (ODI), we 
examined osprey data collected from eBird. The baseline density map was 
first established using general bird observation data across the U.S. We 
then compared this baseline with osprey-specific observations to calculate 
the ODI, identifying areas of potential observation bias. This index was 
integrated into a species distribution model for ospreys, adjusting for 
over-sampling in urbanized areas and under-sampling in less accessible regions. 
This correction aims to enhance the accuracy and reliability of the osprey 
distribution model, providing insights beneficial for conservation efforts.

## References

- **Assessing the effect of sample bias correction in species distribution models**: 
  This study discusses the Relative Overlap Index, which informs the extent of spatial 
  similarity between corrected and uncorrected models relative to the variability between 
  model replicates. The study can be found at 
  [ar5iv](https://ar5iv.labs.arxiv.org/html/2103.07107).


