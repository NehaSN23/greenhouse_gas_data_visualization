# Greenhouse Gas Emissions Analysis Project

## Project Overview
This project focuses on analyzing greenhouse gas emissions across various countries, industries, and categories. The dataset provides detailed information about emissions sources, quantities, and distributions, enabling insights into trends, sectoral contributions, and geographical patterns over time. The analysis aims to support decision-making for sustainability and policy interventions by providing visualizations and data-driven insights.

---

## Dataset Details
The primary dataset used in this project is `greenhouse_gas_emissions_dataset.csv`. It contains detailed information about greenhouse gas emissions, with the following columns:

### Column Names and Data Types
| Column Name                  | Data Type     | Description                                                                 |
|------------------------------|---------------|-----------------------------------------------------------------------------|
| `iso3_country`               | String        | 3-letter ISO country code (e.g., `USA`, `IND`, `CHN`)                      |
| `start_time`                 | DateTime      | Start date of the record (e.g., `2015-01-01`)                              |
| `end_time`                   | DateTime      | End date of the record (e.g., `2015-12-31`)                                |
| `original_inventory_sector`  | String        | Sector responsible for emissions (e.g., `electricity-generation`)          |
| `gas`                        | String        | Type of greenhouse gas (e.g., `CO2`, `CH4`, `N2O`)                         |
| `emissions_quantity`         | Float         | Emissions quantity in tonnes                                               |
| `emissions_quantity_units`   | String        | Unit of emissions quantity (`tonnes`)                                      |
| `temporal_granularity`       | String        | Granularity of data (`annual`, `month`)                                    |
| `created_date`               | DateTime      | Record creation timestamp                                                  |
| `modified_date`              | DateTime      | Record modification timestamp                                              |

### Categories and Subcategories
The dataset includes emissions data grouped into main categories and their respective subcategories:

#### Main Categories and Subcategories
| Main Category               | Subcategories                                                                                     |
|-----------------------------|--------------------------------------------------------------------------------------------------|
| **Agriculture**             | `synthetic-fertilizer-application`, `cropland-fires`, `enteric-fermentation`, `manure-management`, `other-agriculture-soil-emissions`, `rice-cultivation` |
| **Buildings**               | `other-onsite-fuel-usage`, `residential-and-commercial-onsite-fuel-usage`                        |
| **Flourinated Gas**         | `fluorinated-gases`                                                                              |
| **Fossil Fuel Operations**  | `coal-mining`, `oil-and-gas-production-and-transport`, `oil-and-gas-refining`, `other-fossil-fuel-operations`, `solid-fuel-transformation` |
| **Manufacturing**           | `aluminum`, `cement`, `chemicals`, `other-manufacturing`, `pulp-and-paper`, `steel`              |
| **Mineral Extraction**      | `bauxite-mining`, `copper-mining`, `iron-mining`, `rock-quarrying`, `sand-quarrying`             |
| **Power**                   | `electricity-generation`, `other-energy-use`                                                    |
| **Waste**                   | `biological-treatment-of-solid-waste-&-biogenic`, `incineration-and-open-burning-of-waste`, `solid-waste-disposal`, `wastewater-treatment-and-discharge` |

---

## Project Objectives
1. **Trends Analysis**:
   - Identify emissions trends across years (e.g., 2015 vs. 2021).
   - Compare main categories and subcategories of emissions over time.
2. **Geographical Insights**:
   - Analyze emissions by country and visualize regional contributions.
   - Generate choropleth maps for emissions distribution.
3. **Sectoral Analysis**:
   - Highlight major contributors to emissions within sectors like `Agriculture`, `Power`, and `Manufacturing`.
   - Use Sankey diagrams to show the flow of emissions between main categories and subcategories.
4. **Data Distribution**:
   - Visualize distributions of emissions quantities using histograms and bar charts.

---

## Visualizations and Insights

### Key Visualizations
1. **Trends Over Time**:
   - Line charts comparing emissions trends for 2015 and 2021.
   - Insights into which sectors increased or decreased their emissions over time.

2. **Geographical Distribution**:
   - **Choropleth Map**: Visualizes emissions across countries, highlighting regions with the highest contributions.

3. **Sectoral Distribution**:
   - **Sankey Diagram**: Shows emissions flow from main categories (e.g., `Agriculture`) to subcategories (e.g., `synthetic-fertilizer-application`).
   - Bar charts display the contributions of sectors over time.

4. **Data Distributions**:
   - Histograms to analyze emissions quantities and their distributions.
   - Comparison of `annual` and `monthly` temporal granularities.

### Key Insights
- **Trends**:
  - Certain sectors, like `Power` and `Manufacturing`, show significant emissions over time.
  - Subcategories such as `electricity-generation` and `cement` are major contributors.

- **Geography**:
  - Countries like the United States, China, and India are significant emitters, as visualized in the choropleth map.

- **Sectoral Analysis**:
  - The `Agriculture` sector has consistent emissions, with key subcategories being `synthetic-fertilizer-application` and `cropland-fires`.
  - The `Waste` sector has significant contributions from `solid-waste-disposal` and `wastewater-treatment-and-discharge`.

---

## Usage and Outputs

### File Outputs
1. **Interactive HTML Visualiza
