# DJ Colors
This website is for a well known DJ Group called Colors. They wanted a website that reflected their brand image, modern design with useful information.
# UX - Single Page
With that in mind, I decided to go with a responsive modern mobile-first approach, single page design. With a well-combined colour theme that reflected their image.

### Wireframes
* [Mobile-First Approach](https://tomost2019.github.io/dj-colors/assets/wireframes/mobilefirst.png)
* [Desktop](https://tomost2019.github.io/dj-colors/assets/wireframes/desktop.png)

#### Who is it for?
Anyone that has a passion for music. Does not matter if they know DJ Colors or not. The website is built to accommodate hardcore and new fans! With easy modern single page design. Responsive mobile-first approach.

#### How?
By creating a modern responsive mobile-first single page design. With useful information and plenty of interaction possibilities with DJ Colors.


### User Stories

1. As a fan of Dj Colors, I want useful information such as Global Tours. I also want to interact with DJ Colors.
2. As a new fan of the music, I want to interact with Dj Colors. Listen to music and connect on social media. 
3. As a possible customer, I want to know how I can book DJ Colors for my own event.

## Technologies Used
* HTML - Skeleton of the website.
* CSS - Custom styling.
* Javascript - Smooth-scroll and scrollspy.
* Bootstrap 4 Framework - Layout and responsiveness.
* Git - Version Control.
* Github - Deployment.
* C9 - Online IDE.

### Features

#### Navbar
The navbar stays on top of the website at all times. Following the user, so they always can access the proper information they want. The design is responsive with soft animation to show the user which section they currently are at on the website.

On mobile devices, the navbar turns into a "hamburger" but with the same useful navigation and soft animations. There is a heartbeat animation effect on the collapse icon showing that the user can interact with it. This occurs at the beginning when the user is landing on the website.

The hamburger is closed when a link is clicked so that the content is always in front of the user.

#### Landing Page
The user lands on a visually pleasing page with a slogan that is meant to wake curiosity to explore more. With a big arrow to point out that the user can continue exploring further down or go directly to DJ Colors social media. The social icons on the footer have a heartbeat animation effect to point it out at the beginning.
#### Music
DJ Colors are well known worldwide and this section is just a handful of their top singles. It is meant for users to easily being able to listen and to decide if they want to continue on to their Spotify page.
#### About Us
This section is a short story of how it all began. With a big picture album that will encourage the user to explore more about DJ Colors on their social media.
#### Global Tour
Global Tour is a smooth popup that immediately presents the Global Tour information that the user wants. It is also showing a clip from youtube from their previous events. Promoting how exciting it is! There is a big "X" showing how the user can exit from the popup.
#### Book Us
The User loves DJ Colors and really want to be able to book them for their own event! That is easily made by clicking "Book Us" that will present itself with a smooth popup and a form with just enough information that DJ Colors needs. A big "X" marks how the user can exit the popup.
#### Footer
The footer acts the same way as the navbar. It is always following the user and it has smooth animations. It is basically a navbar for social media that makes it easy for the user to interact with DJ Colors.

### Implemented Features

* Scrollspy is used from Bootstrap so the website can track where the user is at the webpage and highlight that on the navbar.
* Modals from the Bootstrap framework is used to present useful information to the user.
* The website is using "smooth-scroll" for a smooth visual pleasing UX. 
* The heartbeat animations at the beginning are implemented using animate.css

### Future Development
* Integration with Spotify API at the music section.
* Automated "Book Us" system.
* Webshop for buying Tickets to the Global Tour.
* Photo album in the "About Us" section using Instagram API

## Testing
I did some extensive testing of the website several times. I used Chrome Debugger. I tested the website in Chrome, Firefox, Safari and Edge. The hardware I tested on was PC, iPhone, Android Device and Mac.

In Chrome Debugger I used the responsive method to resize the window to see how everything looked. I also used it for checking how it would look on different mobile devices.

### Testing Client Stories

#### Navbar 
All fans can access information fast and the navbar is always on top.
#### Music
Fans can listen to music and continue to listen on Spotify through the link or footer.
#### About Us
New and old fans can see the latest photos from the events.
#### Global Tour
Quick and useful information when the fans need it.
#### Book Us
Potential customers can easily  book Dj Colors.
#### Footer
The footer is always at the bottom. Providing an easy way to interact on social media with DJ Colors.



### Automated

[HTML Validator W3](https://validator.w3.org)<br>
[W3 CSS Validator](https://jigsaw.w3.org/css-validator/)<br>
[Autiprefixer CSS Validator](https://autoprefixer.github.io/)



### Manual Testing:

<ol>
<li>Navbar
<ol type="I">
  <li>The Logo is working as a home button.</li>
  <li>The navbar is highlighting each section meaning that the scrollspy is working. </li>
  <li>The hamburger menu is working on mobile devices. The menu is collapsed after a link is clicked.</li>
</ol>
</li>
<li>Landing Page
<ol type="I">
    <li>The arrow link is working.</li>
    <li>The animations are working.</li>
</ol>
</li>
<li>Music
<ol type="I">
    <li>The HTML Audio controls are working.</li>
    <li>The link "Visit Spotify for more" is working.</li>
</ol>
</li>
<li>Abot Us: The photo album is working and the buttons for next and previous are working.</li>
</li>
<li>Global Tour: The smooth popup is working and it is showing the iFrame video from youtube.</li>
</li>
<li>Book Us: The form is correctly aligned and the required inputs are working. </li>
</li>
</ol>

### Known Bugs
When clicking on "Global Tour and Book Us" while the user is on the Landing Page the background image seems to be moving when the modal is being activated. This is because the background image is fixed and that there is no scroll in modal mode. 

This bug happens in Chrome and Firefox. 

**Possible solutions:**
* Change the background-attachment to scroll. Side effects: The visual effects of the overall design on the website is affected. 
* Disable scroll for the user on the single page. Side Effects: Poor UX.
* Enable scroll on the modal and set Body padding-right to 0 and !Important. Side effects: The social icons on the footer is getting padding from the modals, making them move. Scrolling is enabled on the website behind the modal.
* Adding custom javascript.

[Read more](https://stackoverflow.com/questions/32675849/screen-zooms-in-when-a-bootstrap-modal-is-opened-on-ios-9-safari)

### Performance
I optimized the images on the website for best performance. I measured the performance using the Chrome Debugger with network and the performance tab.

## Deployment
I deployed this project by using Github Pages:

1. Log into Github
2. Select the DJ-Colors repository
3. Go to Settings > Github Pages
4. Choose: Source > Master branch
5. The Github page is now deployed. Retrive the link and paste it in the description.

*You can also fork the project to get a copy to your Github account. Deploy Github pages as above*

**Run Locally**

[Cloning a repository](https://help.github.com/en/articles/cloning-a-repository)


## Credits
**Research:**

[Github](https://www.github.com)<br>
[Stackoverflow](https://stackoverflow.com)<br>
[CSS-Tricks](https://www.css-tricks.com)<br>
[Bootstrap](https://www.getbootstrap.com)<br>
[W3 Schools](https://www.w3schools.com/)

**Other:**

Code Institute

### Content
All content on this website is written by me.

### Media

[Music](https://www.bensound.com/)<br>
[Images](https://unsplash.com/)<br>
[Background](https://stock.adobe.com/ie/)<br>
[Gifs](https://giphy.com/)

### Acknowledgements

[Animate CSS](https://daneden.github.io/animate.css/)<br> 
[Smooth-scroll](https://github.com/cferdinandi/smooth-scroll)<br> 
[Fontawesome](https://www.fontawesome.com)<br> 
[Flag-icons](https://cdnjs.com/libraries/flag-icon-css)<br> 
[Favicon](https://gauger.io/fonticon/)<br> 
[Fonts](https://fonts.google.com/)

## Disclaimer
This is my first milestone project and the group DJ Colors is not real. The stories and all the content, music and images has no connections. The project is a part of my portfolio. 

