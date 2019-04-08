# Photographer’s  Website 

[View website in GitHub Pages]( https://github.com/debapriya9b/Milestoneproject-photographer-website)

Stream One Project: User-Centric Frontend Development - Code Institute

This is a website for a photographer based in Athlone, Ireland.Website features a gallery of the photographer’s work, a about me page to know her little 
personally, a photo gallery displaying the pieces of her work recognized by different  magazines and  a contact me page for the interested customers to 
connect with the photographer personally for photo shoot.In the contact me page the Package details are also mentioned fot the customer's reference.
The website is the foreground of her business , it’s the first point of contact for fans or customers.

The business goals of this website are:
* Build brand awareness.
* Provide high quality examples of the photographer’s work.
* Drive sales in the form of first contact (via the contact page) that will then lead to a sales call with the photographer.
* Excellent UX to keep potential clients on site long enough to fill out the contact form.

## UX

##### The ideal client for this business is:

* Any product owner/companies for their product photo shoot
* Families/individuals to capture their special days like birthday/marriage/engagement etc
* Parents for baby photo shoot/maternity photo shoot
* Magazines for travel photos/animal photos/abstract photos
* Interior decorators  


My goal in the design was to make it as easy as possible to access information on the site while striving for a minimalist design. This website is:

* Easy to navigate.
* Steps the client through easy to understand learnable information.
* Gives the client the information they need without overloading them.
* Guiding them to the goal of the website - to fill out the contact form.



##### User  stories

* Itu,33 years, interior decorator : “I want a single website where I can get different categories of photography be it wild life, landscape ,portrait etc …so that it is easier to choose photos based on my clients' interest.
* Lisa,25 years, business-woman : “I want an easy to fill in contact form, so I can make contact with the photographer for my family photo shoot.”
* As an interested client: “I want to know what past clients thought of her work before fixing an appointment with the photographer."
* As an interested observer and/or potential client: “I want to follow the photographer on social media, so I can keep up with her latest news.”
* Bela,55 years: ”I want to easily navigate the site, so I can find what I need efficiently.”
* Akash,36 years,Magazine owner : "Its very helpful if you get all kinds of photo under one roof (read as under one website).Then I can get pictires for my magazine articles easily"


##### Wireframe mockups:

* [Home](wireframes/Home-page.jpg)
* [About](wireframes/About-page.jpg)
* [Clients](wireframes/Clients-Page.jpg)
* [Contact](wireframes/Contact-page.jpg)
* [Portfolio](wireframes/Portfolio-Page.jpg)



## Features
Each page has a responsive navbar with a LOGO "Priya B".Logo is connected to home page,so whenever,from any page navigator 
can come back to home page easily by just one click to LOGO

Each page has a footer with a copyright information and social media icons linking to all the photographer's social media pages. 

##### Home

Home page is featuring some photographer’s work as a slide show, fixed-top, responsive navigation bar .
A quotation of an famous photographer can be seen under the slide show images.


##### About

The About page features one picture of the photographer herself with her son to keep it simple and connected with the customers
The about page also includes some brief but compelling copy about the photographer.
*Enough information to satisfy curiosity without overwhelming the user*.

At the bottom of the page (above the footer) are, the link has been provided so that the interested customer can directly go to contact page to connect with the photographer.


##### Portfolio

In the portfolio page the photographer have showcased her photographs. Each photo has a hover effect and if anyone wants a full screen image, it can be obtained in a new page with a single click on the photograph.
The Gallery page is laid out in **columns of thumbnail images**, 6 columns wide for mobile devices, 4 columns wide for tablets and 3 columns wide for desktop. 


##### Clients

In the Clients page, photographer showcased the photos which have got the recognition in different magazines in different time period.


##### Contact

The Contact page features a **contact form**, which requests client name and email, subject and below that a box to leave a message. 
The bottom of the form contains a **Send Button**

Below the contact form, all the photoshoot packages are displayed for the customer's reference.


### Existing Features

* Header Logo - Exists on [every page](../index.html) and allows all users to easily recognize the business brand. Clicking the logo returns users to the home page as they would expect.
* Header Navigation Bar - Exists on [every page](../index.html) and allows all users to easily navigate all the website's pages and find what they are looking for quickly.
* Footer Copyright Info - Exists on [every page](../index.html) and protects business copyright.
* Footer Social Icons - Exist on [every page](../index.html) and allows all users to access the social platforms that the photographer uses.
* [About Page](about.html) - Allows potential clients to connect with the photographer  without overloading them with information.Interested users can directly go to the contact page to connect with the photographer through a provided link.
* [Portfolio Page](portfolio.html) - Allows all visitors to the website to view thumbnail images of the photographer’s  work. Each thumbnail can be clicked to open an individual fancybox viewer.
* [Clients Page](clients.html) - Allows potential clients to see the previous works of the photographer which has been recognised by Leading magazines.
* [Contact Form](contact.html) - Allows potential clients to ask questions, and/or make the first step in their ordering process.
* [Contact Form](contact.html) - Allows potential clients to check the package details for photoshoot before connecting to the photographer.

### Features to implement in future

* Customers can download image with customized width and height ratio as per their interest
* Contact form Send button change from *Send* to *Processing* and then when complete changes to *Sent*. - Javascript Needed
* FAQ page, table with FAQs and dropdown buttons to view answers - Gives potential clients easy to find answers to their common questions. - Javascript  Needed for dropdown functionality. Simple FAQ page could be implemented now.
* Photographer's blog - Allows new potential clients to discover the website through articles written by the photographer establishing her as a thought leader.
* Images can be organized by the categories.
* Instead of mentioning one quotation in the home page,there can be "quotation of the day" dispaly where the quotation will change after a predefined intervals


## Technologies Used

* This project uses HTML and CSS programming languages.
* [Cloud9](https://c9.io) - This developer used **Cloud9** for their IDE while building the website.
* [BootstrapCDN](https://www.bootstrapcdn.com/)
    - The project uses **Bootstrap4** to simplify the structure of the website and make the website responsive easily.
    - The project also uses BootstrapCDN to provide icons from [FontAwesome](https://www.bootstrapcdn.com/fontawesome/)
* [Google Fonts](https://fonts.google.com/)
    - The project uses **Google fonts** to style the website fonts.
* [jQuery](https://jquery.com/)
    - The project uses **jQuery** to reference Javascript needed for the responsive navbar and Fancybox gallery modal.
* [Popper.js](https://popper.js.org/)
    - The project uses **Popper,js** reference Javascript needed for the responsive navbar.


## Testing

If you try to submit the contact form with an invalid email address, there will be an error noting the invalid email address. Furthermore, 
the 'required' attribute is added to the 'name,' 'email,' ‘subject’ and 'message' fields, so if those fields are not filled in, the form will not submit. 
If all field are valid, the page will reload. If a customer is interested in contacting me, they will have to fill out all fields in order for the form 
to go through : Tested

All images in portfolio page will open in a new tab using 'target="_blank"':Tested

All links have been manually tested to ensure that they are pointing to the correct destination

Clicking the logo returns users to the home page from any page:Tested

All social media icons are linked to the respective social media pages of the photographer : Tested

The responsiveness of the website has been tested for Desktop, iPad, iPhones,Galaxy S5 : Tested

## Deployment

This project was developed and stored in git using [Cloud9](https://c9.io)

The project was regularly pushed to [GitHub](https://github.com) repository [https://github.com/debapriya9b/Milestoneproject-photographer-website]
and published to [GitHub pages](https://pages.github.com/) using the GitHub settings.
[https://debapriya9b.github.io/Milestoneproject-photographer-website/]

There are no differences between the deployed version and the development version.


## Credits

### Content

All content in the "About Me” section in this portfolio site were written by me.Pckage details has been taken from 
https://www.google.com/url?sa=i&source=images&cd=&cad=rja&uact=8&ved=2ahUKEwjrr5HxtMDhAhWTShUIHbX3B8EQjRx6BAgBEAU&url=https%3A%2F%2Fwww.template.net%2Fbusiness%2Fexcel%2Fprice-list-template%2F&psig=AOvVaw1lGVX1k3ExszP8QeZl0xrO&ust=1554810012242543

### Media

All photos are taken from https://www.pexels.com/ and https://pixabay.com/  .Both are stock image libraries, with the exception of the photo of myself in the About Me page.

### Code

-Code reference has been taken from:

          -https://www.w3schools.com/

          -https://stackoverflow.com/
          
          -https://getbootstrap.com/docs/4.3/getting-started/introduction/

### Acknowledgements

-I received inspiration for this project from https://www.wix.com/website/templates/html/photography

#### Disclaimer

The content of this Website is for educational purposes only.


