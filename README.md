# Purpose of the project
This project is to show case my apilities and the progression of my performance in building a personal website for an online digital journalist. It is also the first part of the CodeInstitute Milestone projects.

### user stories
 As a visiting user, I would like to contact the owner for business enquiries


# UX Design

## Wireframes

 The initial design of the website was set by using figma to look like this
 https://www.figma.com/proto/YeFJCf1jd1hRs31LjMqynH/Portfolio-sample1?node-id=31%3A221&scaling=scale-down&page-id=0%3A1&starting-point-node-id=31%3A221 as one page with differnt sections.

 But while designing, I made the Hero image with the name/title with a link button as Home page and the rest of the content in another -About me page-. I deleted the contact footer and I made it as an indpended page with a form to be completed and a send button when clicked it will take you into a Thank you page. The header is fixed at the top that means it stcks at the top even if the user scrolls down and it contains links for pages with a logo at the top left.  
 The footer is simple it has the four icons to the social networks.


 - **Desktop Wireframe using Miro:**
    ![Desktop view](https://github.com/Jawahir01/MilestoneProject/blob/master/assets/img/miro-desktop.png)

 - **Tablet Wireframe using Miro:**
    ![Tablet view](https://github.com/Jawahir01/MilestoneProject/blob/master/assets/img/miro-tablet.png)

 - **Mobile Wireframe using Miro:**
    ![Mobile view](https://github.com/Jawahir01/MilestoneProject/blob/master/assets/img/miro-phone.png)


## Features

 **Header**


**Footer**


**Main Page**


**About Page**


**Contact Page**


**Thank You Page**



### Future Features
adding live chat.



# Typography and color scheme

### Colour Scheme
 The two main colours used are black for the background and white for the text or viceresa. Also the lime greencolor is added throughout the website whether for the span or as background hover links and buttons and the fontawesome icon in the Thank you page to give more liveliness to the site.

### Typography
The Oswald, Roboto and Exo font are the main fonts used throughout the whole website with Sans Serif as the fallback font in case for any reason the font isn't being imported into the site correctly.
 



# Technology
 - ### Languages Used
    + HTML5
    + CSS3

 - ### Frameworks, Libraries & Programs Used
    - **Bootstrap 5.2.3:**
    Bootstrap was used to assist with the responsiveness and styling of the website.

    - **Google Fonts:**
    Google fonts were linked into the html files throughout the project.

    - **Font Awesome 6.2.1:**
    Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.

    - **GitHub:**
    GitHub is used to store the projects code after being pushed from Git.

    - **Print 3D:**
    Paint 3D was used to resizing images and editing photos for the website.

    - **Canvas**
    canvas was udes to create the logo.

    - **Miro:**
    Miro was used to create the wireframes during the design process.


# testing

### code validation
- **HTML**
    1. The index file was validated by [HTML Validator](https://validator.w3.org/) and no errors or warning found. 
    !()[]

    2. The experince file was validated by [HTML Validator](https://validator.w3.org/) and no errors or warning found.
    !()[]

    3. The contact file was validated by [HTML Validator](https://validator.w3.org/) no errors were found but a warning about the Unicode Private Use Area I used when placing the fontawesome icon folowed by (;). After searching in [Stack Overflow: Answer by Mike Smith](https://stackoverflow.com/questions/23978976/fontawesome-usage-displeases-w3c-validator/31703251#31703251) and reading the articles https://www.w3.org/TR/charmod/#C073 and https://hsivonen.fi/charmod-checking/ , I undrestood the issues that these are documented/standardized linting rules but also, if I've checked the file in different browsers and it’s working fine, I can safely ignore this warning.
    !()[]

    4. The thank you file was validated by [HTML Validator](https://validator.w3.org/)and no errors or warning found. 
    !()[]

- **CSS**
    the style sheet was validated by using [CSS validater](https://jigsaw.w3.org/css-validator/)
    !()[]
    
### Test Cases

- The footer was annoying. It kepting sticking on top of the header. I gave it the margin-top:100% so that it can go down it worked but it add a more size to the whole page. The mistake was that I was using percintage rather than a px or rem mersuermints. It worked well when the  margin-bottom: 10px; and margin-top: 20px;

- 

- The hero image was not responsive 

I had to change the size from cover to contain 

- The button under the hero image was not responsive though I gave it the justify-content-center class and it was floating to the left so I had to change its display to flex and give it the approbrite margin top and bottom.

- the box inside

**Lighthouse**

when ckecking through lighthouse for mobile devices, I got these results
![]()
The accessibilty score was 78 so, to solve the issue for users who rely on screen readers I added _aria-label="button"_ to all button elements 

### Known bugs
1. 




# Further Testing


# Deployment
- via VS code
- via github pages



# credits

### Content
1. All the content is a resume sample.
 Source: https://www.bestsampleresume.com/sample-communication-resume/digital-journalist-resume.html
    **Note** I changed the name of the candidate to Mathew Allen.

2. The header code is edited using the nav and the navbar sections from https://www.w3schools.com/bootstrap5/

2. The Hero image code is edited using 

3. The icons in the website were from [Font Awesome](https://fontawesome.com)

4. The idea of the span in the Hero text, bttuons and the contact form are from 
    https://bootstrapmade.com/photofolio-bootstrap-photography-website-template

5. The testimonial code is edited using the Quotes Slideshow section and the Testimonials section from https://www.w3schools.com/howto/howto_js_quotes_slideshow.asp 

6. In the Contact page, the icons inside palceholder is from [Stackoverflow](https://stackoverflow.com/questions/19350291/use-font-awesome-icon-in-placeholder). The member @huckbit _Mar 29, 2016 at 14:43_-_ shared his method [code ](https://codepen.io/huckbit/pen/rezezb?editors=1100#0)(https://fontawesome.com/v4/cheatsheet/).
I used the rest of the FontAwesome hex-code icons from (https://fontawesome.com/v4/cheatsheet/)


### Media
1. I edited the design of the logo from [Canva](https://www.canva.com/logos)

2. The photo used in the home page _Hero image_ is from https://www.dreamstime.com/

3. The phtos in the testimonial section are _fake people_ http://www.google.com I searched for random face generator.


### Acknowledgements
1. My supervisor at City of Bristol College _Pasquale Fasulo_.
2. My Mentor Guidance at Code Institute _Rohit Sharma_.
3. Tutors at Code Institute for their assistance _Rebbeca_ and _Ted_


