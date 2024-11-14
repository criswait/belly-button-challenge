# Belly Button Biodiversity Dashboard

Welcome to the Belly Button Biodiversity Dashboard! This interactive dashboard allows users to explore a dataset about the microbes that colonize human navels. The data comes from a study that cataloged various microbial species, also known as Operational Taxonomic Units (OTUs), found in belly buttons.

## Features

- **Demographic Info Panel**: Displays an individual's demographic data such as age, ethnicity, gender, and belly button type.
- **Bar Chart**: Displays the top 10 OTUs present in the selected sample.
- **Bubble Chart**: Shows a bubble chart with each OTU as a point. The size of the bubble represents the abundance of the OTU, and the color represents the OTU ID.
- **Interactive Dropdown**: Users can select a sample to view different sets of data.

## How to Use

1. Visit the app [here](https://criswait.github.io/).
2. Select a sample from the dropdown to see its data visualizations.
3. View demographic information, bar chart of top OTUs, and the bubble chart.

## Technologies Used

- **D3.js**: JavaScript library for data visualization.
- **Plotly.js**: JavaScript library for creating interactive charts.
- **HTML**: For creating the structure of the web page.
- **CSS**: For styling the dashboard.

## Data Source

The data is sourced from a JSON file, which includes a variety of samples and metadata regarding human belly button microbiomes. This dataset is publicly available from [this link](https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json).

## How to Run Locally

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/repository-name.git
