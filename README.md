**Flipkart Reviews Scraper**
This script allows you to scrape reviews for the top 5 most expensive mobile phones on Flipkart, sorted in order of price from high to low, using the Python libraries beautifulsoup, tqdm, and requests.

**Requirements**
Python 3.x
beautifulsoup4
tqdm
requests
Jupyter Notebook
**Usage**
Install the required packages by running the following command in your terminal/command prompt:
Copy code
pip install beautifulsoup4 tqdm requests
Clone this repository or download the Jupyter Notebook Flipkart_Reviews.ipynb

Open the Jupyter Notebook and replace the product_urls list with the desired urls for the top 5 most expensive mobile phones on Flipkart, sorted in order of price from high to low.

Run the cells in the Jupyter Notebook to execute the script.

The reviews for each mobile phone will be saved in a separate CSV file named {product_name}_reviews.csv in the same directory as the Jupyter Notebook.

**tqdm**
tqdm is a library for adding a progress bar to your loops in a Jupyter Notebook or on the command line. This can be useful to visualize the progress of a long-running loop, especially when scraping a large number of reviews.

**Note**
The script is limited to scraping only a specified number of pages for each mobile phone. The number of pages to scrape from per product can be specified by changing the value of the 'REVIEW_PAGES_TO_SCRAPE_FROM_PER_PRODUCT' variable.
Please use this script responsibly and in accordance with Flipkart's terms of use and scraping policies.
