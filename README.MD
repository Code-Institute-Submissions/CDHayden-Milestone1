
# Milestone Project 1

## CH Home Improvement Website

A mobile first fully responsive website for a new home improvement start up. This website allows potential customers to view services offered by CH Home Improvement, read reviews and see examples of their work.

## UX

This website is primarily for the company owner of CH Home Improvement. The owner would like the website to help potential customers contact them with the aim of increasing business. 

However, it is also important that external users of the site have a positive user experience and so their considerations should be taken into account as well.

After taking in the considerations of the company owner and researching various other home improvement business websites I decided to put the contact details for the company in the header. As this was the main call to action required and seemed common place whilst doing some "market research".

I decided against using a single scrolling page as at some point in the future the site owner may want to add more services. I feel that the Family Tree navigation lends itself well to what the site owner wants.



### User stories 

**Site Owner**
1. As a site owner I want to show photos of my work, to demonstrate my quality of work.

2. As a site owner I want to show good reviews I have received, to encourage other external users to hire me.

3. As a site owner I want to encourage users to contact me, so that I can build a good relationship with them.

**External User**

4. As an external user I want to see what services D.W Home improvements offer, so that I can see if they are suitable for my needs.

5. As an external user I want to quickly and easily contact D.W Home Improvements to get a quote, so that I can decide if it is affordable.

6. As an external user I want to see examples of work done by D.W Home Improvements so that I can judge if they are done well.

7. As an external user I want to read reviews of work done by D.W Home Improvements so I am able to judge if they are trust worthy and offer a good experience. 

## Features

### Existing Features
- Image gallery - allows external users to achieve user story 6, by giving them photos of work carried out and the ability to click on them and view a larger image.

- Embedded video - allows external users to achieve user story 6, by giving them a video of work carried out by the company.

- Contact form - allows external users to achieve user story 5, by giving them a way to contact the company via the website.

- Contact detail hyperlinks in the header and footer - allows external users to achieve users story 5, by giving them easy ways to navigate to social media and call or email the company.

- Reviews on each service page - allows external users to achieve user story 7, by being able to read what other people say about the company and see a star rating (out of 5).


### Features Left to Implement
- A call to action button that sticks to the bottom right of the page which when clicked opens a form enabling the user to contact the company.


### Wireframes

Wireframes come in two flavours. One for desktop and tablet (the layout was designed to be the same albeit responsive)and one for mobile. Two pages, groundwork and tiling, were designed to have the same layout and so share the same wireframe.

**Desktop and tablet wireframes**

[Click here to view all wireframes.](assets/images/wireframes/) 
- [Index.html](assets/images/wireframes/index-desktop-tablet.png)
- [Index.html-menudrop](assets/images/wireframes/index-desktop-tablet-menu-dropdown.png)
- [Contact.html](assets/images/wireframes/contact-desktop-tablet.png)
- [Painting.html](assets/images/wireframes/painting-desktop-tablet.png)
- [Groundwork.html-and-Tiling.html](assets/images/wireframes/groundwork-desktop-tablet-AND-tiling-desktop-tablet.png)
- [image-modal](assets/images/wireframes/image-modal-desktop.png)

**Mobile wireframes**
- [Index.html](assets/images/wireframes/index-mobile.png)
- [Index.html-menudrop](assets/images/wireframes/index-mobile-menu-drop.png)
- [Contact.html](assets/images/wireframes/contact-mobile.png)
- [Painting.html](assets/images/wireframes/painting-mobile.png)
- [Groundwork.html-and-Tiling.html](assets/images/wireframes/groundwork-mobile-AND-tiling-mobile.png)

## Technologies Used

- HTML 5 
Used to provide structure to each page of the site.

