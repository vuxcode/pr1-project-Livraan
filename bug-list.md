# Bug List

> Make a list of the things that don't work as expected. Keep a list of things that you have fixed and try to document how you solved them.

1. Problem: The title text jumps down one word line so the title has one word per line when the window screen is resized. The button glides to the side of the title and makes it look bad. 

Fix: Found out that the text was collapsing and to prevent that I needed to write "white-space: nowrap;" , Now the text is working as expected.

2. Problem: The button text color changed when the hyperlink was coded. After that the text color couldn't be changed back or change at all.

Fix: Used the "a" CSS property to change the color of the text(a{ }) and change the color of the text when the button is pressed(a:active{ }).

3. Problem: The button don't work as expected, when you click on the button nothing happens. The button is supposed to start the quiz via another page (another file of code).

Fix: Used the "<a>" tag to get the link to work with the button. Removed the line underneath the link aswell, using the "style="text-decoration: none;"".

4. Problem: The restart button don't work and can't make the button show only at the end where the score is shown.

Fix: Got help on the lesson to refresh my memory and got some new information that helped me fix my problem. Used for example "appendChild" and got the button to work.

5. Problem: Can't change a prototype into a function.

Fix: After getting help from Colin I could replace the prototype into another function and delete that prototype completly.

6. Problem: When clicking on random choices the function that checks the answers tells that every choice is correct, even the wrong answers. So now the user gets 10 out of 10 in score no matter what the user answers.

Fix: After some directions from Colin I found the right way to make the "checkAnswer" function work by if-statement and then (questions[index][1]==choice).

7. Problem: When creating the function for the progress bar one and saving the file the console log says that one element is not defined. 

Fix: Via different sources I got the help to make the bar work. I had spelled element wrong and it was mostly that made the console log error.

8. Problem: When sending the program to my boyfriend I discovered that it couldn't find the file for the actual quiz if I just send the start screen. Therefore the whole code (startscreen and quiz) needs to be in one single file.

Fix: