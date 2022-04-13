# Massive Gym - Project 1
This is a website for a local gym based in West Earlham, Norwich. 
The website will serve potential existsing and new customers living within the local area 
who are interested in getting in shape. The main aim of this website it to design a responsive website using HTML and CSS together to convey a companies message.

# Table Of Content
<!-- TOC -->

- [Massive Gym - Project 1](#massive-gym---project-1)
- [Table Of Content](#table-of-content)
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
    - [Testing](#testing)
    - [Bugs and Fixes](#bugs-and-fixes)
    - [Deploymment](#deploymment)
    - [Cloning the Project](#cloning-the-project)
    - [Technologies used](#technologies-used)
    - [Credits](#credits)

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

## Features

* This website features 4 pages, home.html (homepage), about.html(about us), contact.html(contact us) and open.html(Opening Hours). The website is designed to be basic and simplistic so that the user can easily find what they are looking for and access information in the most simplistic way possible.
### Nav menu
* Nav menu uses a linear gradient with opacity set to 50%, the currently active link will stay underlined after the page has been loaded in so the user knows which page they are currently on.
* Nav menu is also responsive in regards to screen widths and heights.
![ScreenShot_12_04_2022_15_16_08](https://user-images.githubusercontent.com/101630755/162986176-659d186a-e6dc-4d8f-baab-89432bd1ce8b.png)

### Media Queries
* Multiple Media queries have been set to apply when accessed on each different device. changes for responsiveness occur at max width of 298px, 500px and 357px. Min width of 500px. Changes are regarding paragraph size and h2 element size, additionally with the width the size of my div on each page will vary depeinding on the width.
* Multiple Media queries for height have been applied due to certain elements overflowing on the pages. these height changes occur at, 655px,851px,896px,915px,1180px,1368px and 740px. Changes are regarding Font size of paragraphs and H2 elements. additionally smaller screen heights remove the footer so text can fill the space.
### About us

* This page features a paragraph which features the companies mission and their mission statement.
![ScreenShot_12_04_2022_15_18_35](https://user-images.githubusercontent.com/101630755/162985873-7e8940ae-151a-4946-bcde-c9474911fdb4.png)
### Contact us

* This page features the address of the gym the website has been created for.
* This page features a form element so if a potential customer or and existing customer has any questions then they can submit a ticket.

![ScreenShot_12_04_2022_15_22_40](https://user-images.githubusercontent.com/101630755/162986025-3b73c945-9caf-44f9-8aa0-a989bef1c0c9.png)

### Opening Hours

* This page features the opening hours of the gym which are stated in a 12 hour format.

![ScreenShot_12_04_2022_15_32_59](https://user-images.githubusercontent.com/101630755/162986711-e5a7c0e3-375a-44b8-809b-d5525f9a3084.png)


## Testing

* Tested on W3 validator one error url https://validator.w3.org/nu/?doc=https%3A%2F%2Frossjdurnford.github.io%2FProject-1A%2F. 
Error Corrected. Title was missing.
![error check](https://user-images.githubusercontent.com/101630755/162987524-26703efd-83f3-4244-9ba1-9084aefab483.png)
## Bugs and Fixes

* Background cover didnt work,   -webkit-background-size:cover;
    -moz-background-size:cover;
    -o-background-size:cover;
    background-position: center;
    height:100%;
    width:100%;. This was added and fixed the issue. additionally this stopped the whitespace at the bottom of the page.
 * Couldnt get the nav links to underline when selected and the page had loaded, Had to add a class of page-selected, and in the CSS file apply a text decoration of underline with a color of white  

## Deploymment

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

## Cloning the Project

In order to clone this project take the following steps:
 * Just under the Repository name click on the Code tab.
 * Copy the link that is underneath the clone heading.
 * Open GitBash in your IDE.
 * Change your current directory to where you want the clone to be.
 * Type git clone, and then paste the URL copied you have copied earlier.
 * Press Enter to create your clone.

## Technologies used

* HTML - This is for the structure of the website.
* CSS - This is for the styling of the website.
* GitPod - This is to Deploy the Website.
* GitHub - This is to host and edit the website. 
* Screenshot Snipping tool, Downloaded from Microsoft store.
## Credits
* Align Form elements: https://www.youtube.com/watch?v=N8ZMzN40q0g.
* Background image fixing: https://www.youtube.com/watch?v=jNXrg0_KFBQ
