# **Purpose of the project**
Freelance digital journalist and writer Mathew Aleen introduces his online portfolio with a professional photograph of himself and links to different sections of his website. Based in London, Allen has also lived and worked in San Francisco. The portfolio features his best and most recent work experience, as well as some of the agencies he has written for. 

![The_website](/docs/site.png)

## Site Owner's goals
-   Help clients understand more about Mathew's career and his areas of focus as a journalist.
-   Help Mathew effectively present his skills and experience to news agencies.
-   Help recruiters and people who are interested in Mathew's work to reach easily.
  
## External User's goals
Whether I am a visiting user or an interested recruiter, I want to:
- Easily find out about Who is Mathew Allen and What does he do.
- Navigate smoothly to Mathew's previous experiences in journalism and his main skills.
- See what other friends or co-workers may would say about Mathew's professional work.
- Be able to Contact Mathew for further questions or any enquiries.


# **UX Design**

## Wireframes

 - **Desktop Wireframe using Miro:**
    ![Desktop view](https://github.com/../../docs/miro-desktop.png)

 - **Tablet Wireframe using Miro:**
    ![Tablet view](https://github.com/Jawahir01/../../../docs/miro-tablet.png)

 - **Mobile Wireframe using Miro:**
    ![Mobile view](https://github.com/Jawahir01/../../../docs/miro-phone.png)


## Features

 - **Header**
 
    The header at the top of each page contains Mathew's personal logo for his website and a navigation bar links to his home page, his Experience page and his contact page. The navigation bar can extend or collapse, depending on the screen size.
    
    ![header](/docs/header.png)

- **Footer**
  
    The footer at the bottom of all the pages contains four icons of the social media links for _Mathew_ and it will open in a new tap when clicked.
   
    ![footer](/docs/footer.png)

- **Home Page**

    - It has a big hero photo of Mathew with his name and his title job. Addtionly, a button that takes the user directly to make cantact with Mathew
       
    ![hero_image](/docs/Hero_image.png)


    - It also has a brief introduction about Mathew's professionals
    
    ![About-me](/docs/about.png)

    - Testimonial feature that has a sample of people who new Mathew or worked with to give their expressions and opinions about him. 
    
    ![Testimonial](/docs/testimonies.png)

- **Experience Page**

    It contains both Mathew's Experience roles in two different companies and a summary of his skills as a digital journalist.

    ![Experience-page](/docs/experience.png)

    ![Experience-page](/docs/skills.png)


- **Contact Page**

    It has a form of input fields [name, phone number, email address and a message text area] for a user who would like to contact Mathew. The fields in the form are required to be filled so the user can send his message.
    
    ![contact-page](/docs/contact.png)


- **Thank You Page**

    Once the form has been sent, the user is redirected to this thank you page confirming that the message was sent and the user will be contacted soon by Mathew.

    ![Thankyou-page](/docs/thank%20s.png)



## Future Features
- Additional page for his news reports or articles.
- User should recieve an email after sending a message.



# **Typography and color scheme**

## Colour Scheme
The two main colours used are black(background) and white (text) or vice versa. Also, the lime green color is added throughout the website whether for the span or as background hover links ,also for buttons and the fontawesome icon in the Thank you page to give more liveliness to the site.

## Typography
The Roboto font was used in the portfolio for the headings and the buttons. The Oswald was used for the sections' titles, except for the name in the home page the font was Cardo. The Exo font was used for the paragraphs and with Sans Serif as the fallback font in case for any reason the fonts aren't being imported into the site correctly.
 
# **Technology**
 - ## Languages Used
    + HTML5
    + CSS3

 - ## Frameworks, Libraries & Programs Used
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
    canvas was used to create the logo.

    - **Miro:**
    Miro was used to create the wireframes during the design process.

# **Testing**

## Code Validation
- **HTML**
    1. The index file was validated by [HTML Validator](https://validator.w3.org/) and no errors or warning were found. 
    ![Home pasge](/docs/html%20validat.png)

    2. The experience file was validated by [HTML Validator](https://validator.w3.org/) and no errors or warning were found.
    ![Experience page](/docs/html%20validat.png)

    3. The contact file was validated by [HTML Validator](https://validator.w3.org/) no errors were found but a warning about the Unicode Private Use Area I used when placing the fontawesome icon folowed by (;). After searching in [Stack Overflow: Answer by Mike Smith](https://stackoverflow.com/questions/23978976/fontawesome-usage-displeases-w3c-validator/31703251#31703251) and reading the articles https://www.w3.org/TR/charmod/#C073 and https://hsivonen.fi/charmod-checking/ , I undrestood the issues that these are documented/standardized linting rules but also, if I've checked the file in different browsers and it’s working fine, I can safely ignore this warning.
    ![Contact page](docs/cont_validat.png)

    4. The thank you file was validated by [HTML Validator](https://validator.w3.org/) and no errors or warning were found. 
    ![Thank you page](/docs/html%20validat.png)

- **CSS**

    The style sheet was validated by using [CSS validater](https://jigsaw.w3.org/css-validator/)
    ![stylesheet](/docs/css%20validate.png)
    
## **User Story**

As a visiting user:
1. If I would like to gain more information e.g. testimonials of Mathew Allen as journalist, The home page provides a clear photograph of Mathew with a short introduction about him and samples of friends and co-workers testimonies.
2. If I would like to contact Mathew for business enquiries, then i should look for the contact page which is easily to be navigated whether from the header in each page or from the available for hire button in the home page and once clicking, the I can fill my information and send my message.
3. If I would like to understand the professional experience of the site owner, The Experience page have a detailed information about his work experience with different companies and his major skills as a journalist.

  

## **Test Cases**

| Action                             |  Expectation  | Result |
| -------------                      | :-----------: | -----: |
|   On clicking the link of the website.    |    The user should land on the homepage. He should notice a header with a logo at the top left and a navbar of three text links [Home, Experience and Contact] at the top right.  | It is working well as expected.|
| Hovering over the logo. |The logo should appear to be a link. Once it is clicked, the user should be taken to the homepage. In this case. the page should refresh as the user is still on the same page.| It is working well as expected. |
|Hovering over the Home link.        | The user should notice the same header, but the text link is highlighted with grey color indicating that now the user is in the home page.    | It is working well as expected. |
|Scrolling down the home page.            |A big photograph of the site owner should appear with two big text of his name and his role in the middle of the photo. And a clickable button [Available for hire] underneath it.               |  It is working well as expected. |
| Hovering over the Available for hire button.  | The user should notice the button is now little bit darkened and once it is clicked, the user should be redirected to the contact page. | It is working well as expected.|
|Scrolling down the homepage.            | the user should see a box of half-white background color with a title [About me] and a short paragraph about the site’s owner.|  It is working well as expected. |
|Scrolling down the homepage. | the user should see a testimonial section of the title [ What they say ] and underneath it a rectangular box contains a small, rounded photo on the left and a short quote next to. There are also two arrows at the left and the right. |  It is working well as expected. |
| Hovering over the arrows inside the testimonial box  | The user should notice the arrow is highlighted with background color and when whenever it is clicked the user should see another testimony for different person up to six people.             | It is working well as expected. |
|Scrolling down the home page.          | The user should see a footer section. With four icons of links Facebook, Twitter, Instagram and LinkedIn          | It is working well as expected. |
|Hovering over each icon in the footer Section.|The user should notice the icon is highlighted with bright color and once clicked the user will be taken to each of the icon’s website in a new tab. | It is working well as expected. |
| Hovering over the Experience text Link in the header. | The user should notice the text link will be highlighted with bright color. Once it is clicked, the user will be taken to the Experience page. then, the link text will be highlighted with grey color indicating that now the user is in the Experience page with the same header at the top and the same footer at the bottom.| It is working well as expected.
Scrolling down the Experience page. | The user should see a big box of darkened background picture with a title of my [WORK EXPERIENCE] and lists of paragraphs. | It is working well as expected. 
| Scrolling down the Experience page. |  The user should see another big box of a grey background colour with a title of [Summary of My Skills] and list of paragraphs.  | It is working well as expected.
|Hovering over the Contact link in the header.    | The user should notice the text link will be highlighted with bright color and once it is clicked, the user will be taken to the contact page. Then, the link text will be highlighted with grey colour indicating that now the user is in the contact page with the same header at the top and the same footer at the bottom.               | It is working well as expected. |
| scrolling down the contact page.           | The user should see a heading text of [contact me!] and a form of four input fields. The user will see the text [Your name] with user icon in the first field, the text [Your phone number] for phone number with phone icon in the second field, the text [Your Email] for an email address with an envelope icon in the third field and a text [You Message] for a message text with chat icon for the fourth field. These texts with the icons will disappear when the user starts to fill each field. The user will see also [send Message] button underneath the form.                  | It is working well as expected. |
| Hovering over the send me message button.  | The user should notice the button is now little bit darkened and once it is clicked, a note will appear for the name input that it must be filled first by the user. Again, if the user clicked the button another note for the phone input that it has to be filled. Same as for the email address field and the message field. This indicates that the form should be completed before clicking the send button. When the form is filled the user can click the.           | It is working well as expected. |
|After clicking the send message button  |  The user will be redirected to Thank you page where he should see first the same header and footer. The user also will see in the middle of the page a box with off-white background color. It contains a heading [Thank You], down the heading is big, rounded check icon. There is also a sentence for the user that his message had been sent and the site owner will contact him soon.  |It is working well as expected. |
 
 ---

## Fixed Bugs
- ### **Using Chrome Devtool:**
    - The div Hero image was not big and only centred in the middle of the page, making the name/title and down box to overlap. To fix it, I was noticed that I did not wrap the hero image div and the name/title div around their div container  and I mistakenly closed the div container before that. Then I added `display: contents;` to the div .hero-container so that the image can fill the whole width of the container. 
  
    ![exp-box: before](/docs/hero%20image.png)
    - For mobile device the texts in both the experience box and the skills box in the Experience page used to overlap. To fix the problem I changed the div height style from height to min-height.
  
    ![exp-box: before](/docs/exp-box.png)

    - The button under the hero image was floating to the left so I had to delete the __justify_content_center__ and then give it the approbrite margin top and bottom.
  
    ![button: before](/docs/button.png)

- ### **Using Lighthouse**
    When ckecking through lighthouse for desktop and mobile devices I got these results
    ![Desktop: before](/docs/1.png)

    ![Mobile: before](/docs/3.png)

    The accessibilty score was 89 and 78 so, to solve the issue for users who rely on screen readers I added _aria-label="button"_ to all button elements, _aria-label="Link to"_ to all link elements and for the text elements to have sufficient color contrast against the background I darkend the background for the buttons from  #159765 to #0f5b3e5f.

    ![Desktop: before](/docs/2.png)

    ![Mobile: before](/docs/4.png)

## **Unknown Bugs**
No bugs were found.


# **Deployment**
- ### **Via VS Code**
- ### **Via github pages:**

    To deploy the page via github pges follow these steps:
    1. On GitHub, navigate to the repository ***
    2. Under your repository name click **Settings**.
    3. In the "Code and automation" section of the sidebar, click  Pages.
    4. Under "Build and deployment", under "Source", select Deploy from a branch.
    5. Under "Build and deployment", under "Branch", use the None or Branch drop-down menu and select a publishing source.
    6. The live link of the website will appeare on the Github Pages section.

**The live link** https://jawahir01.github.io/personal_site/


# **Credits**

## Content
1. All the content is a resume sample.
 Source: https://www.bestsampleresume.com/sample-communication-resume/digital-journalist-resume.html

    _**Note:**_  I changed the name of the candidate to Mathew Allen.

2. The header code is edited using the nav and the navbar sections from https://www.w3schools.com/bootstrap5/

3. The Hero image code is edited using responsive images section from https://www.w3schools.com/bootstrap5/

4. The icons in the website were from [Font Awesome](https://fontawesome.com)

5. The idea of the span in the Hero text, bttuons and the contact form are from 
    https://bootstrapmade.com/photofolio-bootstrap-photography-website-template

6. The testimonial code is edited using the Quotes Slideshow section and the Testimonials section from https://www.w3schools.com/howto/howto_js_quotes_slideshow.asp 

7. In the Contact page, the code of the icons inside the palceholder is from [Stackoverflow](https://stackoverflow.com/questions/19350291/use-font-awesome-icon-in-placeholder). The member @huckbit _Mar 29, 2016 at 14:43_ shared his method in this [code](https://codepen.io/huckbit/pen/rezezb?editors=1100#0), then I used the rest of the FontAwesome hex-code icons from https://fontawesome.com/v4/cheatsheet/


## Media
1. I edited the design of the logo from [Canva](https://www.canva.com/logos)

2. The photograph used in the home page _Hero image_ is from https://www.dreamstime.com/

3. The photos in the testimonial section are _fake people_ from [google](http://www.google.com). I searched for _random face generator_.


## Acknowledgements
1. My supervisor at City of Bristol College _Pasquale Fasulo_.
2. My Mentor Guidance at Code Institute _Rohit Sharma_.
3. Tutors and community members at Code Institute.