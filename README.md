# Simple Travel Guide

This project focuses on providing the user with general information about food, attractions and events
in a specific city. It aims to inform the user on what they can expect when visiting a selected city, however, 
does not bring focus to specific businesses or locations. The project emphasises the overall **experience** to 
give insight that is vital to the user when making a decision on where to travel. 

## UX

This website is for people searching for inspiration for their next travel adventure, without the overload of 
information that comes with some blogs and/or other travel sites. It aims to provide the user with the general
 atmosphere of a location, rather then "10 Best Places to See in '#'. It gives the user freedom of exploration, 
without leaving them feel like they are obligated to go here or there.  

### User stories

* Hero images on each page intrigue the user and provoke further exploration;
* They are then met with a question of 'where' or 'what', enticing them to interact;
* From the home page the user gets brought to further information about their selected city;
* If their initian selection is not what they are looking for, they can navigate to other cities from the menu
bar;
* From engaging with the information they can choose "Lets Go" and will be brought to an external booking site;
* The home page also encourages for the user to share their experience, that would then be used to further 
develope the website and grow the information (adding destination, updating existing information);
* The user can also subscribe to a Newsletter, for information in any updated content;
* Finally, the user can follow the creator on external platforms such as Facebook, Instagram and/or Twitter;
This project encourages engagemnt and exploration.


### Wireframes

Available at: "wireframes/simple-travel-wireframes.pdf".

## Features

### Existing Features

* Menu/navigation feature - allows the user to navigate from destination to destination, as well as to return to home page;
* Tab feature - allows the user to interact with the possible destinations;
* Contact feature - allows for engagement with the content creator, by sharing their experience;
* Newsletter feature - provides user with content updates, after subscription;
* Footer feature - promotes relevent external social media links of content creator;
* Anchor tag features - allow the user to navigate between pages within the website, as well as, enter external links;

### Features Left to Implement

* Drop down feature in the navigation bar for destinatioms;
* Add visuals to "Things to Do";
* Implement an active state on navigation bar;
* Backgorund to navigation in mobile view, so it doesn't get lost in the hero image;
* Make call to action buttons stand out more;

## Technologies Used

As my first solo project I refrained from using frameworks like Bootstrap, as my intention was to gain better understanding of HTML and CSS.
Thus the main technologies used are:
    *HTML
    *CSS

I have also implemented some JavaScript, in order to make my tab bar responsive. The sample code for this was gained from w3schools.com/ . 

I used https://fonts.google.com/ to source the fonts for this project.
fontswesome.com/ was used for icons.

These online resources are reliable and accessible to everyone.

## Testing

The website functions and responds as intended in the UX design. 
It is responsive to different screen sizes.
It is simple to navigate due to the consistancy in design. 
It is interactive and engaging.

### Features Tested

* The navigation bar is responsive, the logo directs the user to home page and destinations to their correct pages;
* "Lets Visit" anchor tag for all destination is responsive and linked to the correct page;
* Interactive tab funcion works efficiently upon selection of destination;
* "Lets Visit" anchor tag will open a new page, in the same window, whereas, "Lets Go" and social media achor tags will open up a new window;
* Contact form and/or the newsletter cannot be submitted unless all fields are filled out, automated "Please fill in this field" pops up;
* Where applied, hovers are responsive;
* Some content is hidden (hero-text, footer, newsletter) on smaller displays to minimize visual crowding;
* On screens smaller then 1045 px, .what2do becomes a single column row, oppose to the 3 columns on wider displays;

### Bugs addressed

* "Paris" hero image did not cover the entire screen on larger displays, by using the css property background-size:cover; I was able to fix this issue;

### Bugs not yet addressed

* I noticed that on an average phone size display the "Paris" tab displays background-colour, as well as, content colour when selected;
* "Book Now" feature does not stand on it's own and is not in a consistant position throughout the destination pages.

## Deployment

I decided to use GitHub Pages to deploy my project. I found this process very efficient and easy. 
    1. I selected Simple-Guide project repository;
    2. Changed the source settings;
    3. And was provided with a link to my live website.

In order to for others to view my source code, the repository is made public and can be cloned or downloaded as necessary. A specific commit can
also be selected in order to track the project progress.

## Credits

### Content
* Information for tab content was sourced from Wikipedia. 
    1. Prague "https://en.wikipedia.org/wiki/Prague";
    2. Dublin "https://en.wikipedia.org/wiki/Dublin";
    3. Paris "https://en.wikipedia.org/wiki/Paris".

* Information for .what-to-do mainly used personal experiences and presumptions.

* .what-to-do Paris (events) was sourced from "https://en.parisinfo.com/discovering-paris/major-events/what-to-do-in-paris";
* .what-to-do Dublin (see) was sourced from "https://www.dublinpass.com/dublin-attractions/dublin-attractions-guide.html?utm_medium=search&utm_source=GoogleDBP&utm_adcampaigngroup=DBP&matchtype=e&utm_term=what%20to%20do%20and%20see%20in%20dublin&utm_creative=147005593131&addisttype=g&KPID=go_cmp-394026296_adg-27829203296_ad-147005593131_aud-396671218980:kwd-31636519279_dev-c_ext-_prd-&utm_campaign=GC-DBP-GGL-PPC-EUR-IE%2FEN-PROS-NBD-THIN-ALLA-NSA%20%5BEXA%5D&gclid=CjwKCAiAhc7yBRAdEiwAplGxX0kg94I9T7o4oVJgM9HqTdNNIHJwmSHQfPFvYmZWzAPT6-n0Ud5CgRoCXN8QAvD_BwE";
* .what-to-do Prague (see) was sourced from "https://www.thecrazytourist.com/top-25-things-to-do-in-prague/".

### Media

The photos used in this site were obtained from: "https://pxhere.com/".

### Acknowledgements

For this project I was searching for inspiration from other travel guides such as "https://www.lonelyplanet.com/" and/or "https://www.worldtravelguide.net/" 
as well as, the well known "https://www.ryanair.com/ie/en".
