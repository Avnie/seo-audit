# seo-audit

This script is designed to fetch and analyze a web page specified by the user. It uses the requests and BeautifulSoup libraries in Python to fetch and parse the HTML content of the page. The script checks for specific elements like headings, title, description, keywords, and image alt attributes to assess whether the page follows certain practices.

Requirements
Python 3.x
requests library (Install using pip install requests)
BeautifulSoup library (Install using pip install beautifulsoup4)

Run the script and it will prompt you to enter a URL. Make sure to provide a valid URL starting with http:// or https://.

The script will then fetch the web page, parse its content, and perform the following checks:

a. Heading Tags (h1, h2, h3, h4, h5, h6):

Checks if heading tags are present on the page. If found, it marks them as "appropriate" in the results. Otherwise, it adds an error to the list.

b. Title Tag:

Checks if the title tag is present on the page. If found, it marks it as "appropriate" in the results. Otherwise, it adds an error to the list.
Also, checks if the length of the title is less than or equal to 5 characters. If yes, it marks it as "appropriate" in the results. Otherwise, it adds an error.

c. Meta Tags (name="description" and name="keywords"):

Checks if the description and keywords meta tags are present on the page. If found, it marks them as "appropriate" in the results. Otherwise, it adds an error to the list.

d. Image Alt Attribute:

Checks if the alt attribute is present in any of the img tags. If found, it marks it as "appropriate" in the results. Otherwise, it adds an error to the list.
The script will print the analysis results, including any errors found and whether each element is appropriate or not. 

The results will be stored in the dict variable, which you can use for further processing if required.




