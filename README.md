# Web-Review-Scrapper
I have developed a Web Review Scrapper that can extract all the product reviews from Flipkart(we can create a review scrapper for any e-commerce website).The library used is BeautifulSoup(bs4).

The flow for scrapper is:

->Input: Any product

->It will check in the database whether the product reviews are already stored. If not, then it will go to the website and scrap the reviews.

->Output: It will display all the reviews for the product.



The project is integrated with Flask Framework and is deployed on heroku platform.

All the reviews are stored MongoDb database.
