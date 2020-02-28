# Contents:
    * UX 
    * Project Goals
    * Target Audience Goals
    * Site Owner Goals
    * User Requirements and Expectations
    * Design Choices 
        * Fonts
        * Icons
        * Colours
        * Styling
        * Images
        * Backgrounds
    * Wireframes 
    * Features 
        * Features that have been developed
        *  Features that will be implemented in the future
    * Technologies Used 
    * Testing 
    * Bugs 
    * Deployment 
    * Credits 

# UX (User experience)

## Project Goals
The goal of this project is to provide information about well known altrenative rock band Linkin Park. The website has to be attractive 
and informative for users and fans interested in this band. Because it is a fan page it has to have pictures of band members and media 
files to create a better picture for new fans too.

### User Goals:
* The website is easy to use and is User Friendly
* Information on website is readable and easy to understand
* Added pictures and videos are interactive and clear
* Capability to send message cia contact form
* Interact with the website on Desktop, Tablet and mobile 

### Site Owner Goals:
* To provide suitable and not too crowded website for users interested in band
* To attract new and current fans 
* Receive contact details through use of contact form
* To make sure all information provided is correct 

# User Requirements and Expectations:

### Requirements:
* Menu items working smoothly and respond correctly
* Be provided with informative articles and media files
* Website content displayed in a suitable and not offensive manor
* Contact form validation to get in touch with band

### Expectations:
* Choisen menu options leads to a correct section of the website
* Can click on a buttons and get expected response
* Watch videos on a website
* Content is visually approachable 
* Pop out nav appears in place of navbar on Tablet + Mobile devices
* Quick Links takes to a wanted part of the website
* Social Links responds as suspected
* Contact Us form works correctly

# Design Choices:
The theme of this project is a Linkin Park fans website. Knowing that this is alternative rock band colour scheme was picked to create 
better atmosphere which suits band itself.

### Fonts:
My first choice of font was <a href="https://fonts.google.com/?query=Martel+Sans&selection.family=Lato">Martel Sans</a> because it looks
tidy and neat but also has soft edges to make text look not too heavy for a reader.

I also used another font which was <a href="https://fonts.google.com/?query=Josefin+Sans&selection.family=Lato">Josefin Sans</a> for short biography paragraph of Linkin Park band. 
I wanted paragraph to stand out a little bit and this font was perfect for that.

### Icons:
The icons used as social links in footer section. They are all known social website's icons. I used 'font-awesome' 'Facebook', 'Instagram', 'Twitter'
and 'Youtube' icons. I had to make sure they were reasonable size to be seen on a smaller devices too.

### Colours:
* #fff (White)
* #1E90FF (Dodgerblue)
* #F5F5F5 (White smoke)
* #F08080 (Lightcoral)
* #DCDCDC (Gainsboro)
* #000 (Black)

### Styling:
Thanks to SASS/SCSS I was easily able to set variables in my stylesheets that ask as the house style - this means that the styles can be used in multiple places without 
having to repeat code. Using SASS also allowed me to better structure my stylesheets.

### Images + Background:
The background image I chose to on the banner I found via google search typing bands name but link to it can be found in Credts section.
More images can be found in About Us section of website and they are member's pictures for new and current band fans to recognise them in media.

I found images on random websites via google search. 

* <a href="https://www.bhmpics.com/">Bhmpics</a>
* <a href="https://www.pinterest.com/">Pinterest</a>
* <a href="https://www.phoenix.org">Phoenix</a>
* <a href="https://www.complex.com/">Complex</a>
* <a href="https://www.WordPress.com/">WordPress</a>

# Wireframes:
I built wireframes for this project using <a href="https://balsamiq.com/">Balsamiq</a> mockups. I created basic wireframes for Mobile/Tablet/Desktop
on Balsamiq to show how structurally elements would appear on the page for different devices. Wireframes can be found by clicking this link in my repository:

<a href="https://github.com/vaida898/LinkinPark-fan-page/tree/master/wireframes">Wireframes for Desktop, Mobile and Tablet</a>

# Features:

* Slide out navigation for mobile/tablet devices
* Interactive youtube videos
* Popping buttons and menu items (hover.css)

# Technologies Used:

## Languages:

* <a href="https://developer.mozilla.org/en-US/docs/Web/HTML">HTML</a>
* <a href="https://developer.mozilla.org/en-US/docs/Web/CSS">CSS</a>
* <a href="https://www.w3schools.com/js/">JavaScript</a>


