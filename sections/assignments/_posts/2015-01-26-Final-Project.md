---
title:    GRASPS - Algorithms, Part 1
subtitle: Word Guessing Game
due-date: 2015-03-20
---

### Description


The goal of this project is to create a word guessing game between two human players.  Player 1 provides a word and Player 2 tries to guess what it is using feedback received from the computer.

### Game Sequence

1. Player 1 chooses a secret word by entering that word into an <kbd>ask</kbd> block.  The word is immediately hidden from view after Player 1 finishes entering it.
2. The computer then tells Player 2 how many letters are in the mystery word and asks Player 2 to make a guess.
3. After Player 2 makes a guess, the computer should tell the player whether the guess was right or wrong. Remember guesses should be case-insensitive.
4. If Player 2 was wrong, the computer should also tell Player 2 how many letters in the guess were correctly positioned in the actual answer.  The computer does not, however, have to say which letters were correct or which positions they were in.
5. The conversation alternates back and forth until Player 2 guesses the secret word correctly.


#### An example of how the game sequence might play out:
     
**Computer:** What is the secret word?
**Player 1:** fireball
**Computer:** There are 8 letter(s) in the secret word. Try to guess it!
**Player 2:** superfragilisticexpialidocious
**Computer:** No, there are 8 letter(s) in the secret word.
**Player 2:** facebook
**Computer:** No, but 3 letter(s) are correct!
[f, e, b are in the correct positions]
**Player 2:** firebell
**Computer:** No, but 7 letter(s) are correct!
[f, i, r, e, b, l, l are in the correct positions]
**Player 2:** fireball
**Computer:** Yes, that is correct! You figured out the secret word in 4 guesses.


Your game will need at least one sprite to, but there are no graphical requirements other than that.  However, you are encouraged to add graphical elements!

### Extra For Experience

**Algorithm:** Instead of only telling the player that the number of letters that are correct, also tell her the exact letters that are in the correct positions.

**Graphics:** Add graphics or animation to the game.




### Submission Guidelines

Save your Scratch file - This is the file with all your code.  Name this file as GRASPS with your first and last name, such as:
                GRASPS_AliceAbernathy.sb2
                
Upload this file to your Dropbox portfolio folder.




### Tips


- Save your code often!
- Code a little bit at a time and test as you go.
- Remember to handle the situation when the user guesses a word that is too long or too short.


### Collaboration Policy:

*This assignment must be completed individually.  You may discuss high-level ideas with other students, but you should not share code.*