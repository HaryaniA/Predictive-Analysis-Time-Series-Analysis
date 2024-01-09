# Time-Series-Analysis
Primary objective is to understand the underlying patterns, trends, and structures within the temporal data to make informed decisions, predictions, or to gain insights into the behavior of the system over time

### Overview:

This repository hosts the code implementation for a time series analysis project focused on human activity recognition using accelerometer data. The project involves selecting and processing time series data for two subjects engaged in walking, running, climbing up, and climbing down activities. Two visibility graph techniques, Natural Visibility Graph (NVG) and Horizontal Visibility Graph (HVG), are applied to the accelerometer data, and various metrics are computed for analysis.

### Project Tasks

1. Data Selection: 
Select a sample size of 1024 points (from 1000 to 2023) for each of the chosen 2 subjects.

2. Visibility Graphs: 
Apply NVG and HVG to each accelerometer signal for walking, running, climbing up, and climbing down.
A total of 48 graphs will be generated (2 subjects * 3 accelerometer directions * 4 activities).

3. Graph Metrics: 
For each graph, compute the average degree, network diameter, and average path length.

4. Tabulated Results: 
Tabulate the computed metrics in a table format.

5. Scatter Plots - Walking and Running
Generate scatter plots of average degree vs network diameter, coloring the points according to walking and running.
Do this for each accelerometer signal and each method (NVG and HVG).

6. Scatter Plots - Climbing Up and Climbing Down
Generate scatter plots of average degree vs network diameter, coloring the points according to climbing up and climbing down.
Do this for each accelerometer signal and each method (NVG and HVG).

### Tools and Libraries

Python: Programming language used for code implementation.

NumPy, Pandas: Libraries for data manipulation and analysis.

Matplotlib: Library for data visualization.

NetworkX, ts2vg: Library for network analysis, used for graph-related operations.


Feel free to explore the code files for detailed implementation and results. If you encounter any issues or have questions, please refer to the documentation or contact the project contributors.


Happy Analyzing!
