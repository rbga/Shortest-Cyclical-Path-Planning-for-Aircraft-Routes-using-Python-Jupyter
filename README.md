# Aircraft Network Analysis with Python

This project focuses on analyzing aircraft networks using Python and various libraries like Pandas, Openpyxl, Numpy, and Matplotlib. The project aims to extract data from an Excel file, build an adjacency list representation of aircraft networks, perform Depth First Search (DFS) on the networks, and visualize the results.

**Note: The original Jupyter Notebook containing the code and detailed results is not available in this repository as it was deleted before uploading to Git. However, you can view the PDF file in the repository to get an overview of the code and some results.**

## Table of Contents
- [Introduction](#introduction)
- [Dependencies](#dependencies)
- [Data Extraction](#data-extraction)
- [Adjacency List Creation](#adjacency-list-creation)
- [Depth First Search (DFS)](#depth-first-search-dfs)
- [Results](#results)
- [Visualization](#visualization)

## Introduction
The project uses Python to analyze aircraft network data and perform network-related operations. The main tasks include:
- Reading aircraft network data from an Excel file.
- Constructing an adjacency list representation of the aircraft networks.
- Performing Depth First Search (DFS) on each aircraft's network.
- Visualizing the results with plotted graphs.

## Dependencies
To run this project, you need to have the following Python libraries installed:
- Pandas
- Openpyxl
- Numpy
- Matplotlib

Install the required libraries using the following command:
```
pip install pandas openpyxl numpy matplotlib
```

## Data Extraction
The data is extracted from the 'dat.xlsx' file, which contains information about aircraft networks. The 'Origin City' and 'Destination City' columns are extracted and stored in separate variables for further analysis.

## Adjacency List Creation
The project creates an adjacency list representation of the aircraft networks using the extracted 'Origin City' and 'Destination City' data. The Graph class is used to create and store the adjacency list for each aircraft/fleet.

## Depth First Search (DFS)
Depth First Search is applied to each aircraft's network to traverse the nodes and generate results for each fleet.

## Results
The results of the Depth First Search (DFS) for all 25 aircraft fleets are stored in a DataFrame and saved to an Excel file named 'data.xlsx'.

## Visualization
The project utilizes Matplotlib to visualize the aircraft network results. The Depth First Search (DFS) results for each aircraft are plotted and displayed as graphs.

Please note that you need the 'dat.xlsx' file containing the aircraft network data in the same directory as this notebook to run the code successfully.

Feel free to explore the PDF file and experiment with the aircraft network analysis in Python!
