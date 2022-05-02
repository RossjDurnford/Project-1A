# Massive Gym - Project 1

This is a website for a local gym based in West Earlham, Norwich. 
The website will serve potential existsing and new customers living within the local area 
who are interested in getting in shape. The main aim of this website it to design a responsive website using HTML and CSS together to convey a companies message.
Link to the deployed site. https://8000-rossjdurnford-project1a-rwbj31z9ycl.ws-eu42.gitpod.io/index.html.

![Mockup](https://user-images.githubusercontent.com/101630755/163556707-5bdf0196-7582-4b0b-977b-249dbd77d515.png)


<!-- TOC -->

- [Massive Gym - Project 1](#massive-gym---project-1)
- [User Experience](#user-experience)
    - [Design Choices](#design-choices)
        - [Fonts](#fonts)
        - [Color Scheme](#color-scheme)
- [Features](#features)
    - [Nav menu](#nav-menu)
    - [Media Queries](#media-queries)
    - [About us](#about-us)
    - [Contact us](#contact-us)
    - [Opening Hours](#opening-hours)
- [Future Features](#future-features)
- [Testing](#testing)
    - [W3 Validator](#w3-validator)
    - [Lighthouse test](#lighthouse-test)
    - [CSS Validation](#css-validation)
    - [Compatability Test](#compatability-test)
    - [Responsiveness Test](#responsiveness-test)
- [Bugs and Fixes](#bugs-and-fixes)
- [Deploymment](#deploymment)
- [Cloning the Project](#cloning-the-project)
- [Technologies used](#technologies-used)
- [Credits](#credits)
    - [Code](#code)
    - [Media](#media)
- [Acknowledgements](#acknowledgements)

<!-- /TOC -->

# User Experience

## Design Choices

### Fonts

The fonts used for this project are Segoe UI', Tahoma, Geneva, Verdana, sans-serif. This was used for all aspects of the page to remain consistent with the theme set for the pages and the design across multiple pages.

### Color Scheme

The colour scheme for this project is largely centered around the background colours and trying to fit in with that as well as being noticeable. The colours used are as follows:
* H1,P,A. White
* H2 Home page, White, Red, rgba(9, 86, 185, 0.938)
* H2 All other pages, rgba(9, 86, 185, 0.938)
* Nav and Footer, Linear Gradient, rgba(9, 86, 185, 0.938) into Black

# Features

* This website features 4 pages, home.html (homepage), about.html(about us), contact.html(contact us) and open.html(Opening Hours). The website is designed to be basic and simplistic so that the user can easily find what they are looking for and access information in the most simplistic way possible.

## Nav menu

* Nav menu uses a linear gradient with opacity set to 50%, the currently active link will stay underlined after the page has been loaded in so the user knows which page they are currently on.
* Nav menu is also responsive in regards to screen widths and heights.
![ScreenShot_12_04_2022_15_16_08](https://user-images.githubusercontent.com/101630755/162986176-659d186a-e6dc-4d8f-baab-89432bd1ce8b.png)

## Media Queries

* Multiple Media queries have been set to apply when accessed on each different device. changes for responsiveness occur at max width of 298px, 500px and 357px. Min width of 500px. Changes are regarding paragraph size and h2 element size, additionally with the width the size of my div on each page will vary depeinding on the width.
* Multiple Media queries for height have been applied due to certain elements overflowing on the pages. these height changes occur at, 655px,851px,896px,915px,1180px,1368px and 740px. Changes are regarding Font size of paragraphs and H2 elements. additionally smaller screen heights remove the footer so text can fill the space.

## About us

* This page features a paragraph which features the companies mission and their mission statement.
![ScreenShot_12_04_2022_15_18_35](https://user-images.githubusercontent.com/101630755/162985873-7e8940ae-151a-4946-bcde-c9474911fdb4.png)
## Contact us

* This page features the address of the gym the website has been created for.
* This page features a form element so if a potential customer or and existing customer has any questions then they can submit a ticket.

![ScreenShot_12_04_2022_15_22_40](https://user-images.githubusercontent.com/101630755/162986025-3b73c945-9caf-44f9-8aa0-a989bef1c0c9.png)

## Opening Hours

* This page features the opening hours of the gym which are stated in a 12 hour format.

![ScreenShot_12_04_2022_15_32_59](https://user-images.githubusercontent.com/101630755/162986711-e5a7c0e3-375a-44b8-809b-d5525f9a3084.png)

# Future Features

For the future of this page, I would consider adding in a page that allows people to ask questions and post them on the website as an FAQ page. Additionally i would also like to add an online membership so that people who wish to join the gym can sign up online and pay online for their memberships. To add to this I would also like to add a booking system for the website so that people can book appointments with a Personal Trainer Via the website.

# Testing

## W3 Validator

* Tested on W3 validator one error url https://validator.w3.org/nu/?doc=https%3A%2F%2Frossjdurnford.github.io%2FProject-1A%2F. 
Error Corrected. Title was missing.
![error check](https://user-images.githubusercontent.com/101630755/162987524-26703efd-83f3-4244-9ba1-9084aefab483.png)
## Lighthouse test

This page was also tested using https://www.webpagetest.org/lighthouse. This page measures the following;
* Performance - How fast the page loads up content.
* Accessibility - Does the site meet the needs of multiple users.
* Best Practices - Site is in line with industry best practices.
* SEO - Site is optimised for search engine results.
![lighthouse](https://user-images.githubusercontent.com/101630755/163369928-7005a992-959f-4711-b08e-578727ddbac6.png)

## CSS Validation

The CSS of this website has also been tested by using https://jigsaw.w3.org/css-validator/#validate_by_uri+with_options. This was done by directly inputting the CSS into the validator.

![CSS-validator](https://user-images.githubusercontent.com/101630755/165264415-2bcfeaf3-936b-496e-b22e-f0fedf7ab2e0.png)

## Compatability Test

This site was tested on Explorer and Chrome.
The first image is the Explorer test.

![explorer-test](https://user-images.githubusercontent.com/101630755/165274321-8a653dfa-298d-456b-beb0-0f2964857f23.png)

The second Image is the Chrome test.

![ScreenShot_12_04_2022_15_17_18](https://user-images.githubusercontent.com/101630755/165274765-2d6cd3d6-8290-4bee-b02c-1bdb2e1b453b.png)

## Responsiveness Test

I have conducted a responsiveness test on this project using the developer tools in google chrome for every device type that is available within the Chrome Dev tools. During the process some adjustments had to be made to media queries, however after making these changes the website has responded well and the appearance of the website on multiple devices would be considered as acceptable. Additionally no features have been removed during this time. Further too this all Links and images are fully working on every device however on some mobiles in future a hamburger menu may be more applicable.





# Bugs and Fixes

* Background cover didnt work,   -webkit-background-size:cover;
    -moz-background-size:cover;
    -o-background-size:cover;
    background-position: center;
    height:100%;
    width:100%;. This was added and fixed the issue. additionally this stopped the whitespace at the bottom of the page.
 * Couldnt get the nav links to underline when selected and the page had loaded, Had to add a class of page-selected, and in the CSS file apply a text decoration of underline with a color of white  

# Deploymment

This information was found on the Code institute IDE and Deployment Essentials.
To deploy this project the steps that i took are as follows:

* Open in GitPod Workspace
* Open a terminal in the workspace
* Use the code git add followed by the file names
* Once all files are added type "git status" to check the files have been uploaded.
* Once the files are uploaded travel to Git Pages. This is found on the settings tab of the GitHub repository.
* Once on the settings tab click on pages.
Once on the pages tab i changed the branch to main and refreshed the page.
* Once the webpage was refreshed my page was then published with a link.

# Cloning the Project

In order to clone this project take the following steps:
 * Just under the Repository name click on the Code tab.
 * Copy the link that is underneath the clone heading.
 * Open GitBash in your IDE.
 * Change your current directory to where you want the clone to be.
 * Type git clone, and then paste the URL copied you have copied earlier.
 * Press Enter to create your clone.

# Technologies used

* [HTML](https://www.w3schools.com/html/html_intro.asp) - This is for the structure of the website.
* [CSS](https://www.w3schools.com/css/css_intro.asp) - This is for the styling of the website.
* [GitPod](https://stackoverflow.com/questions/63588658/what-is-gitpod-what-does-it-actually-do) - This is to Deploy the Website.
* [GitHub](https://github.com/) - This is to host and edit the website. 
* Screenshot Snipping tool, Downloaded from Microsoft store.

# Credits

## Code

* Align Form elements: https://www.youtube.com/watch?v=N8ZMzN40q0g.
* Code Institue Tutoring team

## Media

* Background image fixing: https://www.youtube.com/watch?v=jNXrg0_KFBQ
* https://cdn.pixabay.com/photo/2016/11/19/12/43/barbell-1839086_960_720.jpg. Background image was sourced from here.
 
# Acknowledgements

* Code Institute Diploma in Software Development (E-commerce Applications).
* Code Institute Tutoring team.
* Precious Ijege - Guidance. 
