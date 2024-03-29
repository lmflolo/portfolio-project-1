# Modern Annex #

This site promotes a business that creates custom designs and building plans for small annex buildings and tiny homes.

The site will be targeted towards customers who are planning to build an annex or tiny home and want a custom design and building plans that they can provide to a contractor. Modern Annex will be useful for potential customers to learn what the business does, to see previous designs and builds, and to contact the business owner with questions or enquiries.

![Modern Annex website mock-up](assets/documentation/readme-amiresponsive.png)

[Click here to view the live website](https://lmflolo.github.io/pp1/)

- - - -
## User Stories ##

- As a visiting user, I want to easily navigate between pages on the website.
- As a visiting user, I want to know what the business is about.
- As a visiting user, I want to view the previous work of the owner.
- As a visiting user, I want to contact the owner for business enquiries.
- As a visiting user, I want to receive feedback when I successfully submit the contact form.

- - - -
## Features ##

### Existing Features ###

#### The Header ####
- Featured on all three pages, the fully responsive header includes the company name which links to the home page when clicked, and a navigation menu with links to the Home page, Gallery and Contact page, and is identical on each page to allow for easy navigation.
- The header will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the browser's ‘back’ button.
- The header also remains fixed to the top of the page as the user scrolls, to allow for easy navigation between pages without making the user have to scroll back up to find the navigation links.

![Header](assets/documentation/readme-header.PNG)

#### The Navigation Bar ####
- The link for the active page will display with an underline, as a visual cue to show the user which page they are currently on.
- As the user hovers over each link in the menu, a text underline will appear to provide the user feedback as to which link they are about to click on.

![Nav Bar](assets/documentation/readme-navbar.PNG)

#### The Hero Section ####
- The Hero section includes a background image with text overlay to allow the user to see/read at a glance what the business is about. 
- This section introduces the user to Modern Annex with an eye-catching image and title to grab their attention.

![Hero Section](assets/documentation/readme-hero-section.png)

#### The About Us Section ####
  - The About Us section will allow the user to read about who the business is and what they do. 
  - The user will see images that illustrate the business concept. This should encourage the user to get in touch for a business enquiry. 
  - At the bottom there are call-to-action links that direct the user to the gallery and contact pages where they can get more information.

![About Section](assets/documentation/readme-about-us-section.png)

#### The Footer ####
  - The footer section is very simple. It is a strip with the same background color and font color as the header, and contains a copyright disclaimer. 
  - The footer is still valuable to the user as it lets them know they have reached the bottom of the page, and acts as a counterbalance to the header.

![Footer](assets/documentation/readme-footer.PNG)

#### The Gallery Page ####
  - The gallery is fully responsive and will provide the user with images to see more of the previous projects that the business has done. 
  - This section is valuable to the user as they will be able to easily identify the type of buildings that the business owner has designed in the past. 

![Gallery](assets/documentation/readme-gallery.png)

#### The Contact Page ####
  - The contact page will allow the user to contact the website owner with a business enquiry or any questions they may have. The user will be able to freely write their message in a text area. The user will be required to submit their first name, last name, and email address.
  - An asterisk indicates to the user which input fields are required.
  - This page provides value to the user through interaction with the website, and as a means to get in touch in a quick and convenient way.

![Contact Page](assets/documentation/readme-contact.png)

#### The Form Feedback Page ####
- The form feedback page appears after a user correctly fills out the contact form and clicks the submit button.
- The header and navigation menu remains at the top of the page for easy navigation, and a link is provided to take the user back to the previous page.
- This page provides value to the user as feedback to let them know the form was successfully submitted, and allows them to easily navigate back to the other pages.

![Form Feedback Page](assets/documentation/readme-form-feedback.png)

### Future Features ###

- Image gallery carousel, or the ability to enlarge images by clicking on them
- Replace call-to-action links with more visible buttons on home page
- Call-to-action links or buttons on the gallery page
- Frequently Asked Questions
- Social media links in the footer
- Background image on the contact page and form feedback page, and/or a nicer background color
- More detailed information in the About Us section about how the business works
- More input fields in the contact form to get more detailed information from the customer

- - - -
## Wireframes ##

<details>
  <summary>Desktop wirefames</summary>
  <p>Index Page:</p>
    <img src="assets/documentation/wireframe-index-desktop.png">
  <p>Gallery Page:</p>
    <img src="assets/documentation/wireframe-gallery-desktop.png">
  <p>Contact Page:</p>
    <img src="assets/documentation/wireframe-contact-desktop.png">
  <p>Form Feedback Page:</p>
    <img src="assets/documentation/wireframe-form-feedback-desktop.png">
</details>

<details>
  <summary>Mobile wirefames</summary>
  <p>Index Page:</p>
    <img src="assets/documentation/wireframe-index-mobile.png">
  <p>Gallery Page:</p>
    <img src="assets/documentation/wireframe-gallery-mobile.png">
  <p>Contact Page:</p>
    <img src="assets/documentation/wireframe-contact-mobile.png">
  <p>Form Feedback Page:</p>
    <img src="assets/documentation/wireframe-form-feedback-mobile.png">
</details>

Disclaimer: The final project may look different due to changes during development.

- - - -
## Technology ##

Technologies used for this project are HTML5 and CSS3.

- - - -
## Testing ##

- During development the site was constantly tested and debugged using Chrome DevTools.
- All links on the website, including the navigation links and the logo, have been tested to make sure they take the user to the right page when clicked.
- I have tested that the contact form works as intended; all fields with an asterisk are required to be filled in, the email input only accepts an email, and the submit button takes the user to the form feedback page.

### Responsiveness and Devices ###

- All pages have been thoroughly tested for screen sizes from 280px wide (Galaxy Fold size) and up, using the device toolbar in Google Chrome DevTools.
- After deployment the site has been tested and confirmed to work with Chrome, Edge and Firefox on Windows desktop, Chrome and Safari on a 13-inch MacBook Pro, Chrome and standard browser on an Android phone, and Safari on iPhone 13, both with vertical and horizontal screen orientation on the mobile devices.
- The site is fully responsive on all tested screen sizes and no images are overly pixelated or stretched. There is no unwanted horizontal scroll, and no elements overlap.

### Code Validation ###

- **HTML**: No errors or warnings were shown when checking code with the official [W3C HTML validator](https://validator.w3.org/)
- **CSS**: No errors were found when checking code with the official [W3C (Jigsaw) CSS validator](https://jigsaw.w3.org/css-validator/)

### Accessibility ###

- All pages have been tested with Lighthouse in Chrome DevTools and have a high accessibility score.

<details>
  <summary>Lighthouse Screenshots</summary>
  <p>Index Page:</p>
    <img src="assets/documentation/lighthouse-index.png">
  <p>Gallery Page:</p>
    <img src="assets/documentation/lighthouse-gallery.png">
  <p>Contact Page:</p>
    <img src="assets/documentation/lighthouse-contact.png">
  <p>Form Feedback Page:</p>
    <img src="assets/documentation/lighthouse-form-feedback.png">
</details>

- All pages have been tested with the [Wave](https://wave.webaim.org/) accessibility evaluation tool with no errors.
- The alerts point out that two adjacent links go to the same URL (i.e. the logo and Home button in the navbar), and that some images have long alternative text.

<details>
  <summary>Wave Screenshots</summary>
  <p>Index Page:</p>
    <img src="assets/documentation/wave-index.png">
  <p>Gallery Page:</p>
    <img src="assets/documentation/wave-gallery.png">
  <p>Contact Page:</p>
    <img src="assets/documentation/wave-contact.png">
  <p>Form Feedback Page:</p>
    <img src="assets/documentation/wave-form-feedback.png">
</details>

### Unfixed Bugs ###

- There are no known unfixed bugs at the point of final deployment.

- - - -
## Deployment ##

The live site can be viewed here: https://lmflolo.github.io/pp1/

### Gitpod ###

The site was developed using the Gitpod IDE. All code and files were saved and submitted to the GitHub repo with git version control by using the Git commands 'git add', 'git commit' and 'git push'.

### GitHub Pages ###

The site was deployed using GitHub Pages. The steps to deploy are as follows: 
1. From the GitHub repository, navigate to the Settings tab at the far right of the top menu
2. Then navigate to the Pages tab in the left-side menu
3. From the Source section drop-down menu, make sure 'Deploy from a branch' is selected
4. Select 'main' and '/ (root)' from the Branch drop-down menus, then click Save
5. After giving the site a few minutes to build, refresh the page and the link for the live site will appear at the top of the GitHub Pages tab

- - - -
## Credits ##

### Content ###

- This README document is based on the Code Institute [README template](https://github.com/Code-Institute-Solutions/readme-template).

- [Love Running](https://github.com/lmflolo/love-running):
  - Inspiration for layout and design, reference on how to approach this project.
  - Used and adapted HTML and CSS code for the header (logo and navigation menu), hero section and contact form.
  - Reference for media queries.
  - Used code for removing default margin, padding and border on all HTML elements.

- Instructions on how to make the fixed header were found on [W3Schools](https://www.w3schools.com/howto/howto_css_fixed_menu.asp)
- The favicons were obtained from [favicon.io](https://favicon.io/)

- I learned how to implement the form feedback page by reading previous posts from David Bowers in the Code Institute Slack community, and by looking at his [Portfolio Project 1 site](https://pp1.dev-bowers.com/contact.html).

- I have used the following Code Institute student project sites, as well as their GitHub repositories, as inspiration to see what a high quality project looks like. This includes inspiration for layout and design, fonts, how to implement code, how to comment the code, what to write in the README, etc.
  - Batala Bangor: [live site](https://emmahewson.github.io/mp1_batala_bangor/), [GitHub repo](https://github.com/emmahewson/mp1_batala_bangor)
  - MadMiners SMP: [live site](https://madmaddie81.github.io/mad-miners-smp/index.html), [GitHub repo](https://github.com/MadMaddie81/mad-miners-smp)

### Media ###

- All images used on this website were downloaded from [Unsplash](https://unsplash.com/)