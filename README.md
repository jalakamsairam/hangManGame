# hangManGame


#psuedocode for hangman game for beginners

 // when the page loads, the program randomly selects an index from our word bank.
// var wordBank = [“tree”,”cloud”,”cat”]

// var targetWord;

// var wordArray;

// var count = 8;

// var inputLetter;

// var wrongLettersArray;



//this is the target word. 

//targetWord is equal to “tree”

//split the word up and push in to an array. // lets put this inside of a function - 

// what it does is creates the blankSequenceGenerator 


// string with as many "_" as there letters in your target word

// create a function that searches an array of letters or your word and returns the index of that/those letters if the user input matches. If it does then you know the index of the "_" that you need to replace with 

//var str = "jerome"

//evertime the user inputs a letter
//check to see if the letter exist in the word
//check to see if the blank sequence matches the word
//push letters tried
//decredment count

//wordArray = targetWord.split(“”)
 // wordArray = [’t’,’r’,’e’,’e’]
//loop through the word array and for every element add to the blankSequence variable += ‘_’

  //- there are some edge cases - this included spaces in the word for example “green bean”/// I will attend to this later
///
// blankSequence = “_ _ _ _”

//I need to now push this blankSequence to screen // in a function? Sure…. this function all it does is push the renderBlankSequence 
//everytime we call the renderBlankSequence function it pushes the variable blankSequence to screen

//I want to be able to find the index of characters 


// return wrongLettersArray;
// }
//every time i enter i must deduct one from the count variable whose value is eight
//before pushing the letter to the word check for duplicates if(index == -1){then push the wrong letter to the wrongLetters array}
//when the count becomes zero end the game and send out the message saying gameover.

//when the user guesses the word correctly send out the message saying "you won".
