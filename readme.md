![readme-logo](https://user-images.githubusercontent.com/55837085/79745415-2576c200-8300-11ea-88f4-068e556fdbea.jpg)
# Where Next?
Where Next is a holiday planner which had been designed to make your job easy and to help you decide where you want to visit next,
we do this by asking our user to pick a country from the list and type in a location within that country (e.g. UK, London) and once that has been selected. We filter the place into three categories:
- Hotels
- Activities
- Bars/Restaurants
You can pick between these three filters, and the website will then filter your desired location for what you've searched so either hotels, Activities or bars & Restaurants.

## UX:

### User stories
- As a frequent traveller, I like to be able to research my destination first and find the best hotel.

- As an adrenaline seeker, I want to be able to research what activities I can find in the area.

### Strategy
My goal on this website is to keep it simple and easy to use while giving the user all the information they need.

### Scope
For the users, I want to be able to provide them with as many options as possible and to help them decide on their next holiday destination.

### Structure
I wanted to let the user filter the options, so they're precise, e.g. search London, UK for hotels.

### Skeleton

![wireframe-ml2](https://user-images.githubusercontent.com/55837085/79775268-e78f9300-832b-11ea-9776-86efa7b5b208.png)

### Surface
The colour scheme is grey and white to give the website a minimal look.

### Technologies
HTML
CSS
JAVASCRIPT
Bootstrap (4.4.1)
Google Maps/places api


##Features
The features of this website are:
- hotel, restaurant and attractions filtering
- responsive Maps
- when selecting the country, you will only see results (cities) in that country
- information about an establishment, e.g. hotel
- reviews of an establishment

### Features Left to Implement
Features i would like to implement in the future:
- Increase the information displayed to the user about an establishment
- add more countries
- increase usability

## Testing
The employer and recruiter user story achieved the intended outcome of providing them with a showcase of myself and my work. In the about me section, they can read a bit about my background, and if they're viewing on a desktop, the background of this section is a photo of me. They are able to see my showcased projects via the project cards in the "Work" section. They can view both the live version and the GitHub repository by clicking on the Font Awesome icons. They are also able to view my social media profiles via clicking on the icons in the footer. They are also able to download my CV by either clicking on CV in the navbar dropdown, or by clicking on the document icon in the footer.

If you try to submit the contact form with an invalid email address, there will be an error noting the invalid email address. Furthermore, the 'required' attribute is added to the 'name,' 'email,' and 'message' fields, so if those fields are not filled in, the form will not submit. If all field are valid, the page will reload. If an employer or recruiter is interested in contacting me, they will have to fill out all fields in order for the form to go through.

All links will open in a new tab using 'target="_blank"' and the CV will download to your default folder for downloads on click using the 'download' attribute. All links have been manually tested to ensure that they are pointing to the correct destination.

By clicking on the links in the navbar, the scrollSpy effect will work regardless of whether or not you're viewing the sections in the same order they are listed in the dropdown navbar.

This site was tested across multiple browsers (Chrome, Safari, Internet Explorer, FireFox) and on multiple mobile devices (iPhone 4, 5, 7: Chrome and Safari, iPad, Samsung Galaxy) to ensure compatibility and responsiveness. During the testing phase, I realized that background-attachment: fixed was not compatible with iOS browsers. On Chrome and Safari in iOS, the background photos appeared zoomed-in and blurry. To fix this, the background-attachment: scroll property value was added in a media query.

## Deployment
The website was deployed using GitHub pages to do this all I had to do was activate google pages and point the source to the master branch.

## Credits

### Content
Information about the countries such as cities and establishments are from the google maps API

### Media
The logo was created by me
All media regarding Google is from the Google Maps API

### Acknowledgements
I gained inspiration for my project from:
- Tui
