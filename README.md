# belly-button-challenge Module 14

In this assignment, you will build an interactive dashboard to explore the Belly Button Biodiversity dataset Links to an external site., which catalogs the microbes that colonize human navels.
The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

Dashboard Features:

Dashboard comprises of :
Drop Down Menu: select the test subject id no. to visualize the garph and charts.

Demographic Info Panel: it displays the demographics information of the chosen subject id.

Bar chart: The top 10 OTUs found in that test subject will be displayed in bars, where the sample_values are presented as the values for the bar chart and the otu_ids presented as the labels for the bar chart
When a user hover over a bar, the otu_labels are presented as the hovertext for the chart

Gauge chart: the value of scrubs per week is displayed on the chart.

Bubble chart: larger the sample value large the size of bubble. 
On the chart, the x values are the otu_ids, the y values are the sample_values
The colors of the bubbles are based on otu_ids, and the hovertext are the otu_labels