## Tools and Libraries:

* <a href="https://getbootstrap.com/">Bootstrap</a>
* <a href="https://fontawesome.com/icons?d=gallery">Font-Awesome</a>
* <a href="https://mdbootsrap.com">MDbootstrap</a>
* <a href="https://jquery.com/">jQuery</a>
* <a href="https://ianlunn.github.io/Hover/">Hover.css</a>

### Testing planning + Testing stories:
The most of the testing has been conducted in GitPod but I also have used chrome dev tools to inpspect
layout of my page on mobile device and tablet.

All testing has been done manually clicking and typing into provided contact us form. 

#### Home page:

I tested if all navigation bar links work and sends user to a correct section of page. 

I added JavaScript code to make expanded navigation bar close up while scrolling through website on mobile
devices. 

1. Click navigation bar links. DO they take you to the correct section of the page?
2. Click on a logo image. Does it take you to home page? 
3. Resize the window. Does toggle icon appear and your menu works then it is clicked?
4. Click 'Read more' button. Does it take you to page section 'About us'?

#### About Us:

In this section I wanted to have only short paragraph and images of member. I wanted paragraph to
be on the left side of page and images on the right. The best helper in this case was bootstrap grid 
system. I just have to make sure that iamges and paragraph align in a way I wanted them. I was testing
it manually resizing in google chrome inspect option.

1. Resize window. Do images and paragraph of text responding correctly on a smaller devices?

#### Media:

This section of page has to have two videos embedded from youtube.com website and I wanted to have
them next to each other. On a smaller devices my plan was to have them stacked on each other. The 
most testing in this section has been done by making sure that videos are responsive via pc, tablet 
and mobile device. Knowing that these media files are videos I have to test that they are working 
and can be viewed on the website.

1. Resize the window. Do embedded videos are responsive depending of device size?
2. Play video. Do videos play on a website? Can you go to youtube.com website and watch it there?

#### Contact Us:

Contact us section purpose is to get a qoutes form fans of a band or everyone interested into band's 
movememts. User has to type in his email address, name and suggestions he has in mind for band. 
The testing I conducted on this form is to make sure all fields do work as expected and 'submit project' 
button send you back to home page.

1. Type in wrong type of email. Does field show rules of email address?
2. Type in all information and press 'submit project' button. Does it send you to home page?

# Deployment:

Linkin Park fan page was developed on GitPod, using git and GitHub to host the repository.

When deploying Linkin Park fan page using GitHub Pages the following steps were made:

* Opened up <strong>GitHub</strong> in the browser.
* Signed in using username and password.
* Selected my <strong>repositories</strong>.
* Navigated to <strong>'/vaida898/LinkinPark-fan-page'</strong>.
* In the top navigation clicked <strong>'settings'</strong>.
* Scrolled down to the <strong>GitHub Pages</strong> area. 
* Selected <strong>'Master Branch'</strong> from the <strong>'Source'</strong> dropdown menu.
* Clicked to confirm my selection.
* Linkin Park fan page now live on GitHub Pages.

#### Running Linkin Park fan page Locally

Cloning Linkin Park fan page from GitHub:

* Navigate to <strong>'/vaida898/LinkinPark-fan-page'</strong>.
* Click the green <strong>'Clone or Download'</strong> button.
* Copy the <strong>url</strong> in the dropdown box.
* Using your favourite <strong>IDE</strong> open up your preferred <strong>terminal</strong>.
* Navigate to your desired file location. 
* Copy the following <strong>code</strong> and input it into your terminal to clone Linkin Park fan page.
 ```git
  git clone https://vaida898.github.io/LinkinPark-fan-page/
   ```

# Closing Notes:

Developing this project first time I have used <strong>Bootstrap</strong> which I find was so helpful and capable to helper.
Then I get a hang on grid system I thought to myself that is such a briliant thing and so handy for any website developer. 
It helps so much with layout of page and it can be very mobile device friendly. For the further development of this project 
I would probably try to add more styling features such as zoom-in while image is clicked, sliding in heading of the page and
maybe carousel for images to have an album not only couple images. I managed to make it work on all sizes of devices which I 
think was a challange for me and user was happy to see all the content on any device it has been tried on. 

# Credits:

* <a href="https://htmlcolorcodes.com/color-names/">Colour names and codes</a>
* <a href="http://linkinparkweb.yaia.com/biography.html">Linkin Park biography</a>
* <a href="https://www.cssmatic.com/box-shadow">Shadow box parameters</a>
