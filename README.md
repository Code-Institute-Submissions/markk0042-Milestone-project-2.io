# MILESTONE PROJECT 2: Interactive Frontend Development - Code Insititute

HI reader,

### Welcome to my Milestone two project for code Institutes 2nd of 4 projects for my journey to become a full stack developer.

## DEMO:
My wireframe mockup is attached to my repository on github for viewing.
A live demo version can be found **[here](https://markk0042.github.io/Milestone-project-2.io/)**


## Introduction:
In my current project I picked to do it on, is about a Tourism site, showcasing Irelands top 7 tourist attractions throughout ireland (according to reports from @IrishCentral
May 13, 2015). I chose this project because Ireland is amongst the top 10 countries in Europe for visitng as a city break, and why not see other parts of the fabulous country
of Ireland while here!. In this website you will see a standard navbar structure, with a Jumbotron of a beautiful image of the cliffs of Moher in the backroung, 
with a company slogan on the front of the image. Then as you scroll down there is images at the bottom of the page in a carousel structured image slider, with a title and
location of where each image is from in the Country/Region, with the option to view them slowly when they automatically slide by function or by the user clicking 
on the arrows on either side of the image for previous or next.Then I have created a page outlining the images of a small detail of history of each attraction site,
and adding a API to the base of the screen for the user to interact and see how far or near the different attractions are from them. There is also in the footer standard links  
to the social networks, and contact details with adress also.There is a price page for if the user decides to take fantastic tour of the country at the various destinations, 
with different price ranges, OAPs, youth and family tickets, and a timetable of when the coaches leave the terminal each day for the tours, with a downloadable feature of each timetable.
Then on the contact page I added the email.js SDK file and set up the email function, giving the user the ability to contact the staff for further information regarding the features and dates etc.

The main goal is to make the company known on the web and to trigger a new and broader interest of Ireland fabulous historical monuments and sites.

## UX
I aimed to make the website as clear as possible to the user to promote the Tourism company.
To have a simple layout, structure, and not over powered website, with the main focus on the companies services, products and features.
To promote deals, and prices for all ages and discounts at certain T&Cs.

## User stories
By research of asking friends, family, work colleagues and neighbours, I wanted to find out what they would like to see on the website, how it can help people who do not know much or Ireland in regards to history.
I asked for the most beneficial elements that would be essential for them to have ability to view on it:

### The following ideas came to mind:

 - As a user of the tour site, I want to see if this company is priced well, compared to other sites of the same attraction. (**Timetable page**)
 - As a user of the tour site, I want to know if this company can offer different destination to be picked up from besides Dublin. (**Tour Page**)
 - As a user of the tour site, I want to know how much it will cost, is there any deals for family tickets or OAPs?.( **Timetable page**)
 - As a user of the tour site, I would like to see customer reviews of previous tours that were undertaken. (**Main Landing page**)
 - As a user of the tour site, I would like to see the option/ ability to have a email contact for the company, as work takes over my time and I wouldnt be able to ring during my 9-5 job. ( **Contact page on Nav**)
 - As a user of the tour site, I would find it beneficial for the youth that there is social links which could represent deals, images, and information regarding the tours, site and any change to schedules. ( **Social links in footer**).
 - As a user of the tour site, I think some history of each attraction and details where theyre situated would benefit sales more as some history may appeal differently to others.. (**Tour page**)

### Strategy
The goal in the design was to make it as easy as possible to access, short and an informative B2B based site,
while striving for a minimalist and user-friendly design as possible.

### Scope
For B2B visitors, we wanted to provide them with a short overview of the products and the companies strongest points.
This way, they would be able to get a glimpse of what the company sells and if it is a trustworthy partner to do business with.

### Structure
The site is structured to get the right information as quickly as possible.
Contact information on the top and further down buttons to get to the contact form.
A navigation bar that's always available to quickly scroll between pages.
The proper order of the pages is created to trigger the reader to contact us.

### Skeleton
By using figma the following wireframes were created:

[EL1TE wireframe](https://github.com/D1ang/EL1TE/blob/master/mockups/wireframe.pdf)

[Responsive phone wireframe](https://github.com/D1ang/EL1TE/blob/master/mockups/responsive.pdf)

### Surface
The colours blue and orange were used to create a high energy "sport" like feel.
After a short Google search for the most used Google Fonts on sport sites, Oswald was chosen on its popularity and demand.
The buttons are styled as blocks to be in comformt with the header block and to keep the style in check with the blue call to action block.

## Technologies
1. HTML - *To create a basic site*
2. CSS - *To create a nice style and to stand-out*
3. Bootstrap - *To improve responsiveness*
4. Figma - *To create a wireframe*


## Features
This site uses a parallax scrolling effect in CSS to create a subtle element of depth that results in a distinctive and memorable website. 
The navbar collapsed on smaller screen sizes to be useful for phones and will be available on every page.
On larger screens a "call to action" blue box wil appear so user can contact more quickly without scrolling through the page.
by using Smooth Scrolling a scroll effect has been added as the site felt a bit sluggish.
The buttons are created to move the user to the contact page as this would be the final step that we would like to achieve.


### Features Left to Implement
In the future, we would like to add an order system with a login so existing customers can order more products easily.
Also, we would like to add some animations to the cards in the products and prices section to move on the page when the section is scrolled to. 


## Testing
All links will function, but the social media links will open the main page of that particular platform.
The "Send us your details" button will return to the home section.
Custom CCS code is written for every button comfort design.

This site was tested across multiple screen sizes on Chrome, Safari and Internet Explore
To ensure compatibility and responsiveness it was also tested on an android based mobile device (OnePlus5).
When the webpage is visited on larger screens a blue box is shown on the upper right side of the screen.
This will disappear on smaller screens the box is used for direct to call actions and social media.
A navigation bar is shown all the time and will transform to an option bar on smaller phone screens.

The text and card-decks will properly align on every screen size. The card-decks have some extra CSS code to improve alignment of the content within the cards.
The footer will place the text beneath each other to make it better readable for smaller screens.

## Bugs:

### Card-decks responsive:
The standard Bootstrap functions gave problems with the content inside cards. On card-decks the content got squashed so a solution needed to be found.
[stack overflow](https://stackoverflow.com/questions/48406628/bootstrap-align-button-to-the-bottom-of-card)
This solution steps away from the regular bootstrap grid and uses a workaround in CSS to fix the responsive problems.

### Scrolling:
The site felt a bit sluggish when scrolling with the buttons to different pages.
[w3schools.com](https://www.w3schools.com/howto/howto_css_smooth_scroll.asp)
By using Smooth Scroll the navigation buttons to the pages will react more fluid.

### Navbar hamburger icon:
The navigation bar hamburger icon that shows on smaller screens had an outline when pressed, and jumped a few pixels up.
This has been fixed by adding a top-padding of 3 pixels in the style and by adding the following code:

>.navbar-toggler:focus,
>.navbar-toggler:active {
>	outline: none;
>	box-shadow: none;
>}


The following tests have been used to ensure proper site functionality:

- [GTmetrix](https://gtmetrix.com/): To test on website loading times
- [W3C HTML Validator](https://validator.w3.org/): This validator checks the markup validity of Web documents in HTML.
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/): This validator checks the markup validity of Web documents in CSS.
- [Unicorn Revealer](https://chrome.google.com/webstore/detail/unicorn-revealer/lmlkphhdlngaicolpmaakfmhplagoaln?hl=en-GB): Inspecting on overflow errors
- [Autoprefixer CSS online](https://autoprefixer.github.io/): Autoprefixer is a PostCSS plugin which parses your CSS and adds vendor prefixes


## Deployment
This site is hosted using GitHub pages via my repositories, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch(I have noticed a short delay inmage rendering once pushed to the master branch for website viewing on a live demo). In order for the site to deploy correctly on GitHub pages, the landing page must be named `index.html` and not inside any files or folders.

To run locally, you can clone this repository directly into the editor of your choice by pasting the link into your terminal on your computer
To cut any ties with this GitHub repository, type `git remote rm origin` into the terminal and this will remove the origin of the repo.


## Credits

### Content
I copied information from () for the information on the tour section, the timetable information and layout, I used and created and styled, the quotes I used were from ()

### Media
All photos were taken from [Adobe Stock](https://stock.adobe.com/), a stock image library.
All material from Adobe Stock are licensed with a paid account.


### Acknowledgements

- The Parallax Scrolling effect was found on w3schools.com [link](https://www.w3schools.com/howto/howto_css_parallax.asp) (by mentor advice)
- Fixing the card-decks responsiveness [link](https://stackoverflow.com/questions/48406628/bootstrap-align-button-to-the-bottom-of-card)
- The following site [link](https://www.mbsportswear.nl/) was used as an insparation for the navigation bar and blue "call to action" box.menu-not-working)