# HW 2 - CS 625, Spring 2025

Name: Bhargav Iyer 
Due: February 4, 2025

## Data Cleaning
1) I first worked with removing Blank Rows within the file.
2) Then removed the Gross Column.
3) Finally, I trimmed the Movie titles so that leading and subsequent spaces would be removed.
4) Next I filled all the blank values with N/A for the text type columns.  I went through a text facet and replaced blank or " " with N/A.
5) I changed Run Time and Rating to numerical values and replaced blanks with 0s.
6) I then edited votes by removing the commas from it and then converting it into a numerical value. I then replaced the blanks with 0s.
7) For the second step of data cleaning, I added a bunch of text filters to stop those specific values (Roman Numerals) from appearing in the list.
8) I then applied a text facet to first remove the parenthesis, then remove any strings after a space.  After that I added a dash and the same year after any data that has only 1 year.  After all this, I split the data into 2. with the dash as the delimiter for startyear and end year.
9) For the third task, I created a new column based off of the Rating column.  I used a bunch of if statements to determin whether it was a super hit, hit, average, flop, or not known.

## Analyzed Clean Data

1) There are 81 rows that are movies that were superhits in 2021.  I first added a text filter for 2021 for both the startYear and EndYear.  I then applied another text filter for Verdict to check for Super Hit

2) I did two sorts, the first one was on the ratings and the second was the start year.I then added a text filter for Genre and checked each genre for the highest rated movie for the required years between 2018-2020.
   - Animation: She-Ra and the Princesses of Power
   - Action: She-Ra and the Princesses of Power
   - Adventure: She-Ra and the Princesses of Power
   - Biography: The Last Dance
   - Comedy: The Midnight Gospel
   - Crime: Elite
   - Drama: The Dragon Prince
   - Family: Julie and the Phantoms
   - Fantasy: Paranormal
   - Horror: Paranormal
   - Mystery: The A List
   - Sci-Fi: Snowpiercer
   - Sport: "Formula 1: Drive to Survive"
   - Thriller: Elite
   - War: Greatest Events of WWII in Colour
   - History: The Last Dance
   - Romance: Velhas Amigas
   - Western: (None within timeframe)
   - Reality-TV: Queer Eye
   - Animation: She-Ra and the Princesses of Power
   - Musical: Go! Vive a Tu Manera
   - Short: Mighty Little Bheem
   - Music: Thythm + Flow
   - News: Patriot Act with Hasan Minhaj
   - Documentary: "Formula 1: Drive to Survive"
   - Talk-Show: "Stranger Things: Spotlight"
   - Film-Noir: (None within timeframe)
   - Game-Show: The Circle

3) Most common genres in database by count.  I found these by creating text facet by genre and sorted the facet by count to find most common genre.  I then sorted the data by votes.
   - Comedy - Lugar de Mujer - 16 votes
   - Animation, Action, Adventure - 3Below: Tales of Arcadia - 5 votes
   - Drama - Kacche Dhaagey - 5 votes

5) Stars: Song Chae-Yoon, Ga-rim Han, SeolaGoedam - 694 votes - Genre: Short, Horror, Mystery.  I had found this by sorting using Run-Time from smallest to largest.  I then found the movies that are 10 minutes long and found information regarding those movies.

6) I removed a comma from Votes and then changed it into a numerical column.  I then sorted the column based on votes.  I then added a text filter on Verdict to filter for Flop.
- Death Note
- The Human Centipede (First Sequence)
- Scary Movie 5
- 365 dni
- Sharknado

