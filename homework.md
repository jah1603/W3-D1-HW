## Questions

1.  Return ALL the data in the 'movies' table.

SELECT * FROM movies;

2.  Return ONLY the name column from the 'people' table

SELECT name FROM people;

3.  Oops! Someone at CodeClan spelled Jesus's name wrong! Change it to reflect the proper spelling ('Jezuz Perez' should be 'Jesus Perez').

UPDATE people SET (name) = ('Jesus   Perez') WHERE name = 'Jezuz   Perez';

4.  Return ONLY your name from the 'people' table.

SELECT 'James   Henderson' FROM people;

5.  The cinema is showing 'Batman Begins', but Batman is DC, not Marvel! Delete the entry from the 'movies' table.



6.  Create a new entry in the 'people' table with the name of one of the instructors.
7.  Emily Milne has decided to hijack our movie evening, Remove her from the table of people.
8.  The cinema has just heard that they will be holding an exclusive midnight showing of 'Avengers: Infinity War'!! Create a new entry in the 'movies' table to reflect this.
9.  The cinema would also like to make the Guardians movies a back to back feature. Find out the show time of "Guardians of the Galaxy" and set the show time of "Guardians of the Galaxy 2" to start two hours later.

## Extension

1.  Research how to delete multiple entries from your table in a single command.