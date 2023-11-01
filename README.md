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

* The header is located at the top of every page. I made this the full width of the page and I also made it static. This is so the user always has the logo at the top of page. The user also always has either the the navigation bar or hamburger menu always available for easy navigation. The logo also acts as a link back to the home page when clicked on and the cursor changes to a pointer when hovered over to portray this. I have added a slight border shadow underneath the header to make it slightly pop out from the main content and to emphasise that is is a static element.

<details>
<summary>Header</summary>

![Header](assets/readme-files/header.png)

</details>

* The navigation bar is also static and fully responsive. On screen sizes above 992px the browser will display a navigation bar with all the different pages of the side on the screen for easy navigation. The current page the user is on has an active class on it to change to dark green so the user knows where on the site they currently are. The navigation links have a pseudo class rule applied to them and the background changes to light green and the font changes to black when hovered over. I made them different colours than the active class so as to avoid confusion for the user.

<details>
<summary>Navigation Bar</summary>

![Navigation Bar](assets/readme-files/nav-bar.png)

</details>

* The hamburger menu is also responsive and is only displayed on screen sizes less that 992px. This is because there are a lot of links in the navigation bar so this is broken down into a clickable menu that will display the navigation links when it is pressed. This is to avoid having the screen feel too cluttered on smaller screens. The current page the user is on has an active class on it to change to underline the text so the user knows where on the site they currently are.

<details>
<summary>Hamburger Menu</summary>

![Hamburger Menu](assets/readme-files/hamburger.png)

</details>

* The footer is located at the bottom of each page and contains links to our social media pages. Because this is a fiction website each icon just takes you to the home page of the site and this opens in a new window. The footer is the full width of the screen to match the width of the header and maintain a similar feel throughout the site. It is not static because with the header already being static i didnt want too much of the screen to be taken up by having two static elements. The footer icons have a pseudo class rule applied to them and change colours when hovered over.

<details>
<summary>Footer</summary>

![Footer](assets/readme-files/footer.png)

</details>

* I created a border-shadow class that is used throughout many elements across the website. This is because I wanted to make a consistent style that will create a sense of familiarity throughout the many elements across the site. The border-shadow class consists of two rules, one being border-radius and the other box-shadow.

<details>
<summary>Border Shadow Class</summary>

![Border Shadow Class](assets/readme-files/border-shadow.png)

</details>

* All pages feature a large hero image covering the full width of the screen underneath the header. This hero image is fully responsive and uses a responsive unit of measurement to size it and also repositioning of the image through media queries as the box size increases. On all pages except the home page I have placed the title of this page in the centre of the hero image with an orange background on the heading to increase contrast and accessibility. I have applied my border-shadow class to the heading box to make it pop out a bit and emphasise that it is on top of the image and not a part of it.

<details>
<summary>Hero Image</summary>

![Hero Image](assets/readme-files/hero-screenshot.png)

</details>

##### Home

The top section of the page features a page title, a slogan, a quotation box and a paragraph explaining a bit about our company. All of these use a responsive unit of measurement to increase in size as the screen does and font sizes are adjusted through media queries where necessary.

At the bottom of the page we have three images of dogs that are clickable links to different pages on the site. I used an overlay on the images to further increase accessibility with the contrast of the font. Each of these has a hover pseudo class applied so when you hover over the text it turns orange and the cursor turns into a pointer. Being a responsive website I have displayed these in a column on smaller screen sizes and in a row on larger screens. I did this by using a flex-box and changing the direction through a media query.

<details>
<summary>Mobile Home Page</summary>

![Mobile Home Section One](assets/readme-files/mobile-home1.png)

![Mobile Home Section Two](assets/readme-files/mobile-home2.png)

</details>
<details>
<summary>Desktop Home Page</summary>

![Desktop Home Section One](assets/readme-files/desktop-home1.png)

![Desktop Home Section Two](assets/readme-files/desktop-home2.png)

</details>

##### About

The first section of this page is the trainers section. This consists of a heading styled with a green box and border shadow, and introductions for each of our three trainers. I have presented this with an image of the trainer placed above a text box for each of them. I have styled the text box orange with my border-shadow class added to it.

The second section of the page is the benefits section. This consists of a heading styled with a green background and border shadow, and also four sections detailing the benefits of training your dog with Pawfect Pups. Each of the four sections consists of an image of a dog to the left and a text box styled orange with my border-shadow class added to it.

With this page being fully responsive the trainers section is aligned as a column on small screens, and aligned in a row on larger screens. This was done by changing the flex direction with a media query. With the benefits sections being horizontally orientated I displayed in a column on all screen sizes so as to not appear cluttered on larger screen sizes. I did make sure to increase the box size and font size as the the screen size increases through media queries or responsive units of measurement.

<details>
<summary>Mobile About Page</summary>

![Mobile About Section One](assets/readme-files/mobile-about1.png)

![Mobile About Section Two](assets/readme-files/mobile-about2.png)

![Mobile About Section Three](assets/readme-files/mobile-about3.png)

</details>
<details>
<summary>Desktop About Page</summary>

![Desktop About Section One](assets/readme-files/desktop-about1.png)

