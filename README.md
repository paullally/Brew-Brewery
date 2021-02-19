<h2 align=center id="top"><img src="assets/images/logo.png" max-height=100px></h2>

# **Table of Contents**

* [**Purpose**](#purpose)
* [**User Experience Design (UX)**](#user-experience-design)
  * [**User stories**](#user-stories)
  * [**Structure**](#structure)
  * [**Design**](#Design)
    * [**Colour Scheme**](#colour-scheme)
    * [**Typography**](#typography)
    * [**Frameworks**](#frameworks)
     * [**Icons**](#icons)
    * [**Wireframes**](#Wireframes)
- [**Features**](#features)
    * [**Existing Features**](#existing-features)
    * [**Features on every page**](#features-on-every-page)
    * [**Home page**](#home-page)
    * [**Future Features**](#future-features)
- [**Technologies Used**](#technologies-used)
    * [**Front End Technologies**](#front-end-technologies)
    * [**Other Technologies**](#other-technologies)
* [**Testing**](#testing)
    * [**Code Testing**](#code-testing)
      * [**Validator Testing**](#validator-testing)
    * [**User Story Testing**](#User-Story-Testing)
    * [**Manual Testing**](#manual-testing)
      * [**Lighthouse**](#lighthouse)
      * [**Responsive Testing**](#responsive-testing)
    * [**Bugs Discovered**](#bugs-discovered)
         * [**Resolved Bugs**](#resolved-Bugs)
          * [**Unresolved Bugs**](#unresolved-Bugs)
* [**Deployment**](#Deployment)
    * [**GitHub Pages**](#Using-Github-Pages)
    * [**Locally**](Run-Locally)
* [**Credits**](#Credits)
  * [**Content and Media**](#Content-and-Media)
  * [**Acknowledgements**](#Acknowledgements)


 # **Brew Brewery**
## **Purpose**
I created this website to promote a fictious Brewery called **Brew Brewery** this website focuses on the backstory of the company, the products that Brew Brewery offer and also a way to get in contact with the company.

Not all craft beer is good beer and finding good craft beer can be hard nowadays with the craft brewing market being highly oversaturated.

**Brew Brewery** was created with this in mind to offer customers an insight into our brewing process while also being able to view the products we have on offer and where to buy them.


The live website can be found [here](https://paullally.github.io/Milestone-1/).

*** 
# **User Experience Design**

## **User Stories**

- As a user, I want to be able to navigate through the website easily so i that i know where to find the relevant information.
- As a user, I want to be able to see the products on offer so that I know what types of beer are available. 
-   As a user, I want to be able to read a description on of the products so that I can make a decision on what I would like to try. 
- As a user, I want a link that directs me to a site to buy these products so I don't have to search for this information myself. 
-    As a user, I want to be able view the website on all devices so I can show others the website on my mobile phone or laptop. 
-   As a user, I want to be able read about the company history to find out more about the company and its staff.
-   As a user, I want to be able read about the brewing process to learn about there unqiue brewing style. 
-   As a user, I want to be able know what the website is about from first glance to easily understand the main purpose of the site. 
-   As a user, I want to be able get in contact with the company so i can book in for a tour and give my feedback on the products they offer. 
-    As a user, I want to be able view their social media websites to get more frequent updates from the company.

## **Structure**
Every page contains a Navigation bar at the top of the webpage that will dissapear when you scroll down and reappear when you scroll up. it will direct them to new pages making it easy to navigate the website 
<br>This fufils the user story:
> As a user, I want to be able to navigate through the website easily so i that i know where to find the relevant information.

All pages  contain a Footer Element with links to the **Brew Brewery's** social media, a copyright disclaimer and a link to the **Drink Aware** website to promote safe and resposible drinking 
<br>This fufils the user story:
>As a user, I want to be able view there social media websites to get more frequent updates from the company.

All pages are fully responsive and the layouts will change dependant on screen size. To ensure that content and images are displayed properly and is readable on every device
<br>This fufils the user story:
> As a user, I want to be able view the website on all devices so I can show others the website on my mobile phone or laptop. 

The home page contains details on the backstory of **Brew Brewery**. The products they offer and the Brewing process they use. <br>
This fufils the user stories:
 
 > As a user, I want to be able read about the company history to find out more about the company and its staff.<br>
 > As a user, I want to be able read about the brewing process to learn about there unqiue brewing style. <br>
 > As a user, I want to be able know what the website is about from frist glance to easily understand the main purpose of the site.

 The products page contains images of the beer that is on offer, When you hover over the image an overlay will appear with the name of the beer and a learn more button. When this button is clicked you are given a description of the beer and a link to where to buy that beer. <br>
 This fufils the user stories:
  > As a user, I want to be able to see the products on offer so that I know what types of beer they have on offer.<br>
 > As a user, I want to be able to read a description on of the products so that I can make a decision on what I would like to try.<br>
 > As a user, I want a link that directs me to a site to buy these products so I don't have to search for this information myself. 

The contacts page contains a form that can be filled out by inputing you name email address and a message. <br>
This fufils the user story:
>  As a user, I want to be able get in contact with the company so i can book in for a tour and give my feedback on the products they offer. 

## **Design**
---

### **Colour Scheme**

<h2 align=center id="top"><img src="assets/images/colours.png" max-height=200px></h2>

### **Typography**

- [**Montserrat:**](https://fonts.google.com/specimen/Montserrat?query=mont)
    - The primary font across the website, using four different weights: 400, 500, 700.
    - Montserrat was used for the main heading tags and the footer text elements. 
    - Montserrat was chosen due to is readablity for all users.

- [**Source Sans Pro**](https://fonts.google.com/specimen/Source+Sans+Pro?preview.text_type=custom&query=sou)
    - The secondary font across the website.
    - Source Sans Pro was used for the Navigation bar Links and paragraphs in a font weight of 400.
    - Source Sans Pro was chosen for its readablity and compliments  Montserrat well.
- [**Permanent Marker**](https://fonts.google.com/specimen/Permanent+Marker?preview.text_type=custom&query=perm)
    - This font was used to created the logo text.
    - Permanent Marker was used on the navigation bar logo and the landing image logo.
    - This font was used due its distinct style and playfulness.  

### **Frameworks**
- [MDBoostrap](https://mdbootstrap.com/)
    - Taking the responsiveness of Bootstrap and the front-end UI of Materialize, MDBoostrap makes use of both of these. So all aspects of the site were clean and accessible for all users. 

- [JQuery](https://code.jquery.com/jquery/)
    - In order to minimalize the amount of Javascript used across the application, I chose to implement a lot of the JS functionality with JQuery.

### **Icons**
- [Font Awesome Icons](https://fontawesome.com/)
    - All the icons used across this website were taken from Font Awesome and styled to match the colour scheme.

### **Wireframes**

#### **Desktop**

[**Home page**](wireframes/homepage1.png) <br>
[**Products page**](wireframes/productspage1.png)<br>
[**About page**](wireframes/aboutpage1.png)

#### **Tablet**

[**Home page**](wireframes/homepage3.png) <br>
[**Products page**](wireframes/productspage3.png)<br>
[**About page**](wireframes/aboutpage3.png)


#### **Moblie**

[**Home page**](wireframes/homepage2.png) <br>
[**Products page**](wireframes/productspage2.png)<br>
[**About page**](wireframes/aboutpage2.png)

## **Features**
---
### **Existing Features**
###  **Features on every page**
- Navigation bar on Desktop
<h2 align=left id="top"><img src="assets/images/navbardesktop.png" max-height=200px></h2>

- Navigation bar on Tablet/Mobile
<h2 align=center id="top"><img src="assets/images/navbarmobile.png" max-height=200px></h2>

- Footer on Desktop
<h2 align=left id="top"><img src="assets/images/footerdesktop.png" max-height=200px></h2>

- Footer on  Tablet/Mobile
<h2 align=center id="top"><img src="assets/images/footermobile.png" max-height=200px></h2>


### **Home page**
The Home page is split up into 2 sections:
- A landing video with and animated logo that appears in the middle of the video.
- 3 Headings and paragraphs that give information about **Brew Brewery**. The products offered and details about the brewing process used to make the beer.

### **Products page**
The Products page is split up into 2 sections:
- On the main section of the products page their is 8 unqiue beers. When you hover over these images an overlay appears with the name of the beer and a learn more button.
- When you click the learn more button a modal will pop up which will give you a description off the beer and a link to a website where you can buy the beer.

### **Contact page**
The Contact page is one section:
- On the contact page their is a background  image with 2 headings and a contact form on top of this image, Each part of this form is required to be filled.



### **Future Features**

Age verification:

When someone loads the website i would haved like to have a page dedicated to verify that they are over the age of 18 to ensure that users know this website is for people who a legally allowed to drink.

Newsletter: 

On the contact page there is a check box that allows you to subscribe to **Brew Brewery's** newsletter.I would have liked to created a program that will send out a monthly newsletter to the users that have subscribe.  

## **Technologies Used** 
---
- ### **Front End Technologies**
    - HTMl
    - CSS
    - Javascript
    - [**JQuery**](https://jquery.com/) to simplify DOM manipulation.
    - [**MDBoostrap**](https://mdbootstrap.com/) a front end framework used to create responsive aspects across the site. 
    - [**Font Awesome**](https://fontawesome.com/) Font awesome Icons are used for the Social media links contained in the Footer section of the website.
    - [**Google Fonts**](https://fonts.google.com/) Google fonts are used throughout the project.

- ### **Other Technologies** 
    - [**Gitpod**](http://gitpod.io/) the cloud based IDE used for development 
    - [**Github**](https://github.com/) to store and share all project code remotely.
    - [**Balsamiq**](https://balsamiq.com/?gclid=Cj0KCQjwo6D4BRDgARIsAA6uN1-NxDOthq9pGqYzB_1iRxlBvHVwi_4_LaZuGqQT46csctF0xCiTXUMaAqmuEALw_wcB) used to create wireframes.
    - [**TinyPng**](https://tinypng.com/) used to compress image sizes. 
    - [**Mp4Compress**](https://www.mp4compress.com/) used to compress landing video.

## **Testing** 
---

### **Code Testing**
#### **validator testing**

[W3C Markup Validation](https://validator.w3.org/)

- W3C Markup Validation was used to validate both the HTMl and CSS for this application.
No Errors were noted.

### **User Story Testing**

1. As a user, I want to be able to navigate through the website easily so i that i know where to find the relevant information.
    - The Navigation bar Contains the relevant information to be able to easliy navigate through the website
2. As a user, I want to be able to see the products on offer so that I know what types of beer are available. 
    - The Products page contains images of each beer available.
3. As a user, I want to be able to read a description on of the products so that I can make a decision on what I would like to try. 
    - Each beer has its own modal that gives a description of its flavour profile.
4.  As a user, I want a link that directs me to a site to buy these products so I don't have to search for this information myself. 
    - Each modal has a link that redirects you to a website where you can buy that beer.
5. As a user, I want to be able view the website on all devices so I can show others the website on my mobile phone or laptop. 
    - The **Brew Brewery** website is fully responsive and users are able to view it on all screen sizes.
6. As a user, I want to be able read about the company history to find out more about the company and its staff.
    - The **Brew Brewery** Home page has a brief paragraph dedicated to story of the company
7. As a user, I want to be able read about the brewing process to learn about there unqiue brewing style. 
    - The **Brew Brewery** Home page has a brief paragraph dedicated to the brewing process **Brew Brewery** uses.
8. As a user, I want to be able know what the website is about from first glance to easily understand the main purpose of the site.
    - On the home page there is a landing video of people enjoying some of **Brew Brewery's** finest products.
9.  As a user, I want to be able get in contact with the company so i can book in for a tour and give my feedback on the products they offer. 
    - **Brew Brewery's** website has a contact page that users can fill out to give feedback to the company and book a tour.
10. As a user, I want to be able view their social media websites to get more frequent updates from the company.
    - The Footer which is found on each page has links to all of **Brew Brewery's** social media.


### **Manual Testing**

manual testing was complted to ensure the application was responsive across all devices and achieved best practices in sofware developement.

#### **Lighthouse**

A desktop Lighthouse report was completed on **Brew Brewery's** website<br>
The results were as follows:
<h2 align=center id="top"><img src="assets/images/lighthousedesk.png" max-height=100px></h2>


A mobile Lighthouse report was completed on **Brew Brewery's** website<br>
The results were as follows:
<h2 align=center id="top"><img src="assets/images/lighthousemobile.png" max-height=100px></h2>

#### **Responsive Testing**