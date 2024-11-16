# Overview:
This project involves web-scraping and analysis of data related to Mars. The activity is divided in two parts.
## Part 1: Scrape Titles and Preview Text from Mars News
This part of the project uses automated browsing with **Splinter** to visit the Mars news site and extract HTML code, which is then parsed with **Beautiful Soup**. The titles and preview texts of the news articles are scraped and stored as pairs in Python dictionaries, where each dictionary contains:
* `title`: The title of the news article.
* `preview`: A short preview text of the article.

All extracted dictionaries are stored in a Python list for easy access and further analysis.

## Part 2: Scrape and Analyze Mars Weather Data
In this part, an HTML table containing Mars weather data is scraped and transformed into a **Pandas** DataFrame for analysis. The following steps were taken:
1. **Data Extraction**: Splinter and Beautiful Soup were used to scrape the HTML table from the source.
2. **Data Cleaning**: Columns were appropriately named, and data types were cast to ensure consistency.
3. **Analysis**:
   - Calculated the total number of unique months on Mars.
   - Counted the total number of Martian days (sols) represented in the dataset.
   - Found the average minimum daily temperature for each month to identify the coldest and warmest months, and plotted these results in a bar chart using **Matplotlib**.
   - Analyzed atmospheric pressure to identify months with the lowest and highest values, with results also visualized in a bar chart.

## Tools and Libraries
* **Splinter**: Used for browser automation and web interaction.
* **Beautiful Soup**: Employed for parsing HTML and extracting relevant data.
* **Pandas**: Utilized for data manipulation and analysis.
* **Matplotlib**: Used for creating visualizations to showcase analysis results.

## Output
The cleaned and analyzed data is exported as a CSV file.









