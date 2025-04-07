How to run:

1) Install NodeJs LTS
2) Install composer
3) Install angular by running this command in CMD: npm install -g @angular/cli
4) Install laravel by running this command in CMD: composer global require laravel/installer
5) Clone this repository
6) Open terminal in frontend folder and run: npm install
7) Open terminal in backend folder and run: composer install
8) Connect database from .env file. For Project's purpose, XAMPP mysql was used.
9) Run php artisan migate in backend terminal to make the database and the required tables. 
10) Serve frontend from frontend terminal: ng serve
11) Serve backend from backend terminal: php artisan serve
12) In browser, go to localhost:4200/login
13) change port from 4200  to whatever is being used to serve frontend.



Website details:




Warning: UI design and frontend view might still be suseptible to change.



The website starts at the home page that gives the user the options to login or Register. 


Login Page: 



(The backgroud is a dynamic short video on loop and not a still image)



Registration Page:




*Design will be changed in the future


Logging in redirects user to their Profile, the main HUB of the website. Most pages are accessable from here:
The posts are loaded using the concept of pagination and adds 5 posts everytime the bottom of the page is scrolled to (*The existing posts are only for test puroses)



*Posts positioning and style of display is suseptible to change

Users can also click on their profile picture to add/change profile picture:





The About page houses most of the info of the user



All these information can be clicked on to add or edit: 





Users can use the "Make a Post" button on their profile to add posts. In these posts, they can add multiple images and/or videos, or simply post a text post. 
All posts with their images and/or videos and captions are primarily displayed in profile (as shown above).




The user can now also access a working Newsfeed where the posts of all the users they follower appear.




Now, a user can go to another users profile and click on send message to create a new chatbox and start sending messages.






Furthermore, a user can create group chats by using the corresponding button, adding new memebers and confirming the group name.




Parallel to message sending, everytime a person receives a text, they receive a notification in their profile.







Users can now chat with a Helper AI bot:







Users can add and chat with groups of people in a group chat:






Users has their github information and their repositories posted.


















