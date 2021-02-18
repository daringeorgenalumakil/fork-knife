# Testing
## Table of Contents
* [Encounterd Issues](#EncounterdIssues)
* [Testing User Stories](#TestingUserStories)
* [Testing Functionality](#TestingFunctionality)
* [Testing Combatability](#TestingCombatability)
* [Testing Performance](#TestingPerformance)
* [Code Validation](#CodeValidation)
* [Further Testing](#FurtherTesting)
# EncounterdIssues
## Issues found during the process: 
* Collapse Menu wont close back when cliciking on the icon again without selecting any dropdown links.
    * Fixed this by commenting out the unwanated JS Libraries bellow each page.
* Other issues foud during the process was when using [W3C Markup](https://validator.w3.org/). For example: ![Error](/assets/images/errorfoundonpage.png) These errors were found on all the pages which has buttons as links to different pages.
    * Fixed this by taking out *Button* tag from the *a* tag and kept the *a* tag on its own.
# TestingUserStories
* Testing User Stories
    * To be able to navigate through the website comfortably and easily.
        * As soon as the user is landed on the page they are met with Nav bar on the top with links to differ pages.
        * User is also met with button which takes them right to a specific page rather thank going to nav links for accessibility.
    * To be able to see through mobile first and pass it to my peers.
        * The project is build in a mobile-first manner which means that every piece of information is design to be easily displayed on 
            mobile first and expanded on a bigger screen whitout changing the functionality.
    * To easily understand the purpose of the page.
        * As the user lands on the website, the first thing it shows up is a big heading which briefly describe the websites purpose.
    * To be able to find who owns the Buisness and how to contact them, This will give me more confidence to book a table and also the restaurant.
        * Users are given forms on relevant pages with either buttons or forms to be able to contact the buisness.
    * To be able to view some photos of popular dishes.
        * Users will be met with gallery page to show the images of popular dishes along with other images for the restaurant. 
# TestingFunctionality
# TestingCombatability
# TestingPerformance
* Performance Testing was done by using the Chrome Developer tool called [Lighthouse](https://developers.google.com/web/tools/lighthouse). Used this application for testing the performance of every page. Here are the results:
    * ## Index page
        * ![Error](/assets/images/landingpageperformance.png)
        * Performance did vary on this page due to the heavy use of images especially images in the carousel for gallery. Overall the performance was satifying.
    * ## Menu pages
        * ![Error](/assets/images/menupageperformance.png)
        * Performance on this page were extremely good as these pages only had one image in them.
    * ## Offers page
        * ![Error](/assets/images/offerspageperformance.png)
        * Performance on this page was acceptable, just had slight issue with painting the page as the offers are serperated into 2 different sections. Other than that the performance was acceptable.
    * ## Contact page
        * ![Error](/assets/images/contactpageperformance.png)
        * Performance on this page were extremely good as these pages only had one image in them and a map to give directions for the User.
# CodeValidation
* HTML
    * HTML was tested and validated with [W3C Markup](https://validator.w3.org/) by direct input. No errors or issues. The results are satisfying on all pages.
* CSS
    * CSS was validated with [W3C CSS](https://jigsaw.w3.org/css-validator/) by direct input. The results came with no errors.
# FurtherTesting