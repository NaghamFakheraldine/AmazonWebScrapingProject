# AmazonWebScrapingProject

This Python project aims to monitor the price of a specific item on Amazon and notify the user via email when the price drops below $15.

### Libraries Used
BeautifulSoup: For web scraping.
Pandas: For data manipulation and analysis.
CSV: For storing scraped data.
smtplib: For sending notification emails.

### Project Overview
The code retrieves the price and title of a particular Amazon product. If the price falls below $15, it sends an email alert to the user. The script runs on a daily schedule, continuously checking for price drops.

### How to Use
Python Libraries: Ensure you have the necessary libraries installed (BeautifulSoup, Pandas).
Amazon URL: Provide the URL of the Amazon product you want to monitor in the check_price() function.
Email Credentials: Replace the email credentials in the send_mail() function with your own.
Run the Script: Execute the script to begin monitoring the item's price.
Data Storage: The scraped data is stored in the AmazonWebScrapingProject.csv file in the same directory.

### Note
Make sure to adjust the URL and the email login credentials to match your specific product and email details.

