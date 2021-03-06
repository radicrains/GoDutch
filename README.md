# GoDutch

## Application Description
This is a bill spilting app that tracks spendings between friends/family.

## Table of Content
- [Links](#Links)
- [Database/Storage](#Database/Storage)
- [Technologies](#Technologies)
- [Objective](#Objective)
- [Approaches Taken](#Approaches-taken)
- [Accomplishments](#Accomplishments)
- [Difficulties faced](#Difficulties-faced)
- [Wireframe Design and User Stories](#Wireframe-Design-and-User-Stories)
- [RESTful Routes](#RESTful-Routes)
- [Additional Features were under Considerations](#Additional-Features-were-under-Considerations)
- [Credits](#Credits)

## Links
- [Application Link](www.google.com)

## Database/Storage
* **MongoDB** is a document-oriented database which stores data in JSON-like documents with dynamic schema. 

## Technologies
* **EJS** is used to generate HTML with plain javascript to append to frontend.
* **Method-override** is used to to convert HTTP verbs such as PUT or DELETE in places where the client doesn't support it
* **shortid** is used to create amazingly short non-sequential url-friendly unique ids
<!-- * **Bcrypt** is used to hash and store passwords in database -->
* **Express-session** is used to store the user state with each given being assigned a unique session. 
<!-- * **MomentJS** is used as a wrapper to handle Date object
* **Multer** is used to handle multipart/form-data for images uploading  -->
* **Bootstrap Material Design** is used for CSS framework for HTML and CSS design templates

## Objective
* Make a full **CRUD** (Create, Read, Update and Delete) using 
**Node.js**, **MongoDB**, **Express** and **EJS** and adheres to **MVC** (Models, Views, and Controllers) file structure.

## Approaches Taken
* set up a basic MVC structure with basic CRUD routes.
* set up database with collections and schema validation in the MongoDB
* built authentication page
* linked the app to heroku
<!-- * modular testing on the upload file with cloudinary and multer. 
    > initially this is not in the full code, after basic functional test completed, implement it to the routes.
* follow the initial wireframe design and user stories
  > started with show route for albums, then images, comments and lastly users. -->

## Accomplishments
* The application is meeting the minimum viable product (MVP)'s requirements.
* User to be able to create friends, add expenses for tracking, view owing and view settled amount.

<!-- 
* Every user is able to create album, add image to existing album, view other users, view all albums, view all images, add comment, delete comment/image/ablum, edit comment/album, follow/unfollow users/albums, etc. -->

<!-- * the image file can be uploaded through local file.  -->

## Difficulties faced

    
## Wireframe Design and User Stories
* ### Landing Page (Not Signed in)
<!-- |Main Page | About Page|
|--|--|
|<img src="public/assets/images/app/1.PNG" width="500px"/>| <img src="public/assets/images/app/2.PNG" width="500px"/>|

|Sign Up Page | Login Page|
|--|--|
|<img src="public/assets/images/app/3.PNG" width="500px"/>| <img src="public/assets/images/app/4.PNG" width="500px"/>|

* ### Landing Page (Signed in)
<table><tr><td>
 <img src="public/assets/images/app/5.PNG" width="500px"/>
</td></tr></table>

* ### All Albums
<table><tr><td>
 <img src="public/assets/images/app/6.PNG" width="500px"/>
</td></tr></table>

|Owned Ablum |Not Owned Album (Following) | Not Owned Album (Not Following)|
|--|--|--|
|<img src="public/assets/images/app/album owned.PNG" width="200px"/>|<img src="public/assets/images/app/album following.PNG" width="200px"/>|<img src="public/assets/images/app/album not following.PNG" width="200px"/>|

* ### All Images
<table><tr><td>
 <img src="public/assets/images/app/7.PNG" width="500px"/>
</td></tr></table>

* ### Following Page
<table><tr><td>
 <img src="public/assets/images/app/8.PNG" width="500px"/>
</td></tr></table>

* ### Album Page
<table><tr><td>
 <img src="public/assets/images/app/10.PNG" width="500px"/>
</td></tr></table>

* ### User Profile Page
<table><tr><td>
 <img src="public/assets/images/app/11.PNG" width="500px"/>
</td></tr></table>

* ### Comments Modal
<table><tr><td>
 <img src="public/assets/images/app/9.PNG" width="500px"/>
</td></tr></table> -->

## RESTful Routes
<!-- 
|No.|Route | URL    | HTTP Verb | Description |
|--|-------|--------|-----------|------------ |
|1 |Index  | /      | GET       | Home Page   | 
|  |       | /about | GET       | About Page  |
|2 |New    | /signup| GET       | Signup Form |
|  |       | /login | GET       | Login Form  |
|  |       | /albums/new | GET       | Create New Album Form  |
|3 |Create | /signup| POST      | Records the entered Information into database as new user|
|  |       | /login | POST      | Authenticates credentials against database and redirect to / |
| |        | /ablum/create/file | POST | Add new album via image upload through file into database and redirect to /main
| |        | /ablum/create/url | POST | Add new album via image upload through url into database and redirect to /main
| |        | /image/create | POST | Add new image into database and redirect to its original page. 
| | |/account/comment /:currentUser /:dataUser/create | POST | Add new comment into database and redirect to orignal dataUser's profile page|
| | |/comment/create| POST | Add new comment into database and redirect to its album's page|
| | |/album/follow | POST | Follow Album
| | |/album/unfollow | POST | Unfollow Album
| | |/user/follow | POST | Follow User
| | |/user/unfollow | POST | Unfollow User
|4| Show   | /main  | GET       | Show all albums |
| |        | /images  | GET     | Show all images |
| |        | /account  | GET    | Show current user's profile |
| |        | /users/:userName  | GET     | Show requested user's profile |
| |        | /albums/:albumName | GET     | Show requested album's details |
| |        | /following | GET | Show all the following albums and users
|5 |Edit   | -  | GET       | There is no edit route set up for edit album, image and comment as are routed to modals via buttons
|6 |Update | /albums/:albumName | PUT       | Update requested album's details |
|  || /comment/:location /:updatedUser/:albumName /:imageIndex/:commentIndex/ | PUT | Update comment in the requested album and redirect to original page|
|7 |Destroy| /logout| DELETE    | Destroys session and redirect to /
| | |/:albumName| DELETE | Destroy requested album and redirect to /main
| | |/:albumName/image /:imageIndex | DELETE| Destroy requested image from requested album and redirect to its album's page
| | |/comment/:location /:albumName/:imageIndex /:commentIndex | DELETE | Destroy requested comment from requested image  and redirect to its original page -->

## Additional Features were under Considerations
<!-- * **Notifications** - application to send notifcation to user when there is another user commented on image, add new image to the album, followed album has new image, has new follower, etc. 
* **Enhance Users Database** - to get more users profile into the database like profile picture, email address, gender, age, biodata, etc. 
* **Like feature for image** - to have a like button for individual image -->

## Credits
<!-- * All the **alpha trials users** and **fellow coursemates**  -->

