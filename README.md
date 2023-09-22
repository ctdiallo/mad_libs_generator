# Mad_libs_generator
The program executes a simple mad lib game where the user is prompted to fill in the blanks so it would create a story about their trip to Ibiza. 

The user is asked to input various details such as the mode of transport, an adverb, a noun, the weather, temperature, who their favorite DJ is, and a verb. 

These inputs are then used to construct a narrative about their trip.

Here's a breakdown of how the code works:
1/ We used a while True loop to keep the game running until the user decides to exit.
2/ Inside the loop, the user is prompted to input the details. In turn, variables are used to store the inputs. 
We added lower() case, and strip() in order to avoid issues with spaces and capital letters.
Note:  for the temperature, there is an input validation with isdigit to ensure that the user enters a number.

3/ In the third part of our code, the story is built into variables using the inputs above , concatenation and f-strings.

4/ We stored the story lines as  a list of strings called Ibiza_mad_lib.
The program then uses a for loop to print each line of the story.

5/ After printing the complete story, the user is asked if they want to play again. If the user responds with anything other than "yes," the program exits the loop, and the game ends.
