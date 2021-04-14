<h1 align="left">Milestone Project One - "Driven: Formula One Fan Club"</h1>

[View the live project here.](https://michaelhesch.github.io/ci-ms-1/)

The purpose of this website is to promote a fictional Formula One fan club called "Driven" which operates across Europe.  The page serves to highlight the benefits of being a member in the club, upcoming club events, and location information about fictional physical club locations.  In addition, the page includes a form where a visitor can apply to become a member in the club, with a choice of membership level.

## User Experience (UX)

-   ### User stories

    -   #### First Time Visitor Goals

        ##### As a first time visitor, I want to:
        1. Learn about the Driven Formula One club, and the benefits it offers.
        2. Learn about upcoming events being held by the club.
        3. Learn about where the club operates physical locations throughout Europe and the opening hours of each club.

    -   #### Returning Visitor Goals

        ##### As a returning visitor, I want to:
        1.  Sign up for the club using the form in the "Join the Club" page.
        2.  Check for newly posted upcoming club events.
        3.  Check the physical club locations across Europe and opening hours of each club.

-   ### Design
    -   #### Colour Scheme
        -   The page color scheme is based on dark and light gray tones to give a clean and somewhat spartan design asthetic throughout the site.
    -   #### Typography
        -   The font used throughout the site is the Google Font 'Open Sans' which gives a clean and simple font which is easy to read across font sizes.  The goal of selecting this font was to further encourage a clean and simple aesthetic on the site.  Sans-serif serves as the backup to Open Sans if it fails to load.
    -   #### Imagery
        -   Hero image utilized across the site presents a dramatic view of a Formula One car with the club name overlayed to engage and excite the visitor about the club.  In addition the landing page uses images of Formula One races in progress to draw the visitor's attention to the key details about the club.

*   ### Wireframes

    -   Mobile Wireframes - Home, Club Locations & Join The Club pages - [View](https://github.com/michaelhesch/ci-ms-1/tree/main/documentation/wireframes/mobile-wireframes.pdf)

    -   Tablet Wireframes - Home, Club Locations & Join The Club pages - [View](https://github.com/michaelhesch/ci-ms-1/tree/main/documentation/wireframes/tablet-wireframes.pdf)

    -   Desktop Wireframes - Home, Club Locations & Join The Club pages  - [View](https://github.com/michaelhesch/ci-ms-1/tree/main/documentation/wireframes/desktop-wireframes.pdf)

## Features

-   Three page, responsive design across device & browser sizes.

-   Presentation of information about the Driven club. 

-   Application form to join the Driven club.

## Technologies Used

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
-   [JavaScript](https://en.wikipedia.org/wiki/JavaScript) - as required by Bootstrap for menu responsiveness, no other JavaScript elements were included.

### Frameworks, Libraries & Programs Used

1. [Bootstrap 4.2.1:](https://getbootstrap.com/docs/4.2/getting-started/introduction/)
    - Bootstrap was used to assist with the responsiveness and styling of the website.
1. [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the 'Open Sans' font into the style.css file which is used on all pages throughout the project.
1. [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used on the index page to add icons to add a visual highlight to the "club benefits" section, and for the social media links in the footer of all pages.
1. [jQuery:](https://jquery.com/)
    - jQuery was included with Bootstrap and required to make the navbar responsive, enabling the "hamburger" menu to function when viewing the page on a mobile device or small screen.
1. [Maps.ie:](https://www.maps.ie/create-google-map/)
    - Online tool to create Google Maps iframe tags for specific locations was used to set up the Club Locations maps.
1. [Wikipedia:](https://en.wikipedia.org/wiki/Formula_One_car)
    - Wikipedia pages covering Formula One and Formula One cars used for photo content.
1. [Pixabay:](https://www.pixabay.com/)
    - Pixabay free & royalty free stock images page used to include additional photo content.
1. [w3schools.com:](https://www.w3schools.com/bootstrap4/default.asp)
    - Referenced w3schools Bootstrap 4 page to leverage code samples to work off of for different features, for example in configuring the responsive menu bar.
1. [Code Institute Full-Stack Developer Course:](https://www.codeinstitute.net/)
    - Referenced past projects in Code Institute Full-Stack course for code samples to work off of, for example in the "Upcoming Events" section of the index page.
1. [Balsamiq:](https://balsamiq.com/)
    - Balsamiq was used to create the design wireframes used to outline the webpage before development.
1. [GIMP:](https://www.gimp.org/)
    - GIMP (GNU Image Manipulation Program) is a free and open source image editor, used to resize and adjust the images used on the site for better performance.
1. [Visual Stuido Code:](https://code.visualstudio.com/)
    - Visual Stuido code was used as the desktop development IDE for the project, managing the code and assets for the page during development.
1. [Git:](https://git-scm.com/)
    - Git was used for version control by utilizing the Windows command prompt/terminal interface to commit and push to GitHub.
1. [GitHub:](https://github.com/)
    - GitHub is used to store the project's code after being pushed from the local development machine using Git, as well as host the page using GitHub Pages.

## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.  Results of those checks are documented in PDFs included in the project repository and can be accessed by following the links below.

-   [W3C Markup Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - [Results](https://github.com/michaelhesch/ci-ms-1/tree/main/documentation/validation/)
-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - [Results](https://github.com/michaelhesch/ci-ms-1/tree/main/documentation/validation/)

### Testing User Stories from User Experience (UX) Section

-   #### First Time Visitor Goals

    1. Learn about the Driven Formula One club, and the benefits it offers.
        1. When a user arrives at the landing page of the site, they are presented with a clean and clear menu bar for navigation, featuring the name of the club, and a large hero image section to draw their attention.  
        1. The hero image also features a text tagline to further reinforce the brand of the club and further draw the user's attention.  [View Screenshot](https://github.com/michaelhesch/ci-ms-1/tree/main/documentation/screenshots/Home-Hero.PNG)
        1. Continuing further down the page, the benefits of membership in the club are clearly featured in three large tiles with brief text descriptions of each feature. [View Screenshot](https://github.com/michaelhesch/ci-ms-1/tree/main/documentation/screenshots/Home-Features.PNG)

    2. Learn about upcoming events being held by the club.
        1. The second component of the landing page, after the club benefits, is a listing of upcoming club events by location, including day and time. [View Screenshot](https://github.com/michaelhesch/ci-ms-1/tree/main/documentation/screenshots/Home-Events.PNG)

    3. Learn about where the club operates physical locations throughout Europe and the opening hours of each club.
        1. Once the user navigates to the Locations tab, the club's physical locations are clearly displayed in a large grid, including the address and opening hours of each location, as well as a map to help the user visualize the location in each city. [View Screenshot](https://github.com/michaelhesch/ci-ms-1/tree/main/documentation/screenshots/Locations.PNG)

-   #### Returning Visitor Goals

    1.  Sign up for the club using the form in the "Join the Club" page.
        1. After a user visits the page and learns more about the club, they may want to return to submit an application.  This is accomplished by navigating to the "Join the Club" page and filling out a form to collect the user's basic details.  [View Screenshot](https://github.com/michaelhesch/ci-ms-1/tree/main/documentation/screenshots/Join.PNG)
        1. In addition, the user can select their desired membership level from two options, standard & premium, based on the features of each level displayed in the form. [View Screenshot](https://github.com/michaelhesch/ci-ms-1/tree/main/documentation/screenshots/Join.PNG)

    2.  Check for newly posted upcoming club events.
        1. The club events highlight section on the landing page would be updated rountinely by the club as new events are held, and as time passes, so this section will provide a quick and easy reference point for a returning user to view events. [View Screenshot](https://github.com/michaelhesch/ci-ms-1/tree/main/documentation/screenshots/Home-Events.PNG)

    3.  Check the physical club locations across Europe and opening hours of each club.
        1. As the club expands, users can easily view newly added locations on the "Locations" tab of the page, which would be updated to include the address and opening hours details for new club locations. [View Screenshot](https://github.com/michaelhesch/ci-ms-1/tree/main/documentation/screenshots/Locations.PNG)

### Further Testing

-   All pages were tested for responsiveness and any visible bugs using Google Chrome developer tools to change the viewing size across devices.  In addition, all pages on the site were tested for correct behavior on a 27" desktop monitor, a 15.1" laptop monitor, an iPhone 11 and a 10.5" iPad.
-   The Lighthouse tool in Chrome Developer tools was used to generate performance scores and identify areas for improvement in both mobile and desktop views of the page.  Results of this scoring can be viewed via the links below:

    1.  Mobile Scores:
        1. [Home Page](https://github.com/michaelhesch/ci-ms-1/tree/main/documentation/lighthouse/home-mobile.pdf)
        1. [Club Locations Page](https://github.com/michaelhesch/ci-ms-1/tree/main/documentation/lighthouse/locations-mobile.pdf)
        1. [Join the Club Page](https://github.com/michaelhesch/ci-ms-1/tree/main/documentation/lighthouse/join-mobile.pdf)
    
    1. Desktop Scores:
        1. [Home Page](https://github.com/michaelhesch/ci-ms-1/tree/main/documentation/lighthouse/home-desktop.pdf)
        1. [Club Locations Page](https://github.com/michaelhesch/ci-ms-1/tree/main/documentation/lighthouse/locations-desktop.pdf)
        1. [Join the Club Page](https://github.com/michaelhesch/ci-ms-1/tree/main/documentation/lighthouse/join-desktop.pdf)

-   Please note that while efforts to coprrect some defects indicated in these results are due to issues found in external dependencies, such as Bootstrap's CSS, the version of jQuery used in this Bootstrap implementation, the HTTP version configured in the GitHub Pages server that the site is deployed on, etc. or other faults that are beyond the scope of this project to remedy.

### Issues Encountered in Development

- [Resolved] Font size responsiveness.  During testing of the initial implementation of the page, I found that on smaller device sizes the font sizes for some elements remained too large as the rest of the page scaled appropriately.  This was particuarly an issue for the hero image text banner, the page title on the menu bar, and the headings for the responsive elements on the landing page and club locations pages.  This was resolved by including CSS media queries to add additional responsivenss to reduce the text size based on device screen size.   
- [Resolved] Image asset linking.  Upon deploying the site, image links that worked locally were not working.  Upon further investigation, this was due to the file path used in the local development environment being inconsistent with what was needed for the GitHub Pages environment.  Specifically, the local environment links were set up as "../Project_Path/assets/img/img.jpg", which returned to the root directory, where they needed to be "./assets/img/img.jpg" when deployed to "point" to the correct file path.
- [Open] Club Locations page maps.  The current implementation of maps via iframes does not allow for the items displayed on the maps to be cleaned up, resulting in a somewhat 'busy' or cluttered user experience on this page.  This can be fixed using the Google Maps JavaScript API to hide the map markers that are displayed by default, however I was not able to find a solution to do this through the iframe implementation used for this page.

## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the following steps:

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/michaelhesch/ci-ms-1/)
2. From the Repository menu, select "Settings" at the far right of the menu bar.
3. Scroll down the Settings page and select the "Pages" option.
4. Under "Source", click the dropdown and select "Main" to select the main branch of the project.  Press "save".
5. The page will automatically refresh.
6. The site has now been published and GitHub will display the [link](https://michaelhesch.github.io/ci-ms-1/) in a green box.

### Making a Local Clone

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/michaelhesch/ci-ms-1/)
2. Under the repository name, click "Code", then select the clipboard icon under "Clone with HTTPS" to copy the link.
3. Open Git Bash
4. Change the current working directory to the location where you want the cloned directory.
5. Type `git clone`, and then paste the URL you copied in Step 2.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```

6. Press Enter. Your local clone will be created.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
> Cloning into `Test-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```

Click [Here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) to visit GitHub Help for more detailed explanations of the cloning process.

## Credits

### Code

-   [Code Institute Full-Stack Developer Course](https://www.codeinstitute.net/) : Code snippets from example projects, Love Running and the UCD Resume in particular, were used as basis for Hero Image layout and Upcoming Club Events section. 

-   [Bootstrap4](https://getbootstrap.com/docs/4.4/getting-started/introduction/) : Bootstrap Library used throughout the project mainly to make site responsive using the Bootstrap Grid System, as well as for basic layout of navigation menu and form layout.

-   [README Template](https://github.com/Code-Institute-Solutions/SampleREADME) : Template for the README.md file for this project was sourced from Code Institute.

### Content

-   All text content in the page was written by the developer.

-   Addresses and other contact details presented in the site, including map locations, were selected by the developer.

### Media

-   All Images were sourced externally, from Wikipedia or are royalty free images from Pixabay.  Specific image credits below:

-   The hero image came from [Pixabay](https://pixabay.com/photos/ferrari-formula-1-fernand-alonso-f1-490617/)

-   The upcoming club activity background image came from [Pixabay](https://pixabay.com/photos/racetrack-lane-line-arrival-sport-794589/)

-   The three feature images used in the club benefits section came from [Wikipedia - Formula One](https://en.wikipedia.org/wiki/Formula_One) and [Wikipedia - Formula One Car](https://en.wikipedia.org/wiki/Formula_One_car)

### Acknowledgements

-   My Code Institute Mentor for helpful feedback on my ideas prior to development and throughout the project.
