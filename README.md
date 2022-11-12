Hello!  Welcome to my Portfolio website.

# Katherine Biggs - Portfolio Website

![Katherine Biggs Portfolio website - Responsive](assets/readme_images/amiresponsive-portfoliowebsite.png 'Shows responsive views of site')

[View the live project here](https://kat632.github.io/Portfolio-Website/ "Link to deployed site - Katherine Biggs Portfolio website")

***

## Table of Contents

- [Katherine Biggs - Portfolio Website](#katherine-biggs---portfolio-website)
  * [Introduction](#introduction)
  * [UX](#ux)
    + [User Stories](#user-stories)
    + [Design](#design)
      - [Colour Scheme](#colour-scheme)
      - [Typography](#typography)
      - [Imagery](#imagery)
  * [Features](#features)
    + [Design Features](#design-features)
  * [Issues and Bugs](#issues-and-bugs)
  * [Technologies Used](#technologies-used)
    + [Languages Used](#languages-used)
    + [Frameworks, Libraries & Programs Used](#frameworks--libraries---programs-used)
  * [Testing](#testing)
  * [Deployment](#deployment)
    + [Forking the Repository](#forking-the-repository)
    + [Creating a Clone](#creating-a-clone)
  * [Credits](#credits)
    + [Content](#content)
    + [Code](#code)
  * [Acknowledgements](#acknowledgements)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>


## Introduction

This is my portfolio website.

I wanted to build a single page portfolio website in order to showcase my work, using Bootstrap 4 and a little JavaScript/JQuery.

[Back to top ⇧](#)

## UX 

### User Stories

To ensure the UX is simple and user-friendly, by providing easy navigation through all pages on the site.

**Visitor Goals**

*	As a website visitor, I want to easily understand the main purpose of the website and learn more about the organisation.

*	As a website visitor, I want to be able to easily navigate through the site to find content.

*	As a website visitor, I want to be able to view the website clearly on any mobile device.

*	As a website visitor, I want to know what services are provided by the organisation.

*	As a website visitor, I would like to see examples of previous projects undertaken by the organisation.

**Developer Goals**

*	To create a fluid and responsive layout for ease of use on common devices.

*	To fine-tune and implement some of the skills I have learnt so far.

### Design

#### Colour Scheme
This is probably my favourite colour scheme ever.  I love the way the colours work together against the white background.  I wanted the website to look professional and match the hero image.

I used [coolors](https://coolors.co/) to generate the original palette based on the hero image.

![Katherine Biggs Portfolio website - Colour Palette](assets/readme_images/coolors-palette.png 'Shows coolors colour palette')

#### Typography

Lato and Roboto Monospace

The main body of the website, including all the headings uses the Lato font.  Lato is a sans-serif typeface, created in 2010 by Polsih font designer Lukasz Dziedzic.  "Lato" means "summer in Polish.  I like its rounded edges and I feel it conveys the same warmth as the colour palette and the hero image.

The paragraphed texts on the website use the Roboto Mono font which is a monospaced version of the Roboto font family.  It was designed by Christian Robertson and I chose it because it is very similar to the font used in GitPod.  It looks like a programming font.

Both fonts were chosen from [Google Fonts](https://fonts.google.com/ 'Google Fonts website')

#### Imagery
The hero image of me was taken by [Vanda Szabo](https://vsphotography.co.uk/ 'Vanda Szabo Photography').  I am very grateful to her for gifting it to me.


[Back to top ⇧](#)

## Features

### Design Features
This is a single-page website featuring a consistent responsive navigational system:

- The **Technical Skills Modal** contains my current skillset.  The modal is draggable when viewed on a desktop computer and I have tabulated my skills because I thought it looked neat.  The table is responsive, but not in a way that lends itself to being viewed on a small screen.  Therefore for mobile screens, I have hidden the table and my skill are displayed in simple bootstrap columns.  Details of the code for the draggable modal can be obtained from this section [Code](#code) within this readme file.  

- The **Footer** contains my contact information.  If the footer is viewed on a larger screen, an animated butterfly is visible.  Details of the code for this butterfly can be obtained from this section [Code](#code) within this readme file.

[Back to top ⇧](#)

## Issues and Bugs 

**Issues** - I did not follow the "mobile first" design principle and I designed the Portfolio section of the website to have text that appears when hovered over.  This was never going to work for touchscreen devices and so I had to find a solution to solve the problem.
- ***Solution***: I came across [this article](https://bootcamp.uxdesign.cc/mobile-doesnt-have-hover-dude-b37e8e0b586e "Link to artice entitled 'Mobile Doesn't Have Hover Dude"), but ultimately it didn't help me in my solution.  The solution in the end was to design two completely different views for touchscreen and mouse/keyboard devices (desktop).  The desktop device view is a Bootstrap 4 masonry grid with information displayed on mouseover and the touchscreen view shows responsive Bootstrap 4 cards with the information displayed underneath an image of the website.
I discoverd that CSS queries can be set for only touchscreen or not devices from [this article](https://ferie.medium.com/detect-a-touch-device-with-only-css-9f8e30fa1134 "Link to article about detecting touchscreen devices using CSS").

[Back to top ⇧](#)

## Technologies Used
### Languages Used
- [HTML5](https://en.wikipedia.org/wiki/HTML5 "Link to HTML Wiki")
- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets "Link to CSS Wiki")
- [JavaScript](https://en.wikipedia.org/wiki/JavaScript "Link to JavaScript Wiki")


### Frameworks, Libraries & Programs Used
- [Bootstrap 4](https://getbootstrap.com/docs/4.0/getting-started/introduction/ "Link to Bootstrap page")
     - Bootstrap was used to implement the responsiveness of the site, using bootstrap classes.
- [Google Fonts](https://fonts.google.com/ "Link to Google Fonts")
    - Google fonts were used to import the fonts "Lato" and "Roboto Mono". These fonts were used throughout the project.
- [Font Awesome](https://fontawesome.com/ "Link to FontAwesome")
     - Font Awesome was used throughout the website to import icons (e.g. social media icons) for UX purposes.
- [Git](https://git-scm.com/ "Link to Git homepage")
     - Git was used for version control by utilizing the GitPod terminal to commit to Git and push to GitHub.
- [GitHub](https://github.com/ "Link to GitHub")
     - GitHub was used to store the project after pushing
- [Am I Responsive?](http://ami.responsivedesign.is/# "Link to Am I Responsive Homepage")
     - Am I Responsive was used to generate the mockup imagery.
- [Formspree](https://formspree.io/ "Link to the Formspree website")
     - Uses the Formspree API.  Uses an AJAX library to send the data as JSON.

[Back to top ⇧](#)

## Testing

Testing information can be found in a separate [testing file](TESTING.md "Link to testing file").

## Deployment

This project was developed using a [GitPod](https://gitpod.io/ "Link to GitPod") workspace. The code was commited to [Git](https://git-scm.com/ "Link to Git") and pushed to [GitHub](https://github.com/ "Link to GitHub") using the terminal.

### Forking the Repository
By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

1. Log into [GitHub](https://github.com/login "Link to GitHub login page") or [create an account](https://github.com/join "Link to GitHub create account page").
2. Locate the [GitHub Repository](https://github.com/Kat632/Portfolio-Website "Link to GitHub Repo").
3. At the top of the repository, on the right side of the page, select "Fork"
4. You should now have a copy of the original repository in your GitHub account.

### Creating a Clone
How to run this project locally:
1. Install the [GitPod Browser](https://www.gitpod.io/docs/browser-extension/ "Link to Gitpod Browser extension download") Extension for Chrome.
2. After installation, restart the browser.
3. Log into [GitHub](https://github.com/login "Link to GitHub login page") or [create an account](https://github.com/join "Link to GitHub create account page").
2. Locate the [GitHub Repository](https://github.com/Kat632/Portfolio-Website "Link to GitHub Repo").
5. Click the green "GitPod" button in the top right corner of the repository.
This will trigger a new gitPod workspace to be created from the code in github where you can work locally.

How to run this project within a local IDE, such as VSCode:

1. Log into [GitHub](https://github.com/login "Link to GitHub login page") or [create an account](https://github.com/join "Link to GitHub create account page").
2. Locate the [GitHub Repository](https://github.com/Kat632/Portfolio-Website "Link to GitHub Repo").
3. Under the repository name, click "Clone or download".
4. In the Clone with HTTPs section, copy the clone URL for the repository.
5. In your local IDE open the terminal.
6. Change the current working directory to the location where you want the cloned directory to be made.
7. Type 'git clone', and then paste the URL you copied in Step 3.
```
git clone https://github.com/USERNAME/REPOSITORY
```
8. Press Enter. Your local clone will be created.

Further reading and troubleshooting on cloning a repository from GitHub [here](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/cloning-a-repository "Link to GitHub troubleshooting")

[Back to top ⇧](#)

## Credits 

### Content
- All my own work, except for where otherwise credited.

### Code 
References used:
- [Stack Overflow](https://stackoverflow.com/ "Link to Stack Overflow page")
- [Bootstrap](https://getbootstrap.com/ "Link to BootStrap page")
- [Draggable Modal](https://codepen.io/adamcjoiner/pen/PNbbbv "Code for draggable modal adapted from here")
- [Bootstrap 4 Masonry Grid Layout](https://codepen.io/vinguerra/pen/KmoJRm "Code for Bootstrap 4 masonry grid layout")
- [Bootstrap Responsive Card Layout](https://stackoverflow.com/questions/34140793/bootstrap-4-responsive-cards-in-card-columns "Link to Bootstrap 4 responsive cards")
- [Bootstrap 4 Responsive Table Layout](https://codepen.io/JacobLett/pen/mBQoOj "Link to Bootstrap 4 Reposnive Table Layout")
- [CSS Butterfly](https://codepen.io/dazulu/pen/aOzqvz "Link to code for CSS Butterfly")

[Back to top ⇧](#)

## Acknowledgements

- I would like to thank myself, for taking the time to build this portfolio website.  Sounds big-headed, but I have a full-time job now as well as running a yoga studio and teaching yoga classes.  This website felt like it would be a "nice to have", but actually I've really enjoyed building it in my spare time.
- I would also like to thank my website testers: Chris Morley, Linda Biggs, Mark Keene, Jo Ablett, Tim Jackson.

[Back to top ⇧](#)

***
