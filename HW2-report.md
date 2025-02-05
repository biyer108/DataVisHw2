# HW 2 - CS 625, Spring 2025

Name: Bhargav Iyer 
Due: February 4, 2025

## Data Cleaning
1) I first worked with removing Blank Rows within the file.
2) Then removed the Gross Column.
3) Finally, I trimmed the Movie titles so that leading and subsequent spaces would be removed.

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

3) sdf

4) Stars: Song Chae-Yoon, Ga-rim Han, SeolaGoedam - 694 votes - Genre: Short, Horror, Mystery.  I had found this by sorting using Run-Time from smallest to largest.  I then found the movies that are 10 minutes long and found information regarding those movies.

5) I removed a comma from Votes and then changed it into a numerical column.  I then sorted the column based on votes.  I then added a text filter on Verdict to filter for Flop.
- Death Note
- The Human Centipede (First Sequence)
- Scary Movie 5
- 365 dni
- Sharknado

