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
* ## Issues found during the process: 
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
* ## Index page
    * Starting from top to bottom, left to right, click on every button, link, toggle to check for expected action.
        * top navigation fully functional including the brand title and logo.
        * Book a Table button toggles the modal form. The X button and clicking outsite the modal container closes the modal.
        * Modal form: submit button is submiting the form.
        * Footer: Social media buttons open each the expected link on a new tab.
* ## Offers, Contact and Menu Pages.
    * Starting from top to bottom, left to right, click on every button, link, toggle to check for expected action.
        * All the buttons in these pages take the user to the desired page.
* ## Testing browser back/forward action
    * Navigation: browser back and forward and mobile back tap acts as expected throughout. Although, when modal is opened, the back click/tap targets the url and it doesn't toggle/close the modal. In order to function like this, it requires further Javascript coding. This is left to be implemented.
* ## Testing form validation
    * Book a table modal form: the form was tested for validation by trying to submit first with no field filled and then by filling the fields one by one. Result as expected, all fields asked for input. The email field asks for email format with @ and the date and time fields cannot be filled differently.
    * Submit a Feedback modal form: the form was tested for validation by trying to submit first with no field filled and then by filling the fields one by one. Result as expected, all fields asked for input.
# TestingCombatability
* ## Responsiveness
    * Using DevTools and different device sizes such as mobile and tablet, the website was tested for any posible screen size combination and orientation. No issues found. Site is size compatible.
* ## OS Test
    * ### Desktop
        * The website was tested on Windows 7 and Windows 10 systems. Result as expected, desktop system-cross compatible.
    * ### Mobile
        * The website was tested on Android 9 and Android 10. Result as expected, mobile system-cross compatible.
    * ### Tablet
        * The website was tested on iPAD pro. Result as expected, tablet system-cross compatible.
* ## Browser Test
    * The website was tested on Google Chrome, Firefox, Safari, Edge, Internet Explorer. Browsers versions were all up to date. Further testing was done using [Browser Ling](https://www.browserling.com/) and the website was tested for android 7 native browser. Results were consistent. Conclusion: the website is browser-cross compatible.
# TestingPerformance
* Performance Testing was done by using the Chrome Developer tool called [Lighthouse](https://developers.google.com/web/tools/lighthouse). Used this application for testing the performance of every page. Here are the results:
    * ## Index page
        * ![Performane Index](/assets/images/landingpageperformance.png)
        * Performance did vary on this page due to the heavy use of images especially images in the carousel for gallery. Overall the performance was satifying.
    * ## Menu pages
        * ![Performance Menu](/assets/images/menupageperformance.png)
        * Performance on this page were extremely good as these pages only had one image in them.
    * ## Offers page
        * ![Performance Offers](/assets/images/offerspageperformance.png)
        * Performance on this page was acceptable, just had slight issue with painting the page as the offers are serperated into 2 different sections. Other than that the performance was acceptable.
    * ## Contact page
        * ![Performance Contact](/assets/images/contactpageperformance.png)
        * Performance on this page were extremely good as these pages only had one image in them and a map to give directions for the User.
# CodeValidation
* HTML
    * HTML was tested and validated with [W3C Markup](https://validator.w3.org/) by direct input. No errors or issues. The results are satisfying on all pages.
* CSS
    * CSS was validated with [W3C CSS](https://jigsaw.w3.org/css-validator/) by direct input. The results came with no errors.
# FurtherTesting
* ## Overflow
    * Every page was tested for overflow by using the [Unicorn Revealer](https://chrome.google.com/webstore/detail/unicorn-revealer/lmlkphhdlngaicolpmaakfmhplagoaln?hl=en-GB) chrome extension to highlight the elements margins.