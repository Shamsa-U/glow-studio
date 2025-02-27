# Glow Studio Website - Shamsa Uwase

![Am I responsive](/readme-images/am-i-responsive.png "Am I responsive check") 

Glow Studio is a modern nail salon dedicated to providing high-quality nail care and artistry. Our website is aimed to appeal to both new and returning clients, showcasing our services, latest designs, and special offers. It also provides an easy and seamless booking experience. The site is fully responsive, ensuring a smooth and visually appealing experience on any device.

The website features 3 pages and has been built using HTML, CSS and Bootstrap.

### Live Project 
[View Glow Studio project here.](https://shamsa-u.github.io/glow-studio/index.html "View Glow Studio's Live Website")

___

# Table of Contents:
[1. User Experience (UX)](#ux)
  - [1.1 User Stories](#user-stories)
  - [1.2 External Users' Goals](#external-users)
  -	[1.3 Site Owners goals](#owner-goals)
  -	[1.4 Features to include](#features)

      
[2. Design Choices](#design)
  - [2.1 Colour Palette](#colour)
  - [2.2 Typography](#typography)
  - [2.3 Images](#images)

[3. Site Structure](#structure)
  - [3.1 Wireframes](#wireframes)
  - [3.2 Home Page](#home)
  - [3.3 Gallery Page](#gallery)
  - [3.4 Booking Page](#booking)

 
[4. Features](#sitefeatures)
  - [4.1 Navigation Bar](#nav)
  - [4.2 Hero Images](#hero)
  - [4.3 Form](#form)
  - [4.4 Footer](#footer)
  - [4.5 Future Features](#future)

[5. Technologies Used](#tech)

[6. Testing](#testing)
  - [6.1 Chrome DevTools](#devtools)
  - [6.2 Manual Testing](#manual)  
  - [6.3 W3C HTML](#w3chtml)
  - [6.4 W3C CSS](#w3ccss)
  - [6.5 Lighthouse](#lighthouse)
  - [6.6 Peer review](#peer-review)
  - [6.7 Contrast Checker](#contrast)

[7. Bugs & Fixes](#bugs)

[8. Deployment](#deployment)

[9. Credits](#credit)
  - [9.1 Code](#code)
  - [9.2 Images](#image-credit)
  - [9.3 Content](#content)
  - [9.4 Acknowledgements](#acknowledge)

___

<a name="ux"></a>

# 1. User Experience (UX)

<a name="user-stories"></a>

## 1.1 User Stories

<a name="external-users"></a>

### 1.2 External Users’ Goals:

The site users are potential clients and returning customers who are interested in nail care treatments offered at Glow Studio. 

- External users may want to explore the services provided, such as manicures, pedicures and nail art options.
- External users may want to view previous designs to see if they are interested in the designs offered.
- External users may want to know the studio’s location, opening hours, and pricing. 
- External users may want to easily request to book an appointment online or contact the studio via the contact information provided. 

<a name="owner-goals"></a>

### 1.3 Site Owner’s Goals:

Glow Studio is focused on attracting new clients while retaining existing customers by showcasing services and expertise.

- The studio wants to highlight client transformations.
- The site should provide a seamless booking system for appointments.
- The studio wants to engage with a wider audience through social media integration.
- The site owner requires an easy-to-use contact form for inquiries and bookings.

<a name="features"></a>

### 1.4 Features to Include:

- A gallery showcasing client results and potential services.
- Detailed descriptions of services offered and pricing.
- Clear contact information, location details, and business hours. 
- A simple and effective booking system for appointments. 
- Links to social media for engagement.

___ 
<a name="design"></a>

# 2. Design Choices

<a name="colour"></a>

## 2.1 Colour Palette

![Color palette 1](/readme-images/2%20color%20palette.png "Color palette")
![Color palette 2](/readme-images/color%20palette.png "Color palette 2")

A simple colour scheme has been used. The dark brown colours bring out the muted pink tones throughout the website.

I used ![Coolors](https://coolors.co/) to decide on the colour scheme.
The font colour and background colour for the header and body were checked for contrast on [Deque Contrast Checker](https://color-contrast-checker.deque.com/) and scored ’12.81 - Super' showing the contrast makes the accessibility good. The contrast was checked for the footer and was scored 12.81 - Super’.

## 2.2 Typography

- The __Poetsen One__ font is used for the Glow Studio logo at the top of the site and for headings. Sans-serif is the fallback font in case the title font does not load correctly. __Poetsen One__ adds elegance and sophistication to the logo, reflecting the studio's commitment to beauty and radiance.
- The _Akaya Kanadaka_ and _Overlock_font is used for all other body text. It is a clean and easily legible font.

<a name="typography"></a>

## 2.3 Images

- I used Font Awesome icons for the social media information and contact information to give the user visual clues.
___
<a name="structure"></a>

# 3. Site Structure

The website has a Home page and two other pages. The initial wireframes for these can be found below.

<a name="wireframes"></a>

## 3.1 Wireframes

### 3.1.1 Landing Page

![Landing page wireframe](/readme-images/home-wireframe.png "Landing page wireframe")

### 3.1.2 Gallery Page

![Gallery page wireframe](/readme-images/gallery-wireframe.png "Gallery page wireframe")

### 3.1.3 Booking Page

![Booking page wireframe](/readme-images/booking-wireframe.png "Booking page wireframe")

___
<a name="home"></a>

# 3.2 Home page and Our Services section

The homepage (index.html) is a straightforward landing page featuring a welcome message integrated into the hero image. Below that is the 'Our Services' (index.html#services) section where there are three cards that act as previews to the site’s services, the 'view gallery' button below this provides seamless navigation.

![Home page visual top](/readme-images/homepage-top.png "Home page visual top")

![Home page visual 'Our Services' section](/readme-images/homepage-ourservices.png "Home page visual 'Our Services' section")

![Home page visual bottom](/readme-images/homepage-bottom.png "Home page visual bottom")

<a name="gallery"></a>

## 3.2 Gallery page

![Galley page visual top](/readme-images/gallery-top.png "Home page visual top")

![Gallery page visual mid](/readme-images/gallery-mid.png "Gallery page visual mid")

![Gallery page visual bottom](/readme-images/gallery-bottom.png "Gallery page visual bottom")

The gallery page (gallery.html) provides clear information about services provided, manicures and pedicures as well as a carousel of nail art designs for simple viewing. Each service is provided with a price to ensure that uses are fully informed.

<a name="booking"></a>

## 3.3 Booking page

![Booking page visual top](/readme-images/booking-top.png "Booking page visual top")

![Booking page visual mid](/readme-images/booking-mid.png "Booking page visual mid")

![Booking page visual bottom](/readme-images/booking-bottom.png "Booking page visual bottom")

The Booking page provides a simple form to request users information in order for them to request to book an appointment. The booking form was set to method POST which sends the information to the code institute form dump. If this site were to go live this would be updated to redirect to a thank you HTML page instead.

___
<a name="sitefeatures"></a>

# 4. Features

<a name="nav"></a>

## 4.1 Navigation Bar  

All pages can be accessed through the navbar, enabling users to navigate the site effortlessly without having to return to the homepage. On desktop, the navbar is displayed as a horizontal list, while on mobile, it switches to a vertical drop-down menu. The navbar is not sticky, allowing users to view more content as they scroll down the page.

![Nav bar visual](/readme-images/nav-bar-ss.png "Nav bar visual")

![Nav bar mobile visual](/readme-images/drop-nav.png "Nav bar mobile visual")

<a name="hero"></a>

## 4.2 Hero Images  

The home page features a hero image across the top to create a welcoming view. The form has a background image instead with a semi-transparent overlay to maintain the branding.    
* All images were compressed to allow faster loading using [TinyPNG](https://tinypng.com/) 
* Credit for all images can be found in the Credit section below.

<a name="form"></a>

## 4.3 Form  
The booking page features a simple form that users can complete to send booking requests to Glow Studio. The fields are all set to be required and the large text area features placeholder text.

<a name="footer"></a>

## 4.4 Footer  
The footer element links to social media channels and shows the location,the phone number and email address for ease of contact.

<a name="future"></a>

## 4.5 Future Features

- If this site was to be published i would make a Thankyou.html that redirects users to a page thanking them for their interest and an aim to get back message to reassure users that their form has been accepted.
- I will research using NextGen formats for images in future as this gave me a low performance score.
- It was suggested in Peer Review that I make the service cards more responsive (clicking image to pop up a more detailed description) rather than just a zoom effect. This is something I will consider for the future.

___
<a name="tech"></a>

# 5. Technologies Used

- HTML - used for structuring and presenting information on the website.
- CSS - used for styling the HTML code.
- Bootstrap v5.3.3 - used to improve the responsiveness of the site for access on different size devices.
- Balsamiq - Balsamiq was used to create wireframes for the project.
- Font Awesome: The project uses icons from Font Awesome version 6.
- Chrome DevTools: This featured heavily as I tested the site throughout to adjust sizing and spacing.
- Google Fonts: The fonts used have been imported from Google Fonts.

___
<a name="testing"></a>

# 6. Testing
The Glow Studio website has been tested using the following methods:

<a name="devtools"></a>

### 6.1 Chrome Developer Tools  
* I utilized the Developer Tools to assist with debugging throughout the project, allowing me to inspect my pages and make necessary adjustments.

<a name="manual"></a>

## 6.2 Manual Testing  
The following aspects were tested manually as I worked through the project. I reviewed each element using the Live Server in Gitpod to ensure that everything functioned as expected.

The following elements were manually tested:

### Navigation bar

|TEST                  | DESIRED OUTCOME                      | PASS / FAIL  |
| -------------------- | --------------------------------     | ------------ |
| Home page | When 'Home' hyperlink clicked, the browser directs me to index.html. The hover effect (underline) appears when mouse is over hyperlink.    | PASS |
| Our Services section | When 'Our Services' hyperlink clicked, the browser directs me to index.html#servcies. The hover effect (underline) appears when mouse is over hyperlink.     | PASS |
| Gallery Page | When 'Gallery' hyperlink clicked, the browser directs me to gallery.html. The hover effect (underline) appears when mouse is over hyperlink.     | PASS |
| Booking Page | When 'Booking' hyperlink clicked, the browser directs me to booking.html. The hover effect (underline) appears when mouse is over hyperlink.     | PASS |
| All pages | All pages responsive using DevTools to resize the screen size for mobile to desktop.     | PASS |
| Background Colour | The background colour does not distract from the text.     | PASS |
| Text Colour | The text colour significantly contrasts to the background colour to allow good accessibility.     | PASS |
| Font-style | The logo font displays as Special Elite and the menu links font appears as Roboto.     | PASS |


### Footer

|TEST                  | DESIRED OUTCOME                      | PASS / FAIL  |
| -------------------- | --------------------------------     | ------------ |
| Background Colour | The background colour does not distract from the text.    | PASS |
| Text Colour | The text colour contrasts to the background colour to allow good readability.     | PASS |
| Font-style | The heading font displays as Poesten One, the sub-heading font displays as Akaya Kanadaka and the paragraph font appears as Overlock.     | PASS |
| Icons | The Font Awesome icons display as the expected size and colour.     | PASS |
| Social Media Icons | The Font Awesome icons link to the correct social media pages.     | PASS |


### Home Page

|TEST                  | DESIRED OUTCOME                      | PASS / FAIL  |
| -------------------- | --------------------------------     | ------------ |
| Text Colour | The text colour contrasts to the background colour to allow good accessibility.     | PASS |
| Font-style | The heading font displays as Poesten One, the sub-heading font displays as Akaya Kanadaka and the paragraph font appears as Overlock.     | PASS |
| Hero Image | The image covers the width of the screen and is the specified height. The image is responsive and resizes for different devices.     | PASS |
| Welcome message | The text is centered on the screen.     | PASS |

### Gallery Page

|TEST                  | DESIRED OUTCOME                      | PASS / FAIL  |
| -------------------- | --------------------------------     | ------------ |
| Text Colour | The text colour contrasts to the background colour to allow good accessibility.     | PASS |
| Font-style | The heading font displays as Poesten One, the sub-heading font displays as Akaya Kanadaka and the paragraph font appears as Overlock.     | PASS |
| Image carousel | Image carousel is on autoplay once it is in sight.      | PASS |

### Booking Page

|TEST                  | DESIRED OUTCOME                      | PASS / FAIL  |
| -------------------- | --------------------------------     | ------------ |
| Text Colour | The text colour contrasts to the background colour to allow good accessibility.     | PASS |
| Background image | The background image covers the container.     | PASS |
| Form | The form is centered. The background area is transparent. The font can be easily read on the background. The placeholder text is displayed. The submit button directs the form to the code institute form dump. All fields are required.  | PASS |
| Google Map | Map shows the correct area and resizes on different devices.      | PASS |
___
## Code Validation

<a name="w3chtml"></a>

### 6.3 W3C HTML Validator
The HTML code for all pages was tested using the W3C Validator through direct input and successfully validated without issues.

![w3c Home page](/readme-images/index-html-checker.png "W3C Validator screenshot Home page")

![w3c Gallery page ](/readme-images/gallery-html-checker.png "W3C Validator screenshot gallery page")

![w3c Booking page](/readme-images/booking-html-checker.png "W3C Validator screenshot booking page")

<a name="w3ccss"></a>

### 6.4 W3C CSS Validator  
The CSS code was tested using Jigsaw W3C CSS Validator. It was validated by direct input and passed all checks.

![css](/readme-images/css-checker.png "CSS Validator screenshot")

<a name="lighthouse"></a>

### 6.5 Lighthouse - Desktop  
I used the Lighthouse reports in Google DevTools to examine the desktop pages of the website for:  
* Performance  
* Accessibility  
* Best Practices  
* SEO  

index.html
![Lighthouse report for index.html](/readme-images/index-lighthouse.png "Lighthouse report for index.html")

gallery.html
![Lighthouse report for gallery.html](/readme-images/gallery-lighthouse.png "Lighthouse report for gallery.html")

booking.html
![Lighthouse report for booking.html](/readme-images/booking-lighthouse.png "Lighthouse report for booking.html")

### Lighthouse - mobile

I used the Lighthouse reports in Google DevTools to examine the mobile pages of the website for:
* Performance
* Accessibility
* Best Practices
* SEO

index.html
![Lighthouse report for index.html](/readme-images/index-mobile-lighthouse.png "Lighthouse report for index.html")

gallery.html
![Lighthouse report for gallery.html](/readme-images/gallery-mobile-lighthouse.png "Lighthouse report for gallery.html")

booking.html
![Lighthouse report for booking.html](/readme-images/booking-mobile-lighthouse.png "Lighthouse report for booking.html")

#### Further Testing

Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

The website was viewed on a variety of devices such as Desktop, Laptop, iPhone 13 pro, iPhone 14 proMax, iPad air.

<a name="peer-review"></a>

## 6.6 Peer Review  
The project was shared to Slack for peer review and the following changes were made: 
* TBC

<a name="contrast"></a>

### 6.7 Contrast Checker  
The colors used in the site were checked for contrast using [Coolors Contrast Checker](https://coolors.co/contrast-checker/) and results were 'super'.
___
<a name="bugs"></a>

# 7. Bugs & Fixes:

* After running W3C html validator I discovered my button was inside a div with an unclosed element. I fixed this by correcting the adding a closing div.

* During my mentor meeting, my menotr pointed out i should have more pages so i added a gallery page.

* During my mentor meeting, my mentor noticed i did not have my form inputs set to 'required'. I went back and added that in the booking.html code.

* During my mentor meeting, my mentor noticed some unecessary indents in my css code making it look messy. I went back and removed them.

* During my mentor meeting, we realised the images were loading slowly, so I attempted to fix this by reducing the image size and compressing the images using tinypng.com. 

* Largest contentful paint element was making my perfomance report score low on mobile. I changed the size of the h2 element.

___
<a name="deployment"></a>

# 8. Deployment

The project was deployed to GitHub Pages using these steps:

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Main Branch" and press save.
5. A link will be generated for your live site.

___
<a name="credit"></a>

# 9. Credits

<a name="code"></a>

## 9.1 Code

* The initial code for the header, footer and navigation was taken from the Code Institute Love Running and Boardwalk games projects

* Help centring the images on the Landing page circles was found here: https://stackoverflow.com/questions/32477563/how-can-i-fit-images-into-circles-without-stretching

* Hover effects sourced from https://stackoverflow.com/questions/58939609/bootstrap-4-nav-link-hover-effect

* Help creating the grid layout was found from https://getbootstrap.com/docs/4.0/layout/grid/ 

* The stylised social media links in the footer took inspiration from  https://learn.codeinstitute.net/ci_program/diplomainwebappdevelopment

* Help to adjust the height of my rows https://stackoverflow.com/questions/42388989/bootstrap-center-vertical-and-horizontal-alignment 

* TBC

<a name="image-credit"></a>

## 9.2 Images

Most images were sourced from the open source website, pexels.com.
These include:

* TBC

Other images were sourced from:

* TBC

<a name="content"></a>

## 9.3 Content

* All content was written by myself.

<a name="acknowledge"></a>

## 9.4 Acknowledgements

* Thank you to my mentor, Marcel, for continuous helpful feedback.
* Thank you to my friends and colleagues for participating in testing and review.
* Thank you to the tutors and staff at Code Institute for their support. 