# Healthy Daily Life

![Home page gif](assets/gif/Home-page.gif)

[Click on this link to visit the website](https://obiwanbonobi.github.io/PP1/)

<br>

# Content

- [Purpose of the project](#Purpose of the project)
    * [User experience](#user-experience)
- [Features](#features)
   * [Navigation](#navigation)
   * [Footer](#footer)
   * Hero-image section
   * About Us section
   * Video section
   * Gallery section
   * Contact section
- [Future features](#future-features)
- [Typography and color scheme](#design)
- [Technology](#technologies-used)
- [Testing](#testing)
    * [Validation HTML and CSS](#validation-html-and-css)
    * [Testing on devices and browsers](#testing-on-devices-and-browsers)
- [Deployment](#deployment)
- [Credits](#credits)

<br>

# Purpose of the project


## User experience


## My vision for the website

The layout is intuitive and visually appealing, making it easy to navigate through and explore his work. I've optimized the site for all devices, ensuring that whether on a desktop, tablet, or smartphone, the content remains accessible and aesthetically pleasing. I've paid close attention to loading times to keep the user engaged and prevent frustration. 

Whether it's the captivating visuals or the carefully crafted text, I've strived to create a harmonious blend that provides valuable information. In addition, I've included a user-friendly contact form, and Fabian is committed to a swift response. I've placed a strong emphasis on accessibility to ensure that everyone, regardless of ability, can enjoy the site without barriers.

<br>

# Features

### Navigation

### Footer



<br>



<br>

# Future features

I want to add javascript to all pages and make the whole site more interactive.
- I want to add a zoom in feature for all pictures
- I want to make a "entry" page with a large design that will take you to the main website when you first load the website
- I want to make the pages move right to left when you go to the next page to the right. And left to right when you go to the previous page.
- Add more collaborations
- I want to improve the collaboration navigation

<br>

# Design

- <b>Font</b> : With the help of the Code Institute, Love running project, I got my font from [google fonts](https://fonts.google.com/)
- <b>Favicon generator</b> : I made my own favicon with [this website](https://favicon.io/)

### Colour scheme



<br>

# Technologies used

- The website is written in HTML and CSS only
- I did all my coding with the program VS Code, [Visual Studio Code](https://code.visualstudio.com/)
- All my code was uploaded to [Github](https://github.com/), to my [Github account](https://github.com/ObiWanBonobi)


<br>

# Testing

Every link on all pages got tested on several devices and webbrowsers. The contact form has been tested as well and works as it should.

### Validation HTML and CSS

<details>
<summary>The home page had an initial error with the < footer > where I had put an < p > in a < ul ></summary>
<img src="assets/images/readme_images/index.html-1st-test-with-error.png" name="Html index validation">
<img src="assets/images/readme_images/issue-with-index.html.png" name="Html index validation">
<img src="assets/images/readme_images/index.html-issue-fixed.png" name="Html index validation">
<img src="assets/images/readme_images/index.html-fixed-and-validated.png" name="Html index validation">
</details>

<details>
<summary>The collaborations page also had an initial error where I had put my collab navigation in a < section > which needed an header I ended up changing it to < aside ></summary>
<img src="assets/images/readme_images/collaborations.html-1st-test-with-error.png" name="Html Collaborations validation">
<img src="assets/images/readme_images/collaborations.html-issue.png" name="Html Collaborations validation">
<img src="assets/images/readme_images/collaborations.html-issue-fixed.png" name="Html Collaborations validation">
<img src="assets/images/readme_images/collaborations.html-page-fixed-and-validated.png" name="Html Collaborations validation">
</details>

<details>
<summary>The contact page had no issues from the start</summary>
<img src="assets/images/readme_images/contact.html-good-and-validated.png" name="Html Contact validation">
</details>

<details>
<summary>The contact send page did not have any issues as well</summary>
<img src="assets/images/readme_images/contact-send.html-good-and-validated.png" name="Html Contact send validation">
</details>

<details>
<summary>The CSS file did not have any issues as well</summary>
<img src="assets/images/readme_images/css-validation.png" name="CSS validation">
</details>

### Lighthouse test

<details>
<summary>The home page had an initial error where I had used < h3 > where I shoul've used a < h1 >. After I changed that it came back with this result :</summary>
<img src="assets/images/readme_images/lighthouse-test-index.png" name="Lighthouse home validation">
</details>

<details>
<summary>The collaborations page also had an initial error where I had used < h3 > where I shoul've used a < h1 >. After I changed that it came back with this result :</summary>
<img src="assets/images/readme_images/lighthouse-test-collaborations.png" name="Lighthouse collaborations validation">
</details>

<details>
<summary>The contact page didn't have any issues :</summary>
<img src="assets/images/readme_images/lighthouse-test-contact.png" name="Lighthouse contact validation">
</details>

<details>
<summary>The contact send page also didn't have any issues :</summary>
<img src="assets/images/readme_images/lighthouse-test-contact-send.png" name="Lighthouse contact send validation">
</details>

### Testing on devices and browsers

I tested the deployed wedsite on several devices webbrowsers :
- Iphone 14
- Ipad gen 3
- Google pixel 7
- Samsung galaxy tab S6
- HP envy 
- PC build

<br>

- Google chrome
- Microsoft edge
- Apple Safari

<br>

# Bug fixes

- When I deployed the website for the first time with my facilitator David Calikes and fellow student Alihan Teker, the images weren't loading. We tried several "fixes" before getting to the correct bug fix :
    * We changed the image format from webp to jpg, however that didn't work
    * We checked on another device and webbrowser and it still didn't work
    * We ended up realising that it had to do with my file path, this is where we noticed I had added a / infront of the assets/images/... file path
- When I added a link to my collaborations page in the home page, I noticed it wasn't working. Turns out I had done the same thing as with the images. Accidentally added a / infront of the file path
- When I was adding the navigation in the collaborations page I noticed that the Footer link that goes to Instagram stopped working. 
    * I checked the code and didn't notice a mistake
    * I then checked on dev tools where I noticed that the Main element when a full 100% down and it basically make the footer dissapear behind it.
    * I went into my css file and noticed that I had set width and height to 100%. I changed those values and the footer was "visible" again
- The paragraph in the contact page wasn't changing with my css demands. I had accidentally placed a # instead of a . infront of my class name for this paragraph.
- I ended up changing the size for all images because they were taking too long to load. When I changed the images with the help of a website, I saved these images with the new name the website gave me, which had an space at the end of the name. So ofcourse it didn't work, I knew from the program that if you add a file with a space in it, it needs to be wrapped in " ". I ended up deleting the space.
- The Lighthouse test was coming back a little lower and I didn't know why [this forum helped me realise it was my chrome extentions](https://stackoverflow.com/questions/54126343/how-to-fix-unchecked-runtime-lasterror-the-message-port-closed-before-a-respon)
- In my last validation I added some videos to the collab page and I had left a style in the iframe in the html file, so I deleted that and added it to the css file.

<br>

<b>I have not noticed any existing bugs, since I fixed all the existing ones.</b>

<br>

# Deployment

The website was deployed to my account on GitHub pages. The steps I took to deploy the website went as followed: 
  - Go to my [GitHub repository called PP1](https://github.com/ObiWanBonobi/PP1)
  - In there, I navigated to the Settings tab 
  - From the source section drop-down menu, I selected the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

You can see deployed wedsite [here](https://obiwanbonobi.github.io/PP1/index.html)


# Credits

- <b>Layout, contact form and code</b> : the navigation and footer layout, the contact form code and some of the basic code I partly got from the Code Institute learning program and projects, [Love Running](https://github.com/Code-Institute-Org/love-running-2.0) and Coding Coffee House
- <b>README</b> : a bit of the layout from the Code Institute Coding club sample, and the [Love Running project](https://github.com/Code-Institute-Solutions/readme-template), and from Siobhan Gorman's project [Sourdough Bakes](https://github.com/siobhanlgorman/Sourdough-Bakes)
- <b>README funtions</b> : got some ideas from cosmiccoincidence's [README](https://github.com/RE-SS3D/.github/blob/main/profile/README.md)
- <b>Images</b> : All images come directly from Fabin Schwabegger


- <b>Most of my credit goes to the Code Institute program where I made notes on every section and got most of my ideas and code from there.</b>
