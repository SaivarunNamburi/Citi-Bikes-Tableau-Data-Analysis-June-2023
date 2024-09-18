# Citi Bike Data Analysis - June 2023

This repository contains the analysis of Citi Bike ride data from June 2023, focusing on identifying patterns in usage, ride duration, peak hours, and high-traffic areas. It also includes recommendations for optimizing bike and scooter placements to improve user availability and system efficiency.

## Overview
In June 2023, over 3.45 million Citi Bike rides were recorded in New York City. The analysis examines:
- Peak ride hours
- Popular start and end stations
- Differences between member and casual user ride behavior
- Usage of classic vs. electric bikes
- Recommendations for bike placement optimization

---

## Key Insights

### 1. **Peak Ride Hours**
- **Busiest Time**: Most rides occurred between **3 PM and 7 PM**, aligning with evening commuting hours.
- **Peak Hours**: 
  - Start Time: 3 PM - 7 PM
  - End Time: 4 PM - 8 PM
- **Implication**: Bikes should be heavily stocked at key locations during evening rush hours.

### 2. **Ride Duration**
- **Classic Bikes**: Average ride duration between **30 and 40 minutes**.
- **Electric Bikes**: Shorter average ride duration, ranging from **20 to 25 minutes**.
- **Insight**: Short trips indicate localized commuting for electric bikes, while classic bikes are used for slightly longer distances.

### 3. **High-Traffic Areas**
The top 3 stations with the highest ride traffic:
1. **11 Ave & W 41 St**
2. **Broadway & W 58 St**
3. **University Pl & E 14 St**

### 4. **User Types**
- **Subscribers (Members)**: Primarily use Citi Bikes for weekday commutes, especially during rush hours.
- **Casual Users**: Ride patterns are more distributed, likely reflecting tourists and leisure riders.

### 5. **Bike Type Usage**
- **Electric Bikes**: Popular among casual users, ideal for short trips.
- **Classic Bikes**: Preferred by subscribers for longer, regular commutes.

---

## Recommendations for Bike Placement Optimization

1. **Reposition Bikes in High-Traffic Areas**:
   - Focus on the top 3 stations: **11 Ave & W 41 St, Broadway & W 58 St, and University Pl & E 14 St**.
   - Ensure adequate bike supply during peak hours (3 PM - 7 PM).

2. **Dynamic Bike Rebalancing**:
   - Use real-time ride data to move bikes from low-demand to high-demand areas during peak hours.

3. **Seasonal and Weather-Based Adjustments**:
   - **Summer and Clear Weather**: Deploy more bikes during weekends and warm weather to accommodate increased demand in tourist areas.
   - **Balance Supply**: Ensure that high-ride-completion areas are restocked to maintain availability.

4. **Support Localized Commuters**:
   - Deploy more **electric bikes** in neighborhoods where short-distance commutes are common to reduce shortages.

---

## Installation and Usage

### Prerequisites
- Ensure you have the following tools installed:
  - [Tableau](https://www.tableau.com) or [Power BI](https://powerbi.microsoft.com) for data visualization.
  - Python (if planning to further analyze the dataset using Python libraries like pandas or matplotlib).

### Data Source
The dataset for June 2023 can be accessed via the [Citi Bike System Data](https://citibikenyc.com/system-data).

### Running the Analysis
1. **Download the Dataset**: Download the June 2023 Citi Bike data from the provided link.
2. **Import the Data**: Import the dataset into Tableau or Power BI.
3. **Visualizations**: Use the provided visualizations to analyze ride patterns, popular stations, and user behaviors.

---

## Files in the Repository

- **datasource link**: Contains the June 2023 Citi Bike dataset (if applicable) (https://citibikenyc.com/system-data)
- **analysis**: Tableau file is exported as pdf format
- **README.md**: This documentation file.
- **Documentation**: Documented in the word docs file

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

## Contact
For any inquiries or further collaboration, feel free to reach out.

---

## Acknowledgements
- The Citi Bike data is provided by the [NYC Citi Bike System](https://citibikenyc.com/system-data).
- Map visualizations are powered by [Mapbox](https://www.mapbox.com/).
