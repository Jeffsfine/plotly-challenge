# Belly Button Biodiversity

## Background
This interactive dashboard explores the Belly Button Biodiversity Dataset. This dataset catalogs the microbes that colonize human navels. The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

The dashboard was built with interactive charts to help explore the dataset. 
The entire set of graphics are controlled by selecting the Test Subject ID from the dropdown on the top left side of the dashboard.

## Bar Chart

Here the `samples.json` file was read by using the D3 library.
That information was used to create a horizontal bar chart with the top 10 OTUs found in that individual (displayed in dropdown).
The hover text comes from (`otu_labels` ). 



## Bubble Chart

The bubble chart was created using:
- `otu_ids` for the x values.
- `sample_values` for the y values.
- `sample_values` for the marker size.
- `otu_ids` for the marker colors.
- `otu_labels` for the text values.



## Demographic Information 
This box shows demographic information of the currently selected test subject.
This data is given by the sample metadata.


## Gauge Chart

The Gauge Chart quickly shows the weekly washing frequency of the individual.



# Dashboard in action



## Deployment

The dashboard is deployed publicly on GitHub Pages [here.]()
