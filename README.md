# Hal-App-Manager-Landing-page
A landing page created using HTML,CSS, and JavaScript

This is a landing page I created using HTML, CSS and a little bit of JavaScript. The landing page is created using flexbox to help create a responsive site that will work on mobile devices. The site features an automatic slide show that goes through an array that contains images and also includes a count down timer to the launch of the application, both created using JavaScript. The layout of the landing page was created using a couple of FlexBoxs.

The most challenging aspect of this landing page for me was creating the text that would adjust the font size to a decent size on mobile/smaller display. I was able to do some research and found the calculation that will allow the font to resize at a certain display width and after I got the calculation the rest was just adjusting the sizing to what I would like.

The script for the automatic slide show:

The way the script works is that there are 3 var i, images, and time. The image var is an array, the i var is set to 0 and the time var is set to 2000 milliseconds. Currently, the image array has 3 images.
I created a function that changes the image src in the html to the images[i]. The way I was able to get it to change is by creating an if/else statement. If var i is less then the length of the image array-1(because the array starts at 0 and not 1, so you have to subtract 1 from the total length to avoid looking for an image that's not in the array) then you would add one until i is greater then the length. The else statement then reset i to 0 and then it repeats.
Then I set the timer to 2 seconds and also add onload the script will run.

The script for the timer:

With this script I had a hard time trying to keep everything simple with the styling aspect of the results, so what I can up with was to display the result day,hour,min,and sec, but I would wrap the results in the h2 tag and at the end add an h3 tag as the label for the corresponding results. What this allowed me to do was to style all the results at once using css. I was able to create the background on all the h2 at once and that only left me to style the container for the positioning. So I was able to style the script without having to do each element individually which saved me time.
