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