# responsive-portfolio

The main objective of this project was to develop a responsive portfolio webpage that is optimized at varying screen sizes. This was done with bootstrap and media queries.
There are 3 different webpages: About, Contact and Portfolio. On each of these pages is a navigation bar and a footer. The navigation bar
allows you to access any of the webpages. The footer has a copyright message.

Key Components:
1. Navigation Bar- As the size of the screen shrinks the header moves to correspond to the size. When you reach a small screen the tabs are displayes underneath the header. 
when it is big the tabs are on the far right.
2. The Footer- It takes up the the entire page regardless of the screen size.
3. About Page- It consists of a textbox with an image and a paragraph. As the size of the screen shrinks it takes up a larger percentage of the screen. It is also stays aligned with the header in the navigation bar regardless of the screen size even though the margin changes. The text is displayed inline with the image in a big screen but the text moves below the image with a small screen. The size of the image remains constant regardless of screen size.
4. Portfolio- This page contained a box with a header and images of the different projects with text displayed on top of the images. There are 2 images per row in a big screen, but just 1 with a small screen. The box also aligns with the header in the navigation bar.
5. Contact - This page allows the user to enter name and email address along with a message and press submit. It also has similar responsive sizing and alignement as the other pages.

Problems:
For certain things media queries were used instead of bootstrap's built in classes.
2 images don't display in the portfolio page in each row until you have a really wide screen.
The line separating portfolio goes all th eway across the box.
Padding and margins could be optimized.

Future Objectives:
Fix the problems.
Add actual content to the page.
Add more styling and respoonsive behaviors.
Refactor the code.