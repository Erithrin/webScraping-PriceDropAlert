# webScraping-PriceDropAlert



I developed a simple automated price-tracking system using Python and Beautiful Soup to monitor discounts on Birkenstock sandals. 
The script scrapes the Birkenstock website at configurable intervals (default: every 60 seconds) to track pricing changes.
This project was created for personal use, specifically to monitor the price of this product: https://www.birkenstock.com/us/gizeh-birko-flor/gizeh-electricmetallic-birkoflor-0-eva-w_3651.html#sz=48


Key Features:
- Uses Beautiful Soup to scrape price and product details directly from Birkenstock’s official website.
- Cleans and stores the extracted data in an Excel sheet for historical tracking.
- Automatically checks if the price drops below $99 and triggers an email notification with the product link.
- The scraping frequency is configurable, with a default setting of every 60 seconds, allowing easy adjustments.

This ensures real-time price tracking and alerts, making it convenient for users to purchase when prices are favorable! 
The script can be modified to include multiple products with different price thresholds.

For the smtp to work, you need to google "Google app password" and generate an app password. For this to work, 2FA needs to be enabled.


Tests :

Screenshot of excel sheet that stored the product details -

![image](https://github.com/user-attachments/assets/41b4b175-6ef4-4062-b966-8d704c006dd5)

The automatic email I received when the price dropped below $99 -

![image](https://github.com/user-attachments/assets/ec2ccc43-cca9-4b69-9f2d-d7cdb5dca394)

