# Vasileia's Portfolio
Milestone Project : User-Centric Frontend Development - Code Institute 

I am a Full Stack Web Developer and a Makeup Artist and this is my portfolio website, created to attract clients. My portfolio includes a little bit about myself and my experience, it highlights my work and achievements by including before and after pictures of clients and makeup tutorials so that anyone who visits my website can learn something, as well as a form where clients can book their next appointment! 

## Demo 

A live demo can be found [here](https://vasileia-apostolou.github.io/Portfolio/).

## UX 

I've created this website for those who are looking for a makeup artist and for those who would like to learn how to create fun and colorful makeup looks. Overall, the goal of this website is to show my passion, provide service, and share a few of my tips. 

* As a new user, I should:   

    * Get to know who Vasileia is.
    * Get to know what her achievements and work experience is.
    * Look at her makeup skills on her clients.
    * Learn a few tips on how to recreate her looks.
    * Be able to book an appointment.
    * Look at her social media for further connections.
   
* As a client, I should: 
     
    * See and learn from Vasileia's new tutorials.
    * See Vasileia's new clients.
    * Be able to contact her for my next appointments.


 ### Strategy 

 My objective in the design was to build a fully responsive site that provides easily accessible information to clients and people who want to learn makeup techniques. 


### Scope

For clients, my goal was to provide a brief overview of myself as a Makeup Artist and the love I have for what I do. This includes a brief introduction about me, my work, sharing makeup tutorials, a booking form for appointments, and many options for contacting me through social media.

### Structure 

In the Home section, there's a background picture, my name and job title. 
In the About section, there's a short introduction and work experience paragraph with a picture of myself on the right.
Next, in the Portfolio section there's a carousel slider with client photos. In the Tutorial section there are 4 videos from Youtube, in the Contact section a booking form 
and lastly, in my footer there are links to my social media.


### Skeleton
[Wireframes](https://github.com/Vasileia-Apostolou/Portfolio/blob/master/assets/wireframes/Wireframes.pdf)

### Surface

The light pink color scheme was chosen to give a girly and fun look.


## Features 
In the Home section, I wanted something clean and simple, so I included my name and job title. In the About section, I wanted to briefly introduce myself and what I have achieved as a Makeup Artist in the past. In the Portfolio section, I wanted them to see some of my before and after work on clients so I can show my skills. I created the Tutorials section because I wanted anyone who visits my website to leave with learning something on how to improve their own makeup skills. In the Contact section, I wanted to provide a means for the user to book an appointment without necessarily needing to call. And lastly, in my footer, I included my social media links for further connections.

### Features Left To Implement

In the future, I would like to add more pictures of clients that I've worked with to expand my portfolio and add a new page with Quizzes so that users can easily find out what their skin type is and what colors work best on their skin. Additionally, I would like to create a new page whereby I will share my favorite makeup companies and products and provide users with a coupon code.

## Testing
The client user story achieved the intended outcome of providing them with a showcase of myself and my work. In the About section, you can read a bit about my work experience, and there is a photo of me. You are able to see my work in the Portfolio section where there'll be before and after photos of my clients. Plus in the Tutorials sections you can watch a few of my videos on how to achieve some of my colorful looks.

### Browsers and Devices
 The site was tested in the following browsers to ensure the site is compatible and responsive.
  * Chrome
  * Mozilla
  * Safari
  * Opera
  * Internet Explorer 

I have noticed that on Safari and Internet Explorer there was a gap between the Home and About page. To fix this...
The site was also tested on multiple devices such as MacBook Pro, Huawei Mediapad T5, Iphone 8 Plus and Huawei P30 Pro to ensure it would be correctly displayed across mobile devices.

### Navbar
This website has a fixed navigation bar containing five menu items. In a tablet and mobile view the navigation bar collapses into a hamburger menu. Bootstrap alongside its Javascript/JQuery plugins was used to achieve this. The Navbar item that it's being hovered will become a bit bigger and darker.

### Portfolio 
The carousel slider automatically goes to the next photo after 10 seconds. It includes buttons on the left and right so you can go in the next or previous photo.Those buttons have a trasparent burgundy color and when you hover over them they become darker.

### Tutorials
You can play the videos in the Tutorial sections ....

 
### Contact Form
The required attribute is added to the "Full Name", "Phone Number", and "Email Address" fields so that if they are not filled in, the form will not submit.If you also try to submit the contact form with an invalid email address, there will be an error noting the invalid email address.If a client is interested in booking an appointment all fields need to be filled. However, If all fields are valid the information will be cleared and the page will reload.

### Buttons 
Once you hover over the "Book Now" button, the color will change from burgundy to a dark pink it will be enlarged and there will be a light shadow around the button which was achieved with [Hover.css](http://ianlunn.github.io/Hover/). Once the button is clicked it will remain the same dark pink color.


### Footer
You can also able to view my social media profiles via clicking on the icons in the footer.All media links will open in the correct destination once they're clicked. This was tested manually and achieved using 'target="_blank" in each link.











## Technologies Used 

### Languages 

1. [HTML](https://en.wikipedia.org/wiki/HTML)

HTML was used in this project to keep up with the latest industry standards.

2. [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets).

CSS was used for styling the content on the website

3. [Bootstrap](https://getbootstrap.com/)

Bootstrap classes were used to build the navigation bar and to make the website responsive.


### Tools 

1. [Git](https://git-scm.com/)

Git was used in this project for version control.

2. [Gitpod](https://www.gitpod.io/)

Gitpod was used to develop this project.


### Libraries

1. Social Media Icons were taken from [Font Awesome](https://fontawesome.com/).
2. Hover CSS Animations were taken from [Hover.css](http://ianlunn.github.io/Hover/).
3. Fonts were taken from [Google Fonts](https://fonts.google.com/).

  

## Deployment 

This site was developed using Gitpod. All changes to the code were then added and committed to a local repository. The commits were then pushed to my GitHub repository. The project was hosted using GitHub pages directly from the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named index.html. The process of deploying this project on GitHub pages can be seen as bellow; 

* Go to the settings tab of the repository, and scroll down to GitHub pages.
* Under GitHub pages, click on "source" and select the master branch.
* You will be automatically taken to the top of the page wherein a light blue bar will be stated: "GitHub pages source saved".
*  Scroll down to GitHub pages where will be stated "your site is ready to be published at "[https://vasileia-apostolou.github.io/Portfolio/](https://vasileia-apostolou.github.io/Portfolio/)".
* Click on the URL and you will be auto-referred to the published webpage. When returning to the GitHub repository setting, scroll down to GitHub pages and you will see a light green block stating "Your site is published at "[https://vasileia-apostolou.github.io/Portfolio/](https://vasileia-apostolou.github.io/Portfolio/)".

To run locally, you can clone this repository directly into the editor of your choice by pasting `git clone https://vasileia-apostolou.github.io/Portfolio/.git` into your terminal. 

To cut ties with this GitHub repository, type `git remote rm origin` into the terminal.

## Credits 

### Content 
All content in the "About" section was written by me.


### Media 
* Background pictures were taken from [Unsplash](https://unsplash.com/).
* Tutorials were take from my [Youtube](https://www.youtube.com/channel/UC-u1GYx9G1DYBpufa3GyPlg?view_as=subscriber) channel.
* My picture in the "About" section was taken from my [Instagram](https://www.instagram.com/vasiliaxzibit/) account.

 ### Acknowledgements 
  * I received inspiration from [Haley Schafer's](https://www.haleyschafer.com/) project.





