# Energy Storage Financial Analytics Dashboard
Part of my portfolio → [jefferynketiah.com](https://jefferynketiah.com)

An automated data pipeline written in Python that extracts, cleans, and visualizes market capitalization data and revenue performance for key entities in the grid-scale and next-generation battery sectors.

## Project Architecture
- **Data Acquisition:** Utilizes the `yfinance` API to retrieve maximum historical share prices and structural corporate balance sheets.
- **Data Engineering:** Dynamically transposes quarterly metrics, handles missing inputs, converts object types, and normalizes standard revenue scales into millions USD.
- **Visualization:** Renders synchronized, dual-panel time-series plots via `Plotly` to map capital market valuations directly against operational earnings.

## Target Companies Analyzed
1. **QuantumScape (QS):** Focusing on solid-state lithium-metal architectures.
2. **Enphase Energy (ENPH):** Representing decentralized microinverters and residential battery modular systems.

## How to Run
1. Install dependencies: `pip install yfinance pandas plotly`
2. Run the notebook: `jupyter notebook Energy_Storage_Dashboard.ipynb`
