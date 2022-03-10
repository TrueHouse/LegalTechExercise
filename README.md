# Alternative 2

I have chosen to do the Alternative 2 exercise. I have commented the necessary steps inside the code to make it more readable. I hope I succeeded in that. Additionally, here is an overall step-by-step description of my program:

1. I import the necessary modules
2. I chose to use a class to get define the way how my program should process the standard questions that had the same answer structure.
3. When initializing, I told my program to use the input that was passed to the StandardQuestion class to choose the right "answer".
4. I also defined a getAnswer() function to return the answer after iniztializing the class
5. Then I checked for the requirement of Art. 34 3. as to not ask unnecessary questions if it was too late anyway
6. Then I checked the legal basis of the agreement based on the user's input and saved it as a boolean. I used the boolean later to decide on the text of one question. 
7. Then I created multiple instances of the StandartQuestion class with the different questions. Depending on the user input, I printed a message. One of those would be an Error for an unexpected input.
8. In the end, I printed an overall result of the program. As I don't have any information on the chances connected with different answers, I just used the rudimentary "Chance" integer to indicate the "success rate". This could be changed with experience. In a more advanced program, there could be an algorithm instead to make a real assessment.
