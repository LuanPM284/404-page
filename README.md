# 404-page
An exercice to test my knowledge on HTML and Sass
The Webpage url: https://luanpm284.github.io/404-page/ \
[Source page for the instructions](https://github.com/becodeorg/Swartz-9/blob/main/1.The-Field/8.Html-CSS/error-404.adoc)

Some size guides: 
> Desktop screens: range from 1024×768 to 1920×1080. Mobile devices: range from 360×640 to 414×896. Tablets: range from 601×962 to 1280×800.

## Learning objectives
At the end of this challenge you should be able to:

- write semantic HTML

- understand CSS positioning

## The mission
You have to create a new repository called 404-page containing the HTML and CSS required for an error 404 page.

**Instructions**
[x] create the repository
```bash
# Enter BeCode directory where current projects are stored
cd ./BeCode
# Clone the repository created online at Github
git clone https://github.com/LuanPM284/404-page.git
# Enter the new directory
cd 404-page
# Create the necessary files to have a web page, index, style
touch index.html
touch style.scss
# Make a new directory for the images and possible logos
mkdir images
cd images
# A generic file in order for the push command to be accepted by github, avoid having empty folders
touch .gitignore
cd ..
# Add, commit and push to remote repository
git add .
git commit -m ""
git push
```

[x] write an error 404 page in HTML and CSS

[x] try to use as much semantical HTML as possible

[x] add a back button that redirects to your Github profile

[x] change the position of your content on the page

[x] commit/push

[x] deploy on a Github page

**Optional**

[x] add an animation when mousing hover an element

For the animation I will be using : https://animate.style/

Code to link the animations classes:

```HTML
<head>
  <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"
  />
</head>
```

After we only need to iniate by writting `class="animate__animated animate__theAnimationIWant"`

The general idea was made to see if I could change the background depending on the size of the screen. Here flowers where chosen from a random theme generator, after that I used bing image generator for the middle page and found other 2 open-source, [here](https://www.freepik.com/free-photos-vectors/cherry-blossom).

The buttons are just a basic animation where I added a delay and a infinite repeat in order to be somthing visible. 

I see that I have still a lot to learn in terms of animations, and that does seem fun to mess around. Something for the future.


Resources
[CSS3 animations](https://www.w3schools.com/css/css3_animations.asp)

[animate](https://animate.style/)

[CSS positioning](https://learnlayout.com/position.html)

---

This concludes by 404 page, it took much longer than the assigned time but I'm glad I could work with *Sass* and *animations*. 