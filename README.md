### Project Description
**Amazon Price Tracker** is a Python-based web scraper that monitors product prices on Amazon and sends email notifications when prices drop below a specified threshold. This tool enhances user engagement by allowing users to make informed purchasing decisions based on real-time price updates.

### README.md

```markdown
# Amazon Price Tracker

## Description
Amazon Price Tracker is a Python-based web scraper that monitors product prices on Amazon and sends email notifications when prices drop below a specified threshold. This tool enhances user engagement by allowing users to make informed purchasing decisions based on real-time price updates.

## Features
- **Price Monitoring**: Continuously tracks the price of a specified product on Amazon.
- **Email Alerts**: Sends email notifications when the product price drops below a set threshold.
- **Data Logging**: Records product price history in a CSV file for analysis.

## Requirements
- Python 3.x
- Libraries: `requests`, `beautifulsoup4`, `pandas`, `smtplib`

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/PrayujaTeli/Amazon-Price-Tracker.git
   cd Amazon-Price-Tracker
   ```

2. Install the required libraries:
   ```bash
   pip install requests beautifulsoup4 pandas
   ```

## Usage
1. Open the Python script and update the product URL and desired price threshold.
2. Replace the email credentials in the `send_mail()` function.
3. Run the script:
   ```bash
   python amazon_price_tracker.py
   ```

4. The script will check the product price every hour and send an email notification if the price drops below the specified threshold.

## Note
Make sure to follow Amazon's terms of service when scraping their website. This tool is for personal use only and should not be used for commercial purposes.
