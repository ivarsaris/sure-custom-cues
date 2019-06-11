
# Sure Custom Cues

**First milestone project; User-centric frontend development - Full stack software developer course - Code Institute**

This website is made for Sure Custom Cues, a small pool cue making business located in Cologne, Germany. The website has five pages using various technologies.
The website includes information about the company and its history, innovations it has made as well as custom cues for sale and a gallery showcasing cues.

![image of homepage]("https://github.com/ivarsaris/sure-custom-cues/blob/develop/assets/images/homepage.png")

## UX

The goal of the website is to give visitors a clear image of the work that Sure Custom Cues does. On every page, there's a bar at the top with 
contact information of the business and links to its social media accounts.

The goal of the design was to make it easy for visitors to find and access any part of the website. The dark background and light text in modern font
was chosen to create a modern style. This was one of the wishes of Andreas Sure, director of Sure Custom Cues. 

I started by creating a mock-up using [Wix](https://ivarsaris.wixsite.com/mysite.)

## Features

On top of each page is a bar with the contact information of the company and links to its social media accounts. The homepage features a slide show created with a keyframes query in CSS. 

The website has five pages:
1. Homepage: Introduces the company and has an automatic slide show with images of cues.
1. About page: Explains the philosophy and tells the story of the company.  
1. Innovations page: Gives an overview of all innovations developed by Sure Custom Cues.
1. Custom cues page: Gives and overview of the custom cues currently for sale and a gallery of cues made.
1. Impressum: An overview of information about the company in order to comply with German law. This page is linked to only from the homepage.

Several images, including the gallery images, increase in size when they are hovered. This was achieved by using the transform function in CSS.

#### Features left to implement

In the future, I would like to make a slide show for each custom cue for sale. So potential customers can slide through
three or four pictures and better look at the cue. Also, I would like to add a section with videos which show the 
innovations and cues being tested.

Since many of Sure's customers are German, I would like to add a German version of each page which can be linked to from the English pages. 

## Technologies used

The following technologies were used in order to create the website;

* HTML; coding language used to create the content of the website
* CSS; coding language used to style the content
* Bootstrap (v4.3.1) https://getbootstrap.com/ ; CSS library used to style sections of the website.
* Font awesome library: https://fontawesome.com/ ; used to display the copyright and social media icons.  

## Testing

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

1. The images that increase in size became larger than the device, so a part of the image was outside the screen and not visible. This was fixed
by adding a media query to CSS and reducing the amount the image would increase on a small device.

1. The drop-down menu of the innovations page is displayed when hovering over it in the navigation menu. On mobile, when clicking on the
innovations link, the menu is displayed shortly, then the innovations page opens. 

## Deployment

The website is hosted using Github pages. It was deployed from the developer branche. 


## credits

#### Content
All content on the website was written by me. 

#### Media
All images were taken, with permission, from the Facebook and Instagram account
of the company, or send to me by Andreas Sure. 

#### Acknowledgements

The design of slide show on the homepage was taken from [here](https://www.hyde-design.co.uk/joomla-bites/80-create-a-css-slide)
I modified it to fit the style of the page.

The way of getting a full background image was taken from [here](https://css-tricks.com/perfect-full-page-background-image/.)
