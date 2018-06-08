# Hangman

Let's play [hangman](https://en.wikipedia.org/wiki/Hangman_(game))!

On the class GitHub site there is a barebones repository setup for hangman:

[https://github.com/CodeAcademyMHCC/hangman-starter](https://github.com/CodeAcademyMHCC/hangman-starter)

As part of a portfolio-building project each student is going to fork their own copy of this repository and make changes to the game. There is a [README](https://github.com/CodeAcademyMHCC/hangman-starter/blob/master/README.md) file in the repository with a list of suggestions for how to make changes to the project. The list is also reproduced here:

1. Add a stylesheet to the page and play with the game's design. You will likely need to edit the HTML to add classes and possibly reorganize the HTML to suit your needs.
2. There is an intentionally unfixed bug in the gameplay right now regarding case sensitivity. See if you can identify the bug and figure out a fix!
3. When the game ends the game should restart itself or give the player an option to restart the game. At the moment it just "stops" and the gameplay mechanics break. See if you can fix this!
4. Add some copy to the site that elaborates on the rules for hangman using properly formatted HTML — lists, emphasized text, bold texts, hyperlinks, etc. You can look at the Wikipedia page linked to at the top and borrow their explanation of the rules.
5. At the moment the game shows the correct and incorrect guesses, but doesn't actually "draw" the hangman. See if you can come up with a solution for displaying a progressively drawn image of the hangman. Hint: the element with the ID `hangmanProcess` might be a good place to do this!
6. See if you can change the alert message when a player wins or loses. Additionally, instead of an alert dialog, see if you can style the entire page to change based on the outcome of the game — perhaps a green background for a win and red for a loss.
7. The game has a single hard-coded word ("computer") to guess right now. See if you can update this so that the game either randomly chooses from an array of words, or perhaps even pull the words randomly from another source. If you're really adventurous you can explore the [Wordnik API](https://developer.wordnik.com/).
8. See if you can add something on the screen that tells the player how many guesses they have remaining.
9. Redesign the game to give it a completely different, kinder, [less capital punishment oriented theme](https://george.mand.is/2018/03/a-more-politically-correct-version-of-hangman/). 

There are opportunities to focus on the visual design as well as the game logic, depending on where you'd like to put your focus. We will be checking-in as a class on this project, sharing the changes we've made and discussing how the game works as a class.

There is no due date per se on this project but it is part of an ongoing series of projects we'll be exploring the final few weeks to help students build a portfolio.