![Readme2](https://user-images.githubusercontent.com/55837085/80528434-d4b13a00-898d-11ea-89e8-116ae799a894.jpg)
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
- HTML
- CSS
- JAVASCRIPT
- Bootstrap (4.4.1)
- Google Maps/places api


## Features
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
This website has been tested using Chrome Devtools and HTML validator, and it was essential making sure the final version matched the wireframe, so Chrome dev tools were run
to check that everything looked right and functioned, once the mistakes had been found, they were fixed and retested to see if they reappear.

The manual tests I ran:

<table>
    <tr>
        <th>Test</th>
        <th>Input</th>
        <th>Expected output</th>
        <th>Output</th>
        <th>Pass?</th>
    </tr>
    <tr>
        <td>Testing to see if the correct country comes up when selected country</td>
        <td>USA</td>
        <td>Cities that are in USA</td>
        <td>Cities that are in USA</td>
        <td>Yes</td>
    </tr>
    <tr>
        <td>Testing to see if the filter changes when a different filter option is clicked</td>
        <td>Change filter</td>
        <td>Filter should change to chosen filter</td>
        <td>Filter Changed</td>
        <td>Yes</td>
    </tr>
</table>

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
