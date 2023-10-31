# Pawfect Pups

![Pawfect Pups Preview Image](assets/readme-files/pawfect-pups-preview.png)

[Click here to view the live project](https://lunartechfreek.github.io/pawfect-pups/contact.html)

## Introduction

Pawfect Pups is a fictional dog training company made for educational purposes as the first portfolio project for my diploma in software development that i am studying with the code intitute. This website is aimed at dog owners who would like to find a local dog training company.

While designing this website i took into account the real world demands that customers would have for a real dog training company. I have created static website with a total of six pages that are responsive and contain relevant and useful information to reach these goals.

I have applied the the technologies i have learnt so far and used HTML5 and CSS3 to create my website. Other technologies used are listed in the technologies used section further down the page.

## UX

### User Demographic

The ideal users for this website will be:

* External - New user
* External - Current user
* Site owner

### User Stories

#### External - New User Goals

* As a new user i want to, find a good dog trainer.
* As a new user i want to, find a suitable training class.
* As a new user i want to, navigate the site with ease.
* As a new user i want to, use a well layed out and visually appealing website.
* As a new user i want to, easily find relevant information.
* As a new user i want to, see pictures of the training they offer.
* As a new user i want to, be able to find where they are located with ease.

#### External - Current User Goals

* As a current user i want to, navigate the site with ease.
* As a current user i want to, see that the website is updated regularly with any changed to the trainers, classes or the contact details.

#### Site Owner Goals

* As the site owner i want to, build my business online.
* As the site owner I want to, show the full range of the services we offer.
* As the site owner I want to, show the user our dog trainers.
* As the site owner I want to, provide a visually friendly user experience.
* As the site owner i want to, provide an easy to navigate website.
* As the site owner I want to, show the user photos from our training sessions.
* As the site owner I want to, provide clear contact details and where to find us.

### Devolpment Planes

Whilst planning the website the site owner will use the five development planes as a staple to accommodate to the user goals that are written above. These planes will be used to meet user demands and expectancies.

#### Strategy 

The website will be targeted at the following audience:

* New dog owners.
* Experienced dog owners.
* Dog owners training for competitions.
* People interested in dog training.
* People with dogs of any age.
* People with dogs of any breed.

The website needs to enable the user to:

* Navigate the site with ease.
* Easily find information about the company.
* Easily find contact information.
* Easily find the booking page.
* Have a clear understanding of the booking process.

The website needs to enable the site owner to:

* Easily gather information about customers through the booking form.
* Provide clear information about the company.
* Provide clear contact details.
* Provide clear location details.

#### Scope

While developing the scope plane we decide what requirements our website will need in regards to the user needs defined in the strategy plane and user stories.

The required content of the website will need to include the following:

* Information about the business.
* Information on the classes they offer.
* Information on the trainers.
* Pictures of the training being undertaken.
* Contact information.
* The address.
* A live google map with the exact location.
* A booking page with a form to submit.
* A guide to the booking process.

The required functions of the website will need to include the following:

* A fully responsive website made with a mobile first approach.
* A responsive nav bar which will change dependant on screen size for accessibility ease on different screen sizes.
* A booking form.
* A page for after the form is completed with a 'back to home' button for easy navigation.
* An iframe of google maps.

#### Structure 

While developing the structure plane i decided that the best way to present this information would be in a hierarchical tree structure. This is because i feel it is a easy to navigate structure that is commonly found and the user will be used to using throughout other websites.

#### Skeleton

While developing the skeleton plane i created wireframes using [Balsamiq](https://balsamiq.com/).

I created the wireframes with a mobile first approach and designed wireframes for mobile, tablet, and desktop to ensure that the site will be fully responsive upon completion.

#### Design

##### Colour Palette

I decided on my colour palette using [Coolers](https://coolors.co/). I started off by finding a nice vibrant orange and then used the palette generator to find the other colours that complemented the orange. 

I chose for my colour scheme to be the main orange and to have greens as my secondary colour. I chose the vibrant orange because it conveys a friendly and positive emotion.

I wanted to choose greens as my other colours because I feel it relates very well to the theme of the website and dog training. This Is because people automatically have an image of dogs training in a field and I wanted to portray the idea of the green grass into the webpage.

I chose a vibrant green to further convey a friendly and positive emotion. I opted for a darker green also to break up the bright colours when using this to cover other elements on the page.

I also chose a sea-salt white for the base colour of the page and a rich black for the font colour.

I used [WebAIM](https://webaim.org/resources/contrastchecker/) to check the contrast of all my font colours against the background for accesability.

<details>
<summary>Colour Palette</summary>

![Colour Palette](assets/readme-files/colour-palette.png)

</details>

##### Fonts 

The fonts used throughout the website are BioRhyme and Montserrat. I imported these fonts by using [Google Fonts](https://fonts.google.com/). BioRhyme is used for all heading elements throughout the page. I chose this font because I felt like it portrayed a fun and playful emotion which suits the image the company is trying to perceive.

I found the font pairing of Montserrat through an article on [Designerly](https://designerly.com/best-font-pairings/#:~:text=BioRhyme%20works%20best%20for%20headings,Montserrat%2C%20Crimson%20Text%20and%20Eczar.). I used a backup font of Sans-Serif incase there was a problem loading the other fonts.

##### Imagery

The imagery used was all sourced from [Pexels](https://www.pexels.com/). I used Pexels because I found they had a good range of dog training photos and also a lot of photos using the same trainers. This helped me to use different pictures of the same people and help to create a realistic feel to the website even though the company is of course fictional.

The images were then resized using [BeFunky](https://www.befunky.com/) which is an online image editor. I then compressed the images further using [TinyPNG](https://tinypng.com/).

### Features 

#### Design Features 

##### General

Each page on the site has some general features that remain consistant throughout. These are:

* The header is located at the top of every page. I made this the full width of the page and I also made it static. This is so the user always has the logo at the top of page. The user also always has either the the navigation bar or hamburger menu always available for easy navigation. The logo also acts as a link back to the home page when clicked on and the cursor changes to a pointer when hovered over to portray this.

* The navigation bar is also static and fully responsive. On screen sizes above 992px the browser will display a navigation bar with all the different pages of the side on the screen for easy navigation. The current page the user is on has an active class on it to change to dark green so the user knows where on the site they currently are. The navigation links have a pseudo class rule applied to them and the background and font change colours when hovered over but are different colours than the active class so as to avoid confusion for the user.

* The hamburger menu is also responsive and is only displayed on screen sizes less that 992px. This is because there are a lot of links in the navigation bar so this is broken down into a clickable menu that will display the navigation links when it is pressed. This is to avoid having the screen feel too cluttered on smaller screens. The current page the user is on has an active class on it to change to underline the text so the user knows where on the site they currently are.

* The footer is located at the bottom of each page and contains links to our social media pages. Because this is a fiction website each icon just takes you to the home page of the site and this opens in a new window. The footer is the full width of the screen to match the width of the header and maintain a similar feel throughout the site. It is not static because with the header already being static i didnt want too much of the screen to be taken up by having two static elements. The footer icons have a pseudo class rule applied to them and change colours when hovered over.

##### Home

The home page features a large hero image covering the full width of the screen at the top underneath the header. The top section of the page features a page title, a quotation box and a paragraph explaining a bit about our company.

At the bottom of the page we have three images of dogs that are clickable links to different pages on the site. I used an overlay on the images to further increase accessibility with the contrast of the font. Each of these has a hover pseudo class applied so when you hover over the text it turns orange and the cursor turns into a pointer. Being a responsive website I have displayed these in a column on smaller screen sizes and in a row on larger screens.
