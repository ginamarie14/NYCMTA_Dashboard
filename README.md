# NYCMTA_Dashboard
NYC MTA Dashboard: What does access to public transportation look like across the 5 boroughs?

This interactive dashboard gives an image of access to public transit across New York City's five boroughs. The inspiration behind this is actually the reason I joined MADS; as a graduate in geography specializing in urban development and regional planning, I have long looked for ways to better urban spaces and make them more accessible for the people that live in them. A big driver in urban accessibility, or accessibility anywhere, is the means of transportation available to the public. 

Paris, France is now known as the 15-minute city, because you can access schools, pharmacies, banks, public transportation, hospitals, supermarkets, and restaurants within 15 minutes of any point. This has been proven to improve quality of life across multiple aspects, including more resilient local economies, reduced traffic, and access to educational and cultural resources.

While New York City is more than 10x larger than Paris, the possibility exists to imagine a 30-minute city in the same vain, and it is my belief that access to public transportation is the first step in achieving such a feat. For this reason, I believe that the first step to improving urban planning in New York would be to evaulate the current state of public transportation across the boroughs.

This project uses Plotly and Dash.

## Features

- **Interactive choropleth map** showing subway station density by neighborhood
- **Comparative bar chart** of stations across top neighborhoods
- **Time-series line chart** displaying service frequency by hour of day
- **Scatter plot** exploring the relationship between population density and transit access
- **Interactive filters** to explore different boroughs and station count thresholds

## Setup Instructions

### Prerequisites

- Python 3.7 or higher
- Jupyter Notebook or JupyterLab

### Installation

1. Clone this repository:
   ```
   git clone https://github.com/ginamarie214/NYCMTA_Dashboard.git
   cd NYCMTA_Dashboard
   ```

2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook:
   ```
   jupyter notebook
   ```

4. Open the `nyc_mta_dashboard.ipynb` notebook and run all cells

### Data Sources

This project uses the following public data sources:

- MTA GTFS data (subway routes, stops, and schedules)
- NYC Neighborhood Tabulation Areas (NTAs)
- NYC Population data by neighborhood

The notebook automatically downloads these datasets when run.

## Dashboard Usage

- Use the **Borough dropdown** to filter to a specific borough or view all boroughs
- Adjust the **Station Count slider** to filter neighborhoods by their number of subway stations
- Hover over map areas to see detailed information about each neighborhood
- Click on legend items to filter visualizations by borough
