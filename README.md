# Sociohydrological Data Repository for Reservoir Operator Behavior and Flood-Drought Tradeoffs

**Title:** Homo juridicus, homo heuristicus, and homo anticipans: a sociohydrological study of operator behavior and flood-drought tradeoffs in reservoirs

## Overview

This data repository contains dataset to support the sociohydrological study on reservoir operator behavior, focusing on flood and drought management tradeoffs. The dataset includes key time series data.

## Repository Contents

The repository consists of the following datasets:

1. **Reservoir Storage Levels (Observed):**
   - **Description:** Actual storage levels of the reservoir over the study period.
   - **Time Step:** Daily
   - **Function:** Provides empirical storage data for analyzing historical reservoir behavior and calibration of models.
   - **Source/Reference:** CA Department of Water Resources (2022)

2. **Reservoir Inflow Sequence:**
   - **Description:** Daily inflow sequence into the reservoir, representing hydrological input.
   - **Time Step:** Daily
   - **Function:** Used as the main input for reservoir simulation models.
   - **Source/Reference:** California Nevada River Forecast Center (CNRFC, 2022)

3. **Flood and Drought Events:**
   - **Description:** Information on major flood and drought events over the study period.
   - **Time Step:** Yearly (Aggregated from detailed records)
   - **Function:** Helps to categorize hydrological extremes for analyzing operator responses.
   - **Source/Reference:** FEMA (Federal Emergency Management Agency)

4. **Model-Simulated Reservoir Storage Levels:**
   - **Description:** Simulated reservoir storage levels from our model, as shown in the qualitative validation section.
   - **Time Step:** Daily
   - **Function:** Used for model validation and comparison with observed storage data.
   - **Source/Reference:** Model-derived data (Refer to study methods for model specifications)


## File Structure

The repository includes the following files:

- **/data/observed_storage.csv**: Observed reservoir storage levels (daily).
- **/data/inflow_sequence.csv**: Daily inflow sequence to the reservoir.
- **/data/flood_drought_events.csv**: Yearly summary of flood and drought events.
- **/data/model_simulated_storage.csv**: Model-simulated reservoir storage levels (daily).

Each file includes a header row describing the data columns and is formatted as a CSV file for accessibility and compatibility with most data analysis software.

## Usage Notes

- **Citation**: When using this dataset, please cite the original study as well as the sources listed above.
- **Restrictions**: Data in this repository is encouraged to use only for academic and research purposes.
- **Contact**: For additional data or specific inquiries, please contact the lead researcher.

## References

1. California Nevada River Forecast Center. (2022). Inflow to the dam. California Nevada River Forecast Center. Retrieved from https://www.cnrfc.noaa.gov/
2. CA Department of Water Resources. (2022). Water storage data. California Department of Water Resources. Retrieved from https://water.ca.gov/
3. FEMA. Flood and drought damage data. Federal Emergency Management Agency. Retrieved from https://www.fema.gov/
