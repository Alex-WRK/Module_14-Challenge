# Bellybutton Biodiversity Dashboard

The Bellybutton Biodiversity Dashboard is an interactive web application for exploring microbial diversity in bellybutton samples. This dashboard provides visualizations, including bar charts, bubble charts, and a gauge chart, to help users understand the microbial composition of different subjects' bellybuttons. Users can select a specific test subject ID to view corresponding data.

## Technologies Used

- **HTML:** The project's front-end structure is built using HTML, providing the foundation for content and layout.

- **JavaScript:** JavaScript is used to add interactivity to the web application. It handles data loading, chart rendering, and updating content based on user interactions.

- **D3.js:** D3.js is a JavaScript library used for data visualization. It's utilized to create the bar chart and bubble chart in the dashboard.

- **Plotly:** Plotly is another JavaScript library used for creating interactive data visualizations. It's used for rendering the bar chart and bubble chart.

## Features

- **Selection of Test Subject ID:** Users can select a specific test subject ID from a dropdown menu, which dynamically updates the charts and metadata displayed on the page.

- **Bar Chart:** Displays the top 10 Operational Taxonomic Units (OTUs) found in the selected individual. The chart uses sample values as the bar heights, OTU IDs as labels, and OTU labels as hover text.

- **Bubble Chart:** Represents each sample's microbial diversity, with OTU IDs on the X-axis, sample values on the Y-axis, marker size based on sample values, marker colors based on OTU IDs, and hover text showing OTU labels.

- **Demographic Information:** Displays metadata, including demographic information such as age, ethnicity, gender, location, and more for the selected individual.

- **Gauge Chart:** Visualizes the weekly washing frequency of the selected individual. The chart is updated based on the selected individual's data.

## Usage
Open the web application in your web browser using [this link](https://alex-wrk.github.io/Module_14-Challenge/)

From the "Select a Test Subject ID" dropdown, choose a test subject ID to explore.

The page will update to display the following information for the selected individual:

Bar chart showing the top 10 OTUs.
Bubble chart displaying microbial diversity.
Demographic information.
Gauge chart showing the weekly washing frequency.

#### References
Hulcr, J. et al. (2012) A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable. Retrieved from: http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/Links to an external site.

###### All codes used are from week 14 classes and troubleshooting was done with ChatGPT 
