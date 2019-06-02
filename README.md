# Footnotes

This application is a small book lookup site that uses goodreads API, Flask, and SQL. It uses a postgreSQL database to keep track of users, their reviews, etc..

application.py contains several routes. Most routes are restricted if the user is not logged in.

HTML templates use jinja to extend layout.html.

Additionally, books were imported to the SQL database using Import.py Import.py uses csv.reader() to iterate over every column and row in the file, importing into the database as it runs.
