To complete this task, use the data set in the attached file. Indicate the answer to each of the
following steps and time to complete the entire task.
1.1. Download the data set movie_metadata.csv, which contains data about films from IMDb
(Internet Movie Database).

1.2. The duration column contains data on the film length. How many missing values are there
in this column?
1.3. Replace the missing values in the duration column with the median value for this column.
1.4. What is the average film length? Give the answer as a floating-point figure rounded to
two decimal places.
1.5. Create a movie_duration_category column, which will contain three categories
depending on the film length:
• Category "1. <90" if the film is less than 90 minutes long
• Category "2. 90–120" if the film is between 90 minutes and two hours long (inclusively)
• Category "3. >120" if the film is more than two hours long
1.6. Build a summary table for films released after 2000 (inclusively), to list the numbers of
films:
• Table rows: year
• Table columns: movie duration category ("<90", "90–120", ">120")
• The year of release should be displayed in the YYYY format.
1.7. How many films between 90 minutes and two hours long were released in 2008?
1.8. The plot_keywords column holds keywords characterizing the film's plot. Using the data
in this column, create a column called movie_plot_category, to contain four categories
depending on the key words in the column:
• Category "love_and_death" if the keywords include both "love" and "death"
• Category "love" if the keywords include the word "love"
• Category "death" if the keywords include the word "death"
• Category "other" if the keywords do not meet the conditions above
1.9. The imdb_score column shows a viewer rating for the film. Build a table to reflect the
average rating of films depending on which movie_plot_category category they belong to.
1.10. What is the average rating of films in the "love" category? Give the answer as a floatingpoint
figure rounded to two decimal places.
1.11. The budget column contains the film's budget. What is the median budget for all the films
listed? Give the answer as an integer.
