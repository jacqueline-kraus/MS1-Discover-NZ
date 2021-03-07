# Discover New Zealand 

Code Institute - User-Centric Frontend Development Milestone Project.

This project is a website with 7 pages about travelling to New Zealand.
The purpose of the website is to show based on experience how to travel through New Zealand in a short time (18 days) and with low budget. 

![Website](readme-files/readme-images/screenshot-devices-discover-nz.png) 

## [Life website in github pages](https://jacqueline-kraus.github.io/MS1-Discover-NZ/index.html)
--- 
# Table of contents
- [UX](#ux)
    - [Website owner business goals](#website-owner-business-goals)
    - [User goals](#user-goals)
    - [User stories](#user-stories)
    - [Structure of the website](#structure-of-the-website)
    - [Wireframes](#wireframes)
    - [Surface](#surface)
- [Features](#features)
    - [Existing features](#existing-features)
    - [Features left to implement](#features-left-to-implement)
- [Technologies used](#technologies-used)
- [Code Validation](#code-validation)
- [Testing](#testing)
- [Deployment](#deployment)
- [Credits](#credits)

---

# UX

## Website owner business goals
- As the website owner, the goal is to provide information and inspiration and share experience for everyone interested in travelling to New Zealand. 

## User goals
- User is provided with general information about New Zealand
- User can find a possible route to take, which includes all Must Sees
- User can find tested accommodations in New Zealand with links to the booking pages
- User finds highlights and Lord of the Ring Fans tips what places to visit
- User finds inspiration through a extensive image gallery
- User can get in contact with website owner to ask questions or share experience

## User stories
### As a business owner:
- I want to give clear information and recommendation to potential New Zealand travellers
- I want to provide a clear, easy understandable website, that leads the User through

### As a user:
- I want to find information about travelling through New Zealand in a short amount of time
- I want to know which route is the best and most time saving to take
- I want to know what I have to see and what things I can leave out in my trip
- I want to know recommendations on where I can sleep
- I want to be able to ask the website owner questions about their experience

## Structure of the website

The website is optimised for all devices (desktop, mobile and tablet). It is supposed to be user friendly and easy to understand. There are small differences on some pages between mobile and desktop, to have a better visualisation of the content, based on the device. With hover effects and a lot of links (which redirects to websites with more information) the user gets some interaction. By not only having a navigation bar on top of the page, but also having a call to action on every pages body bottom (which leads to the following page), the user has two ways to read through the website.

## Wireframes
Wireframes can be found here: LINK WIREFRAMES
Note: the original wireframes changed while developing the project, so some pages look very different than initially intended.

## Surface
### Fonts
The 2 fonts that were used are Montserrat and Raleway (by Google Fonts).
Montserrat is mainly used for headlines and the Logo, Raleway is mainly used for texts that are not headlines (there may be exeptions). As a backup I used in both fonts "sans-serif"

### Colors
To have a harmonic visual impression of the website and to be aligned with the colors shown in the images, I used mainly following colors:
- Body background color: #ededed
- Text color: #464646
- Background color header and footer: #f9f9f9

### Images
- All images on the website are originally taken by me. Commercial use of the images are not allowed.
- Image backup-color: black

# Features
The website consists of 7 pages. All pages are accessible by a navigation bar in the header. A different way of navigating page by page (starting with the Homepage) are the CTAs (call to action) at the bottom of the pages (except of contact page, as it is the last page you can navigate to).
## Existing Features
### Navigation Bar (in the Header):
-  Visible on all pages
- Responsive (adapts to burger menu on mobile)
- Left: Logo (linked to homepage) 
- Right 4 Links:
    - Home 
    - Planning (has a dropdown with 4 items:)
        - route
        - accommodation
	    - highlights
	    - lotr
    - Gallery
    - Contact

### CTA (call to action):
- visible on the bottom of the body in all pages, except of the contact page (last page)
- used as an option to navigate through the website (page by page)

### Footer:
- visible on all pages
- Content: short "about me", link to contact form, social links

### Home (index.html):
- introduction text for what the website is about
- text with general information about New Zealand
- 4 images with links to different pages (in case user is interested in something in particular)

### Route (route.html):
- images of recommended route (screenshot of Google maps)
- explanatory text for screenshot (city by city)

### Accommodation (accommodation.html):
- Text with tips for finding accommodations
- Table with recommended accommodations (includes links to booking websites)

### Highlights (highlights.html):
- List of top 10 highlights to visit with information and links

### Lotr (lotr.html):
- 5 items for lord of the rings fans to visit in New Zealand along the trip
- includes external links for more information

### Gallery (gallery.html):
- image gallery to scroll through

### Contact form (contact.html):
- required form fields: Name, Emailaddress and Message
- On submit, "thank you" alert message will be shown

## Features left to implement:
- embed google maps in the route page: I used a screenshot from Google maps and linked it to a preselected route. Ideally this map would be directly embedded with Google maps. The reason I didn't do it, is that Google changed their requirements of using their Google Maps API.

# Technlogies used:
- HTML: for structuring the website
- CSS: to style the HTML code
- Bootstrap: for responsiveness and additional style
- Fontawesome: as an icon library
- Google Fonts: as a font resource
- hover.css: for hover effects
- Balsamiq: for creating wireframes

- Github: for hosting the projects repository and creating a live page with Github pages
- Gitpod: as a platform for developing the project
- Git: as a system for tracking version control

### Technology used that is required by bootstrap for some functionality to work:

- jQuery
- Popper.js
- Javascript 

# Code Validation
- [W3 CSS Validator](https://jigsaw.w3.org/css-validator/) to validate CSS code
- [W3 HTML Validator](https://validator.w3.org/) to validate HTML code

# Testing

## Functionality testing
For testing responsiveness and styling I used for the project Chrome Developer Tools.

## Compatibility testing
The website was tested through virtual devices with Chrome Developer Tools.

Browser tested: Google Chrome and Safari.

The website was tested on following hardware devices:
- Macbook Air with MacOs Catalina
- Huawei P30 Pro with Android 10
- Google Pixel 2XL with Android 11
- Microsoft Surface 7 Pro with Windows 10

## User stories testing
### As a business owner:
- I want to give clear information and recommendation to potential New Zealand travellers
    > User can find a clear roadmap of information about New Zealand. Each page has a different topic of information.

- I want to provide a clear, easy understandable website, that leads the User through
    > Through the navigation menu plus the CTAs in the bottom of each page, the user will be guided trhough the page. The design is rather simple with the focus on the content.

### As a user:
- I want to find information about travelling through New Zealand in a short amount of time
    > The user can find valuable information how to see most of New Zealand in a short time, through recommendations on each page.
- I want to know which route is the best and most time saving to take
    > On the page "route" the user can find the information of a detailed plan trip (with map).
- I want to know what I have to see and what things I can leave out in my trip
    > The user can find a list of hightlights. Everything that is not listed there does not need to be included.
- I want to know recommendations on where I can sleep
    > User finds recommendations on the accommodation page with external links to the booking pages.
- I want to be able to ask the website owner questions about their experience
    > User can do that through the contact form.


## Bugs and problems 
- When browsing the website on desktop, there is a bug in the navigation menu. When opening the dropdown (Planning) and clicking on any item, by clicking the item has a blue background. This should not be the case.
- On some tablet devices the dropdown menu items are centered instead of right aligned.
# Deployment
## Github pages

## Local deployment




# Credits

## Content
All content is originally written by me.

## Media
- On the page "Route" there are 2 screenshots taken from Google Maps.
- The icons are taken from Fontawesome
- All other images on the website are originally taken by me. Commercial use is not allowed.

## Problem solving helpers
- [w3schools.com](https://www.w3schools.com/)
- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Learn)
- [stackoverflow](https://stackoverflow.com/)
- [Bootstrap documentation](https://getbootstrap.com/docs/4.3/getting-started/introduction/)

## Code
- Bootstrap: for grid, form and styling of the website
- hover.css: for hover effects
- Google Fonts: for the fonts used
- Fontawesome: for the icons
- Gitpod full template provided by Code Institute
