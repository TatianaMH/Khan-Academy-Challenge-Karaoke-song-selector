# Khan-Academy-Challenge-Karaoke-song-selector

[Finished Project](https://www.khanacademy.org/computer-programming/spin-off-of-challenge-karaoke-song-selector/5109744467755008)

**STEP ONE Khan is asking me to just select the song titles from the prewritten table. This is the SQL I wrote**
SELECT title FROM songs

**STEP TWO Khan asked me to select titles of the songs that have an 'epic' mood or a release date after 1990. so I picked mood**
SELECT title FROM songs WHERE mood = "epic";

**STEP THREE Khan asked "Add another SELECT that uses AND to show the titles of songs that are 'epic', and released after 1990, and less than 4 minutes long."**
SELECT title FROM songs WHERE mood = "epic" AND duration < 240 AND released > 1990;
