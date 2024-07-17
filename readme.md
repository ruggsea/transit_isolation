# Transit Isolation

This repository explores ways to calculate time distances to points of interest in cities. In this case, the notebook focuses on calculating the distance to hospitals in Rome.

## Getting Started

To get started with this project, you will need to have the following:

- Jupyter Notebook
- Python 3.x
- Required Python packages (specified in `requirements.txt`)

## Data Sources

- Mobility data: The mobility data used in this project is sourced from the Municipality of Rome Mobility website.
- City boundaries: The city boundaries used in this project are sourced from the Rome Data Portal.

## Project Structure

- `transit_isolation.ipynb`: This is the main Jupyter Notebook containing the code for calculating time distances to hospitals in Rome.
- `data/`: This directory contains the necessary data files for running the notebook.
- `rome_static_gtfs/`: This directory contains the GTFS data for Rome's public transportation system.
- `municipi.geojson`: This file contains the shapefile data for the municipi (city districts) in Rome.

## Usage

To run the notebook, follow these steps:

1. Clone this repository.
2. Install the required Python packages by running `pip install -r requirements.txt`.
3. Open `transit_isolation.ipynb` in Jupyter Notebook.
4. Follow the instructions in the notebook to calculate time distances to hospitals in Rome.

## TODO

- Fix missing stops from the transit graph.
- Optimize the walking distance calculations.
- Calculate the walking distance between hexes so even hexes with no public transport stops can have the time to hospital estimated.

## Contributing

Contributions to this project are welcome. If you have any suggestions or improvements, feel free to open an issue or submit a pull request.
