# Web_Scraper

This is a web scrapper built in Python, that can be used to extract reviews from online shopping website : https://www.amazon.in/

The output will be saved in CSV format.
The generated output contains the following 14 data fields:
                                             
> Product Details:
  1. product_name
  2. product_variant
  3. product_image
  4. avg_reviews for that product

> Review Details:
  1. review_title
  2. star_rating given by the reviewer
  3. review_date
  4. review_content
  5. helpful score of the review
  6. variant of the product for which review is given
  7. verified - whether the purchase is verified or not
  8. review_images - images posted by the reviewer
  9. author_profile - profile of the reviewer
  10. author_name - name of the reviewer

### Libraries used
- Python Requests, to make requests and download the HTML content of the pages ( http://docs.python-requests.org/en/master/user/install/).
- LXML, for parsing the HTML Tree Structure using Xpaths 
- Python Dateutil, for parsing review dates (https://github.com/dateutil/dateutil/)
- Selectorlib, to extract data from the YAML file (https://pypi.org/project/selectorlib/)
