# Finance First
![mock-up](assets/images/screen-homepage.png)

A Code Institute Project (P1). Visit the live site [here](https://katherine-holland.github.io/PP1-Finance-First/index.html)

Contents
1. [Introduction](#introduction)
2. [Design](#design)
3. [Features](#features)
4. [Manual Testing](#testing)
6. [Deployment](#deployment)
6. [Future Features](#future)
7. [Credits](#credits) 

## Introduction
**Audience:**
Finance First is the first stop for UK based parents and guardians looking to invest in their children's future. It raises awareness of and provides an introduction to the financial products on offer in the UK aimed specifically at children aged between 0 - 18.

**Client side:**
The site is designed to feel established and trustworthy, drawing on a standard layout, simple fonts and a consistent colour scheme. The website is designed to encourage a targeted audience to sign up to an email list, to generate a valuable database for marketing purposes. 

## Design
The wireframe was created using Balsamiq. I created a basic landing page design which I then used as the basis for my project.

![Wireframe for Mobile](assets/images/wireframe.png)

### Colours
I chose a cool colour palette to give a professional feel to the site. I used websites such as Hargreaves Lansdown https://www.hl.co.uk/ and Point 72 https://point72.com/ as my inspiration. The cool tones flow well together, allowing the reader to view light to dark as they scroll down the page and the blues are calming. Green is also a colour often used when denoting images money and contrasts well with blue. I feel the understated, consistent colour scheme alongside the content creates a website which feels trustworthy; an important consideration, especially when designing a site to convey financial information and encourage sign up. 

![Colour palette](assets/images/palette.png)

### Fonts
I used Google fonts and choose two fonts that look good together and would look professional and accessible in design. I chose 'Hind Madurai' and 'Rubik'.
Although I felt these fonts looked professional, they were also slightly less formal feeling and rounded which suited the topic of investing for children.

![Fonts](assets/images/fonts.png)

## Features
Below are the core functions and elements I incorporated into the site.

### Navigation Bar
I used Font Awesome to select my icons. I chose v4 icons to be compatible with the version I was coding with.
I decided to lay out my navigation, with the 'Home Page' in the far right corner and the 'Sign Up' page on the left. This was to allow 'Sign Up' to be more dominant, therefore encouraging users to sign up to the newsletter and to increase the likelihood of growing an email list quickly.
I also allowed the user to hover over the sections which would then change colour, I feel this helps to orient the user within the navigation.

### Buttons
I created two buttons on the 'Homepage' and a button on the 'Sign Up' page. The buttons change colour on hover and the text also switches colour. I feel visually this helps the user to navigate the site easily.

### Videos
I added two videos that explained the two financial products I had selected for this website- Junior ISAs and Junior SIPPs. I set the videos to mute which I felt was best practice and embedded them into the page, the links to YouTube also opened in a seperate window.

### Images
I chose images that related to finance but with a child theme. A piggy bank as the hero image seemed an obvious and relatable choice. Stacking blocks were used to indicate compounding finance, an intention of a Junior SIPP and a seedling in a money pot to denote new growth and the start of a financial journey.

![Image](assets/images/piggybank.webp)

### Sign Up Form

### Footer
Social Media icons

## Deployment
I deployed the site and tested it using two different and popular browsers, Chrome and Firefox, both of which worked well.
I then checked the site using Google Dev Tools testing the mobile responsiveness on all devices. The site worked well as I had used a container to add mobile responsiveness. I did however, have some challenges to allow the design to look good on Galaxy Fold. After amending the text width on the Homepage, and the 'sign up' box on the Sign Up page, the site looked much better on this device.

## Manual Testing
I used various methods to test the accessibility of my site and the quality of my code. The testing resulted in a number of error messages and suggestions which I took note of and implemented the necessary changes.

**W3Schools HTML Validator**
1. An error was brought to my attention in the footer. I had added my GIF in the middle of my list, instead of after the list. I amended this to below the list items.
2. I had missed out a /div on my sign up page which I added in.

**Lighthouse**
1. Lighthouse alerted me to the button background colour and text contrast not being accessible on hover. I amended the buttons so that when the hover was activated the button not only changed colour but the text also switched to contrast well with the lighter green.
2. I added aria-labels to the navigation icons as Lighthouse flagged up that they were not accessible to screen readers.

**W3 CSS Validator**
1. I had a missing curly brace in my code which I added in.

## Future Features
1. Ideally, I would create my own videos for the site using original content and branded with Finance First.
2. I would add a privacy policy and a full disclaimer plus a data protection page to ensure the site was legally compliant with UK Data Protection laws.
3. I would set up the back end with an email provider to allow the email data to be filtered into a useful email database.
4. I would set up google analytics and a Facebook pixel to track where user traffic originated.
5. I would link the social media icons to Finance First social media sites.

## Credits
**Wireframe:**
https://balsamiq.com/

**Nav bar icons:**
https://fontawesome.com/v4/

**Nav Bar code:**
https://www.w3schools.com/howto/howto_js_topnav_responsive.asp

**Mock Up:**
https://ui.dev/amiresponsive?url=https://katherine-holland.github.io/PP1-Finance-First/index.html

**Fonts:**
https://fonts.google.com/

**Buttons:**
https://www.w3schools.com/html/tryit.asp?filename=tryhtml_links_button_element 

**Sign Up Form**
https://www.youtube.com/watch?v=T2r0HSc4UlA

**Video Credits**
Thanks to:
Which: https://www.youtube.com/watch?v=S-c3SsEFJcg
The Retirement Cafe: https://www.youtube.com/watch?v=CR6XMcdZG4M&t=3s


**Original footer GIF code:**
https://www.w3schools.com/html/tryit.asp?filename=tryhtml_images_hackman

**GIF by Zurich Schweiz, GIPHY:**
https://giphy.com/stickers/ZurichVersicherung-transparent-ODG034tmOF7O0IPLM7

## Images:
Unsplash:

## Website Validators:
https://validator.w3.org/
https://jigsaw.w3.org/css-validator/
Google Dev Tools - Lighthouse

## Favicon Creation:
https://favicon.io/favicon-converter/

## Tutorials & Advice:
https://www.w3schools.com/
Code Institute - Love Running Tutorial
Code Chic: https://www.youtube.com/watch?v=T2r0HSc4UlA


Special thanks to my Mentor Spencer Barriball for his support and guidance.
