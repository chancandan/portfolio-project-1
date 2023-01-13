# VISIT MACAU - Overview

Visit Macau is a travel website providing information to users on the S.A.R. region of China - Macau. Information on featured or top attractions to visit and see in Macau. A gallery of images on the website sparks wonder and awe in visitors to the website in the hope they add Macau to their bucket list of places to travel to. The live website can be viewed [here](https://chancandan.github.io/portfolio-project-1/index.html)

![Mockup](docs/readme_images/visit_macau_mockup.JPG)


## Features 

### Navigation
* Navigation Menu
    * Contains links to the Home, Gallery and Contact US pages and will be responsive on all devices.
    * This will allow users to easily navigate between the pages within the site on any size device. 
![Navigation Bar](docs/readme_images/naivgation_bar.JPG)
    * Design changes to a hamburger menu for mobile users on a smaller screen. 
    * Once clicked by the user it will displays the 3 different link options in a verical column.

![Hamburger Column](docs/readme_images/hamburger_column.JPG) 

* Footer
    * This will contain icons as links to social media websites that will open in new tabs. Icons will be accessible to the visually impaired who may be using a screen reader, by the use of aria labels.
    * These various social media links will allow the user to follow Visit Macau's social channels where they can get more up to date information where available and interact with other users or fans of the site.

![Footer](docs/readme_images/footer.JPG)
* 404 Page
    * An error 404 page will be implemented and will display if a user navigates to a broken link.
    * Here, the 404 page will allow the user to a choice to report the broken link or problem by linking back to the contact page or if the user simply wants to contuining browsing on the site they have the option to easily navigate back to the homepage without having to think about using the browsers back button. The option to stay on the site will be offered in an easy manner.

![404](docs/readme_images/404_image.JPG)
* Favicon
    * An image of Macau's famous white lotus flower will be implemented site wide as a favicon.
    * For users who have a lot of tabs open in their browser this will make locating the Visit Macau page much easier and will help to make it stand out against some sites which don't include this feature.

![Favicon](docs/readme_images/visit_macau_favicon.JPG)


### Home / Landing Page
* Home page hero image
    * One image of Macau's skyline including the famous Grand Lisboa building will be used as the hero image. It will have a zoom transition.  
    * This image is an at-night shot and the lights of the building will set the tone and convey to the user immediately that Macau is very well known for it's nightlife and will put this association in the user's mind.

![Home Page Hero Image](docs/readme_images/website_homepage_hero.JPG)

* Featured Attractions
    * A pick of 4 of the top featured tourist tractions in Macau. Useful information to the user in where to go and what to see.
    * This section also protrays to the user what the website is all about, if they haven't already grasped it at this stage.
    * The implementation of icons above featured attraction from the 'Font Awesome' website. Each icon is related to their attraction underneath and immediately gives the user a clue as to what each attraction is without having to read the text included.
    * Carefully selected images of each attraction that markets an emotion in the user, e.g. the blue sky in the St Paul's ruins image.

![Attractions](docs/readme_images/featured_attractions.JPG)

* Section breaker
    * The use of a <hr> element with a section symbol to break the featured attractions section from the next section of the informational videos.

![Section breaker](docs/readme_images/hr_section_break.JPG)

* Why Choose Macau?
    * The implementation of embedded Youtube videos via the use of iframes to market Macau as a destination to visit and to give the user a better understanding of what kind of a place Macau is with the images they'll see in the videos.

![Embedded Videos](docs/readme_images/why_choose_macau.JPG)

### Gallery Page
* Gallery
    * Once navigating to the gallery page the user can view different images of Macau on their screens which have interactive effects once the user hover their cursor over them on desktop.
    * Each image is of a high quality and carefully selected to market6 Macau to the user ina  positive light. The gallery is responsive and it will allow the user to view the content in an eye-catching way on any device. 

![Gallery](docs/readme_images/gallery.JPG)

### Contact Us Page
* Contact us form
    * A contact  form will be implemented to allow users to contact the site. The form will consist of the following fields and attributes: 
        * First Name (required, type=text)
        * Last Name (required, type=text)
        * Email (required, type=email)
        * Radio (required, type=radio)
        * Message (required, type=textarea)
    * Having successfully filled out all required fields and clicking the submit button on the contact form, a 'Thank You' message will appear as the user will be navigated to a thank-you.html page that will resemble the contact us page.
    * This form will allow the user to contact Visit Macau if they have any further questions or require any more information. 

![Contact Form](docs/readme_images/contact_us_form.JPG)

![Thank You Message](docs/readme_images/thank_you.JPG)

### Existing Features

* Responsive design
* 4 featured attractions
* Interactive google map
* Hero image with zoom transition
* Contact form and thank you / success page
* 2 videos for users to interact with via playback functions
* Responsive gallery with zoom and opacitiy transitions on hovering



### Features Left to Implement

* Hotels information section

* I'd also like for my contact form to actually submit the information to the domain or to a point of data collection. 



## Design

### Wireframes
<br>
Landing / Home page
<br><br>

![Home Page large screen](docs/readme_images/first_homepage_wireframe.png)

![Home Page small screen](docs/readme_images/home_mobile_wireframe.png)
<br>
Gallery page
<br><br>

![Gallery page large screen](docs/readme_images/gallery_large_screen_wireframe.png)

![Gallery page tablet screen](docs/readme_images/gallery_tablet_wireframe.png)

![Gallery page small screen](docs/readme_images/home_mobile_wireframe.png)
<br><br>
Contact US form successful submission thank you page.
<br><br>
![Contact Us form submission thank you success](docs/readme_images/contact_us_wireframe.png)

![Contact form submission success](docs/readme_images/contact_mobile_wireframe.JPG)


## Technologies

* HTML5
    * The structure of the Website was developed using HTML5 as the main language.
* CSS3
    * The Website was styled using custom CSS3 in an external file.
* GitHub
    * Source code is hosted on GitHub and delpoyed using Git Pages.
* Git 
    * Used to commit and push code during the development opf the Website
* Font Awesome
    * Icons obtained from https://fontawesome.com/ were used as the Social media links in the footer section and also for the icons above the featured attractions section on the main page. 
* Tinyjpg
    * https://tinyjpg.com/ was used to reduce the size of the images used throughout the website
* Favicon.io
    * favicon files were created at https://favicon.io/favicon-converter/ 
* Balsamiq
    * wireframes were created using balsamiq from https://balsamiq.com/wireframes

    ## Testing 

### Responsiveness

All pages were tested to ensure responsiveness on screen sizes from 320px and upwards as defined in [WCAG 2.1 Reflow criteria for responsive design](https://www.w3.org/WAI/WCAG21/Understanding/reflow.html) on Chrome, Edge, Firefox and Opera browsers.

Steps to test:

1. Open browser and navigate to [Visit Macau](https://chancandan.github.io/portfolio-project-1/index.html)
2. Open the developer tools (right click and inspect)
3. Set to responsive and decrease width to 320px
4. Set the zoom to 50%
5. Click and drag the responsive window to maximum width

Expected:

Website is responsive on all screen sizes and no images are pixelated or stretched.
No horizontal scroll is present.
No elements overlap.

Actual:

Website behaved as expected on all browsers.

Website was also opened on the following devices and no responsive issues were present seen:

- HP Laptop 15 -bs1xx
- Lenovo Chromebook
- iPhone SE
- iPhone X
- iPhone 14 Pro Max
- iPad (6th Generation)
- MacBook Air

### Accessibility

### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org)

![Contact HTML Validator Results](docs/testing/contact_validator.JPG)

![Avdentures HTML Validator Results](docs/testing/adventures_validator.JPG)

![Home HTML Validator Results](docs/testing/home_validator.JPG)

![Gallery HTML Validator Results](docs/testing/gallery_validator.JPG)

![404 HTML Validator Results](docs/testing/404_validator.JPG)

- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org)

![CSS Validator Results](docs/testing/css_validator.JPG)

### Bugs

Bugs were found along the way and correct, as well as countless errors which were fixed. All were a learning curve and helped better my understanding of both HTML5, CSS3 and how they interact with each other. One such example was my absence of headings in my structure. I learned the key importance of headings and that they play a key role in the structure of HTML5. The below example was easily fixed by including a h2 element inside of my section. Fix image also shown beneath.
![Empty heading bug](docs/readme_images/empty_heading_bug.JPG)<br>

![Heading bug fix](docs/readme_images//heading_bug_fix.JPG)

### Unfixed Bugs
Responsiveness of the website worked on all devices, screen sizes and orientation with the exception of landscape orientation on mozilla firefox. I was unable to resolve this bug on time but will address in a future release.

## Deployment
