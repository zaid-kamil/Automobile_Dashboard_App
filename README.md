# Automobile Dashboard App

[Video Demo](https://www.youtube.com/watch?v=SqKjYOzeKZw)

This repository contains a Streamlit application for analyzing automobile data. The app provides various functionalities to visualize and explore the data, including numerical analysis, textual analysis, and correlation analysis.

## Features

- **Load and Preprocess Data:** The app loads the automobile data from a CSV file, preprocesses it by handling missing values, fixing data types, and dropping unnecessary columns.
- **Display Raw Data:** Users can view the raw data in a tabular format.
- **Column-wise Data Types and Summary:** Provides a summary of column-wise data types and statistics for numerical and textual data.
- **Numerical Analysis:** Visualize numerical data using line charts and histograms.
- **Textual Analysis:** Analyze textual data using pie charts and bar charts.
- **Correlation Analysis:** Explore correlations between numerical and categorical data using scatter plots and box plots.
- **1D Distribution:** Visualize the distribution of selected columns using a sunburst chart.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/zaid-kamil/Automobile_Dashboard_App.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Automobile_Dashboard_App
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Run the Streamlit application:
```bash
streamlit run app.py
```

## File Structure

- `app.py`: Main application file containing the Streamlit code.
- `data/Automobile_data.csv`: CSV file containing the automobile data.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
