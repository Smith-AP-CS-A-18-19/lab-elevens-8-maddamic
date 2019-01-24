# Elevens 8

Follow the instructions provided for Activity 8 in the student lab guide. This is more of an exploratory lab, so you will not need to copy any of your previous code into the repo. Answer the questions from the Student Guide in this document and ensure that you save and push the repo. You have one week to complete this lab.

1. Discuss the similarities and differences between *Elevens*, *Thirteens*, and *Tens*.

    The similarities are the Board, newGame, size, isEmpty, deal, deckSize, cardAt, replaceSelectedCards, cardIndexes, toString, and gameIsWon methods because they will be the same no matter the game. The differences are the isLegal, anotherPlayIsPossible, containsPairSum11, and containsJQK methods because they are changed when the game is changed.

2. As discussed previously, all of the instance variables are declared in the `Board` class. But it is the `ElevensBoard` class that “knows” the board size, and the ranks, suits, and point values of the cards in the deck. How do the `Board` instance variables get initialized with the `ElevensBoard` values? What is the exact mechanism?

    They get initialized with the concept of inheritance.

3. Now examine the files `Board.java` and `ElevensBoard.java`, found in this repository. Identify the `abstract` methods in `Board.java`. See how these methods are implemented in `ElevensBoard`. Do they cover all the differences between *Elevens*, *Thirteens*, and *Tens* as discussed in question 1? Why or why not?

    Yes, these override methods do replace the methods that need to be different, and they leave the ones that need to be the same as the same. This is because all the different methods will be the same such as size or gameIsWon, so there is no need to replace them.  
