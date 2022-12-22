https://daily-dev-tips.com/posts/center-elements-with-tailwind-css/


first: by grid 

Can you believe this code is all we need? Let's explore what's going on.

grid: Gives the element a display: grid css property
place-items-center: Gives it the center value on the place-items property
h-screen: Sets the 100vh (screen-height) as the height
This code will perfectly center the element horizontally and vertically on the page.

second: by flex

As you can see, the div alignment looks similar to the first example but with an extra variable.

flex: Adds the display: flex CSS property
justify-center: This centers the div horizontally
items-center: This centers the content vertically
h-screen: Sets the 100vh (screen-height) as the height



NB. 
tried with flexing 
need and extra div to work properly - dont know why though