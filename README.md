## Video-Like-Button
Liking a video is the core experience of the most popular sites and apps, like YouTube, Instagram, and Tiktok.

Now you get to build that same experience!

## Instructions
Edit the HTML, CSS, and JS files to create the Like button feature.

Follow the steps below. Run the code after each step, to be sure that the step is working.

Find a video on YouTube and copy the iframe snippet. Add it to the HTML where the comment says to add it.
Add an event listener to the Like button that logs "clicked" when the button is clicked.
In the console, write the snippet of JavaScript to select the span with the class like-count and change the innerText to "1024"
Copy that snippet to the event listener, so the button changes the like count when clicked
Nice! Thats the basic idea of the like button on sites all over the web.

Bonus
It feels a little bit weird that the button still shows up and looks clickable after its been clicked. Disable the button by adding this snippet to the event listener: document.querySelector('button').disabled = true;

Some sites use an icon of a heart instead of the word "Like" in the button. Try finding an icon and swapping the text to a heart icon.