# A simple Trivia Game 
repository is here: https://github.com/booppenheimer/36-react-trivia-game


<img src="./public/trivia_game_image.png" width="450">

### Play game here [CodeSandBox](https://codesandbox.io/p/github/BoOppenheimer/36-react-trivia-game/master?file=/src/App.jsx:1,1)
Goals - To make a simple trivia game with True/False answers. Retrive questions from an API endpoint. Project is to demonstrate:

### note this game was written a few years ago circa 2020 ish as well. 

  1. Use of API (using async, superior to promise. async uses generators truly waits for response.)
    * Correct formating of given data. // using an external NPM package React HTML parser for this. 
    * Mutating this data, adding another field per record.

---
## Todos stuff to work on complete. Used to show logic of construction. 
- [x] 3 screens working intro screen, game, results.
- [x] Global css reset, boxsizing
- [x] API working, simply get 10 questions.
- [x] Format question correctly 
- [x] State for user response / percentage of questions asked
- [x] add icons?
- [x] feedback to correct / incorrect responses. Perhaps an overlay with a big :x: or :+1: checkmark :white_check_mark:?
- [x] Results screen
- [x] Summery of total questions asked as a table? 
- [x] reset game, a bit hacky using a form with default settings to reset entire game.
- [x] add animations?
- [x] clean up, remove all comments, unused code.

</br>

## Summery of project: 

* Not happy with being able to use react dev tools and view answers. Would correct this with the server and make these another endpoint. 
* Using React HTML parser. Much easier than creating a /regex replace for each of the HTML codes. 
* Had state all broken up, big pain to synchronize updates of the state, so put as much as possiable into single object state. Always a better stratagy.
* Added very basic animation, I really like framer-motion.
* Used react-icons, lacks finite control of svg viewbox it seems.
* Could build a lot of components for this, but decided to keep somewhat sane and build into .app. Larger scale project would warrent it.


# Installing and running
1. requires internet connection
2. need to run: npm install to install mondules
3. npm start - default port is changed to 3009, so localhost:3009 to review, can be changed in the package.json.


