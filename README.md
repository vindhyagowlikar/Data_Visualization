# Data_Visualization

Week 4: Data Visualization
Overview
This project demonstrates basic data visualization in Python using weather and sales data. The notebook reads data from weather_data.csv, creates five visualizations, displays them, and saves each chart as a PNG image.
Visualizations
1. Temperature by Date (Line Plot) — shows how temperature changes over time.
2. Temperature Distribution (Histogram) — shows the frequency distribution of temperature values.
3. Humidity vs Temperature (Scatter Plot) — explores the relationship between humidity and temperature.
4. Rainfall vs Sales (Scatter Plot) — explores the relationship between rainfall and sales.
5. Correlation Heatmap — displays correlations between Temperature, Humidity, Rainfall, and Sales.
Requirements
- Python 3
- Jupyter Notebook
- pandas
- matplotlib
- seaborn
Install the required libraries:
pip install pandas matplotlib seaborn jupyter
Dataset
Place weather_data.csv in the same directory as w4_data_vis.ipynb.
The CSV file must include these columns:
- Date
- Temperature
- Humidity
- Rainfall
- Sales
The notebook expects these exact column names.
How to Run
1. Download or clone this project.
2. Ensure weather_data.csv is in the same folder as the notebook.
3. Install the required Python libraries.
4. Open the notebook in Jupyter Notebook or JupyterLab.
5. Run all cells.
Example:
jupyter notebook w4_data_vis.ipynb
Output Files
When the notebook runs successfully, it saves these charts in the current directory:
- temperature_lineplot.png
- temperature_histogram.png
- humidity_temperature.png
- rainfall_sales.png
- correlation_heatmap.png
Technologies Used
- Python — programming language
- Pandas — loading and handling tabular data
- Matplotlib — line plot and histogram creation
- Seaborn — scatter plots and correlation heatmap
Note
The notebook imports weather_data.csv directly. The dataset is not included with the notebook, so provide the CSV file separately before running the code.
