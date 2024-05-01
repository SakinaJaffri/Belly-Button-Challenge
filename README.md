# Belly-Button-Challenge
![image](https://github.com/SakinaJaffri/Belly-Button-Challenge/assets/146900226/410416e7-f1aa-4a8b-afa4-5c9022a0139c)


## Background:
This interactive dashboard is designed to explore the Belly Button Biodiversity dataset, which records the microbial composition of human navels in JSON format. The dataset reveals that a small number of microbial species, known as operational taxonomic units (OTUs), are prevalent in more than 70% of individuals, while the remainder are relatively rare.

## Functions:
1. **init():**
   - Retrieves the dataset using D3.js.
   - Calls the getData() and panel() functions to prepare the data for visualization and update the demographic information panel, respectively.

2. **updateChange():**
   - Triggered when an option in the dropdown menu changes.
   - Retrieves the selected option and updates the demographic information panel and visualizations using the getData() and panel() functions.

3. **optionChanged(selectedValue):**
   - Plots the data using Plotly based on the selected value from the dropdown menu.
   - Clears existing HTML elements before plotting new data.

4. **panel(response, dataset):**
   - Retrieves required data and updates the demographic information panel.
   - Clears existing panel values before adding new ones.

## Visualizations:
1. **Bar Chart:**
   - Displays the top 10 OTUs found in the selected individual based on the Test Subject ID.

2. **Bubble Chart:**
   - Shows the distribution of OTUs.
   - X-axis: OTU IDs.
   - Y-axis: Sample values.
   - Marker size indicates sample values, and marker color represents OTU IDs.
   - Hover text displays OTU labels.

3. **Gauge Chart:**
   - Indicates the number of times test subjects washed their belly buttons per week.

## Additional Features:
- Options are dynamically added to the dropdown menu with values as attributes.

## Conclusion:
This dashboard provides an interactive platform for exploring the Belly Button Biodiversity dataset, allowing users to visualize and analyze the microbial composition of human navels. With its user-friendly interface and informative visualizations, it offers valuable insights into the diversity of microbes inhabiting the human body.
