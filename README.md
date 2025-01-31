# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### Screenshot

![A screenshot to the output on Google Chrome](./images/four-card-feature-section.jpg)



### Links

- Solution URL: [Github repo to the code for the challenge](https://github.com/AllisonFavour/fm-challenge6)
- Live Site URL: [Vercel link to view the challenge](https://fm-challenge6.vercel.app/)

## My process

Started by using HTML to give the structure of the layout and having the CSS styling in mind.

I made use of the div with the class name of .container which is the parent element to the rest of the element and simultaneously the the child to the body element.
The .container has three child elements with the class name of .top-container, .bottom-container and footer
The top container houses the two h2 and p elements, siblings to the parent .top-container
The .bottom-container has child elements which all share the class name .cards, each .cards element has two child elements which are .content and .img.
Then for the footer which is a sibling to .top-container and .bottom-container

For my styling i chose SASS as my tool, this enables nesting, variables and lots more feature
I imported poppins from google fonts and then made use of the css * reset to reset the margin, padding and box-sizing.
Afterwards i created variables for colors and fonts to be used in the project as guided by the style guide markdown file provided by the frontend mentor challenge file.
I made use of display flex on the body to centralize all the elements initially 

For the bottom container i made use of display: grid and grid-template-column to achieve the layout as provided from the design file, i also added media query to apply the display grid once the screen size is equal to 650px or higher, which is min-width: 650px (applies from a minimum width of 650 and above) 

Then for the footer element which is a parent to the p tag with the class name of .footer-p, i made use of min-width to either centralize it for a maximum width of 650px and below, and then place at the bottom-left from 650px and above


### Built with

- Semantic HTML5 markup
- CSS custom properties and Flexbox and Grid



### What I learned

I learnt to visualize my solutions first before coding it out. After taking my time to analyse the design image preview of the expected solution, since the Figma file wasnt available to free accounts and then i dived first with building the structure of the layout with HTML.

I learnt it is very important to visualize the HTML structure closely that will also enable our styling process. At first the design image preview looked simple until i started to code it out and i realized it was a bit complex so i had to rewrite my HTML structure having a solid CSS styling process in mind.

I learnt to use SASS (Syntactically Awesome StyleSheets), i had to install Live Sass Compiler which help watch our changes and spot error and then gets compiled to a vanilla CSS file.
Making use of SASS allows some enhanced styling features, i was able to make use of t@ directive which is @import to import fonts from google font, i also learnt and made use variables to store colors and fonts, then i did nesting to help class and structure my elements for styling.

I learnt about css grid to achieve the desired output and also the clamp() property thats takes three argument, first argument takes a minimum value for the size of a font, second argument takes a viewport width and the third argument takes a maximum value for the size of the font. Making use of this processes reduced my need to use more media queries

I relearnt an easier way to use media query alongside the corresponding code instead of placing all the media queries at the bottom.


### Continued development

Ensure its responsiveness to a variety of screens



## Author

- Website - [Allison Favour](https://allison-favour-portfolio-darkmode.vercel.app/)
- Frontend Mentor - [@AllisonFavour](https://www.frontendmentor.io/profile/AllisonFavour)
- Twitter - [@TrillestOjay](https://x.com/TrillestOjay)


## Acknowledgments

Thanks to myself for starting and finishing this particular project, also thanks to chatgpt and claude ai for the quick reminder and providing code suggestions to boost ideas and help learn on the go. What a time to be alive!