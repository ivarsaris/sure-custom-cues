
Sure Custom Cues

First milestone project; User-centric frontend development - Code Institute

This website is made for Sure Custom Cues, a small pool cue making business located in Cologne, Germany. The website has five pages using various technologies.
The website includes information about the company and its history, innovations it has made as well as custom cues for sale and a gallery showcasing cues.



UX

The goal of the website is to give visitors a clear image of the work that Sure Custom Cues does. On every page, there's a bar at the top with 
contact information of the business and links to its social media accounts. The website has five pages;

1. Homepage: Introduces the company and has an automatic slide show with images of cues.
2. About page: Explains the philosophy and tells the story of the company.  
3. Innovations page: Gives an overview of all innovations developed by Sure Custom Cues.
4. Custom cues page: Gives and overview of the custom cues currently for sale and a gallery of cues made.
5. Impressum: An overview of information about the company in order to comply with German law.

The goal of the design was to make it easy for visitors to find and access any part of the website. The dark background and light text in modern font
was chosen to create a modern style. This was one of the wishes of Andreas Sure, director of Sure Custom Cues. 

I started by creating a mock-up using Wix: https://ivarsaris.wixsite.com/mysite.



Features

The homepage features a slide show created with a keyframes query in CSS. 

Several images, including the gallery images, increase in size when they are hovered. This was achieved by using the transform function in CSS.

Features left to implement

In the future, I would like to make a slide show for each custom cue for sale. So potential customers can slide through
three or four pictures and better look at the cue. Also, I would like to add a section with videos which show the 
innovations and cues being tested.



Technologies used

The following technologies were used in order to create the website;

1. HTML; coding language used to create the content of the website
2. CSS; coding language used to style the content
3. Bootstrap (v4.3.1) https://getbootstrap.com/ ; CSS library used to style sections of the website.
4. Font awesome library: https://fontawesome.com/ ; used to display the icons which link to the social media account. 



Testing

The website achieves the goal set out. To give visitors a clear image of the work that Sure Custom Cues does. As well as showcasing what Sure Custom Cues
offers for sale. 

For the visitor it's easy to access any part of the website. The pages give a clear image of what the company does,
and offers for sale. The contact information can be seen on every page, as well as a link to its social media platforms. A visitor that's interested in the 
company and its innovations can go to the about and innovations page. A visitor that's interested in buying a cue can go directly to the custom cues page
without having to scroll through any content.

The innovations page is the longest page with quite a lot of content. For this reason, a drop-down menu is displayed when hovering over the innovations page link.
In this drop-down menu, the different sections of the page are linked to. On the bottom of the page is a "back to top" button so the visitor can easily 
go back to the top of the page without having to scroll. 

The website has been tested on several devices and browsers. It was tested on a Dell and Microsoft laptop, an iPad, a MacBook, a Samsung S9, an Honor 10, and
on an iPhone 7. On all devices the layout worked well. There were a few bugs when opening the website on a mobile device:

1. The impressum page showed a large white space under the content. The reason for this was the size of the background image. 
This was fixed by adding spacing to the page which would only be displayed on a
small device. This way, there would be no unnecessary empty space while viewing on a larger device. 

2. The images that increase in size became larger than the device, so a part of the image was outside the screen and not visible. This was fixed
by adding a media query to CSS and reducing the amount the image would increase on small device.

3. The drop-down menu of the innovations page is displayed when hovering over it in the navigation menu. On mobile, when clicking on the
innovations link, the menu is displayed shortly, then the innovations page opens. 



Deployment




credits

Content
All content on the website was written by me. 

Media
All images were taken, with permission, from the Facebook and Instagram account
of the company, or send to me by Andreas Sure. 

Acknowledgements

The design of slide show on the homepage was taken from https://www.hyde-design.co.uk/joomla-bites/80-create-a-css-slide show-no-javascript-required.
I modified it to fit the style of the page.

The way of getting a full background image was taken from https://css-tricks.com/perfect-full-page-background-image/.
