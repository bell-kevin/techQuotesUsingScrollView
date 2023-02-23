# Technology Quotes using ScrollView

For this project, you will work with a list of 10 items, which will extend beyond a single screen. You will use a ScrollView around an array map function to display the list.

This project displays 10 technology quotes. You may look up quotes, or use the ones shown in the example, which are in this file Download this file. Create an array of objects, each with an "id" or "key" element, a "quote" element for the text of the quote, and an "author" element. The "id" is a string for values "1", "2", "3", and so on.

The screen displays a header for "Technology Quotes", then the quotes and authors below it, displayed in a ScrollView, so the screen can be moved up or down to see the rest of the quotes.

Add background color to the screen (your choice, make sure the text is visible). Increase the font size to 20 for the list items to take up a little more space on the screen. Make sure the text does not touch the right and left edges. Add space between the quotes, for example with bottom margin of 15 in the style for the author. The author's name displays below the text of the quote in italics, on the right of the screen.

Take 2 screenshots as shown above.

Submission: Zip together the root folder and the 2 screenshots, and submit the single zipped folder.

![p](https://github.com/bell-kevin/techQuotesUsingScrollView/blob/main/screenshots/1.PNG)

![p](https://github.com/bell-kevin/techQuotesUsingScrollView/blob/main/screenshots/2.PNG)

https://reactnative.dev/docs/environment-setup

Reading:
Storing Projects When you complete a React Native project, you should keep it on your storage device for a little while. There are multiple instances where one project will be the basis of another project. The Udemy course keeps building on the projects, so you definitely need to keep those around until you are done with that project in the course.

BUT -- React Native projects are huge. There is a folder, node_modules, that takes up most of the space. If you keep every project you create in this course, you would need at least 20GB of space, probably more. How can you manage this terrible drain on your storage?

That node_modules folder is automatically added when you create a new project. Once you are done with the project, you can delete that folder, node_modules, and the size of your project will shrink dramatically.

This does not destroy the project. If you find you need to run an old project again, which no longer has its node_modules folder, open it in Visual Studio Code, open a terminal, and type "npm install". This will load the node_modules folder again, and the project is whole and ready to run.

Note that when you delete that folder, it takes a noticeable amount of time, far more than it takes to reload it.

A good practice for course maintenance is to keep the project in its full state until you are sure you won't be using it in the next few days, then delete the node_modules folder.

== We're Using GitHub Under Protest ==

This project is currently hosted on GitHub.  This is not ideal; GitHub is a
proprietary, trade-secret system that is not Free and Open Souce Software
(FOSS).  We are deeply concerned about using a proprietary system like GitHub
to develop our FOSS project. I have a [website](https://bellKevin.me) where the
project contributors are actively discussing how we can move away from GitHub
in the long term.  We urge you to read about the [Give up GitHub](https://GiveUpGitHub.org) campaign 
from [the Software Freedom Conservancy](https://sfconservancy.org) to understand some of the reasons why GitHub is not 
a good place to host FOSS projects.

If you are a contributor who personally has already quit using GitHub, please
email me at **bellKevin@pm.me** for how to send us contributions without
using GitHub directly.

Any use of this project's code by GitHub Copilot, past or present, is done
without our permission.  We do not consent to GitHub's use of this project's
code in Copilot.

![Logo of the GiveUpGitHub campaign](https://sfconservancy.org/img/GiveUpGitHub.png)
