Lightning Strikes Data Analysis (2019)

Project Overview

This project analyzes lightning strike data across U.S. states using the dataset `Lightning_Data_2019_and_Average.csv`. It includes:

- Grouping data by state and calculating total strikes
- Mapping full state names to abbreviations
- Visualizing the data using a choropleth map with Plotly
- Python notebook for analysis and visualization

Files in Repository

- `lightening.ipynb` – Jupyter notebook with all code and visualizations
- `Lightning_Data_2019_and_Average.csv` – The dataset used
- `README.md` – Project documentation

Visualization Sample

Using Plotly, the project generates a USA choropleth map that displays the total number of lightning strikes per state in 2019.

python
fig.update_layout(
    width=1000,
    height=700,
    title="Total Lightning Strikes by State (2019)"
)


Requirements

To run this project, install the following Python libraries:

bash
pip install pandas plotly


🔍 Example Use Cases

- Understand lightning distribution geographically
- Compare 2019 lightning data with historical averages
- Risk analysis and climate visualization



This dataset is intended for educational and non-commercial research purposes.

