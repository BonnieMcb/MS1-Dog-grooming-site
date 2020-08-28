# Happy Dogs

## Code Institute Milestone Project 1

This website for a fictional company is created for educational purposes only.

![Happy Dogs Responsive](/assets/images/responsivedog.png)    
    
Happy Dogs is a website for a fictional dog grooming business that offers various salon services for dogs. Inspiration for the idea came from a family member who is working on creating such a business for themselves. 
The brief for this first Milestone project was to make a responsive and static website with a minimum of three pages using HTML5 and CSS3. It is the first of four projects as part of the Full Stack Web Development Program at The Code Institute. 

[Click here to view the project live.](https://bonniemcb.github.io/MS1-Dog-grooming-site/index.html)

## UX (User Experience)

### Goals

In terms of my fictional business, the goal was to:
 - Make a user-friendly website to attract new customers.
 - Inform potential customers of the range of services provided while guiding them to book an appointment.
 - Facilitate the booking process.
 - Allow the business to be located via *Google maps*.
 - Ensure the website is able to be viewed on devices and screens of all sizes.


### User Stories

1. As a potential customer, I want to see services on offer and get a feel for the company.
2. As a potential customer who has had a bad experience at a competitor, I want to know who the groomers are and if they are reliable.
3. As a potential user, I browse websites on my mobile phone and want to have a good experience and be able to find and view the information I want.
4. As a potential user I want to know if the business is easy to get to.
5. As a potential customer I want to know what other people say about this business.
6. As a returning customer I want to be reminded of the services available and be able to make a booking easily.

### Design

I wanted the style of the website to feel professional without being too fancy, approachable without being too cutesy. I believe 'modern' would describe the style. I used this to inform my choices of colours, images and fonts. 

For the sub-pages I used the rule of thirds, by giving the main content two-thirds of the page, on the right hand side. The left third is used for a page heading, brief description and an image. 

#### Colour Palette

I used [coolors.co](https://coolors.co) to choose a suite of complementary colours for my website. Initially I had imagined a light turquiose in my mock ups but this looked too medical and I did not want the site to be mistaken for a vet instead of a grooming salon. 

https://coolors.co/1a535c-4ecdc4-f7fff7-ff6b6b-ffe66d

- ![#1A535C](https://placehold.it/15/1A535C/000000?text=+) #1A535C 'Midnight Green Eagle Green'
- ![#F7FFF7](https://placehold.it/15/F7FFF7/000000?text=+) #F7FFF7 'Mint Cream'
- ![#FF6B6B](https://placehold.it/15/FF6B6B/000000?text=+) #FF6B6B 'Bittersweet' 
- ![#FFE66D](https://placehold.it/15/FFE66D/000000?text=+) #FFE66D 'Naples Yellow'

#### Typography

I did not want to make any bold statements with the typography. The main aim was to make the website readable and attractive. I chose the Montserrat font throughout the whole website with Sans Serif as the fallback font in case Montserrat does not load correctly.

#### Imagery

I selected royalty-free images, and attempted to match the website's colour scheme.

#### Wireframes

I did not create the website fully in a design tool only to then create it again in HTML/CSS. Instead I used design tools to mock up rough versions of my site, including design and colour combinations. Since this was a solo project, and my first website created unaided, I was mindful of spending too much time creating perfectly responsive design mockups. As such, I was happy keeping some information in my head rather than drawing out the exact version of the final website. On collabarative projects, however, I would have a more finalised version of the website in a design tool. 

[Wireframes, in Figma](https://www.figma.com/file/hvVtprtZ2O76Y6mLTYofpp/MS1-Dog-Grooming-Website?node-id=0%3A1)

### Features

#### Existing Features

##### Consistent Features across all pages

- Always-visible navigation bar with the *Happy Dogs* logo on the left (linking to index.html) and links to the sub-pages on the right. 
- Navigation bar changes to a hamburger button on small screens.
- Sticky footer with links to social media.
- A 'Back to Top' button that pops up on all pages once the user has scrolled more than 100px.

##### Home

- An aesthetically-pleasing hero image that captures the user's attention.
- Three sections aiming to give the user confidence that this is a reliable and quality company.
- Testimonials, displayed in a carousel format with a bright contrasting colour to grab the user's attention.

##### Services

- The various services that are available are listed on the right two-thirds of the page. 
- Pictograms as well as text are used to inform the user of what each different service entails.
- Each service has a 'Book Now' call-to-action button that links to the Bookings page.

##### Bookings 

- A short booking form takes up the right two-thirds of the page. Some fields are required in order to submit the form.
- The phone number is also listed near the top of the page (as well as the footer) for those who prefer to call.

##### Find Us

- The left third of the page has a short description to give confidence to the user about getting to the location.
- The right side of the page contains an embedded Google map that will take the user to the Google Maps website in a different window when clicked.

#### Features To Be Implemented

- Pressing the 'Book Now' button under a particular service on the Services page should pre-select that service from the drop-down menu.
- A Gallery page with before and after images of styled dogs.
- A log in section for customers to make booking even easier. This would store their personal information so they wouldn't have to fill in the booking form. Additional features such as customer loyalty points could be implemented.


## Technologies Used

#### Languages Used
- HTML5
- CSS3

#### Frameworks, Libraries & Programs Used

1. [Bootstrap 4.5.2 :](https://getbootstrap.com/docs/4.5/getting-started/introduction/)
    - Bootstrap was used in order to ensure easy responsiveness of the site.
2. [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the 'Montserrat' font into the style.css file which is used on all pages throughout the project.
3. [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.
4. [jQuery:](https://jquery.com/)
    - jQuery is needed by Bootstrap for the navbar, carousel, and the Back to Top button.
5. [Gitpod](https://www.gitpod.io/)
    - Gitpod was the environment in which the site was created, using the terminal to commit to Git and Push to GitHub.
6. [Figma](https://www.figma.com/) 
    - Figma was used to create wireframes and aid design and layout decisions.


## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there was no invalid HTML or CSS.

-   [W3C Markup Validator](https://validator.w3.org/) Fully passed, no errors or warnings
-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) My CSS has no errors or warnings, but Bootstrap CSS intentionally does.

### Testing User Stories

#### 1. As a potential customer, I want to see services on offer and get a feel for the company.
- The user is presented with a high-contrast, easily-readable navigation bar with links to other pages on the site. 
- The eye is also drawn down to the hero image, with contrasting text clarifying what the company provides in just a few words.
- The user can then scroll down to read more about the company, with “What we do” visible in tablet and mobile to invite scrolling. 
- A ‘Back to top’ button is provided on all pages once the user scrolls a certain amount, and the nav bar is stuck to the top of the screen as you scroll, so the user never gets stuck at the bottom of a page with nowhere to go.
#### 2. As a potential customer who has had a bad experience at a competitor, I want to know who the groomers are and if they are reliable.
- A description of the team and their qualifications is provided on the home page, immediately followed by testimonials and links to social media for further investigation of the company’s reputation.
#### 3. As a potential user, I browse websites on my mobile phone and want to have a good experience and be able to find and view the information I want.
- The website is responsive on smaller screens with the result being an aesthetically-pleasing and functional site on all screen sizes.
#### 4. As a potential customer I want to know if this place is easy to get to.
- In addition to the address and contact information in the footer, there is also a page with an embedded google map, and parking/public transport information.
#### 5. As a potential customer I want to know what other people say about this business.
Testimonials are found on the home page, and the links to social media are visible on the high-contrast footer on every page.
#### 6. As a returning or potential customer I want to be reminded of the services available and be able to make a booking easily.
- The services are laid out in a clear and clean manner, with a text description, as well as pictograms to provide information at a glance. A ‘Book Now’ button under every different service links to the Bookings page.
- The Bookings page has a short form with required fields, as well as the phone number at the top of the page for those who prefer to call.
- The contact information for phone and email are also provided in the footer on every page.


### Further Testing

-   The website was tested on Google Chrome, Mozilla Firefox and Microsoft Edge browsers.
-   The website was viewed, using Chrome Developer Tools, on a variety of devices such as Desktop, Laptop, iPhone7, iPhone 8 & iPhoneX.
-   A large amount of testing was done to ensure that all pages were linking correctly.
-   Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

### Known Bugs

-   

## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
    - Alternatively Click [Here](https://raw.githubusercontent.com/) for a GIF demonstrating the process starting from Step 2.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site [link](https://github.com) in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/BonnieMcb/MS1-Dog-grooming-site)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/BonnieMcb/MS1-Dog-grooming-site)
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash or Terminal
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.
7. Press Enter. Your local clone will be created.


Click [Here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) to retrieve pictures for some of the buttons and more detailed explanations of the above process.

## Credits

### Code

- The Bootstrap Library and documentation version 4.5.2 was used extensively throughout the project in order to ensure responsiveness across the site, and also to implement certain elements like the card and carousel features.

- Stack Overflow was invaluable, in particular for fixing certain Bootstrap issues.

- Google Maps was used to choose a fictional location and their iframe code was copied to the website in order to embed the map.

- The 'Back to Top' button was based on the code at [codepen.io](https://codepen.io/matthewcain/pen/ZepbeR).


### Content

-   All content was written by the developer.

### Media

Images were used from the following image sharing sites: 

- [Hero image](https://unsplash.com/photos/915UJQaxtrk)
- [Sarah](https://pixabay.com/photos/pup-dog-pretty-girl-christmas-dog-1926897/)
- [Danny](https://pixabay.com/photos/people-man-boy-animal-dog-puppy-2589544/)
- [Testimonial 1](https://www.flickr.com/photos/thomashawk/49270387811/)
- [Testimonial 2](http://www.flickr.com/photos/75885098@N05/49786041748) photo credit: Bennilover
- [Testimonial 3](http://www.flickr.com/photos/14838182@N00/7446546618) photo credit: Мaistora
- [Testimonial 4](https://pixabay.com/photos/adorable-animal-dog-cheerful-cute-3344414/)
- [Services](https://pixabay.com/photos/dog-dalmatians-pet-dog-breed-1020790/)
- [Bookings](http://www.flickr.com/photos/29454428@N08/3210838977) photo credit: State Library of New South Wales collection
- [Find Us](https://pixabay.com/photos/nose-dog-black-pet-the-muzzle-697697/)


### Acknowledgements

-   My Mentor for continuous helpful feedback.

-   My partner Ben for invaluable feedback and endless cups of tea.








