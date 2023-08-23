# Gamlastan Tour

Gamlastan Tour is a web site of a tour guide company of the same name. The company operates different types of tour in the Stockholm old town. The website provides the basic information about tours. It also provides an easy way to reserve tours. The company targets new tourists visiting Stockholm catering different types of tourists to different age group. 

This site targets all sorts of users accessing from different types of devices. The site works seamlessly in laptop, smart phones, and tabs/pads of any size. 

![Screenshot](https://github.com/fokhrun/gamlastan_tours/blob/main/images/screenshots.png)


## Features 

### Design

The user experience of the site is designed based on the following user stories:

1. As a user, I want to navigate to any part of the site without scrolling too much so that I can jump to any part I desire fast 
- It should be supported by a *navigation section* with buttons to jump back and forth to key areas of the site. This section should be sticky to the page. Hence, a user should be able to access the navigation button to go to the top or any other key section of the page wherever in the page she is at the moment. 
2. As a user, I want to learn about whats charming about the tours, so that I can decide if I like the tours or not. 
- It should be supported by a *landing section* with description and images about the tour services. The description should be well articulated, but not too long. There should be images to complement the description and entice the users to join tours. It should also include some high level details of the variety of the tours, so that users can identify the appropriate tour to go.
3. As a user, I want to know about the upcoming tour schedule, so that I can plan my tour fitting my schedule.
- It should be supported by a section for *tour timetables*, which should show upcoming tour dates and time for each type of tour. 
4. As a user, I want to reserve tours fast and without making a mistake while providing my details
- It should be supported by a section to *reserve* where users would be able to fill out a form while being assisted appropriately for different input types.
5. As a user, I want to know about the tour company that allows me to validate whether the tour company can be trusted
- It should supported by a section *About Us* where key information about the tour operator should be provided. 
- It should also be supported by a section *Contact* where key information to reach out to the tour operator should be provided. 

The wireframe below incorporates this design. 

![Wireframe](https://github.com/fokhrun/gamlastan_tours/blob/main/images/wireframe.png)

### Key Features

The site basically has five key features that implements the user stories listed above. 

#### Navigation Bar

Featured on the top part of the site. It includes the site title and buttons to navigate different parts of the site. The buttons are `Home`, `Tours`, `Reserve`, `About`, and `Contact`, which allows to jump to corresponding sections. The navigation bar is sticky. It stays in the same position regardless of wherever users are in the page. 

![Nav Bar](https://github.com/fokhrun/gamlastan_tours/blob/main/images/navigation.png)

#### The landing page image and description

The landing page includes description about the tours. It includes a set of images of the tour locations that tries to provide a visual feeling of the tours. The text is split by the images to make it more tempting.

![Landing Page](https://github.com/fokhrun/gamlastan_tours/blob/main/images/landing_section.png)

#### Tour Timetable

The tour timetable shows the upcoming tour schedules. The timetable includes tour name, tour date, starting time, and expected hours to complete.

![Tours](https://github.com/fokhrun/gamlastan_tours/blob/main/images/tours.png)

#### Reserve Tour

Provides the form to reserve a tour. the form includes four inputs: name, email, phone number, and tour date. Note that there are no multiple tours on the same date, therefore no-additional input necessary for the time selection. The date and phone number inputs include helper information to guide the user to provide inputs in the correct format.

![Reserve](https://github.com/fokhrun/gamlastan_tours/blob/main/images/reserve.png)

#### About Us and Contact Us

Provides a short intro about the company. It also provides links to social media pages.

![About US](https://github.com/fokhrun/gamlastan_tours/blob/main/images/about_us.png)

### Visual Style

The site follows a blue-based theme. The screen is designed to be adjustable on different screen sizes. See the screenshots on different screens above. The title is placed over a slightly darker blue area. The buttons are also placed in the same area. Both the title and the button colors are black. The button texts are black and becomes white over a grey background when hovered. The footer is follows the same slightly darker blue color as the top part of the site. The main content area of the site is light blue.

### Features Left to Implement

- Showing how many spots left to reserve in the reserve form
- Reservation with less clicks/typing
- More images of different types of tours
- Better SEO support

## Bug Needs to be fixed

- Page loading is a bit slow (about 500ms)
- Navigation to sections in the page is a bit off

## Testing 

- We have loaded the sites in different types of devices including Macbook, Windows laptop, IPhone, and Android phones. The text wraps nicely in the landing section seamlessly depending on the size of the screen and the images load appropriately.
- We tested the buttons. It allows to go to desired sections correctly. It takes very little time to move between sections.
- We tested the links, e. g., facebook and instagram links. Each of them opens in a new tab and navigates to appropriate page on when clicked. 
- The forms element displays sufficient visual cues to make it easy to provide correct input. 
- We have tested with other users. In their view, the texts are well-readable, the site is clutter free, and the color palette is engaging. 

### Validator Testing 

- HTML: Initially there were warnings about some syntax errors (about comments) and unclosed tags. Those issues were fixed. Currently it returns no warnings in [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Ffokhrun.github.io%2Fgamlastan_tours%2F)
- CSS: Initially there was a warning regarding incorrect styling attribute. The styling attribute is unused and, hence, removed. 
Currently, there are no warnings in [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Ffokhrun.github.io%2Fgamlastan_tours%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

- Accessibility: Lighthouse inspection gave the score of 100 for accessiblity. Initially, the score was at 97% when text and button colors in the headers and footer sections were not contrasting enough to the background color. Upon choosing the darker color better accessibility score is attained. Therefore, we traded aesthetically pleasing color for improved accessibility. 

## Deployment

The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab.
  - For source, select Deploy from a branch.
  - For branch, choose main.
  - The page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://fokhrun.github.io/gamlastan_tours/ 

## Credits 

### Media

- The image for Gamla Stan has been taken from [pexels](https://www.istockphoto.com/se/foto/aerial-panorama-%C3%B6ver-stockholm-sverige-gm642182274-116549139?utm_campaign=srp_photos_limitedresults&utm_content=https%3A%2F%2Fwww.pexels.com%2Fsearch%2Fgamla%2520stan%2F&utm_medium=affiliate&utm_source=pexels&utm_term=gamla+stan)

- The logos for facebook and instagram has been taken from [iStockImages](https://www.istockphoto.com/se/foto/samling-av-popul%C3%A4ra-sociala-medier-logotyper-tryckt-p%C3%A5-vitt-papper-facebook-instagram-gm1028361154-275672172?phrase=facebook+logo)
