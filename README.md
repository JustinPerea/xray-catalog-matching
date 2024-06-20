# xray-catalog-matching
This project aims to crossmatch X-ray sources in the galaxy IC 342 with catalog sources in SIMBAD and Gaia. The primary goal is to ensure that we exclude any foreground objects or non X-ray binary sources from our final X-ray source list. 
## Project Objectives

- Crossmatch the X-ray source catalog of IC 342 with SIMBAD and Gaia catalogs.
- Identify and exclude foreground objects and non X-ray binary sources.
- Refine the final list of X-ray sources to ensure accurate representation of X-ray binaries in IC 342.

## Methods

- Utilize astronomical libraries such as Astropy and pandas for data manipulation and analysis.
- Implement crossmatching algorithms to find matches between the X-ray sources and catalog entries in SIMBAD and Gaia.
- Analyze and validate the matched sources to filter out non-relevant objects.

## Tools and Libraries

- **Python**: Primary programming language for analysis.
- **Jupyter Notebook**: For interactive data analysis and documentation.
- **Astropy**: For handling and analyzing astronomical data.
- **pandas**: For data manipulation and analysis.
- **Matplotlib**: For visualizing the data and results.

## Expected Outcomes

- A refined catalog of X-ray sources in IC 342, excluding foreground objects and non X-ray binaries.
- Improved understanding of the X-ray binary population in IC 342.
- Documentation and scripts that can be reused or adapted for similar crossmatching projects.

## Folder Structure

- `notebooks/`: Contains Jupyter Notebook files for data analysis and crossmatching.
- `data/`: Contains raw and processed data files.
- `scripts/`: Contains Python scripts used for crossmatching and analysis.
- `docs/`: Contains additional documentation.

## Getting Started

To get a local copy of the project up and running, follow these steps.

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python packages (listed in `requirements.txt`)

### Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/xray-catalog-matching.git