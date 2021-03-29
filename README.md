# JulienNanquette_2_22022021
# v1.0.0
# CSS 
# HTML

2nd project of the web developer course by OpenClassrooms.
Project started on february the 22nd, 2021.

The project hosted on GitHub Pages's link is here ==> https://kulwch.github.io/JulienNanquette_2_22022021/

The project consists in setting up a website based on a two-versions mockup: mobile and desktop. The website must fit the mockup on mobile and desktop versions, and the design can be modified at will for the pad version, yet the content has to be correctly displayed. The design also has to be responsive, and must be set with efficient breakpoints.
The icons to be used are from font-awesome, and the font is a googlefont, 'Railway'. The links to ressources are in the link to the project.
Source: https://openclassrooms.com/fr/paths/185/projects/639/assignment

The mockup link is here: https://s3-eu-west-1.amazonaws.com/course.oc-static.com/projects/Front-End+V2/P2+HTML+%26+CSS/Projet+2+-+Reservia+FR.zip

The html structure for each of the accomodations card is:

```html
<article>
  <a>
    <figure>
      <img />
      <figcaption>
        <header>
          <h3> -name- </h3>
          <p> -price- </p>
          <div>
           -The stars icons-
          </div>
        </header>
      </figcaption>
    </figure>
  </a>
</article>
```

I applied the same html structure on the activities cards.  
I tried to use the less possible number of ```<div>``` and prefered to use semantic tags when possible.
The image loading is set to lazy, to gain speed.
  
I started the project with the desktop version, then set the mobile one, and finally did the pad version. All the work done is uploaded on the "develop" branch, until the final merge branch on "main" when the project is ready to be released. I used Visual Studio Code for the project.

I chose to use multiple stylesheets: one for the common rules applying to the different versions, then one file by version (desktop, mobile and pad) for specific display rules.

I made numerous commits during the project's development, as i prefered to go step-by-step on each part of the project. As i'm still a beginner in the web development, my versioning in this project lacks of mastering. I had to fix several parts, sometimes after modifying the html structure, or after cleaning my css files which can be seen with the amount of commits.

The code is formatted with the Prettier plugin for VS Code. This is the first release of the project, so i put the tag #v1.0.0 on the file, following the semantic release method.

Here are the project's mockups:

![Desktop - 1](https://user-images.githubusercontent.com/76691359/111976544-0715d980-8b02-11eb-87aa-e6bbd49829b2.png)
![iPhone 8 - 1](https://user-images.githubusercontent.com/76691359/111976552-09783380-8b02-11eb-8563-0c9c80b2a40b.png)
