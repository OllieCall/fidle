# **Capstone Proposal -- Class Anemone / Apr - 2022**
## Fidle
### What is Fidle?
Fidle is a fun and mentally stimulating word game. Inspired by the New York Times' game 'Wordle' (and many like it), Fidle offers the same experience but with the additional capability of allowing the user to select how many letters shall be in their mystery word. Wordle is a game where a random five letter word is selected and the user must guess the selected word. The user has six guesses to correctly guess the or they lose. The game offers hints by turning letters from your guessed word into different colors based on the selected word (i.e. If the mystery word is 'SHAKE' and you guess 'STEAP', the 'E' and the 'A' would both turn yellow because they appear in the mystery word, and the 'S' would turn green because it's in the mystery word *and* in the right place). With Fidle the options will range from two to five letter words, with the number of guesses allowed being one more than the number of letter in the word (i.e. A three letter word gets four guesses to solve). The game will stat-track your words and average guesses and allow you to look back on past games.
### Fidle Features
##### As a user I want to be able to change how many letters are in the word I'm guessing to offer more game options.
 - Get input from user
 - Manipulate API request given input
 - Display word on screen
##### As a frequent user I would like to be able to look back on past games and overall stats to see how I've done in the past.
 - Store completed games and stats (avg guesses & win/loss ratio) in db table
 - Filter games by recent date
 - Display stats along with the recent games played in a pop-up window
##### As a user I would like a stat reset ability so I can set all of my stats back to zero.
 - Delete stored data for specific user
 - Display empty stat pop-up window
##### As a user who isn't quite sure how to play this game I would like to be able to know the rules (so I can play).
 - Dispaly game rules and navigation guide upon button press
### Potential Additional Fidle Feature
##### As a user I want to be able to look up other users and friend them.
 - Allow a user search using a username
 - Be able to send a 'friend' request
 - Be able to accept a 'friend' request
##### As a friend of a user I want viewing access to their stats to see how they do.
 - Allow friends the ability to view your stats
### Fidle Models
Merritt, having not yet completed a Django lab I'm finding it difficult anticipating what my models might be. If you would be able to offer guidance here that would be much appreciated, otherwise the plan is to figure out what they will be and have this part done and resubmitted by the end of class on Wednesday.
### Schedule
Due to the fact that I don't have models it's likely I'll have to re-adjust my schedule once I know all that must be done. For now, the rough schedule is as follows:
 - By the end of week one I plan to have a basic Django app running and basic HTML home page
 - By week two I hope to have all models and mvp features complete
 - Through week three I plan to touch up my app and models and work to incorporate my additional features