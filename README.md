## Table of Contents
* [Purpose](#Purpose)
* [User Experience Design (UX)](#User-Experience-Design)
  * [User stories](#User-Stories)
    * [First Time Visitor Goals](#First-Time-Visitor-Goals)
    * [Returning Visitor Goals](#Returning-Visitor-Goals)
    * [Frequent User Goals](#Frequent-User-Goals)
  * [Structure](#Structure)
  * [Design](#Design)
    * [Colour Scheme](#Colour-Scheme)
    * [Typography](#Typography)
    * [Imagery](#Imagery)
    * [Wireframes](#Wireframes)
    * [Differences to Design](Differences-to-Design)
* [Limitations](#Limitations)
- [Features](#Features)
    * [Existing Features](#Existing-Features)
    * [Future Features](#Features-Left-to-Implement)
* [Technologies](#Technologies)
* [Testing](#Testing)
    * [Test Strategy](#Test-Strategy)
      * [Summary](#Summary)
      * [High Level Test Cases](#High-Level-Test-Cases)
      * [Out of Scope](#Out-of-Scope)
    * [Test Results](#Test-Results)
    * [Testing Issues](#Issues-and-Resolutions-to-issues-found-during-testing)
* [Deployment](#Deployment)
    * [Project Creation](#Project-Creation)
    * [GitHub Pages](#Using-Github-Pages)
    * [Locally](Run-Locally)
* [Credits](#Credits)
  * [Content](#Content)
  * [Media](#Media)
  * [Acknowledgements](#Acknowledgements)
  * [Comments](#Comments)


  ## Purpose
This Website was created for the sole purpose of completing the first Milestone Project for the Code Institute's Full Stack Developer course. 
It was built using the knowledge gained from the HTML, CSS and User Centric Design modules. A full list of technologies used can be found in the technologies section of this document.

The live website can be found [here]().

## User Experience (UX)

-   ### User stories

    -   #### First Time Visitor Goals
        1. As a First Time Visitor, I want to easily understand the main purpose of the site and learn more about the organisation.
        2. As a First Time Visitor, I want to be able to easily navigate throughout the site to find content.
        3. As a First Time Visitor, I want to look for testimonials to understand what their users think of them and see if they are trusted. I also want to locate their social media links to see their followings on social media to determine how trusted and known they are.
        4. As a First Time user, I want to view the website and content clearly on my mobile device.

    -   #### Returning Visitor Goals
        1. As a Returning Visitor, I want to find information about events.
        2. As a Returning Visitor, I want to find the best way to get in contact with the organisation with any questions I may have.
        3. As a Returning Visitor, I want to find community links.

    -   #### Frequent User Goals
        1. As a Frequent User, I want to check to see if there are any newly added events.
        2. As a Frequent user, I want to check to see if there are any new photos and media from the organisation activities.
        3. As a Frequent User, I want to sign up to the Newsletter so that I am emailed any major updates and/or changes to the website or organisation.

-   ### Structure
All Pages will contain a Navigation menu at the top of the Webpage that directs them to a new Page to easily allow users to Navigate the site easily.
The Nav Menu will be collapsable on a Mobile device to make use of space on smaller devices.
The purpose of this is to fulfill user story:
> As a First Time user, I want to be able to easily navigate throughout the site to find content.

The Home Page will contain four benefits of hiking.
The purpose of this is to fulfill user story:
> As a First Time user, I want to easily understand the main purpose of the site and learn more about the organisation.

Custom CSS will be used to make the Website responsive by the use of media queries.

All pages will be responsive and the layouts will change dependant on screen size. This is to ensure content flow is appealing,
images are displayed properly and that the content is not shrunk side by side, so small that it is unreadable.
The purpose of this is to fulfill user story:
> As a First Time user, I want to view the website and content clearly on my mobile device.

All pages will contain a Footer Element with Contact Information, and Social Media Icons. The icons used will be
from font-awesome. These are referenced below in the Frameworks-Libraries-and-Programs-Used section of this document. 
The aim of the Footer elements are to fulfill user stories:
> As a First Time Visitor, I want to look for testimonials to understand what their users think of them and see if they are trusted. I also want to locate their social media links to see their followings on social media to determine how trusted and known they are.<br>
> As a Returning Visitor, I want to find the best way to get in contact with the organisation with any questions I may have.


The Gallery Page will contain several photos from various activities the organisation has engaged in.
The purpose of these galleries are to fulfill user story:
> As a Frequent user, I want to check to see if there are any new photos and media from the organisation activities.

The Contact Page will contain a form that can be used to contact the organisation through the website. This will also contain a check 
box that will allow the user to sign up for the organisation newsletter in order to keep up to date with all the news and events.
The purpose of this Page is to fulfill user stories:
> As a Returning user, I want to contact the organisation so I can request more information.<br>
> As a Frequent user, I want to sign up to the Newsletter so that I am emailed any major updates and/or changes to the website or organisation.

-   ### Design
    -   #### Colour Scheme
        -   The main colours used are: "Kelly Green": #00c201 , "Snow": #fffafa , "Flame": #e4572e , "Sky Blue Crayola": #7ee8fa

    -   #### Typography
        -   The Spectral font is the main font used throughout the whole website with Helvetica as the fallback font in case for any reason the font isn't being imported into the site correctly.
        -   All headings throughout the website use Lora font with Arial as the fallback in case for any reason the font isn't being imported into the site correctly.
        
    -   #### Imagery
        -   Imagery is important. The large, background hero image is designed to be striking and catch the user's attention. It also has a modern, energetic aesthetic.

        #### Wireframes
Home Page<br>
![Home Page Wireframe]()<br>
Gallery Page<br>
![Gallery Page Wireframe]()<br>
Contact Page<br>
![Contact Page Wireframe]()<br>

-   ### Limitations
Due to no JavaScript functionality, apart from Bootstraps(JS/JQuery) used for the Modal Form as outlined in the Frameworks Libraries and 
Programs Used section, the contact forms will not store data or send email requests.
***
## Features
 
-   ### Existing Features
    - Let's Walk button on the index.html page opens up the booking modal form .
    - Contact Form - This can be completed on the contact.html page and used in order to contact the organisation with any queries users may have.

### Features Left to Implement
- Users would like to have a forum incorporated into the Website. This feature was not implemented as part of the initial release but will be addressed in a future.
- In order to implement the use of the proposed forum, signup and logins would have to be added.
***

## Technologies

* HTML
	* This project uses HTML as the main language used to complete the structure of the Website.
* CSS
	* This project uses custom written CSS to style the Website.
* [Bootstrap](https://getbootstrap.com/)
	* The Bootstrap framework is used throughout this website for layouts and styling. The car
	* This has also been used to import JavaScript/Query used for the pop up Event booking modal
* [Font Awesome](https://fontawesome.com/)
	* Font awesome Icons are used for the Social media links contained in the Footer section of the website and for the benefits found on the index.html page.
* [Google Fonts](https://fonts.google.com/)
	* Google fonts are used throughout the project to import the *Spectral* and *Lora* fonts.
* [Gitpod](https://gitpod.io/)
	* Gitpod is the tool used to develop the Website.
* [GitHub](https://github.com/)
	* GithHub is the hosting site used to store the source code for the Website and [Git Pages](https://pages.github.com/) is used for the deployment of the live site.
* [Git](https://git-scm.com/)
	* Git is used as version control software to commit and push code to the GitHub repository where the source code is stored.
* [Pixlr](https://pixlr.com/)
	* Pixlr is used to reduce the file sizes of images before being deployed to reduce storage and bandwith.
* [Google Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools)
	* Google chromes built in developer tools are used to inspect page elements and help debug issues with the site layout and test different CSS styles.
* [balsamiq Wireframes](https://balsamiq.com/wireframes/)
	* This was used to create wireframes for 'The Skeleton Plane' stage of UX design.
* [Coolors](https://coolors.co/)
    * This was used to select color palette. 
* [Gradient-animator](https://www.gradient-animator.com/)
    * This was used to generate gradient animation of the body.
* [Techsini](http://techsini.com/multi-mockup/index.php)
    * tecnisih.com Multi Device Website Mockup Generator was used to create the Mock up image in this README.
***


***
## Credits
-   ### Code
    -   The code for hero-image animation was taken from [codeinstitute.net](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+CSE101+2020_Q2/courseware/be0e510a3aca4bccb6e0bba4cf7cf06b/83c6c94d55f44c79a3646810d80ce7a3/?child=last)
    -   The code to style photo elements on Gallery.html page was taken from [codeinstitute.net](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+CSE101+2020_Q2/courseware/be0e510a3aca4bccb6e0bba4cf7cf06b/0b88201f299f4e059c23977b8e25f27a/?child=first)
    -   The code for gradient background animation was taken from [gradient-animator](https://www.gradient-animator.com/)
    -   The code for mobile nav menu was taken from [codepen](https://codepen.io/shieldsma91/pen/zLpbLX)

    
### Content
-   The quote on the hero image was taken from [thewanderlustwithin.com](https://www.thewanderlustwithin.com/mountain-quotes/)
-   The benefits of hiking were taken from [trekfest.org.uk](https://www.trekfest.org.uk/blog/health-benefits-hiking/)
-   The Ciucas Mountain description found on events.html was taken from [uncover-romania.com](https://www.uncover-romania.com/attractions/nature/ciucas-mountains/)

### Media
-   The .gif image associated to "Improves Brain Health" element was taken from [tenor.com](https://tenor.com/view/mental-health-matters-your-mind-matters-brain-take-care-of-yourself-love-yourself-gif-18568638)
-   The .gif image associated to "Tone Muscles" element was taken from [gfycat.com](https://gfycat.com/consideraterealamericanredsquirrel)
-   The .gif image associated to "Reduce Body Fat" element was taken from [tenor.com](https://tenor.com/view/go-to-hell-weight-loss-fat-becoming-fat-overweight-gif-14271805)
-   The .gif image associated to "Strengthen Bones" element was taken from [besthealthphysio.ca](https://besthealthphysio.ca/services/osteoporosis/strong-bone/)
-   The images found in Gallery.html are taken from my personal archive and they are shot during my travels
-   The image found on events.html is taken from my personal archive and it is shot during my travels

### Acknowledgements
I'd like to thank my mentor Daisy McGirr for her guidance throughout my project.<br>