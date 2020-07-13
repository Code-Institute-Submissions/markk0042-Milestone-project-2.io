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

## User stories:

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

### Site Strategy:

The goal in the design of my site was to make it as easy accessable to the user, short and an informative information with the ability to provide further information if the user requests it,
while aiming for a easy user-friendly layout and design as possible.

### Scope:

For B2B visitors, we wanted to provide them with a short overview of the products and the companies strongest points.
This way, they would be able to get a glimpse of what the company sells and if it is a trustworthy partner to do business with.

### Structure:

The site is structured to get the right information as quickly as possible.
Contact information on the top and further down buttons to get to the contact form.
A navigation bar that's always available to quickly scroll between pages.
The proper order of the pages is created to trigger the reader to contact us.

### Skeleton:

By using figma the following wireframes were created:
Landing Page **[here](https://github.com/markk0042/Milestone-project-2.io/blob/master/Wireframe-home-page.png)**

### Surface:
I used White and Grey colours so they were not harsh on the eye and text would be easily readable.
I used font styles from Google Fonts, to improve the look of the site to make it less boring and more interesting.
I used Font Awesome to improve the blandness of the site to create icons representing what the navbar options were.

## Technologies Used:
1. HTML - *To create a basic site*
2. CSS - *To style the site and to stand-out to the eye*
3. Bootstrap4 - *For layouts and platform responsiveness*
4. Figma - *To create a wireframe*
5. Javascript - *To make the site interactive, and responsive*
6. APIs - *To add features to the website, making it more interactive* 


## Features:
The navbar when used on smaller devices will be collapsed into a hamburger style dropdown menu on smaller screen sizes to be useful for phones and tablets and will be available on every page.
On larger screens the navbar will be fully displayed across the screen and all sections will fit the screen to size.
The button on the main page was created to move the user to the Tour page instantly by clicking it without having to look to the nav bar for the tour details.


### Features Left to Implement
In the future, we would like to add an option to make purchases on the website, enter discount codes for the elderly, students, families etc.
Also, I would like to add a FAQ section for future people interested in the tours that could ask questions that others have experienced. 
I would also like to add a video compilation of different tours that capture different parts of the tours, different parts of ireland and maybe some past experience reviews.


## Testing
All links function as expected, the social media links will open the link on a new page using target_blank method.
The "Send Query" button on the contact page will inniatiate the SDK used from email.js to send my email a copy of the users query with their name and email attached to the email the send.
The site when firstly launched was tested by 15 people of my choice, some reported the jumbotron image was not loading this was due to the css not having,

-webkit-background-size: cover;
-moz-background-size: cover;
-o-background-size: cover;

Once these were added the image then rendered 10-15 minutes later  and succesfully appeared.
The site was tested across multiple screen sizes and devices on Chrome, Safari and Internet Explorer via Apple, Samsung, Tablets etc. this was to ensure device compatibility and responsiveness.
When the webpage is visited on larger screens the review section appears with images, on smaller devices the images disappear to fit better.
A navigation bar is shown all the time on the top of the page and will change to an option bar on smaller phone screens and tablets.
The download buttons on each timetable work and open a new window/tab.

The APIs for the google maps work on all devices, with scrolling and zooming function, with the markers indicated on both maps on all devices.

The SDK from email.js works on all devices big and small, fits nicely on all devices, when details are entered into the contact us boxes, if the email box does not contain a valid email it will return the statement "enter a valid email address" and will not submit the form until this is done. When entered correctly and sent the email linked to the SDk template, will recieve a corresponding email from this site, I have tested this on 15 devices and all sent the email through successfully.

When the console Log is checked upon using the site from github pages the concole does not return any errors found, all links work, along with tabs, image loading, ApIs, SDK, and Email.js with no returning errors after being reviewed.

The footer will place the links and text beneath each other to make it more readable and better layout for smaller screens to ensure they fit neatly.

The following tests have been used to ensure proper site functionality:

- [W3C HTML Validator](https://validator.w3.org/): This is a validator that checks the markup of Web documents in HTML.
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/): This is a validator that checks the markup validity of Web documents in CSS.
- [Unicorn Revealer](https://chrome.google.com/webstore/detail/unicorn-revealer/lmlkphhdlngaicolpmaakfmhplagoaln?hl=en-GB): Inspecting on overflow errors
- [Autoprefixer CSS online](https://autoprefixer.github.io/): Autoprefixer is a PostCSS plugin which parses your CSS and adds vendor prefixes

## Deployment
This site is hosted using GitHub pages on my repositories, its deployed directly from the master branch. The deployed site will update automatically when a  new commit(s) to the master branch(I have noticed a short delay image rendering once pushed to the master branch for website viewing on a live demo). In order for the site to deploy correctly on GitHub pages, the landing page must be named `index.html` and not inside any files or folders.

To run locally, you can clone this repository directly into the editor of your choice by pasting the link into your terminal on your computer
To cut any ties with this GitHub repository, type `git remote rm origin` into the terminal and this will remove the origin of the repo.


## Credits

### Content
- I used information from 
(https://www.roadaffair.com/best-places-to-visit-in-ireland/).
(https://en.wikipedia.org/wiki/List_of_tourist_attractions_in_Ireland).,
- For the information on the tour section, then the quotes I used were from 
(https://quotabulary.com/famous-irish-quotes).
- I used assistance from youtube videos such as 
(https://youtu.be/Zxf1mnP5zcw). As I ran into some issues with having my template, and map renerding on my site.
- I used Inspiration from `Code Institutes` form, from our previous projects to add a contact us form to my current project.
- 

### Media
All photos were taken from [Pixabay](https://pixabay.com/), a stock image library.
also from [Wikipedia](https://en.wikipedia.org/wiki/Wikipedia:Public_domain_image_resources).

### Acknowledgements

- The Navbar Scrolling effect was found on Bootstrap4 [link](https://getbootstrap.com//howto_css_parallax.asp).
- The Carousel image slider was found on [link](https://getbootstrap.com//howto_css_parallax.asp).
- The Footer was found on [link](https://mdbootstrap.com/docs/jquery/?utm_ref_id=57491).
- Google Maps APIs [link](https://developers.google.com/maps/documentation/javascript/tutorial).
- The SDK Email.js [link](https://www.emailjs.com/).
