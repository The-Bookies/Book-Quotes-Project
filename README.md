# Book-Quotes-Project
The repository for all base data, python files and final database for our ETL project.

This project's purpose is to download, clean and transform best seller book data, book information and most popular quotes in GoodReads to produce a unique database with the consolidated information that is accessible to all. 

Sources of Data:

Most Popular quotes on GoodReads: https://www.kaggle.com/pramud/most-popular-quotes-on-goodreads

This is a database that contains a json file with the most popular quotes on goodreads, with information on the likes the quote has had, author and the actual text of the quote. 

GoodReads 10K books
https://www.kaggle.com/zygmunt/goodbooks-10k/home

This is a database that contains several CSV files with information on 10K books, including books information, and ratings for books (in two separate CSV files)

NY Times Best Sellers list 2011-2018
https://data.world/typhon/new-york-times-bestsellers-from-2011-to-2018

This is a database that contains all the titles, authors and isbns for books that were included in the bestselling list of the New York Times, along with how many weeks it was in that list. 

On top of this, we will be scraping data from the good reads website https://www.goodreads.com/
for cases when the information on the other three databases is incomplete 

Details on the ETL process:

You can find all files used on the GitHub Repository:

https://github.com/The-Bookies/Book-Quotes-Project

There are three python files used to clean up and transform each of the three databases, leaving only the information needed for our final database and the scraping used to fill in missing information. 

Theres another python file used for joining all three databases, organizing the data and uploading it in a relational database for further using. 

