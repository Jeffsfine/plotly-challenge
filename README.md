
# Belly Button Biodiversity

## Background
This interactive dashboard explores the Belly Button Biodiversity Dataset. This dataset catalogs the microbes that colonize human navels. The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

The dashboard was built with interactive charts to help explore the dataset. 
The entire set of graphics are controlled by selecting the Test Subject ID from the dropdown on the top left side of the dashboard.

### Bar Chart

Here the `samples.json` file was read by using the D3 library.
That information was used to create a horizontal bar chart with the top 10 OTUs found in that individual (displayed in dropdown).
The hover text comes from (`otu_labels` ). 

![bar](https://user-images.githubusercontent.com/74028387/115791238-18b6ff00-a396-11eb-807e-d8a2ec208208.png)


### Bubble Chart

The bubble chart was created using:
- `otu_ids` for the x values.
- `sample_values` for the y values.
- `sample_values` for the marker size.
- `otu_ids` for the marker colors.
- `otu_labels` for the text values.

![bubble](https://user-images.githubusercontent.com/74028387/115791262-24a2c100-a396-11eb-8073-a9f94cc2b290.png)

### Demographic Information 
This box shows demographic information of the currently selected test subject.
This data is given by the sample metadata.
![demo](https://user-images.githubusercontent.com/74028387/115791273-2a98a200-a396-11eb-92e2-1f05c96234bb.png)


### Gauge Chart

The Gauge Chart quickly shows the weekly washing frequency of the individual.

![gauge](https://user-images.githubusercontent.com/74028387/115791283-2cfafc00-a396-11eb-9f5e-5d5504cb12d0.png)


## Dashboard in action

![overview]

### Deployment

The dashboard is deployed publicly on GitHub Pages [here.](Images/overview.gif)
