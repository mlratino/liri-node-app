# liri-node-app
 homework
# LIRI-Bot
LIRI is a Language Interpretation and Recognition Interface. LIRI will be a command line node app that takes in parameters and gives you back data.
LIRI uses the following commands:
* `spotify-this-song`
* `movie-this`
* `do-what-it-says`
Technologies:
* Node.js
* Javascript
* npm packages: require, spotify
How to Run LIRI-Bot

 node liri.js spotify-this-song `<song name here>`
 This will show the following information about the song in your terminal/bash window
    * Artist(s)
    * The song's name
    * A preview link of the song from Spotify
    * The album that the song is from
 * if no song is provided then the program will default to
    * Never Gonna Give you up by Rick Astley
3: node liri.js movie-this `<movie name here>`
* This will output the following information to your terminal/bash window:
    * Title of the movie.
    * Year the movie came out.
    * IMDB Rating of the movie.
    * Country where the movie was produced.
    * Language of the movie.
    * Plot of the movie.
    * Actors in the movie.
    * Rotten Tomatoes Rating.
    * Rotten Tomatoes URL.
* If the user doesn't type a movie in, the program will output data for the movie 