# GoBike Data Analysis Project

## Project Details

This project was completed as part of the GoBike Data Analysis initiative, focusing on understanding trends, user behaviors, and usage patterns within the Bay Area bike-sharing service. The project was conducted in two parts: an Exploratory Analysis to understand the dataset structure and discover preliminary insights, and an Explanatory Analysis to present key findings that tell a story using polished visualizations.

The primary objective was to identify key metrics that define user habits and investigate differences between user types, such as "Subscriber" and "Customer." The findings are presented in a clear, visual format to communicate insights effectively.

## Dataset

The dataset used in this project consists of detailed information about individual bike trips, including:

- **Trip Details**: Start and end times, station locations, and ride duration.

- **User Attributes**: Age, gender, and user type (Subscriber or Customer).

This dataset offers an opportunity to explore bike-sharing habits in the Bay Area and understand user preferences.

## Summary of Findings

After analyzing the data, several key insights were observed:

- Subscribers are more consistent in their usage throughout the week, indicating that they primarily use the service for daily commuting.

- Customers tend to have higher usage during weekends, with longer ride durations compared to subscribers, suggesting more recreational use.

- Younger users, particularly those aged 20-25, tend to have the longest trip durations, especially among customers.

These insights were supported by visualizations such as bar charts, facet plots, and percentage comparisons to highlight the differences in user behaviors across different demographics and times of the week.

## Key Insights for Presentation

The presentation focused on key trends in user behavior, supported by visualizations:

- **Ride Distribution by User Type and Gender**: A bar chart showing that subscribers make up a significant portion of users for both male and female riders, highlighting regular commuting habits.
- **Average Trip Duration by Age Group and User Type**: A facet plot that demonstrates that younger customers (aged 20-25) have the longest ride durations, averaging 25 minutes, whereas subscribers show more consistency in trip length.
- **Ride Activity by Day of the Week**: A bar chart demonstrating higher weekday usage for subscribers, indicating commuting patterns, while customers have increased weekend activity for leisure.

The visualizations were designed with clear axis labels, titles, and annotations to ensure the insights were accessible and engaging for the audience.

## Files

- `GoBike_Exploratory_Analysis.ipynb`: Jupyter Notebook containing the initial exploratory data analysis, including summary statistics and visual exploration of the dataset.
- `GoBike_Explanatory_Analysis.ipynb`: Jupyter Notebook focused on presenting key insights through polished visualizations and answering specific questions about user behavior.
- `GoBike_Analysis_Presentation.pdf`: A presentation summarizing the key findings and insights from the data analysis.

## How to Use

To explore this project, clone the repository and open the Jupyter Notebooks (GoBike_Exploratory_Analysis.ipynb and GoBike_Explanatory_Analysis.ipynb) to see the complete analysis process. The findings can be reviewed in the presentation file (GoBike_Analysis_Presentation.pdf).

## Requirements

The following Python libraries were used in this project:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

To install the required libraries, run:

```sh
pip install -r requirements.txt
```

# Acknowledgements

- **GoBike**: For providing the data used in this project.

- **Udacity**: For providing the guidance and structure to complete this analysis.

