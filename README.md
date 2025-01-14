# Avacado_Project
# Avocado Prices: Descriptive Analysis

This project analyzes the weekly 2018 retail scan data for Hass avocados, exploring factors such as price trends, types of avocados, and volume sold. The dataset provides insights into the retail prices and sales volumes, with features such as date, type (conventional or organic), and regional data.

## Dataset Description

The dataset contains the following columns:
- `Date`: Observation date.
- `AveragePrice`: Average price of a single avocado.
- `type`: Avocado type - conventional or organic.
- `year`: Observation year.
- `Region`: City/region of the observation.
- `Total Volume`: Total avocados sold.
- `4046`, `4225`, `4770`: Volume of specific avocado types based on PLU codes.

Renamed PLU codes for clarity:
- `4046`: Small Hass.
- `4225`: Large Hass.
- `4770`: Extra Large Hass.

## Key Analysis Steps

1. **Data Cleaning**:
   - Dropped unnecessary columns like the unnamed index column.
   - Renamed PLU code columns for better readability.

2. **Descriptive Statistics**:
   - Summarized data statistics using `describe()`.
   - Calculated mean and standard deviation for `AveragePrice`.

3. **Unique Values and Distribution**:
   - Explored unique values and counts for categorical columns (`type`).
   - Visualized distribution of `AveragePrice` using histograms and box plots.

4. **Type-Based Analysis**:
   - Grouped data by `type` and compared descriptive statistics.
   - Examined `AveragePrice` distributions for conventional and organic types.

5. **Visualizations**:
   - Distribution plots for average prices.
   - Boxplots to compare price variations between types.

## Visualizations

- Histograms show the overall price distribution and type-based distribution.
- Boxplots compare the price variation for conventional and organic avocados.

## License
- This project is licensed under the MIT License - see the LICENSE file for details.
  
## Author
- Mirmoy Kumar Mallick
- LinkedIn Profile: linkedin.com/in/mirmoy-kumar-mallick
- Email: mirmoykumarmallick99@gmail.com
