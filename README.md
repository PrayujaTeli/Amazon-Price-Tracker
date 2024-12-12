Here’s the updated content with the video explanation link added:

```markdown
# Amazon Product Scraper and Data Analysis

## Project Overview

This project automates web scraping to extract product data from Amazon, cleans and analyzes the data, and generates visual insights. Key features include:
- Automated scraping of product details such as description, price, rating, and review count using **Selenium** and **BeautifulSoup**.
- Data cleaning and transformation using **Pandas**.
- Data visualization and statistical analysis using **Matplotlib** and **Seaborn**.

The script saves raw, cleaned, and summarized data in CSV format and creates visual plots to explore key trends.

---

## Video Explanation

For a detailed walkthrough of the project, watch the [video explanation here](https://1513041.mediaspace.kaltura.com/media/DSCI511/1_3rlpcddc).

---

## Setup and Installation

### Prerequisites
- Python 3.8 or higher
- Libraries: `selenium`, `beautifulsoup4`, `pandas`, `matplotlib`, `seaborn`
- Microsoft Edge browser and its corresponding WebDriver

### Installation
1. Install required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
2. Download the [Edge WebDriver](https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/) and update the path in the script (`Service` object) accordingly.

---

## Usage

### 1. Web Scraping
- Run the script:
  ```bash
  python Amazon_WebScraper_14648101.ipynb
  ```
- Provide search terms when prompted (e.g., `ultrawide monitor, gaming laptop`).
- Scraped data will be saved in `all_results.csv`.

### 2. Data Cleaning
- The script removes rows with missing values and saves the cleaned data to `cleaned_results.csv`.

### 3. Analysis and Visualization
- Visualizations are generated and saved as PNG files:
  - `data_summary_plots.png`: Overview of data distribution.
  - `correlation_heatmap.png`: Correlation matrix.
  - `pairplot_relationships.png`: Pairwise relationships between features.

---

## Project Structure
```
amazon-scraper/
├── Amazon_WebScraper_14648101.ipynb    # Script
├── requirements.txt                    # List of required Python libraries
├── all_results.csv                     # Raw scraped data
├── cleaned_results.csv                 # Cleaned data
├── data_summary.csv                    # Summary statistics
├── data_summary_plots.png              # Data distribution plots
├── correlation_heatmap.png             # Correlation matrix heatmap
└── pairplot_relationships.png          # Pairwise feature relationships
```

---

## Challenges and Limitations

### Challenges
- **Dynamic Page Content**: Amazon frequently updates its web design, which may break the scraper. Maintaining compatibility requires continuous monitoring and updates to the code.
- **Data Inconsistencies**: Some product listings lack consistent details (e.g., missing price or reviews), leading to incomplete data.

### Limitations
- **IP Blocking**: Excessive scraping may result in temporary bans. 
- **Data Accuracy**: The scraped data reflects accurate product information, but discrepancies may exist due to currency, region, or seller misrepresentation.

---

## Contact
- **Author**: Prayuja Teli
- **Email**: pst29@drexel.edu
```

