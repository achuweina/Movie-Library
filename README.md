Movie-Library
=============

With this small application you can have control over all your movies on your computer.
Add films you've seen or you have in your collection. Add the directors, year and genre.

You need a small database with two tables:

TableGender:
GenderID PK, int, notnull
Name, nchar (50), notnull

TableFilms:
FilmsID PK, int, notnull
K GenderID, int, notnull
Title, nchar (50) NULL
Director nchar (50) NULL
Year, bigint, NULL

You must create the relationships in the database once you have it set up correctly, to enjoy the application.

I recommend that you review the code to check the strings of the tables. :)
