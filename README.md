# On A Plate Catering website

## Milestone Project 1 Overview

This first milestone project will result in the creation of a static responsive front end website that will meet the business needs of On A Plate Catering and their target audiences needs.  
On A Plate Catering is a fictional business that wants to provide excellent food service by delivery of delicious cooked, crowd pleasing dishes.

On A Plate Catering's website is aimed at those looking for food service for events such as weddings, home events (birthday) and coorporate events such as a conference.
The webiste will be a platform to allow the business to advertise and to provide sufficent information to attract new customers. The aim of the website is to allow interested customers to understand the busiesses service and contact the business if they would like to use this service.

## Table of Contents

[Live Website](https://jojo157.github.io/milestoneProject1/)
![](assets/images/websiteImages.png)

## UX

### Goals

#### User Goals

- To view the menu offered
- To organize a corporate spread/package
- To contact the company to book a tasting or find out more information
- To find out what type of events are catered for
- To view images of food provided
- To get a quote for catering an event

#### Site owners goal

- To secure customers business for food service – general and corporate
- To increase orders & attract new clients
- To spread awareness of brand
- To increase social following

### User Stories

#### An engaged couple

- I would like to be able to view a menu of food to see if I like the offering for my wedding.
- I would like to be able to request a quote for a set number of people and know whats included in quote.
- I would like to see reviews from other customers who used service.

#### A business owner

- I would like to be able to view a menu of food to see if I like the offering for a business event.
- I would like to be able to request a quote for a set number of people.
- I would like to see reviews from other customers who used service.
- I would like to know if the catering service can provide a regular service such as canteen food (soups, sandwichs, pastries) or just set number events

#### An event organiser

- I would like to be able to view a menu of food
- I would like to contact to see if a special dish can be made for my event, (i.e can you customize the menu).
- I would like to be able to request a quote.
- I would like to see reviews from other customers who used service.
- I would like to see a gallery of offerings such as cakes etc and again if customize.

#### On A Plate Catering owner

- I want to attract my target audience and ask them sufficent information to offer a quote.
- I want to obtain new coorporate clients for repeat event catering.
- I want to see if there is an appetitie for lunch offerings for coorporate clients.
- I want to increase my brand awareness and social following.
- I want to speak to customers who view my website and may be interested in service. (potetial for IM facility in future)
- I would like to offer ability to secure booking with deposit post recieving a quote.

### Wireframes

Wireframes for this project were created using Balsamiq and can be viewed at below link.

Link to [Wireframe](/assets/wireframes/onAPlateCateringWireframes.pdf)

## Features


### Existing Features

On A Plate Catering website consists of 4 different pages that are responsive at all screen sizes. 
Some of the features contained on the website are:

- Navigation bar - assists users to easily move through the relevant pages with a layout that is intuitive, such as the hamburger icon naviagtion on smaller devices.
- Call To Action Button - The request a quote button is distributed on pages that would encourage an interested party to initiate contact for a quote.
- Request a quote feature - allows all users to contact the company to get a quote for catering a specific event. It helps the comapny by obtaining sufficent infomration to prepare a quote.
- What we offer section Feature - This section gives a potetial customer a very short description of our catering offering.
- Menu Section Feature - This section allows users to browse through a sample menu by courses. The colour layout of different courses makes it easy to distinguish them.
- Testimonials Feature - This section allows users to read reviews from previous customers and help inform their decision.
- Contact Section - This feature gives the contact details, such as address and contact number for On A Plate Catering with a google map of the address. 
- Footer - This section allows users to find out more about the company through its social pages using well recognised icons.


### Features Left to Implement

- Instant messaging service - An IM service would help to obtain more customers by proactively making the first contact.
- Payment Platform - The ability to secure booking with deposit post recieving a quote. 
- A business lunch offering - This feature would provide informatino on packages that could be provided when the business expands into drop off luches to businesses without a canteen.


## Technologies Used

- Frameworks and Libraries
  - [Bootstrap5](https://getbootstrap.com/) was used for the navigation feature as it has a brillant responsive navbar component and button compents. 
  - [Font Awesome](https://fontawesome.com/) was used for the navbar hamburger icon and the social icons used in the Footer. 
  - [Google Fonts](https://fontawesome.com/)  was used to import the font used for the website.           


- Wireframes
  - [Balsamiq](https://balsamiq.com/) was used to create a mock up of the website after exploring the strategy and scope planes of user exerperience for this project.

- Version Control
  - [Git](git-scm.com) was used as a version control system
  - [Github](GitHubgithub.com) was used for repository hosting
  - [Gitpod](gitpod.io) was used as the developer platform

- Other
  -  [Google Map Iframe](https://www.embedgooglemap.net/) was used to create an embed Google Map on the contact page
  -  [Hatchful](https://hatchful.shopify.com/) was used to create the company logo
  -  [Image Color Picker](https://imagecolorpicker.com/) was used to get the hex colour from an image for a background
  -  [Coolors](https://coolors.co/gradient-palette/) was used to create a gradient palette
  -  [Pexels](www.pexels.com) was used to source free stock photos
  -  [Pixabay](https://pixabay.com/) was used to source free stock photos
  -  [W3C Markup]() was used to validate markup code
  -  [W3C CSS Validator](https://jigsaw.w3.org/css-validator/validator) was used to validate CSS code
  -  [W3C Html Checker](https://validator.w3.org/nu) was used to validate HTML code
  -  [Pic Resize](https://picresize.com/) was used to resize images used on the website to improve the website performance
  -  [Ligthhouse](https://github.com/GoogleChrome/lighthouse) was used to audit my website and the results of the audit were used to improve the website performance etc. 




## Testing

### Code Validation

Html pages were validated with [W3C Html Checker](https://validator.w3.org/nu) . Several errors were discovered that have since been fixed. The errors were:

- Error 1 - Element button must not not appear as a descendant of the a element. 
    - This error was fixed by re-reviewing the Bootstrap documentation and puttinh the button class on the a element to give the same output as before.
- Error 2 - iframe element gave error that attributes are obsolute and to use css instead. These attributes were margin height, margin width and frameboard scrolling. 
    - I removed these attributes from the html code and put styling for the iframe in style.css instead.
- Error 3 - The value of the for attribute of the label elemet must be the ID of a non-hidden form control.
    - I had forgot the ID attribute for this form element. I added the ID for the relevant form element. 

Css pages were validated with [W3C CSS Validator](https://jigsaw.w3.org/css-validator/validator) . 2 errors were discovered.

- Error 1 - property overscoll-behaviour doesn't exist.
    - I looked online and verified that the property does exist according to [MDN web docs](https://developer.mozilla.org/en-US/docs/Web/CSS/overscroll-behavior). 
- Error 2 - value error: font-weigth 1000 is not a font weigth value.
    - I had previously looked up the maximum for this value and misinterpreted the answer to mean it was 1000. I changed this to 900 the maximum. 

After fixing the errors I re-ran all HTML and CSS files through the validators and only error present is the overscoll-behaviour error that I can ignore.

### Performance Testing
Performance was tested using Lighthouse, one of google web developers tools. 

#### Home Page
The first time I ran the audit on the home page, the performace was low as per image below.

![](assets/images/homepage-performance-1.png)

The results were not unexpected as I had noticed that the page took several seconds to load. The outputs of the audit highlighted that the website image files were too large and causing performance issues.
I used [Pic Resize](https://picresize.com/) to reduce the image size without sacrificing quality. I then reran the report and was happy that the performance was improved greatly across all pages and I could see this when i reloaded the page.

![](assets/images/homepage-performance-2.png)

#### Menu Page

![](assets/images/menu-performance.png)

#### Quote Page

![](assets/images/quote-performance.png)

#### Contact Page

![](assets/images/contact-performance.png)

The performance was slower on this page as the map is an iframe and is know to be slower because there is an additional overhead for the browser. A future improvement would be to use Javascript to replace the iframe.

According to Lighthouse using the a element with links to another page can pose security and performance risks. To improve my website I followed their advise and added the rel="noopener" property to all of the target="_blank" links. This improved the best practices score across all pages from 86 to 93.

![](assets/images/best-practices.png)

### User Stories Testing

From the user stories listed earlier the aims On a Plate Catering intends to meet currently can be summarised as:
- I would like to be able to view a menu of food 
- I would like to be able to request a quote
- I would like to see reviews from other customers who used service
- I would like to contact the company for more queries
- I want to increase my brand awareness and social following

From Testing the aims are meet as follows:
- I would like to be able to view a menu of food 
    - The navigation bar clearly shows a user where the menu is 
    - A call to action is shown on the home page with a button in the what we offer section leading the person to the menu
- I would like to be able to request a quote
    - A call to action button is present on the landing page and is the first thing a user sees 
    - On the menu page again a call to action button is present guiding the user to the quote page
    - The request a quote option is in the navigation bar
- I would like to see reviews from other customers who used service
    - Testimonials are present on the landing page and are styled to grab the readers attention
- I would like to contact the company for more queries
    - Contact section is shown in the navigation bar
- I want to increase my brand awareness and social following
    - The footer on all pages has links to the social pages as is standard practice for websites and the user would know to navigate here.

### Functionality Testing

I tested the functionality of the site on a laptop first. 
- I clicked on each menu option in the navigation bar and the desired page loaded as expected. 
- I confirmed that the current page is underlined in the navigation bar for each page.
- I checked that the company logo on each page links back to the home page.
- I clicked on the 2 buttons on the home page and the correct pages were navigated to.
- I clicked the button on the menu page and the correct page loaded. 
- I click on the social icons in the footer on each page and verified that the desired social website opens in a new page.
- On the contact page, I checked that the embedded map zoom function works and that when you click view larger map, it opens in a new page on google maps. 
- On the get a quote page, I checked each input to ensure I could enter data and for the drop down list that it works as expected. I pressed the submit button to check it acts as expected. When I build on my coding skills I would have a message appear when press submit. 

The testing was then conducted on a mobile and the above steps were repeated including testing the toggle of the menu, toogle open and close worked on all pages as expected. 

### Validation Testing

The get a quote form was tested for validation
- I tested each input by leaving one blank at a time and checking the correct validation message is given. This worked for all cells except the drop down input. 
    - I then updated the code with required property for this field and retested all cells. The name, email, phone number and catering occasssion all act as expected and are required. The additional text field is not required.

### Compatibility Testing

#### Different devices
Using Google Developer tools, I viewed the website on the following devices:
- Galaxy S5
- Pixel 2
- Pixel 2 XL
- iPhone 5/6/7/8 & Plus
- iPhone X
- iPad & iPad Pro
- Surface duo 
- Galaxy fold

Based on the results I decided to alter media query in styles.css to only change from mobile design to laptop for screen width of greater than 770px as the surface Duo and iPad had sections that looked squashed.


#### Different Browsers

I tested the website on:
- Google Chrome 
- Safari 
- Firefox
- Microsoft Edge
- Internet explorer 

Differences discovered across browsers: 
- The contact page form placeholder text inside fields is not centered on safari as styled. On Chrome, Firefox, Edge the placeholder text is centered.
- The property overscroll-behaviour is not compatible with safari or Internet explorer. This was expected as documented by [MDN web docs](https://developer.mozilla.org/en-US/docs/Web/CSS/overscroll-behavior).
- If autofill a form field it changes the colour of the cell, the cell colour varies depending on the browser.

#### Different Operating Systems
The above testing was conducted on operating systems:
- Windows 10
- MacOS Big Sur 11.1
- iOS 14.3

On the contact page , tested on Internet explorer with windows 8.1 [Lamda Test](https://app.lambdatest.com/) the address and map do not sit as intended. They were positioned beside each other with no spacing.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.

## Credits

### Content

- The text for the menu was copied from [Old Barn Catering](https://oldbarncatering.com/)

### Media

- The photos used in this site were obtained from ...

### Acknowledgements

- I received inspiration for this project from my wife who would like to set up a catering business in the future.
