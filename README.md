# Belly Button Challenge

![Dashboard Preview](https://github.com/SakinaJaffri/Belly-Button-Challenge/assets/146900226/410416e7-f1aa-4a8b-afa4-5c9022a0139c)

## Project Overview

This project involves building an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbial composition of human navels. The goal is to visualize the prevalence of microbial species, also known as operational taxonomic units (OTUs), across different individuals.

## Functions and Features

### 1. **init()**
- Retrieves the dataset using D3.js.
- Calls helper functions (`getData()` and `panel()`) to initialize the visualizations and demographic information panel.

### 2. **updateChange()**
- Triggered when a new option is selected from the dropdown.
- Updates the visualizations and demographic panel for the selected Test Subject ID.

### 3. **optionChanged(selectedValue)**
- Updates the charts (bar, bubble, and gauge) using the selected Test Subject ID.
- Clears any previous data before plotting new visualizations.

### 4. **panel(response, dataset)**
- Populates the demographic information panel with data for the selected individual.
- Clears the existing data before adding new demographic details.

## Visualizations

### 1. **Bar Chart**
- Displays the top 10 OTUs for the selected individual based on the Test Subject ID.

### 2. **Bubble Chart**
- Visualizes the distribution of OTUs.
  - **X-axis**: OTU IDs.
  - **Y-axis**: Sample values.
  - **Marker Size**: Reflects the sample values.
  - **Marker Color**: Represents OTU IDs.

### 3. **Gauge Chart**
- Displays how many times the test subject washed their belly button per week.

## How to Use

1. Clone the repository to your local machine.
2. Open the `index.html` file in your browser.
3. Explore the interactive visualizations by selecting different Test Subject IDs from the dropdown.

## Technologies Used

- **D3.js**: For data retrieval and manipulation.
- **Plotly.js**: For creating dynamic charts (bar, bubble, and gauge charts).
- **HTML/CSS/JavaScript**: For creating the dashboard layout and interactivity.

## Conclusion

This dashboard provides a user-friendly interface for exploring the microbial composition of human belly buttons. By dynamically updating charts and demographic information, it offers insightful visualizations of the diversity of microbial species found in different individuals.

## Contributors

- **Sakina Jaffri** - Developed the dashboard and visualizations.