- CSS
Used to format the HTML of each page. Make each page look visually appealing. 
- [https://developers.google.com/web/tools/chrome-devtools](https://developers.google.com/web/tools/chrome-devtools/)
Used this to test how the site looked at different screen sizes and make sure the responsive layout worked.
- [https://code.visualstudio.com/](https://code.visualstudio.com/)
Visual Studio Code (VSCode) was the IDE used to develop this site.
- [https://git-scm.com](https://git-scm.com/)
Git was used to provide a local version control system. 
- [https://github.com/](https://github.com/)
Used to host and deploy the final version of the site, as well as provide an online repository for the project.

- [Bootstrap](https://getbootstrap.com/)
Used as the foundation of each page. Bootstrap allowed me to quickly provide a mobile first, responsive structure to the website.
- [Fontjoy](https://fontjoy.com/)
Used to find 3 fonts that compliment one another. 
- [Google Fonts](https://fonts.google.com/)
Used to provide access to the fonts identified via fontjoy (see above).
-  [fontawesome](https://fontawesome.com/)
Used to provide access to icons that provide easy, visual representations of text content.
- [colormind](http://colormind.io/bootstrap/)
Used to create the colour pallete of the site.
- [stackedit](https://stackedit.io/)
Used to create the README.MD for this project.
- [rem calculator](https://offroadcode.com/rem-calculator/)
Allowed me to easily convert pixel values to rem values based on HTML font size (14 by default on bootstrap).
- [Contrast Checker](https://webaim.org/resources/contrastchecker/)
Used to make sure that the text colour and backround colours used on the site are contrasting enough to be accessible.
- [Box Shadow Generator](https://www.cssmatic.com/box-shadow)
Used to quickly generate css code for box shadows.
- [https://www.pexels.com/](https://www.pexels.com/)
Used to find photos to use on the site.
- [Pixlr Photo Editor](https://pixlr.com/editor/)
Used to edit the photos used in this project.
- [tinyjpg](https://tinyjpg.com/)
Used to reduce the filesize of images used in this project.
- [https://validator.w3.org](https://validator.w3.org/)
Used to validate the HTML the site.
- [https://jigsaw.w3.org/css-validator/](https://jigsaw.w3.org/css-validator/)
Used to validate the CSS of the site.
- [https://autoprefixer.github.io](https://autoprefixer.github.io/)
Used to make sure that browser specific prefixes were used for CSS.
- [https://www.heropatterns.com/](https://www.heropatterns.com/)
Used to provide a repeating background image for the header of the site.
- [https://jquery.com/](https://jquery.com/)
JQuery was used to dynamically change the content of a modal depending on what photo was clicked. The code for this was taken and slightly modified from the bootstrap documentation on modals.
- [https://realfavicongenerator.net](https://realfavicongenerator.net)
Used to generate the various favicons and html code needed to use them.
## Testing

The project was continually tested throughout development via chrome developer tools. This allowed me to view my site at various responsive breakpoints and tweak the HTML / CSS in the browser. 

At the end of the project I used browserling to test my site in the latest version of the different main browsers. Namely firefox, opera, safari and internet explorer.

I also manually tested certain aspects of my site once development had finished:

- I made sure css effects behaved as expected for:
    - Hover effects:
	    - For the footer icons
		- For images in the galleries on tiling.html and groundwork.html
		- For the menu items in the main navigation bar
	- Media queries:
		- When aligning the header elements I had to apply different styles at different responsive breakpoints. I made sure these were mobile first and had the intended outcome.

- Form validation on the contact page:
	- Trying to submit an empty form
	- Trying to provide an incorrect email address

- The image galleries on the tiling and groundwork pages behaved as expected:
	- Clicking each image to make sure the correct image was loaded into the modal.

### Bugs / Problems
Initially I had trouble correctly positioning the review "media" objects on each of my service pages. After speaking with my mentor it was identifed as having incorrectly using the bootstrap grid (rows nested in rows nested rows...). The simpler layout suggested by my mentor helped me to achieve the positioning I wanted.

## Deployment
You can view the deployed site here: [https://cdhayden.github.io/Milestone1/](https://cdhayden.github.io/Milestone1/)

### How was the site deployed
To deploy this site my local git repository was pushed to a github repository and then hosted on github pages. 

### How do I run this locally?

You will need to download the repository: 

1. Open the [repository](https://github.com/CDHayden/Milestone1)
2. At the top of the page click the "Clone or download button
3. Select the "Download Zip" option.
4. Once downloaded, extract the files into a folder of your choice.
5. Open the folder you extracted the files to and open "index.html" in your browser.

## Credits

### Media
- The photos used in this site were obtained from [https://www.pexels.com/](https://www.pexels.com/)

### Acknowledgements

Thank you to my mentor Reuben Ferrente for his time and valuable feedback and advice.

Thank you to (Anthony)[https://github.com/auxfuse/Milestone1] for creating a collection of very useful resources.

### I received inspiration for this project from 
- [Granada Home Improvements](https://www.granadahome.com)