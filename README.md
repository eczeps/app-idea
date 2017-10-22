# app-idea
All the JavaScript/HTML/CSS code I wrote for the app idea I had

The idea:
In a perfect world, you would use the app to use the camera on your phone to look at a list of ingredients (like are on the backs of food labels). The app would recognize each ingredient individually and highlight some of them according to different factors, such as health risks, environmentally friendly ingredients, etc. Each ingredient that gets highlighted could be clicked on for more information.

What's in this version:
This version is a very rudimentary start at working through some of the underlying infrastructure of the overall idea. It asks for a product name and a company ("oreo" and "nabisco" is the default & what I used a lot for testing) and uses an API to display images of all the results that match your search query. If you click on one of the images, it displays a list of ingredients and highlights each of them. If you click on an ingredient it will open a new tab that redirects to Google.com with the search query "What is " + the ingredient name.

Next steps:
One of the big issues I ran into was that I couldn't find an API for information on the ingredients themselves, so it was hard to do much more than google the ingredients. If I could find some way to get around this I would be able to not only do that but also work on color coding the highlights on the ingredients, which would make the whole thing much more user-friendly because the user would get some level of information without even having to click on the ingredient. I also want to redo a lot of this in python and use jinja. 
