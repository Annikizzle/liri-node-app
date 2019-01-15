<h1>Liri - the  Language Interpretation and Recognition Interface. LIRI is a command line node app that takes in parameters and gives you back data.<h1>


Commands:

1 ) concert-this 

by entering: "node liri.js concert-this ARTIST/BAND NAME" into the terminal, Liri will return upcoming concert          information for the band or artist you entered.

Example:

node liri.js concert-this Elton John
Artist: Elton John
Venue:  Save Mart Center
City:  Fresno
Date:  01/15/2019

2) spotify-this-song

by entering: "node liri.js spotify-this-song '<song name here>'" into the terminal, Liri  returns the following information about the song in your terminal/bash window

Artist(s)
The song's name
A preview link of the song from Spotify
The album that the song is from

Example: 

node liri.js spotify-this-song When I Come Around
this is loaded
Artist Name:  Green Day
Album Name:  Dookie
Song Name:  When I Come Around
Preview:  https://p.scdn.co/mp3-preview/d31a72f5f5a6fee7c92a32bed95ee4e13ce16dde?cid=fb9b0450dacd47e9b95bf54850dc6656


3) movie-this

by entering: "node liri.js movie-this MOVIE NAME" into the terminal, Liri will give you the following information about the specified film:

   * Title of the movie.
   * Year the movie came out.
   * IMDB Rating of the movie.
   * Rotten Tomatoes Rating of the movie.
   * Country where the movie was produced.
   * Language of the movie.
   * Plot of the movie.
   * Actors in the movie.

Example:

node liri.js movie-this Cars
this is loaded
Title:  Cars
Year:  2006
imdb Rating:  7.1
Rotten Tomatoes Rating:  74%
Country:  USA
Language:  English, Italian, Japanese, Yiddish
Plot:  A hot-shot race-car named Lightning McQueen gets waylaid in Radiator Springs, where he finds the true meaning of friendship and family.
Actors:  Owen Wilson, Paul Newman, Bonnie Hunt, Larry the Cable Guy

4)do-what-it-says

This command uses the Spotify to pull the information from the random.txt file and populate information for the song. In this example, the random.txt file contains the following:

spotify-this-song,"I Want it That Way"

and Liri returns:

node liri.js do-what-it-says
this is loaded
Artist Name:  Backstreet Boys
Album Name:  The Hits--Chapter One
Song Name:  I Want It That Way
Preview:  https://p.scdn.co/mp3-preview/e72a05dc3f69c891e3390c3ceaa77fad02f6b5f6?cid=fb9b0450dacd47e9b95bf54850dc6656


