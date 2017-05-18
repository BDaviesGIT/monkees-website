# Band Webite- The Monkees

## Overview

### What is this website for?

This website is a coursework assignment for module 1 of the code institutes web development course.

### The goal?

To build a website (front-end only) for the band "The Monkees" which displays what I have learned from the first module of the web development course. The target audience for the site are the fans of the band, but also potential fans.
Desired features for the site are: the ability to display audio/ video files, showcase the bands music and feature a form that will allow users to book the band for their own events. The site will also link to the band's social media- (facebook, twitter & youtube pages).

## Features

### Existing Features
- Responsive page layout.
- Responsive Navigation to all pages.
- Discography page- working carosel with changing text for each album.
- Media section seperating audio/ video via tab navigation. mp4/ mp3 files embedded onto page but also links to the band's spotify and youtube supplied. Pages act as a platform to upload future video/ audio content for the band.
- Tour section to allow the band to post upcoming tour dates. A button link is provided on this page to take the user directly to the bands ticketmaster page.
- Booking form to allow users to input their own event data to potentially book the band. Name, Email, datea and location of event are required fields with options for the user to submit their telephone and "type of event". The form allows a member of the band's media team to check the date of event with its location and send a follow up e-mail to gather further information and work out further details such as exact location, price, etc. To assist in ensuring a correct contact e-mail is recieved from the user, they must supply an e-mail address which matches the e-mail template. Similarly, for the user to provide a mobile number, they must match the basic mobile number template.
- links to external sites provided including the bands official merchandise store and social media. Glyphicons have been used for social media links.

### Features Left to Implement


## Tech Used

### Some the tech used includes:

- [Bootstrap](http://getbootstrap.com/)
	- **Bootstrap** was used to give the website a clear and responsive layout with fully responsive navigation. Additional features from Bootstrap where also utilised such as glyphicons, buttons etc. 
- [Jquery](http://code.jquery.com)
  - **Jquery** used to add fuctionality to the discography page carosel, allowing track listings to change when the correct album art is navigated to.
- [npm](https://www.npmjs.com/)
	- We use **npm** to help manage some of the dependencies in our application
- [bower](https://bower.io/)
	- **Bower** is used to manage the installation of our libraries and frameworks
 
## Contributing
N/A

### Getting the code up and running
1. Firstly you will need to clone this repository by running the ```git clone <project's Github URL>``` command
2. After you've that you'll need to make sure that you have **npm** and **bower** installed
  1. You can get **npm** by installing Node from [here](https://nodejs.org/en/)
  2. Once you've done this you'll need to run the following command:
  	 `npm install -g bower # this may require sudo on Mac/Linux`
3. Once **npm** and **bower** are installed, you'll need to install all of the dependencies in *package.json* and *bower.json*
  ```
  npm install

  bower install
  ```
4. After those dependencies have been installed you'll need to make sure that you have **http-server** installed. You can install this by running the following: ```npm install -g http-server # this also may require sudo on Mac/Linux```
5. Once **http-server** is installed run ```http-server```
6. The project will now run on [localhost](http://127.0.0.1:8080)
7. Make changes to the code and if you think it belongs in here then just submit a pull request