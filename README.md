# Scrabble
In this project, you will process some data from a group of friends playing scrabble. You will use dictionaries to organize players, words, and points.

1. We have provided you with two lists, letters and points. We would like to combine these two into a dictionary that would map a letter to its point value.
Using a list comprehension and zip, create a dictionary called letter_to_points that has the elements of letters as the keys and the elements of points as the values.

2. Our letters list did not take into account blank tiles. Add an element to the letter_to_points dictionary that has a key of " " and a point value of 0.

3. We want to create a function that will take in a word and return how many points that word is worth.
Define a function called score_word that takes in a parameter word.

4. Inside score_word, create a variable called point_total and set it to 0.

5. After defining point_total, create a for loop that goes through the letters in word and adds the point value of each letter to point_total.
You should get the point value from the letter_to_points dictionary. If the letter you are checking for is not in letter_to_points, add 0 to the point_total.

6. After the for loop is finished, return point_total.

7. Let’s test this function! Create a variable called brownie_points and set it equal to the value returned by the score_word() function with an input of "BROWNIE".

8. We expect the word BROWNIE to earn 15 points:
Let’s print out brownie_points to make sure we got it right.


9.Create a dictionary called player_to_words that maps players to a list of the words they have played. This table represents the data to transcribe into your dictionary:

player1	wordNerd	Lexi Con	Prof Reader
BLUE	  EARTH	    ERASER	    ZAP
TENNIS	EYES	    BELLY	      COMA
EXIT	  MACHINE	  HUSKY	      PERIOD

10. Create an empty dictionary called player_to_points.

11. Iterate through the items in player_to_words. Call each player player and each list of words words.
Within your loop, create a variable called player_points and set it to 0.

12. Within the loop, create another loop that goes through each word in words and adds the value of score_word() with word as an input.

13. After the inner loop ends, set the current player value to be a key of player_to_points, with a value of player_points.

14. player_to_points should now contain the mapping of players to how many points they’ve scored. Print this out to see the current standings for this game!
If you’ve calculated correctly, wordNerd should be winning by 1 point.
