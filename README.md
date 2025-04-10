# election-model-demo-2024

This is not a very good election model. It is meant to teach linear regressions.


### Data Files

- `cleaned_and_merged_data.csv` - Processed dataset used for modeling, containing merged election results and census data with the following key variables. 
    > ⚠️ Note - this includes methodological choices made in `01-prepare-data.ipynb` which you MUST REVIEW.
- `data/` - Directory containing raw data files

### Jupyter Notebooks

#### `01-prepare-data.ipynb`
   - Loads raw election data from county-level presidential results
   - Retrieves census demographic data via the Census API
   - Calculates percentage variables (e.g., percent white, black, hispanic)
   - Computes population density using geographic information
   - Merges election results with demographic data
   - Cleans and processes the data
   - Exports the final dataset to `cleaned_and_merged_data.csv`

#### `02-election-model.ipynb`
   - Loads the processed dataset
   - Has a demo regression model replete with
        - Model diagnostics
        - Residual analysis

🤖 README generated with the help of Claude 3.7 Sonnet