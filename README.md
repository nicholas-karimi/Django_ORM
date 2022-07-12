## Dango ORM

## SQLite Usage
> Load the db file
```sqlite db_name.sqlite3``
> Set the mode
*inisde the sqlite3 terminal*
```.mode csv```
> Import the CSV data
_remove the header row since thats mapped on the db model_
**book_book** is our existing model table for books
```.import books.csv book_book```