![Desktop About Section Two](assets/readme-files/desktop-about2.png)

</details>

##### Classes

This page consists of four boxes with each of these boxes representing a different class the company offers. Each box is styled with an orange background with border radius applied to the edges. Each box contains an image of a dog and a green text box styled with my box-shadow class. These elements are arranged in the box through flex-box. 

The page is fully responsive and the boxes are displayed in a column on smaller screen sizes and are displayed in two rows of two on larger screen sizes. I did this through the use of a flex box. All of the elements are responsive through the use of media queries or responsive units of measurement.

<details>
<summary>Mobile Classes Page</summary>

![Mobile Classes Page](assets/readme-files/mobile-classes.png)

</details>
<details>
<summary>Desktop Classes Page</summary>

![Desktop Classes Page](assets/readme-files/desktop-classes.png)

</details>


##### Booking 

This page consists of a form and an aside element containing a guide to how the booking process works. The form contains a variety of inputs and has four checkboxes styled in css. The are styled dark green to contrast the orange background of the form. The each have a hover pseudo class applied to them to change colour as you hover over them and the cursor will change to a pointer. They also change colour when they have been checked. At the bottom of the form there is a submit and reset button. 

The aside element contains a heading followed by the three steps of the booking process. Each of these steps contains a large icon displayed above a description. The steps is displayed in a column through use of a flex box. 

This page is fully responsive and contains the aside element underneath the form on smaller screens and displays it at the side of the form on larger screens through use of media queries and flex. All of the elements are responsive through use of media queries or responsive units of measurement.

<details>
<summary>Mobile Booking Page</summary>

![Mobile Booking Page One](assets/readme-files/mobile-booking1.png)

![Mobile Booking Page Two](assets/readme-files/mobile-booking2.png)

</details>
<details>
<summary>Desktop Booking Page</summary>

![Desktop Booking Section One](assets/readme-files/desktop-booking.png)

</details>

##### Completed Form 

This page is the page you are directed to after completed the form. It is very simplistic and features a section explaining what happens next that consists of a heading and a paragraph. Underneath that is a link that has been styled in a similar way to the other links using CSS that takes you back to the home page. Although the navigation bar is always there I added this feature in to further increase navigation for the user. I have added a hover class to this link so it changes colour when hovered over and also the cursor will change to a pointer. 

This page is fully responsive through the use of media queries to increase the font size and adjust the margin.

<details>
<summary>Mobile Completed Form Page</summary>

![Mobile Completed Form Page](assets/readme-files/mobile-completed.png)

</details>
<details>
<summary>Desktop Completed Form Page</summary>

![Desktop Completed Form Page](assets/readme-files/desktop-completed.png)

</details>

##### Contact 

The page consists of two sections, an information section and a map section. The Information section consists of two boxes. One containing the contact information and the other containing the business opening times. Both these boxes are styled orange and have my border-shadow class applied to them. 

The map section consists of a heading that has a green background and a fully interactive google map underneath it. The google map is added using an iframe element and an embedded code. 

This page is fully responsive and displays the information box in a column on smaller screens and in a row on larger screens through the use of media queries and flex direction. Each of these boxes use a responsive unit of measurement until they reach a maximum size. The map is also responsive and uses responsive units of measurements until that also reaches a maximum size.

<details>
<summary>Mobile Contact Page</summary>

![Mobile Contact Page One](assets/readme-files/mobile-contact1.png)

![Mobile Contact Page Two](assets/readme-files/mobile-contact2.png)

</details>
<details>
<summary>Desktop Contact Page</summary>

![Desktop Contact Section One](assets/readme-files/desktop-contact1.png)

![Desktop Contact Section Two](assets/readme-files/desktop-contact2.png)

</details>

##### Features To Be Added in The Future

If this were a real company, the features I would add to the website in the future would be:

* A review page where users can leave reviews and also read other users review.
* A gallery page to display pictures.
* A 404 page for wrong addresses typed into the address bar.

### Bugs and Issues

* I encountered an issue mainly with my hero images and their positioning when testing on mobile screens that are horizontal. This is because the media query I had entered for tablets (above 768px) was now taking effect on them but with the screen height being so small they did not look correct. I fixed this by adding a new media query setting a maximum height to be targeted and hence only effecting mobile screens when turned to the side.

* When creating the about page I encountered a bug where the text was an appropriate size but was overflowing from the box in was supposed to be contained in. I fixed this issue by changing the height from inherit to a pixel unit instead.

* I encountered issues with screen sizes between 340px-360px on my map section heading and elements on my contact page. On the map section heading the text flowed onto two lines making the green background box have a lot of spare space and unappealing to the user. And my heading, list and table elements in the two information boxes were not displaying correctly with the font size set. This was fixed by creating a media queries and targeting the elements between this size.

* Another issue encountered was accidentally targeting my footer icons. When I was creating my contact page I set the font size of the icons in the how to guide fairly large. This then targeted my footer icons also. This is because when I was targeting the footer icons previously, I just targeted all 'i' elements. I then did the same when targeting my 'i' elements in my how to guide. I fixed this by changing the DOM selector in the how to guide to only 'i' elements that were children of the div containing the how to guide.

### Technologies

####