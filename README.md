![image of the FakeFairytale battle maps logo.](assets/images/readme/ffbm-logo-banner.jpg)

---------------------------------------------------------------------------------------------------------------------
# FakeFairytale Battle Maps

FakeFairytale Battle Maps is a Youtube channel and content creator in the digital map-making space. It is specifically geared towards users of the DungeonDraft( Henceforth referred to as "DD") software, or those who are in the consideration process of purchasing DD. The website is designed to familiarize people with the FakeFairytale YouTube Channel, Tutorials and Maps and offers content on these three respective fields. FakeFairytale Battle Maps will help people find their way into the world of digital map-making using DD.

*Hello and welcome! My name is FakeFairytale and today I'm going to guide you through the website of* <a href="https://wouter-it.github.io/maps-tutorial/" target="_blank">*FakeFairytale Battle Maps*</a>.

![image of the FakeFairytale Website on different devices.](assets/images/readme/ffbm-screens.jpg)

# Contents
- [User Experience UX](<#user-experience-ux>)
  - [User Stories](<#user-stories>)
  - [Wireframes](<#wireframes>)
  - [Site Structure](<#site-structure>)
  - [Design & Color Scheme](<#design--color-scheme>)
    - [Typography](<#typography>)
    - [Color Palatte](<#color-palette>)
- [Features](<#features>)
  - [Current Features](<#current-features>)  
    - [Logo & Navigation](<#logo--navigation>)
    - [Hero](<#hero>)
    - [About](<#about>)
    - [Sign-up form](<#sign-up-form>)
    - [Footer](<#footer>)
    - [Confirmation message](<#confirmation-message>)
    - [Tutorial](<#tutorial>)
    - [Tutorial Video](<#tutorial-video>)
    - [Maps](<#maps>)
  - [Future Features](<#future-features>)
- [Technologies & Tools used](<#technologies--tools-used>)
- [Testing](<#testing>)
- [Deployment](<#deployment>)
  - [How to deploy the project yourself](<#how-to-deploy-the-project-yourself>)
  - [Copy repo to GitHub](<#to-copy-the-repository-in-github>)
  - [Create local clone](<#to-create-a-local-clone-of-this-project>)
- [Comments](<#comments>)
     - [Regarding Chat GPT Code](<#regarding-chat-gpt-allignment-code>)
- [Credits](<#credits>)
  - [Content](<#content>)
  - [Media](<#media>)
- [Acknowledgements](<#acknowledgements>)
- [Sign-off](<#sign-off>)

# User Experience UX

## User Stories
- As a visitor, I want to immediately understand the purpose of the website upon loading. 
- As a visitor, I want to be able to navigate through the site conveniently.
- As a visitor, I want to see what kind of content FakeFairytale creates.
- As a visitor, I want to have material to improve my map-making skills at my disposal.
- As a visitor, I want to know how to purchase DD.
- As a visitor, I want to be able to contact FakeFairytale.
- As a visitor, I want to be able to find more videos & tutorials.
- As a visitor, I want to download maps made by FakeFairytale.

More information on the Visitor Journeys can be found in the [**_Testing document_**](TESTING.md)

[Back to top](<#contents>)

## Wireframes

The Wireframes for FakeFairytale Battle Maps were made using [Balsamiq](https://balsamiq.com) as the UI proved to be intuitive and easy to grasp. There are wireframes for two separate devices; Full-Screen and Mobile.
The final design of the website varies slightly from the wireframes in some regards as during the process it was discovered the design could be simplified without the loss of clarity.

![sketch design of FakeFairytale Battle maps website on computer.](assets/images/readme/computer-screen-adjusted.jpg)

![sketch design of FakeFairytale Battle maps website on mobile.](assets/images/readme/mobile-adjusted.jpg)

[Back to top](<#contents>)

## Site Structure

The FakeFairytale website has 4 different pages. The [home page](index.html) as default page to greet visitors, the [confirmation screen](confirm-signup.html) that people see when they fill in the sign-up to newsletter form on the home page, the [tutorial](tutorial.html) where people can learn how to install DD and watch the first tutorial video on the software, and the [maps](maps.html) page where people can view and download maps made by FakeFairytale.

Right underneath the home page introduction text, two quick navigation buttons will take the visitor directly to either the tutorial or maps page, based on their input and reason for visiting the website.

[Back to top](<#contents>)

## Design & Color Scheme

### Typography
The typography that were chosen for the project were <a href="https://fonts.google.com/specimen/Bebas+Neue" target="_blank">Bebas Neue</a> for the headers and <a href="https://fonts.google.com/specimen/Montserrat" target="_blank">Montserrat</a> with a fall-back on sans-serif as body text. Bebas Neue was chosen because it already was the main font of the FakeFairytale brand and it suits the role as header well. It is described ad bold and draws in the eyes to the headers to help guide a visitor through the page. Montserrat was chose as body and navigation text based on the recommendation from <a href="https://typ.io/fonts/bebas_neue#:~:text=Bebas%20Neue%20is%20a%20sans,Calluna%2C%20Avenir%20and%20Playfair%20Display." target="_blank">Typ.io</a> as a suitable match. It also has a clean look that'se asy to read and thus suited for explanatory texts.

[Back to top](<#contents>)

### Color Palette

The color scheme chosen is based on the FakeFairytale brand and the colors it employs in it's YouTube channel and logo. However, as those colors were not necessarily designed for the use of a website some minor changes have been made to address that. The original green-grey color has been darkened slightly to increase contrast. Alternatively the red has been derived from the Gnomes Hat in the logo, and the slightly off-black color has been chosen to better match the soft colors already in the palatte.

![screenshot of the green-white contrast and black-white contrast for the website](assets/images/readme/contrast-checker.png)

![screenshot of color palatte, feldgrau, white, penn red, jet black](assets/images/readme/color-palate.png)

[Back to top](<#contents>)

# Features

## Current Features

### Logo & Navigation
- Located at the very top of every page is a fully responsive navigation menu that allows for easy navigation across the site. 
- The FakeFairytale gnome logo is also equipped with a link that returns the user to the home page, as is common on many websites. 
- The logo image disappears on smaller devices as to not take up too much space when limited is available.

![screenshot of nav bar](assets/images/readme/nav-bar.jpg)

[Back to top](<#contents>)

### Hero
- Located just below the navigation is an image and welcome message. The image helps set the tone for the page and is one of the most popular maps made by FakeFairytale. It is blurred out so as to no distract from the message.
- The welcome message immediately states the value the website provides. It is aimed at making you a better map-maker and helps the visitor understand the intent and purpose of the website.

![screenshot of website hero image](assets/images/readme/hero.JPG)

[Back to top](<#contents>)

### About
- A two collumn about section introduces the visitor to the FakeFairytale brand.
- The left-hand text column states the core problems the visitor is experiencing in order captivate them and capture their attention. It then proceeds to introduce the brand to those unfamiliar.
- Two quick navigation buttons help guide the visitor to their destination. They are designed to specifically help the visitor that already knows what they are visiting the page for.
- The right-hand-side video introduces those unfamiliar to the FakeFairytale YouTube Channel with one of it's most popular videos. It also provide knowledge for those who may already know/have Dungeondraft but aren't proficient with it yet.

![screenshot of the about section](assets/images/readme/about-section.jpg)

[Back to top](<#contents>)

### Sign-up form
- A sign-up form lets the visitor register for a mail list that will provide updates on what is happening with the FakeFairytale Brand. It is designed for those who are hooked by the content so far and would like to learn more over the coming period.
- Currently, there is no actual mail list, nor is the form hooked up to any sort of registration system.

![screenshot of sign-up form](assets/images/readme/sign-up-form.jpg)

[Back to top](<#contents>)

### Footer
- The site footer is always located at the bottom of the page and contains both the social media links & an e-mail address visitors can contact.
- The Social Media links are enhanced with icons and open in separate tabs when clicked. They're there for those who do not wish to sign up for a newsletter or are looking to do so through a different medium.
- Email is added to allow people to contact FakeFairytale directly.

![screenshot of website footer](assets/images/readme/footer.jpg)

[Back to top](<#contents>)

### Confirmation message
- The confirmation page provides a message to let the visitor know their action of filling in the form has been successful. It also helps them understand they can now navigate to another page if so desired.

![screenshot of confirmation message](assets/images/readme/confirmation.jpg)

[Back to top](<#contents>)

### Tutorial
- An easy-to-follow step-by-step guide to downloading DD. Fully responsive to align below each other when viewing on smaller devices.
- Designed to help the visitor find their way through the installation process of DD, which can be a bit confusing at times.
- The final step in the process helps guide the visitor to the video below.

![screenshot of dungeondraft installation guide](assets/images/readme/tutorial.JPG)

[Back to top](<#contents>)

### Tutorial Video
- Underneath the DD installation Tutorial there is a special video gaimed at beginners in the DD software environment. 
- The video allows the visitor to immediately start their learnig journey without having to switch websites.

![screenshot of the get started video](assets/images/readme/get-started.jpg)

[Back to top](<#contents>)

### Maps
- On this page, the visitor finds an overview of maps available for download.
- Designed to give an easy birds-eye view of the options available with a clear call to action if they want to download the maps. Also provides basic information about the map.
- Can easily be expanded upon.
- The download buttons are direct download links that allow for immediate downloading without any more user input.

![screenshot of map overview page](assets/images/readme/maps.jpg)

[Back to top](<#contents>)

## Future Features
- A sticky navigation and footer bar to ensure navigation & Social Media links are always available.
- A "Backto top" button in the bottom right corner of each page to ease navigation.
- Make sure the Sign-up Form actually registers applicants and pushes data to a server.
- Back to home button on the confirmation screen.
- Additional Maps to download on the Maps page with the option to donate towards the creator.
- Support for <350px width screens.

[Back to top](<#contents>)

# Technologies & Tools used
- [HTML5](https://en.wikipedia.org/wiki/HTML5/) - takes care of the structure and backbone of the content & website.
- [CSS3](https://www.educba.com/what-is-css3/) - facilitates the styling of content on the page.
- [Balsamiq](https://balsamiq.com/wireframes/) - used to create sketches/wireframes for the website.
- [Gitpod](https://www.gitpod.io/#get-started) - used to deploy adn edit the website.
- [Github](https://github.com/) - used to host website repository.

[Back to top](<#contents>)

# Testing
Please refer to the testing document [**_here_**](TESTING.md) for more information on the testing process for FakeFairytale Battle Maps.

[Back to top](<#contents>)

# Deployment

### **How to deploy the project yourself**
The website was deployed to GitHub pages. In order to replicate the website in your own environment please follow the steps below:
  1. In the GitHub repository which you can find through [this link](https://github.com/Wouter-IT/maps-tutorial) navigate to the **Settings** tab.
  ![screenshot of GitHub repository with settings highlighted](assets/images/readme/step1.jpg)
  2. In settings, navigate to the **Pages** tab on the left-hand side in the section "Code and automation".
  3. Under **Source**, set the branch to **main** and then click **save**.
  ![screenshot of "pages" and branch section highlighted](assets/images/readme/step3.jpg)
  4. Upon selection, the page will automatically refresh. A ribbon display will indicate the deployment has been successful.

[Back to top](<#contents>)

### **To copy the repository in GitHub**
A copy of the repository can be made by forking the GitHub account. You can view adn alter this copy without it affecting the original repository. You can fork the repository by;
1. Logging in to your GitHub and locate the [repository](https://github.com/Wouter-IT/maps-tutorial).
2. On the top right corner of the page is a button called **'Fork'**. Clicking on the button creates a copy of the original repository in your own GitHub Account.
![screenshot on how to fork in github](assets/images/readme/fork.jpg)

[Back to top](<#contents>)

### **To create a local clone of this project**
You can also create a local copy of the project using the following steps:
1. Open the project repository and make sure you are currently in the **<> Code** tab.
2. On the right, click on the left of the two buttons named **<> Code**. This will open a dropdown menu which displays the URL of the project, copy this URL.
![screenshot on how to clone](assets/images/readme/local-clone.jpg)
3. In your IDE of choice, open **Git Bash**.
4. Change the current working directory to the location where you would like the cloned directory to be.
5. Type **git clone** and paste the URL copied from GitHub.
6. Press **enter** and the local clone will be created.

[Back to top](<#contents>)

# Comments

### Regarding Chat GPT allignment code:
Initially after trying and testing multiple approaches to align 4 element to their respective centers but failing I consulted Chat GPT, unaware of the current stance of Code Institute against it due to a lack or research on my part. After resolving 3 of the 4 issues through other methods I came to the conclusion that for the alignment of the confirmation page text the method suggested by Chat GPT simply was the best way to go. As I understand and concur with the vision of Code Institute on the encouragement of learning how to solve problems by yourself instead of using tools like AI, I went on to do research on why the transform translate method works in this situation, and how it works in general. 

- **position: absolute;** makes sure that the div is positioned relative to its nearest positioned ancestor, in this case that will be the #confirm-container which has it's position set to relative.
- **top: 50%;** pushes the #confirm-header down from the top by 50% of its containing element.
- **left: 50%;** repeats that process, but pushes it the right by 50%.

- **transform: translate(-50%, -50%);** moves #confirm-header up and to the left by 50% of its **own** width and height respectively. This is required because otherwise the position absolute 50/50 would center the confirm header on it's left most point. By applying x-50% and y-50% to it, it moves up and to the left aligning its center with the center point of the containing element.

The clarification for this code was found on [Stack Overflow](https://stackoverflow.com/questions/46184458/) written by a user named Terry, and later edited by Peter Mortensen.

Upon concluding my research & learning process I decided to leave the code in, however, I will be sure to avoid Chat GPT in the future.

[Back to top](<#contents>)

# Credits

## Content
- The [Developer Mozilla Webpage on Wrapping text](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Text/Wrapping_Text) for "the overflow-wrap: break-word" in order to keep the paragrahp form interferring with the video content on the right of it.
- My Fonts from [Google Fonts](https://fonts.google.com/).
- [Typ.io](https://typ.io/) for finding a maching font to Bebas Neue.
- [Coolors.co](https://coolors.co/) for the color palatte.
- [CloudConvert](https://cloudconvert.com/jpg-to-webp) for converting images to webp format to reduce loading times.
- [Font Awesome](https://fontawesome.com/) for implementing Icons on the website.
- Credits to the [Wawawoods project README by Ewan Colquhoun](https://github.com/EwanColquhoun/wawaswoods) to help create and structure my own README. This was a tremendous help.
- The code for the Favicon found on [W3Schools](https://www.w3schools.com/html/html_favicon.asp).
- The code that changes the cursor upon hovering over a button & creating a button that leads you to another page on the Website from [Scaler](https://www.scaler.com/topics/how-to-make-a-button-link-to-another-page-in-html/)
- Sections of my own code form the Love Running Walkthrough Project that I have repurposed to suit my needs for this website: Footer & Google Icons Script.
- [Tutorialspoint.com](https://www.tutorialspoint.com/how-to-trigger-a-file-download-when-clicking-an-html-button-or-javascript#:~:text=Use%20the%20download%20attribute%20with,as%20a%20file%20download%20button) for the code on how to create a download button that downloads a file on click.
- [Stack Overflow](https://stackoverflow.com/questions/4216035/css-background-image-alt-attribute) for using a "Title" attribute as alternative for an alt attribute.

[Back to top](<#contents>)

## Media
- All images are made and owned by FakeFairytale, the creator of this website.

[Back to top](<#contents>)

# Acknowledgements
The FakeFairytale Battle Maps page was created as a project for the first milestone of the [Code Institute Full-Stack Development Course](https://codeinstitute.net/nl/full-stack-software-development-diploma/). During the learning process I've received excellent support and guidance from my mentor [Precious Ijege](https://www.linkedin.com/in/precious-ijege-908a00168/) who has been able to keep me focust, confident and made sure my project scope was realistic. I'd like to thank him for his guidance, as well as my wife, who took excellent care of me while I was crunching code.

[Back to top](<#contents>)

# Sign-off
*And that was it folks, I hope you have enjoyed the tour through the FakeFairytale Battle Maps website. Thank you for reading and if there are any question don't hesitate to contact me. My e-mail is on the website!*
  
[Back to top](<#contents>)