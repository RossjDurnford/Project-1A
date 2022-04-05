# Massive Gym - Project 1
This is a website for a local gym based in West Earlham, Norwich. 
The website will serve potential existsing and new customers living within the local area 
who are interested in getting in shape. The main aim of this website it to design a responsive website using HTML and CSS together to convey a companies message.

## Testing

* Tested on W3 validator one error url https://validator.w3.org/nu/?doc=https%3A%2F%2Frossjdurnford.github.io%2FProject-1A%2F. 
Error Corrected. Title was missing.
## Color Scheme

The colour scheme for this project is largely centered around the background colours and trying to fit in with that as well as being noticeable. The colours used are as follows:
* H1,P,A. White
* H2 Home page, White, Red, rgba(9, 86, 185, 0.938)
* H2 All other pages, rgba(9, 86, 185, 0.938)
* Nav and Footer, Linear Gradient, rgba(9, 86, 185, 0.938) into Black

## CSS Rules

* Nav and Footer uses linear gradient with opacity set to 50%.
*  font family is'Segoe UI', Tahoma, Geneva, Verdana, sans-serif, applied to body element.
* Multiple Media queries have been set to apply when accessed on each different device. changes for responsiveness occur at max width of 298px, 500px. Min width of 500px. The rest of the change are applied with a max height.

### Max height changes

The reason for multiple changes is because when the page was viewed at certain heights and widths the p and a elements were not displaying correctly due to the height.

* Screen size: 915px - a font size is 17px
* Screen size: 1368px - p + a font size is 24px
* Screen size: 653px - a font size is 10px, p font size is 17px
* Screen size: 720px - p + a font size is 17 px

## Bugs and Fixes

* Background cover didnt work,   -webkit-background-size:cover;
    -moz-background-size:cover;
    -o-background-size:cover;
    background-position: center;
    height:100%;
    width:100%;. This was added and fixed the issue. additionally this stopped the whitespace at the bottom of the page.

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

## Credits
* Align Form elements: https://www.youtube.com/watch?v=N8ZMzN40q0g.
* Background image fixing: https://www.youtube.com/watch?v=jNXrg0_KFBQ