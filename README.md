# Spartan Gym Website

Spartan Gym is a fictional gym located in Cardiff, UK. The aim of the website is to attract new customers and be a point of reference for existing customers. The website is designed to be user friendly and therefore responsive on all devices

![mockup image](/assets/images/mockup.PNG)

[Live website](https://alexbuzea.github.io/spartan-gym/)

## Table of Contents
1.	[User Experience](#1-user-experience)
    * [Project Goals](#project-goals)
      * [User Goals](#user-goals)
        * [First Time Visitor Goals](#first-time-visitor-goals)
        * [Returning Visitor Goals](#returning-visitor-goals)
      * [Business Goals](#business-goals)

2.	[Design](#2-design)
    * [Colour Scheme](#colour-scheme)
    * [Logo and Fonts](#logo-and-fonts)
    * [Imagery](#imagery)
    * [Content Inspiration](#content-inspiration)
    * [Structure](#structure)
    * [Wireframes](#wireframes)
    * [Mockup](#mockup)

3.	[Features](#3-features)
* 
* 	 
4.	[Technologies Used](#4-technologies-used)
5.	[Testing](#5-testing)
6.	[Deployment](#6-deployment)
7.	[Credits](#7-credits)


# 1. [User Experience]()

## Project Goals

### User Goals

#### First Time Visitor Goals
* Easily find out information about the facilities offered at the gym including photos
* Find out location, prices, opening times and amenities offered
* Find out information about any classes that may be offered
* How to contact the gym if I have any further questions

#### Returning Visitor Goals
* Find out timetable for classes
* Find out any information about personal training
* Check out opening times
* Contact the gym for any further information or suggestions
* Find the gym on social media


### Business Goals
* Attract new members by showcasing the available services in a professional and easy to find way
* Retain existing members by offering them all the information they would need
* Have the website accessible and user-friendly on any device



# 2. Design

## Colour Scheme

For the colour scheme a minimalistic colour scheme was chosen but with a bright red to generate an emotional response. Red is a colour of boldness vigour and stimulation. Red was also was inspired from the spartan helmet used for the company logo which goes with the warrior theme, meant to motivate people. A variation of yellow was also added to the colour palette which is the colour of energy. Coolors was then used to create a palette. 

![colour palette](/assets/images/colour-palette.png)

## Logo and fonts

The warrior helment logo was created in [Canva](https://www.canva.com/) and the white colour for a minimalistic design and to be able to convert it into an svg to achieve the transparent navigation. [Convertio](https://convertio.co/png-svg/) was then used to convert the png logo into an svg.

The fonts were imported from [Google Fonts](https://fonts.google.com/) and Mukta font was used in the headings to give it a minimalistic and easy to read font.

## Imagery

Images were sourced from [Adobe Stock Images](https://stock.adobe.com/), [Unsplash](https://unsplash.com/), [Pixabay](https://pixabay.com/), [Pexels](https://www.pexels.com/),[Gah Gym](https://www.gahgym.com/) and [PNG Tree](https://pngtree.com/)

## Content Inspiration

* I wrote some of the content, and some of the content was inspired or used from the following sources:

  * [Cardiff International Pool and Gym](https://www.leisurecentre.com/cardiff-international-pool-and-gym/gym) was used for inspiration for the Gym page
  * [The Gym Group](https://www.thegymgroup.com/) some of the content on the Gym page was used from the their website
  * [Energie Fitness](https://www.energiefitness.com/cardiff) was used as inspiration for the facilities section on the Homepage
  * [The Fighters Club HK](https://www.thefightersclub.com.hk/) was used as an inspiration for the Homepage
  * [David Lloyd Club](https://www.davidlloyd.co.uk) some of the content on the Classes page was used from the their website
  * [99Designs](https://99designs.com/) was used for inspiration for general looks on gym websites




## Structure

The page is structured in an easy to use and intuitive way and it's designed to be user friendly. The website has a Homepage and 4 other pages: Gym, Classes, Prices and Contact Us.

* Homepage - Landing page with an introduction to the gym, including opening times and location; brief overview of services offered and links to them
* Gym - Provides more information about the Gym facilities and a gallery of the actual gym
* Classes - Provides more information about the classes offered, personal training and the classes schedule 
* Prices - Provides information about the membership types 
* Contact Us - Provides information about gym location, opening times and allows the user to contact the gym or sign up for a membership

### Navigation
* All pages feature a navigation, the homepage has a transparent one and all the other ones have the dark one as it was difficult from accessibility perspective to keep it transparent when it came to contrast issues
* The navigation bar helps the user find easily whichever section he's interested in
* When it shrink the navigation turns into a drop-down one for tablets and mobiles
* Navigation used stays into place, a sticky one has not been chosen as the website is not large and the links from navigation are repeated in the footer

![navigation transparent](/assets/images/structure/navigation-transparent.PNG)
![navigation dark](/assets/images/structure/navigation-dark.PNG)
![navigation mobile](/assets/images/structure/navigation-mobile.PNG)


### Callout buttons
* Callout buttons have been used throughout the website in order to prompt the user to either sign up or contact the gym and a red colour has been used to make it stand out from everything else.

![callout button](/assets/images/structure/callout-button.PNG)

### Headings
* All pages have a heading which features as an quick introduction to the page or as a callout to sign up.

![heading](/assets/images/structure/heading.PNG)

### Footer
* All pages have a footer section which repeats the link from the navigation and the social media links in order to make navigation easy for user.

![footer](/assets/images/structure/footer.PNG)

### 404 Page
* A 404 page has been added in case the user mistypes something on the website which will allow them to go back the homepage. It features the navigation, social media links and a button to take them back to the homepage.

![404page](/assets/images/structure/404page.PNG)



## Wireframes

<details><summary>View wireframes here</summary>
 
### 1.Homepage
<img src="/assets/images/wireframes/wireframe-1-homepage.png">

### 2.Gym page
<img src="/assets/images/wireframes/wireframe-2-gym.png">

### 3.Classes page
<img src="/assets/images/wireframes/wireframe-3-classes.png">

### 4.Prices page
<img src="/assets/images/wireframes/wireframe-4-prices.png">

### 5.Contact page
<img src="/assets/images/wireframes/wireframe-5-contact.png">
</details>


## Mockup

* A mockup image has been added to this file to give an idea of the way the website is displayed on different devices which can be found at the top of this page. [UI Dev](https://ui.dev/amiresponsive) has been used to achieve this.


# 3. Features

## Curent Features
* All current features have been designed with a mobile first approach meaning the website is fully responsive on all screen sizes.
* Bootstrap grid system has been used to achieve this and custom CSS added to it to make some other tweaks to make sure everything looks good on all screens

## Interactive Features
* A Google Maps iFrame has been added on Homepage and Contact page which shows the users the location of the gym
* Links on the homepage have been added via images which directs users to the wanted sections
* A form has been added in the Contact page which users can use to sign up or contact the gym
* Videos have been added in the classes page via iFrames which allows users to start, pause and adjust volume as wanted
* Navbar is responsive and turns into a dropdown navbar on tablets and mobile

## Future Features
* A payment feature that allows users to pay for their membership is something that could be added later on which would make a more convenient user experience and conversion for the business as well


# 4. Technologies Used

## Languages Used

* [HTML5](https://en.wikipedia.org/wiki/HTML5)
* [CSS3](https://en.wikipedia.org/wiki/CSS) 

## Frameworks and Other Software Used
* [Bootstrap 5.3](https://getbootstrap.com/docs/5.3/getting-started/introduction/) 
  * I used Bootstrap throughout the website in order to make it responsive on all devices. It uses Containers, Gridsystem, Flexbox, Button Classes , some Bootstrap icons, aligment, padding/margin classes, shadow classes, navbar component and also some styling classes in the contact form.
* [Gitpod](https://www.gitpod.io/)
  * First part of the project was done via Gitpod IDE initially which was then changed later on to Visual Studio Code 
* [Git](https://git-scm.com/)
  * Git was used in order to push the code to Github on a constant basis and have a backup of the code
* [Github](https://github.com/)
  * Github was used in order to backup the code
* [Visual Studio Code](https://code.visualstudio.com/)
  * Visual Studio Code was used in the second part of writing the code for this website and it is my preffered IDE
* [Paint](https://apps.microsoft.com/store/detail/paint/9PCFS5B6T72H?hl=en-us&gl=us)
  * Paint was used in order to resize some of the images initially that were too large or modify them to specific sizes
* [Paint 3D](https://apps.microsoft.com/store/detail/paint-3d/9NBLGGH5FV99)
  * Paint 3D was used to crop the images to specific sizes which in normal Paint wasn't as easy to do
* [Tiny PNG](https://tinypng.com/)
  * Tiny PNG was used to further reduce the size of all the large images further
* [Snipping Tool](https://en.wikipedia.org/wiki/Snipping_Tool)
  * Snipping TOol was used to take all the screenshots used in the Readme file
* [Balsamiq](https://balsamiq.com/)
  * Balsamiq for Desktop was used to generate the Wireframes which can be found in the Wireframes section in the Readme file

Favicon: https://favicon.io/


# 5. Testing

HTML : https://validator.w3.org/
CSS: https://jigsaw.w3.org/css-validator/
Accessibility: https://wave.webaim.org/
Lighthouse



# 6. Deployment

# Github

# Forking

# Cloning



# 7. Credits
* Stackoverflow


