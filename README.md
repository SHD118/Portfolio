# Portfolio
Profession Portfolio

![](/img/header_readme.PNG)

## About Me
I am in the field of information technology and seeking to become a full-stack developer. Born and raised in NJ and recently moved to Colorado and currently working fully remote. Living with my lovely wife and a puppy named Hiro in Broomfield Colorado. I graduated from NJIT with a degree in Computer science. I spent most of my career at Lockeed Martin as an engineer and now coming close to my 2 year mark at PSEG. I am always a team player and often go out of my way to help others whenever I can. I love learning and can spend hours reading about topics that interest me such as hydroponics, philosophy, physics, technology and much more. One of my goals is to create a nonprofit to help promote hydroponics to areas around the world where soil isn’t rich and water is sparse. If my profile sparks interest and if I can contribute to your team feel free to reach out.


## Description

* What was my motivation: The motivation for this webpage is to create an online portfolio page for potential recuiter and employers to look through my work and find ways to get in to contact with me.
* Why did you build this project?: I wanted an online portfolio for future employers to get to know who I am, the projects I worked on and find a way to get in touch with me.
* What problem does this solve: This webpage showcases projects I created and worked on to see my level as a developer.
* What did I learn:  Building this webpage helped me better understand html/css and formating/positioning elements through flex.


## Table of Content
- [Webpage Example](#webpage%20example)
- [Links](#links)
- [Installation](#installation)
- [Code Breakdown](#Code%20Breakdown)
- [Credits](#credits)
- [Help](#help)
- [License](#license)
- [Links](#links)

<br/>

## Webpage Example
![](/img/Portfolio_webpage.png)


### Installing

* N/A


### Code Breakdown

HTML/CSS Breakdown

- Created a skeleton keeping in mind semantics
  - Created a header and put all the navigation code in it
    - Create a navbar
      - Created a title set to my name in the navbar
        - Float: left
        - Used margin/padding for further position
        - Used pseudo class hover to change font color to aqua upon hovering over it
      - Nav\_items
        - Unordered list
        - Display: flex
        - Float: right
        - Using margin and padding I was able to position the items precisely as I wanted them to display
        - Used pseudo class hover to change font color to aqua upon hovering over it
        - Linked all nav item to the corresponding section on the webpage
  - Created a section called banner to fit an image (background), text and a profile picture of myself in it
    - First I set a height of 400px and width to 100%
    - Set a background to fill the space in
    - I used divs to set the profile pic, banner-text and quote\_name within the section
    - Than within the styling used display inline
    - Used a google font {font-family: &#39;Spirax&#39;, cursive;} for the banner text
    - Leverage float:right for the text and float left for the profile picture
    - Lastly used margins and padding for exact positioning
  - Created a About me section
    - Set display to flex
    - Created an aside tag and set the class to a border styling class
      - Border styling: margin:left, border: right and height set to 200px
    - Styled the about\_me p tags to have margin positioning
  - Created a work section
    - The work section is set to display flex and flex-wrap to contain all the content evenly in the rows
    - Within the work section I created div set to 5 work\_div
      - Displayed set to relative
      - I set the height and width as well as set some margins for position
      - The work div will contain an image of a project but for now I just set a linear-gradient color scheme as a placeholder
      - The first work\_div doe currently contain an image of the refactoring project when clicked on take you to the github project
      - I realized you can&#39;t link to another page in css since I set the background image in the css. I realize I encountered a problem. The way I resolved it was by onclick=&quot;window.location=&quot;url&quot; function in the html.
      - The size of work\_div:first child width and height set to be bigger than the rest of the work\_div to showcase my main project
      - Within each work\_div i added another div with a class called &quot;caption&quot; and a h3 tag
      - The caption overlays the name of the project with the text in the p tag
      - I added a pseudo class so when you hover the opacity changes to 1 and the image rotate slight with a box shadow
  - Created a section for resume
    - Within the section I add an aside and set it to a border class to float left
    - Then created another div set to the resumer\_container class which:
      - Has a width 60% and height to 200px
      - I also added a border and gave it some padding and margin for positioning
      - Finally used a linear-gradient for the background
      - Aligned the .resume\_contain p tags to be text-aligned centered
      - Finally created a button that sent user to a print/download page for my resume by placing my resume in my image directly and using the following
      - The button is set to display and center aligned
      - The button has styling set to it for color, padding, margin, border radius., boxing shadowing.
  - Finally I ended my main content tag
  - Create a footer for all the contact information
  - I first created a class called contact
    - I set the width to 100&amp; and display to flex
    - Than created ul/li tags to list everything and since I used flex they will be displayed in rows
    - I set the text-alignment to center and did some styling for margin, padding and font
  - Lastly created media queries so when the max width is set to 770px the webpage will do the following:
    - The page will change to columns to be more user friendly
    - Change fonts to display more clear as the screen sizes reduce
    - Made all the borders to display below the columns


## Help

Please reach out to me if are you having any issues navigating through the code
```
Contact information: shdesai118@gmail.com
```

## Credits

* https://cssgradient.io/gradient-backgrounds/
* https://fonts.google.com/specimen/Spirax#standard-styles
* https://www.brainyquote.com/quotes/andre_gide_120088
* https://www.w3schools.com/jsref/jsref_touppercase.asp
* https://www.youtube.com/watch?v=Nloq6uzF8RQ&ab_channel=KevinPowell



## License

This project is free use

## Links

[Live Link](https://shd118.github.io/Refactoring-Horiseon-Webpage/)

[Github Link](https://github.com/SHD118/Refactoring-Horiseon-Webpage/blob/master/README.md)


