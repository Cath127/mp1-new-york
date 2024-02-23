# **THRIFTY NYC Website**
The site has been built using HTML5, CSS3 and Bootstrap for the Milestone 1 project for Code Institute's diploma in Web Development.
![responsive images transparent background](https://github.com/Cath127/mp1-new-york/assets/153606011/f78907c9-a198-4b4b-a5af-6c9a41a483d2)

   [View THRIFTY NYC on Github](https://cath127.github.io/mp1-new-york/)

## CONTENTS
* ### [User Experience](#user-experience)
  * #### [Strategy](#strategy)
    * ####   [User Stories](#user-stories)
  * #### [Scope](#scope)
  * #### [Structure](#structure)
  * #### [Skeleton](#skeleton)
  * #### [Surface](#surface)
* ### [Features](#features)
  * #### [Navigation bar](#navigation-bar)
  * #### [Home Section](#home-section)
  * #### [Gallery](#gallery)
  * #### [Tips Section](#tips-section)
* ### [Future Implementations](#future-implementaions)
* ### [Accessibility](#accessibility)
* ### [Technologies Used](#technologies-used)
  * #### [Languages Used](#languages-used)
  * #### [Frameworks, Libraries and Programs Used](#frameworks-libraries-and-programs-used)
* ### [Deployment & Local Development](#deployment--local-development)
  * #### [Deployment](#deployment)
  * #### [Local Development](#local-deployment)
    * #### [How to Fork](#how-to-fork)
    * #### [How to Clone](#how-to-clone)
* ### [Testing](#testing)
  * #### [Testing User Stories](#testing-user-stories)
  * #### [Validator Testing](#validator-testing)
  * #### [Lighthouse](#lighthouse)
  * #### [Full Testing](#further-testing)
  * #### [Solved Bugs](#solved-bugs)
  * #### [Unsolved Bugs](#unsolved-bugs)
  
* ### [Credits](#credits)
  * #### [Code Used](#code-used)
  * #### [Content](#content)
  * #### [Media](#media)
  * #### [Acknowledgements](#acknowledgements)


## User Experience (UX)
### Strategy
The THRIFTY NYC Website is designed to be responsive and accessible on a range of devices.  It allows visitors to find out more about free and discounted activities in New York.

* ### User Stories  
  * #### First Time Visitor Goals
    a.  As a first time visitor, I want to be able to understand the purpose of the site.     
    b.  As a first time visitor, I want to be able to navigate the site easily to find information.   
    c.  As a first time visitor, I want to look at social media links to find how active they are and what content they produce. 

  * #### Returning Visitor Goals
    a.  As a returning visitor, I want to be able to see tips while planning for/visiting NYC.  
    b.  As a returning visitor, I want to access useful websites while planning for/visiting NYC.   
    c.  As a returning visitor, I want to leave a useful tips for others.

  * #### Frequent Visitor Goals
    a. As a frequent visitor, I want to see what new tips have been added.    
    b. As a frequent visitor, I want to check out new features as the website develops.


### Scope
  The goal for the project was to make an informative, easy to navigate, visually appealing website.

### Stucture
  The website a single scrolling page consisting of three sections: Home, Tips and Gallery.

  * #### Home Page 
    Tells users some introductory information what the website is about and useful links (in the form of Font Awesome Icons) which would be useful when visiting/planning a visit to New York.

  * #### Gallery
    Showing some photographs and information of renowned places in New York.

  * #### Tips
    A section where users would be able to read free or discounted attractions and a form where they would be able to send in their own New York tips.


  As well as the three sections the Thrifty NYC email and social media icons are shown in the footer.

### Stucture

* ### Wireframes

  Wireframes were created using Balsamic.  As it is a scrolling website only one wireframe is needed for each device size.

  ![canva-wireframe](https://github.com/Cath127/mp1-new-york/assets/153606011/b34dea91-1f20-46dd-88e5-00ce463f6065)


### Surface
 
  * #### Colour Scheme
     Here are the official colours of the New York Flag
     ![nyc-flag-colours](https://github.com/Cath127/mp1-new-york/assets/153606011/db1196b1-f018-4f89-86c7-5ae12e14e1c8)
     After putting the colours through(https://webaim.org/resources/contrastchecker/) I had this result
     ![original colour contrast check](https://github.com/Cath127/mp1-new-york/assets/153606011/e5a210dd-3eaf-45a9-8f2b-4c34a332ba1d)
     I decided I still liked the orange and navy contrast but lightened the orange colour 
     ![new contrast checker](https://github.com/Cath127/mp1-new-york/assets/153606011/bfccfb8c-bf36-461a-9fa9-f708245cc6cb)


* #### Typography 
   The two fonts used in the website are Poppins and Lexend Deca.  For the Navbar and heading Poppins has been used with Sans Serif as the fallback font. This is a clear and easy to read font. Lexend Deca is the main font used for the whole website with Sans Serif as the fallback font if Lexend isn't working properly.  Lexend is a dyslexia friendly font which is also beneficial for short-sighted people.

## Features
  The website a single scrolling page consisting of three sections: Home, Tips and Gallery.

  * ### Navigation bar
    * #### 
      The navigation bar is at the top of the website to navigate to the different sections.

    * ####
      A fixed navigation bar has been used for the user to always be able to click on the titles regardless of where they are on the website.  

    * #### 
      On larger screens the title is at the left of the navbar and the navigation links are on the right as HOME | TIPS | GALLERY. On smaller screens the title is on the left and a hamburger button on the right. When expanded the section titles have a font awesome icon and are in the middle of the screen.  When a title is clicked the background turns the orange colour of the website background with a green border around it.

       Desktop Navbar ![navbar desktop -fotor-2024021815482](https://github.com/Cath127/mp1-new-york/assets/153606011/0bf9b1cc-0b51-4433-b877-688339c0dd5e)
    
      Mobile Navbar 

      ![mobile navbar](https://github.com/Cath127/mp1-new-york/assets/153606011/277446c5-7b59-4ab2-9a7a-0cc992dfe13f)

  * ### Home Section
    * ####
      The home section consists of a hero image, an image and introduction text and useful website icons.

    * ####
      The Statue of Libery is used as the hero image.  This is an instantly recognisable monument so users know exactly what the website is about without having to read anything.  The hero text is the same orange colour as the website background. Both are fully responsive.

      ![hero image](https://github.com/Cath127/mp1-new-york/assets/153606011/19bdcf71-806f-4746-8650-304b6bcbc18e)

    * ####
      The top of the home section has an aerial image of New York on the left and two paragraphs of introductory text on the right.  For a better user experience on a mobile device the image is above the text and only one paragraph is visible.  On a medium device
      or larger the image and text sit side by side.
      
      Desktop

      ![intro](https://github.com/Cath127/mp1-new-york/assets/153606011/6f47ff13-b663-4219-8f9d-669e61a36bda)

      
      Mobile

      ![intro mobile](https://github.com/Cath127/mp1-new-york/assets/153606011/bbd83933-d1f2-4206-9024-427af3cf519e)

    * ####
      The bottom part of the home section has four Font Awesome icons which are linked to useful websites which open on a new page.  On a mobile device the icons are in a vertical line, a medium device icons are 2x2 and on large devices are positioned in a horizontal line.


      Desktop


      ![websites desktop](https://github.com/Cath127/mp1-new-york/assets/153606011/cfe0459e-d7c4-47e9-a6d8-45748b645b98)


      Tablet

      ![websites tablet](https://github.com/Cath127/mp1-new-york/assets/153606011/dc949ce5-aca0-40c0-8607-e60d700f367b)


      Mobile

      ![websites mobile](https://github.com/Cath127/mp1-new-york/assets/153606011/5d63e28e-6ab6-4bb8-acdd-7ccfd6df0409)


  * ### Gallery
    * ####
      The Gallery section consists of cards showing a photograph and text about some of the most iconic features of the city.

    * ####
      On a mobile device, three cards are displayed vertically: Central Park, Grand Central Station and Times Square.  On medium devices, four cards are displayed 2x2, all the mobile cards and Brooklyn Bridge.  On large devices, six cards are displayed 3x2 with Staten Island Ferry and Outdoor cinema being the two new cards. 
     


      Desktop

      ![desktop gallery](https://github.com/Cath127/mp1-new-york/assets/153606011/c0164788-7373-4b8c-b0cc-0b3041fe0e28)


      Tablet

      ![tablet gallery](https://github.com/Cath127/mp1-new-york/assets/153606011/d358245d-d972-420c-a64c-13844ed2f9f7)


      Mobile

      ![mobile gallery](https://github.com/Cath127/mp1-new-york/assets/153606011/a4ea5b9c-4057-4d4c-bd1b-7e60c7fd8f9d)



 * ### Tips Section
    * ####
      The tips section consists of free tips, discouted tips and a form to submit tips.

    * ####
      Both the free tips and discounted tips column have five tips and buttons to get more information about each one.  On a mobile device these are underneath each other but display side by side on medium devices and bigger.

      Desktop

      ![tips desktop](https://github.com/Cath127/mp1-new-york/assets/153606011/a49e93fe-fa3e-43fd-8c10-1082c29734f2)


      Mobile

      ![tips mobile](https://github.com/Cath127/mp1-new-york/assets/153606011/2241c7c6-a019-4774-8361-1cc149b582c9)


    * ####
      The form part is for someone who has visited New York is able to submit their own tip.

      ![tips](https://github.com/Cath127/mp1-new-york/assets/153606011/872685b9-9a3f-48e7-9f3d-786435f7585c)

  * ### Footer
    * ####
      The Footer section consists of an email address ( thriftynyc@example.com) and social link icons for Facebook, X, Instagram and Tiktok.

      ![footer](https://github.com/Cath127/mp1-new-york/assets/153606011/d2303bb1-4da9-43b3-b8bc-1392a956f43a)


## Future Implementations 
  * #### 
    As more tips are sent in they could be categorised into different types of attractions eg museums, outdoor, food etc.  People could also search for free or discounted tips.  Eventually they could be alphabetized too. 
  * ####
    Discounted deals could be made with food locations offering a percentage off if the customer mentions THRIFTY NYC.
  * ####
    Photos could also be submitted to extend the photo gallery.


## Accessibility
  I have tried to make the website as accessible to everyone as possible.  The ways in which I've done this are:
  * ####
    Using semantic HTML
  * ####
    Using descriptive alt attributes for images throughout the site.
  * ####
    Using easy to read dyslexia friendly fonts.
  * ####
    Using a relevant yet contrasting colour scheme on the whole page.
  * ####
    Providing clear navigation


## Technologies Used

  ### Languages Used
   * #### [HTML5](https://en.wikipedia.org/wiki/HTML5)
   * #### [CSS3](https://en.wikipedia.org/wiki/CSS#CSS_3)
   
  ### Frameworks, Libraries and Programs Used
   * #### [Balsamic](https://balsamiq.com/) was used to create wireframes.
   * #### [VS Code](https://code.visualstudio.com/) was used as a code editor.
   * #### [Gitpod](https://www.gitpod.io/) was used for the CI template and to access VS Code
   * #### Git was used for version control.
   * #### [Github](https://github.com/) was used to store the code for the website.
   * #### [Bootstrap](https://getbootstrap.com/) was used to create the framework of the website.  Code for the navigation bar, forms and cards were used and modified. Additional CSS styling was implimented in style.css.
   * #### [Google Fonts](https://fonts.google.com/) was used to import fonts into the website.
   * #### [Font Awesome](https://fontawesome.com/) was used to add icons for aesthetic purposes.
   * #### [CHAT GPT](https://chat.openai.com/) was used for the slogan and introductory text.
   * #### Google Development Tools was used to troubleshoot and test features, solve issues with responsiveness and styling.
   * #### [Sqoosh](https://squoosh.app/) was used to decrease the dimensions and size of photos.
   * #### [Canva](https://www.canva.com/) was used to display the wireframes and remove the background of the Am I Responsive image.
   * #### [Am I Responsive](https://amiresponsive.co.uk/) was used to display the home page image on different devices.

## Testing 
    
  Chrome developer tools was used to identify and address any problems.
  The following issues were raised in my second mentor meeting:

  * #### To add an overlay to the hero image.
  * #### To make the website icon captions clickable.
  * #### To delete the underline of h2 headings.
  * #### To remove buttons from the tips section and replace with a clickable link at the bottom.
  * #### To move the gallery section after the useful websites and put the tips section last.
  * #### To add meta tags to improve SEO.

  All of these issues were addressed.

### Testing User Stories from User Experience (UX) Section
  * #### First Time Visitor Goals
    a.  As a first time visitor, I want to be able to understand the purpose of the site.

    ![intro](https://github.com/Cath127/mp1-new-york/assets/153606011/6f47ff13-b663-4219-8f9d-669e61a36bda)

    b.  As a first time visitor, I want to be able to navigate the site easily to find information.   

    Desktop Navbar ![navbar desktop -fotor-2024021815482](https://github.com/Cath127/mp1-new-york/assets/153606011/0bf9b1cc-0b51-4433-b877-688339c0dd5e)

    c.  As a first time visitor, I want to look at social media links to find how active they are and what content they produce. 

    ![footer](https://github.com/Cath127/mp1-new-york/assets/153606011/d2303bb1-4da9-43b3-b8bc-1392a956f43a)

  * #### Returning Visitor Goals
    a.  As a returning visitor, I want to be able to see tips while planning for/visiting NYC. 

    ![tips desktop](https://github.com/Cath127/mp1-new-york/assets/153606011/a49e93fe-fa3e-43fd-8c10-1082c29734f2)


    b.  As a returning visitor, I want to access useful websites while planning for/visiting NYC. 

    ![websites desktop](https://github.com/Cath127/mp1-new-york/assets/153606011/cfe0459e-d7c4-47e9-a6d8-45748b645b98)  

    c.  As a returning visitor, I want to leave a useful tips for others.

    ![tips](https://github.com/Cath127/mp1-new-york/assets/153606011/872685b9-9a3f-48e7-9f3d-786435f7585c)

  * #### Frequent Visitor Goals
    a. As a frequent visitor, I want to see what new tips have been added. (Future development)

    b. As a frequent visitor, I want to check out new features as the website develops. (Future Development)

  ### Validator Testing

  W3C validator was used to validate the HTML on the website. It was used to validate CSS in the style.css file too.
  ![HTML Checker](https://github.com/Cath127/mp1-new-york/assets/153606011/b881a286-0b0d-4d63-8970-5d706a1e9865)


  ![CSS validator](https://github.com/Cath127/mp1-new-york/assets/153606011/06f75474-2249-4d47-bbba-a78f47f3cdc6)
  ![CSS warning](https://github.com/Cath127/mp1-new-york/assets/153606011/161d8c66-7160-45e5-b89a-dc371d428de5)

  The CSS warning was due to Google Fonts being used which could not be validated (this didn't affect the validator passing the CSS code).

  ### Lighthouse

  I used Lighthouse within Chrome Developer Tools. This allowed me to test for performance, accessibility, best practices and the SEO (search engine optimization) of the website.

  ![lighthouse](https://github.com/Cath127/mp1-new-york/assets/153606011/28e8ea96-0bb7-4f13-bb73-364645187b9a)
    
  Accessibility Suggestions:

  1.Background and foreground colors do not have a sufficient contrast ratio.  This is due to the colour of the links and the number of links that I have.


  2.Heading elements are not in a sequentially-descending order.  This is due to is being a scrolling webpage so the headings are not in the right order which they would better on a three page website.

### Full Testing
  The site was tested and functioned well on Chrome, Safari and Edge.

  Full testing was carried out on the following devices:

  * #### 
    Laptop
    * ####
      Dell Precision 3550 15.55 inch screen


  * #### 
    Tablet
    * ####
      ipad (7th generation)
    * ####
      Samsung Galaxy S7+

  * #### 
    Mobile
    * ####
      iphone 12
    * ####
      CAT S62 Pro

  I also used Google Chrome developer tools to ensure that they responsive on all different screen sizes.


  Links
   * ####
     All 22 links were tested.  Each link functioned properly and opened up a new website in another tab.

   * #### Contact Form
     * #### 
       To find the form click on tips (navbar) and scroll to the bottom.
     * #### 
       Fill out all the fields including a valid "@" email.
     * #### 
       If the form is completed properly you will get this screen.

      ![Form submit message](https://github.com/Cath127/mp1-new-york/assets/153606011/145aa9d6-64ab-41bf-83ec-4ed9dafc713b)

     * #### 
       If you try to submit without a name you will get this screen.

       ![fill in name](https://github.com/Cath127/mp1-new-york/assets/153606011/9e94920b-99fe-48a2-917c-a3127ab3570b)

     * #### 
       If you try to submit without an email you will get this screen.

       ![fill in email](https://github.com/Cath127/mp1-new-york/assets/153606011/3a7841c2-ce03-4a70-ad41-892ab42d5688)

     * #### 
       If you try to submit without a tip you will get this screen.

       ![fill in tip](https://github.com/Cath127/mp1-new-york/assets/153606011/4924d225-c647-4508-badf-0cd83f4a6407)


### Solved Bugs
  1. CLI message "Your branch is behind 'origin/main' by 1 commit and can be fast forwarded.  Solved by using a force push (git push -f) as advised by Tutor Support.
  2. Font Awesome icons for useful websites weren't centered on xx large devices. Solved by adding justify-content:center in Media Quieries.
  3. Social media icons were too close together so it was hard to choose the required one (especially on a mobile).  Solved by adding margin-right: 20px.
  4. A small gap appeared on the right of the hero image and footer due to the scrolling bar.  Solved by making the footer container fluid so there was no space.
  5. Lighthouse test had a much lower accessibility score than the other three criteria due to no descritpive links in the tips area.  Once unique tips were added the score increased.
  
### Unsolved Bugs
  1. There was a problem with VS code with the message "Failed to set up dynamic port forwarding connection over SSH to the VS Code server".  When this happened I lost my live preview.  Some commits were made before I would have liked because of this.  I then decided to commit when I finished each part I was doing before this message appeared therefore I have a lot more commits than I would have liked.
  2. On only an x large screen the Staten Island Ferry card (in the gallery section) is shorter than the other two cards.


## Deployment



## Credits
### Code Used
* ### [Contrast Checker](https://webaim.org/resources/contrastchecker/?fcolor=02AFD0&bcolor=FFFF00) to ensure colours worked well together.
* ### [Bootstrap Navbar](https://getbootstrap.com/docs/5.3/components/navbar/#how-it-works) code used and styled.
* ### [Code Institute]( https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+CSE101+2020_Q2/courseware/be0e510a3aca4bccb6e0bba4cf7cf06b/6eb8cfc87bfd434a87861a844e00b655/) Love Running Project - how to use Font Awesome icons.
* ### [Code Institute](https://learn.codeinstitute.net/courses/course-v1:codeinstitute+FE+2024_Q1/courseware/a4b90d17e5c94220a0f83f00ce7fa606/7c0e25d1061e47cdae9c492d623bfc65/?child=last)  Whisky Drop Project - how to hide text and pictures.
* ### [Code Institute](https://learn.codeinstitute.net/courses/course-v1:codeinstitute+FE+2024_Q1/courseware/a4b90d17e5c94220a0f83f00ce7fa606/2aca2c94a518427495cc1b4bc641ccbf/)  Whisky Drop Project - Bootstrap grid system.
* ### [Code Institute]( https://learn.codeinstitute.net/courses/course-v1:codeinstitute+FE+2024_Q1/courseware/a4b90d17e5c94220a0f83f00ce7fa606/7c0e25d1061e47cdae9c492d623bfc65/?child=last) CV Project - Layout of putting a picture next to text.
* ### [Youtube]( https://www.youtube.com/watch?v=SvlD_OPszuc) how to implement Bootstrap cards.
* ### [Youtube](https://youtu.be/k4EGA95ZK4o?si=S6k_tMhLWz7guX7w) how to make a scrolling webpage.
* ### [W3Schools](https://www.w3schools.com/howto/howto_css_smooth_scroll.asp) how to have smooth scrolling.
* ### [Code Institute](https://learn.codeinstitute.net/courses/course-v1:codeinstitute+FE+2024_Q1/courseware/616289d66b5641a3808cc43e53842695/b51f7b8b815c4bcd9979d2281b6d97a9/) CV Project - Adding a footer.


### Content
* ### [CHAT GTP](https://chat.openai.com/) was used for the slogan and introductory text.
* ### All other content was written by the developer.

### Media
* ###  All photographs were taken by myself.

### Acknowledgements            




[def]: https://github.com/Cath127/mp1-new-york/assets/153606011/42edf02f-9504-4eed-90b8-d46e37a744d8