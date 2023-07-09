# olympics-data-analysis-web-app
# Olympics Analysis App

This is a Python application built using the Streamlit framework for analyzing Olympic data. It provides various features for exploring and visualizing information about Olympic events, countries, athletes, and medal tallies.

## Installation

To run the application, you need to install the required dependencies. You can do this by running the following command:

```
pip install streamlit pandas plotly matplotlib seaborn
```

Make sure you have the `athlete_events.csv` and `noc_regions.csv` files in the same directory as the Python script.

## How to Use

To run the application, execute the Python script containing the code. It will launch a web-based user interface using Streamlit.

### Sidebar Navigation

The application's sidebar contains navigation options to choose different analysis sections:

- **Medal Tally**: Displays the medal tally for a selected year and country.
- **Overall Analysis**: Shows top statistics about Olympic editions, hosts, sports, events, athletes, and participating nations. It also includes visualizations of participating nations, events, athletes over the years, and a heatmap of the number of events per sport over time.
- **Country-wise Analysis**: Allows selecting a country to analyze its medal tally over the years and its performance in different sports.
- **Athlete-wise Analysis**: Provides insights into the distribution of ages among athletes, distribution of ages based on medal type, a scatter plot of height vs. weight, and a line chart comparing male and female participation over the years.

### Medal Tally

In the **Medal Tally** section, you can select a specific year and country from the sidebar to view the corresponding medal tally. The table will show the number of gold, silver, and bronze medals won by the selected country in the chosen year. If "Overall" is selected for either year or country, the overall medal tally will be displayed.

### Overall Analysis

The **Overall Analysis** section presents various top statistics about the Olympics. It includes the number of editions, host cities, sports, events, athletes, and participating nations. Visualizations show the number of participating nations, events, and athletes over the years. Additionally, a heatmap displays the number of events per sport for each year.

You can also select a specific sport from the dropdown to view the most successful athletes in that sport.

### Country-wise Analysis

In the **Country-wise Analysis** section, you can select a specific country from the sidebar to analyze its performance in the Olympics. A line chart visualizes the country's medal tally over the years. A heatmap displays the number of medals won in each sport by the selected country.

### Athlete-wise Analysis

The **Athlete-wise Analysis** section provides insights into athlete-related data. It includes a distribution plot of ages among all athletes and separate plots for gold, silver, and bronze medalists. Another scatter plot shows the relationship between height and weight for athletes in a selected sport. Lastly, a line chart compares the participation of male and female athletes over the years.

## Conclusion

This Olympics Analysis application offers a range of features to explore and visualize Olympic data. It provides valuable insights into medal tallies, overall statistics, country-wise analysis, and athlete-wise analysis.
A Streamlit web application for the analysis of olympics dataset

Dataset Link: https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results

Live Demo: https://olympic-data-analysis-t92o.onrender.com/
