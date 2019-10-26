# liri-node-app

## Description

Liri is a command line application that takes user commands and queries from the command line and returns data from API's. The following commands have been hard coded into the program to give the user the capability to look up songs, concerts and movie information:

* Concert-this
* Spotify-this-song
* Movie-this
* do-what-it-says
  
### Concert-this

function takes the userInput (command) and the userQuery(artist), and returns the next concert time and date for that artist, as well as location and city.

![concert-this image](/images/concert-this.png)

### Spotify-this

Function takes the userInput (command) and the userQuery(song), and returns the artist, full track name, a preview link and the album.

![spotify-this image](/images/song.png)

### Movie-this

Function takes the userInput (command) and the userQuery(song), and returns title, cast, release date, ratings, country of origin, original language and synopsis.

![movie-this image](/images/movie.png)

### Do-what-it-says

This function is a wildcard that will randomly select one of the functions and produce a search. The only way to find out what it does is to try!

![do-this image](/images/doWhat.png)
