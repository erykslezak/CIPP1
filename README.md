# JMN Suppression

![picture of responsive site from 'am i responsive?'](responsive.JPG "Responsive sample")

**[Live site](https://erykslezak.github.io/CIPP1/)**

---

<span id="top"></span>

## Index

- <a href="#context">Context</a>
- <a href="#ux">UX</a>
  - <a href="#ux-stories">User stories</a>
  - <a href="#ux-wireframes">Wireframes</a>
  - <a href="#ux-theme">Theme</a>
- <a href="#features">Features</a>
  - <a href="#features-all">Site wide</a>
  - <a href="#features-pages">Pages</a>
  - <a href="#features-forms">Forms</a>
  - <a href="#features-future">Still to implement</a>
- <a href="#technologies">Technologies Used</a>
- <a href="#testing">Testing</a>
  - <a href="#testing-auto">Automated</a>
  - <a href="#testing-manual">Manual</a>
  - <a href="#testing-responsive">Responsiveness</a>
  - <a href="#testing-unresolved">Unresolved issues</a>
  - <a href="#testing-bugs">Known bugs</a>
- <a href="#deployment">Deployment</a>
- <a href="#credits">Credits</a>

---

<span id="context"></span>

## Context

JMN Suppression is a fire suppression company that designs, install and maintain all type of fire systems but mainly focus on suppression systems. The focus of this project is to bring their services closer to potential customers by providing detailed information on each of the 'our services' pages.

<div align="right"><a style="text-align:right" href="#top">Go to index :arrow_double_up:</a></div>
<span id="ux"></span>

## UX

### Overview

The site is presented in a minimalist but effective way, providing all the information the user would ever need. Users can find out more about the JMN Company, services they provide, products they use and contact them using different forms depending on the users needs.

<span id="ux-stories"></span>

### User stories

### User stories

For ease of reference, the means by which a user's expectations have been met are summarised in the tables below:

| As a **client** I want | How this is achieved                                                                                                                                                           
| :-------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Visitors to be immediately aware of what the product is                                                                                                   | The logo, information on homepage and the picture provided make it immediately clear what the product is.                                                                                                                                                                |
| Visitors to be able to send in their queries through different forms depending of their needs | The three forms that are accessible through the navbar as well as info bar let users choose the way they want to contact the client. <br> The contact, free site survey and quotation forms let client choose who they want to forward submissions to and be able to adjust the forms to their needs without affecting the other ones.                            |                                                                                                                                                           
| A clean, consistent interface which will not confuse visitors                                                                                             | The header consisting of infobar and navbar, footer, page bar with title and breadcrumbs of each page are simple and consistent. The typography, spacing, image styling and colours match together well to give visitors clear readability. All links have consistent visual feedback, including the hover effect on the menu.

| As a **visitor** I want                                                                                                                                                               | How this is achieved                                                                                                                                                                                                                                                                                                                            
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| To learn something about the company and to be able to contact them directly                                                                        | The About Us page is separate from the rest. It is easily accessible through the navbar for those wishing to learn more about the company and what type of other services they provide. <br>The About page includes short description of who JMN are, a link which brings user to contact us page in order for them to get more information if needed and footer provides JMN address if visitor wishes to visit them directly.|
| To be able to find out more about the services, specifically what products is client using for his services.                                                                                   | Hovering over 'Our Services' will give visitor a subnav of 3 other options containing the process of designing, installing and maintaining suppression systems. <br>Products are on a separate page and provides two most commonly used gas systems and most used panel to accompany the system.                                                                                                                                                            
| For it to be immediately clear what the purpose of the site is and what it has to offer. The interface and layout should be clean, with a focus on services. | Aligns with client's expectations 
| To be able to access all information on a range of devices                                                                                                                            | This is addressed in the <a href="#testing-responsive">Responsiveness</a> section below                                                                                                                                                              
| Site and images to be fast to load                                                                                                                           | Reduction of file sizes have been made for the site to load faster. All done without impacting page quality. E                      |

<span id="ux-wireframes"></span>

### Wireframes

The wireframes were successfully converted into a live functioning website, however for mobile the text and images are not ordered as the website/tablet. This to be changed in future.

The full suite of wireframes for **desktop**, **tablet** and **mobile** devices, plus a **sitemap**, can be accessed [here](wireframes/).

### Site theme

Based on the client's brief expectations for the site, a clean, clear and simple aesthetic has been implemented. 

Two fonts with a soft, dynamic style have been used throughout the whole site: [PT Sans](https://fonts.google.com/specimen/PT+Sans) and [Antic Slab](https://fonts.google.com/specimen/Antic+Slab).

The site theme was chosen based on client's logo that was provided, bright colors were decided to be used. The infobar being #4da558 to complement the logo, for footer decision was to go more dark to not have completely bright site which in that case we have used two darker shades being #363839 and #282A2B for copyright part of footer. The text has different colors depending on it's background, the same goes for links across the site.

<div align="right"><a style="text-align:right" href="#top">Go to index :arrow_double_up:</a></div>

<span id="features"></span>

## Features

<span id="features-all"></span>

### Sitewide

**1. Infobar**

- Infobar has been divided into two sections to keep contact and forms separate.
- Contact side of infobar is linked to both phone and email, for either straight mobile call or mail being created in default mail app.
- Quote side of infobar is linked to different forms for visitor to contact the right department of client's company.
- For mobile browsing the infobar size has been increased vertically keeping all options for visitor useable.

![Infobar](features/infobar.JPG)

**2. Navbar**

- Design has been modified to vertical menu for mobile browsing.
- Dropdown menu has been added to separate services pages and is accessible from all devices.
- Logo's size is decreased for mobile and subnav menu position moved when hovered over the logo.
- Hover effect on all menu selections is bright green matching infobar. Transition has been implemented to add some animations onto site.
- Bottom border of navbar has been created to separate all pages from it with a subtle grey color.

![Navbar](features/navbar.JPG)

**3. Footer**

- Footer has been divided into 3 sections which consist of logo, menu, location and contact details.
- Separate section of footer has been added for copyright.
- Footer is always positioned at the bottom of the site. For mobile footer has been increased vertically keeping all sections of it ordered.
- Menu as contact details are both linked bringing back the bright green colors of infobar.

![Footer](features/footer.JPG)

<span id="features-pages"></span>

### Pages

- All pages across the site have fixed width.
- A section bar has been added that divides header and page. Home page being only one without it.
- Section bar consits of pages title and breadcrumbs aligned left and right.

![Section bar](features/sectionbar.JPG)

**4. Home page**

- An imagee of gas bottles to let visitor know straight away what client's services are.
- Text introducing JMN Suppression to the visitor.

**5. About Us page**

- More information about client's company such as their history, partners and more.
- Link to contact us page.

**6. Design page**

- Page consits of information on how the designing process of fire suppression works describing steps taken.

**7. Installation & Maintenance page**

- An image showing requirements in order to have a safety site.
- FAQ style page describing different type of suppression systems, information regarding commissioning and installation.

**8. Room Integrity Testing page**

- FAQ style page with images beside the paragraphs.
- Information on what type of suppression systems needs that sort of procedure and why is it important.

**9. Our Products page**

- Gives visitor insight of what is our most commonly used system and type of gas.
- Images as well as product names are linked to the manufacturers.

**10. Contact Us page**

- Top of page is divided into two sections. Left containing client's logo and address with contact details. Right containing embedded google maps with address of client's office.
- Contact Us form.

![Contact page](features/contact-page.JPG)

![Contact form](features/contact-form.JPG)

<span id="features-forms"></span>

### Forms

**11. Free Site Survey form**

- Page with a form for visitors to complete in order for client's company to book in a free site survey.

**12. Quotation form**

- Page with a form for visitors to complete in order for client's company to give potentialy a new customer quotation for his/her site.

<span id="features-future"></span>

### Features left to implement

- Online payment form

  _Area has been designed in infobar. Form yet to bo completed with possible stripe integration._

- 'Hamburger' menu for mobile

  _As of now, mobile has a vertical style menu with a sub nav menu displaying over logo if 'our services' section has been hovered over._

- Order of divs on certain pages

  _e.g. For mobile some picture are above the mentioned text and are meant to be under._

- Live chat integration

  _A pop up live chat notification could possibly bring more customers in as visitor would get their answers straight away._

- 404 Page

  _404 Page to redirect if page has not been found._

- Thank you page **THAT IS NOW DONE**

  _Page when form has successfuly been submited.

<div align="right"><a style="text-align:right" href="#top">Go to index :arrow_double_up:</a></div>

<span id="technologies"></span>

## Technologies Used

### Languages

- HTML
- CSS

### Project management

- [GitHub](https://github.com/) - Version control and deployment
- [GitPod](https://gitpod.io/) - IDE used to code the site
- [Balsamiq](https://balsamiq.com/wireframes/) - Wireframe creation app

### Style and theme

- [Font Awesome](https://fontawesome.com/) - Icon used for menu in footer
- [Google Fonts](https://fonts.google.com/) - PT Sans and Antic Slab fonts
- [Free Formatter](https://www.freeformatter.com/html-formatter.html) - Used for formatting HTML code

### Image manipulation

- [ImageOptim](https://imageoptim.com/mac) - App used for cropping and reducing file size of images

### Online resources

- [Stack Overflow](https://stackoverflow.com/)
- [W3 Schools](https://www.w3schools.com/)

<div align="right"><a style="text-align:right" href="#top">Go to index :arrow_double_up:</a></div>

<span id="testing"></span>

## Testing

<span id="testing-auto"></span>

### Automated testing

- [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools) - Ran an audit using lighthouse on all pages for both desktop and mobile.

Summary and Scores:

- All pages have accessibility scores lowered due to `Background and foreground colors do not have a sufficient contrast ratio.`.
- Pages containing section bar have also accessibility scores lowered due to breadcrumbs heading being not in a sequentially-descending order.
- Few mobile issues such as tag `a.active` overlaps other menu causing lower SEO score.
- Some images also do not have explicit width and height and display with incorrect aspect ratio.
- Performance also throws errors due to images being png/jpeg.

</details>

<br>

<details>

### Home:
![Home-Desktop](audit/desktop/index-desktop.png "Home page desktop score")
### About Us:
![About-Desktop](audit/desktop/about-desktop.png "About page desktop score")
### Design:
![Design-Desktop](audit/desktop/design-desktop.png "Design page desktop score")
### Installation & Maintenance:
![Installation-Desktop](audit/desktop/installation-desktop.png "Installation page desktop score")
### Room Integrity Testing:
![Integrity-Desktop](audit/desktop/integrity-desktop.png "Integrity page desktop score")
### Our Products:
![Products-Desktop](audit/desktop/products-desktop.png "Products page desktop score")
### Contact Us:
![Contact-Desktop](audit/desktop/contact-desktop.png "Contact page desktop score")
### Free Site Survey:
![Survey-Desktop](audit/desktop/survey-desktop.png "Survey page desktop score")
### Quotation Details:
![Quotation-Desktop](audit/desktop/quotation-desktop.png "Quotation page desktop score")

<summary>Desktop scores</summary>

</details>

<br>

<details>

### Home:
![Home-Mobile](audit/mobile/index-mobile.png "Home page mobile score")
### About Us:
![About-Mobile](audit/mobile/about-mobile.png "About page mobile score")
### Design:
![Design-Mobile](audit/mobile/design-mobile.png "Design page mobile score")
### Installation & Maintenance:
![Installation-Mobile](audit/mobile/installation-mobile.png "Installation page mobile score")
### Room Integrity Testing:
![Integrity-Mobile](audit/mobile/integrity-mobile.png "Integrity page mobile score")
### Our Products:
![Products-Mobile](audit/mobile/products-mobile.png "Products page mobile score")
### Contact Us:
![Contact-Mobile](audit/mobile/contact-mobile.png "Contact page mobile score")
### Free Site Survey:
![Survey-Mobile](audit/mobile/survey-mobile.png "Survey page mobile score")
### Quotation Details:
![Quotation-Mobile](audit/mobile/quotation-mobile.png "Quotation page mobile score")

<summary>Mobile scores</summary>

</details>

<br>

- [W3C - HTML](https://validator.w3.org/) - No errors or warnings detected - **PASS**

- [W3C - CSS](https://jigsaw.w3.org/css-validator/) - No errors or warnings detected - **PASS**

- [CSS Lint](http://csslint.net/) - CSS lint found 0 errors and 105 warnings. - **PASS**
  - Don't use IDs in selectors

  <span id="testing-manual"></span>

### Manual testing

The following cases were carried out on all pages, both desktop and mobile to ensure that the site is functioning as expected:
**ALL PASSED**

**1. Info bar**

- check that pressing the contact number want to call straight away.
- check that pressing on email will want to open default mail app.
- check if links bring you to correct forms.

**2. Nav bar**

- check if all links in navbar bring you to correct page.
- check if sub nav section of 'our services' display correctly.
- check if logo is linked to bring you back to home page.
- check if active and current styling is applied correctly.

**3. Footer**

- check that logo is linked to bring you back to home page.
- check if all menu links are linked to bring you to correct pages.
- check if the styling applies to all the links.
- check if pressing on mobile / email wants to open default app in order to contact client.

**3. Home**

- check that image resize correctly depending on width of display.

**4. About Us**

- check if pressing 'contact us' at the end of section brings you to contact page.
- check that styling is applied to `tag a` has current and hover styling.

**5. Design**

- check that images resize correctly depending on width of display.

**6. Installation & Maintenance**

- check that image resize correctly depending on width of display.
- check that the external link has styling for current and hover.
- check that the external link also has correct rel and target attribute.

**7. Room Integrity Testing**

- check that images resize correctly depending on width of display.

**8. Our Products**

- check that the images and links bring you to external pages.
  - check that they have the correct attributes set.
  - check that the links have correct styling applied.
- check that images resize correctly depending on width of display.

**9. Contact Us**

- check that logo will bring you back to home page.
- check if phone number / email will open in the default app.
- check if google maps resizes to correct width depending on display.
- following form testing has been done
  - check that form can only be submited once required details are filled in.
  - check that user will get an error if fields are left blank.
  - check that email address needs to be in correct format.

**10. Free Site Survey & Quotation Request**

- following form testing has been done
  - check that form can only be submited once required details are filled in.
  - check that user will get an error if fields are left blank.
  - check that email address needs to be in correct format.

<span id="testing-responsive"></span>

### Responsiveness

The site has been designed with a mobile and tablet browsing in mind. It has been tested through all stages of development using [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools).
Many different media queries have been created to make sure all information and images will be responsive.

Following issues emerged but has been addressed and solved

- Info bar not resizing correctly.
  - `height` has been changed depending on display size to extend the info bar.
- Logo being fixed size covering too much for smaller screens.
  - Reduced the `height` and `width`.
- Nav menu wasn't optimized for mobile and was going off screen.
  - It is now vertical for lower screen devices.
- Sub nav menu was covering the existing vertical menu.
  - It has been moved to right side of main nav bar and left covering logo for smaller screen devices.
- Footer wasn't going vertical the smaller the screen was.
  - It has been changed making the footer fully vertical with everything aligned.

#### Browsers

Tested on the following:

- Chrome
- Edge
- Opera
- Safari 

#### Screen sizes

Tested with Chrome DevTools using profiles for:

- BlackBerry Z30
- Galaxy Note 3
- Galaxy S3
- Moto G4
- Nexus 7
- iPad Mini
- iPhone 4
- Galaxy S5
- Pixel 2
- Pixel 2 XL
- iPhone 5 SE
- iPhone 6/7/8
- iPhone 6/7/8 Plus
- iPhone X
- iPad
- iPad Pro
- Surface Pro
- Nest Hub
- Nest Hub Max
- Mobile S
- Mobile M
- Mobile L
- Tablet
- Laptop
- Laptop L

Real world testing on:

- iPhone 11
- iPhone XR
- MacBook Pro 16" 2021

<span id="testing-unresolved"></span>

#### Unresolved Issues

- For screens of 320px/
  - Fix infobar alignment as it is off.

<span id="testing-bugs"></span>

### Known bugs

- None at present

<div align="right"><a style="text-align:right" href="#top">Go to index :arrow_double_up:</a></div>

<span id="deployment"></span>

## Deployment

There is just one branch of this project and the deployed version of this site is the most current version in the repository.

### How to deploy

To deploy this page to GitHub Pages from its [GitHub repository](https://github.com/erykslezak/CIPP1) the following steps were taken:

- Log into GitHub and locate the repository.
- At the top find and press the **settings** option
- On the left side you will see multiple options. Find the option called **Pages** and click on it.
- Under **Source** select the branch **main**, make sure that **root** has also been selected and then press **Save**.
- The site is now published. It may take a while for it to be available though.
- The site URL is just above the **Source** section visible over green background.

<div align="right"><a style="text-align:right" href="#top">Go to index :arrow_double_up:</a></div>

<span id="credits"></span>

## Credits

- [Stack Overflow](https://stackoverflow.com/) - Many issues I have googled brought me there as other coders were in similar situations. 
- [DeliciousThemes](https://deliciousthemes.com/create-a-drop-down-navigation-menu-with-html5-and-css3/) - Create a Drop-Down Navigation Menu with HTML5 and CSS3
- [Stack Overflow](https://stackoverflow.com/questions/59220029/making-google-maps-responsive-and-resizing) - Fix google maps responsiveness and resizing.
- [DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-add-a-favicon-to-your-website-with-html) - How to add favicon.
- [W3 Schools](https://www.w3schools.com/) - Best resource when it comes to attributes etc. Used it many times and without it I would be more confused.
- [Github](https://github.com/Edb83) - README Layout
- [Mentor]() - I wanna thank my mentor Gerry for support and input.
- [Google](https://www.google.com/) - Ammm yes.

## Content

- [Ansul](https://www.ansul.com/en/us/pages/ProductDetail.aspx?productdetail=INERGEN+Systems+%E2%80%93+150-Bar+%26+200-Bar) - Inergen description and image
- [Kentec](https://kentec.co.uk/product/sigma-xt/) - Kentec description and image
- [Koorsen](https://blog.koorsen.com/what-is-novec-1230) - Novec1320 description and image
- [JMN Fire Alarms](https://www.jmnfirealarms.ie/) - Home, About us, Room Integrity Testing and Forms taken from client's website
- [Fire Magazine](https://www.fire-magazine.com/fire-suppression-system-installation-and-maintenance-a-complete-guide) - Installation & Maintenance page
- [Buildings](https://www.buildings.com/articles/35584/fire-protection-system-design) - Design page

<div align="right"><a style="text-align:right" href="#top">Go to index :arrow_double_up:</a></div>