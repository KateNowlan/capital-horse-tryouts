# Capital Stud Tryouts Auction List 2022

This is a blog/website to present the horses we have on auction to try out for 2022. On there, as a superuser/admin, I can make posts about each auction horse on the list and autheticated users can comment and like posts as well. It's overall quite simple in it's design but it works very well in it's design as intended and is interactive which is great for the prospective clients.

![Home page](./media/home-page.png)

# Business

The Business goals describe the expected user and site owner goals - these drive the design, development, and deployment of the blog/website application. The fulfillment of these goals determine the success of the application.

## External Users

The external users are potential and actual customers of Capital Stud. They are looking for information on the various horses being offered on auction for 2022, as well as being able to contact us to book a tryout of any of the horses.

## Site Owner

The site owner is looking to attract potential customers and be able to manage customer tryout bookings and contact requests in order to engage to the users.

## Features 

### Existing Features

- __Navigation Bar__

  There's a nav bar at the top of the screen. You can go to the homepage, log in/out, sign up.

![Nav Bar](./media/nav-bar.png)


- __The Blog Posts__

  You can see all the different blog posts that have been made, I as admin add these posts manually through Django Admin. The posts have the image of each horse, and if you click on each one it takes you to the post with more information.From here, you can see the likes and comments on a post as well. 

![Blog Posts](./media/blog-posts.png)

- __Login Page__
  This is where users who have made an account can sign in and from there they can comment on posts, like posts and will have the option to contact me as well. 
 

![Login](./media/signin.png)

- __Sign Up page__

  Before the user can login, they must register and sign up to the website. They will have to enter a username and secure password. 

![Sign Up](./media/signup.png)

- __Logout__

  If the user wants, they also have the option to sign out of their account too. You will be asked if you are sure you want to leave the site.

![Logout](./media/sign-out.png)


 __A Blog Post__

  So here is a blog post itself: The name of the horse and it's image are held within a masthead at the top and the information of the horse itself is below.

![A blog post](./media/a-post.png)

- __Blog Post Comments__ 

  Users can see their comments and other people's comments, as well as how long ago they were posted. They can also edit them and delete them from here as well. To make a comment a user must be signed in on their account. 

![Comments](./media/comments.png)

# User Stories

The following user stories have been created to ensure the goals of the users and owner are met.

| User Story | Goal |
| --- | --- |
| **User Story 001:** As a user i can view a post so that i may select one to read | identifying horses on auction |
| **User Story 002:** As a user i can open a post so that i may see all its details | Finding more information on each horse on the auction |
| **User Story 003:** As a site user i can view likes so that users and admin can see which posts are liked | likes on blog posts |
| **User Story 004:** As a site user i can register an account so that i can comment and like and be interactive with the site | Ability to register,sign in,log out |
| **User Story 005:** As a site user i can comment on photos so that i can add my opinion to which horses i like | Ability to comment on blog posts |
| **User Story 006:** As a site user i can like or unlike a post so that i can be interactive with the content | Ability to like/unlike blog posts |
| **User Story 007:** As a site admin i can create, read, update and delete posts so that i can manage content on the site | Ability for admin to manage posts |
| **User Story 008:** As a site admin i can approve or dismiss comments so that we only have comments benefical to the site | Ability for admin to approve/dismiss posts|

## Administrators

An administrator is a manager of the Capital Stud page. This requires the use of a superuser account username and password, as this is not public-facing information.

- ![Administration login Page](./media/admin-login.png) with:
    - the ability for the admin superuser to log in

- ![Administration home Page](./media/admin-home.png) with:
    - the ability to create, view, update and delete the auction horse information visible on the public site.

# Technology

## Key Technology Used

The following key technologies and languages have been used as part of this website:

- [HTML 5](https://en.wikipedia.org/wiki/HTML): HyperText Markup Language, the standard markup language for documents designed to be displayed in a web browser
- [CSS 3](https://en.wikipedia.org/wiki/CSS): style sheet language used for describing the presentation of a document
- [JavaScript](https://www.javascript.com/): high-level, often just-in-time compiled language
- [jQuery](https://jquery.com/): JavaScript library
- [Python](https://www.python.org/): high-level, general-purpose programming language
- [Django](https://www.djangoproject.com/): Python-based open-source web framework
- [Postgresql](https://www.postgresql.org/): open-source database to hold back-end data
- [GitHub](https://github.com/): code repository
- [GitPod](https://www.gitpod.io/): integrated development environment (IDE)
- [Heroku](https://www.heroku.com/): deployment of the website and application

### User Story Board

A user story board was used to assist with the organisation of building the website. This included the user stories representing the key features that should be implemented. These were sorted into the following lists:

- To Do: features where no progress had been started.
- In Progress: features where progress has commenced, but not completed.
- Done: features that have been fully implemented.

![Image of board](./media/user-story.png)

Each user story started in the To Do list, and was moved through to In Progress and Done as development continued. This assisted with ensuring the work was performed in an organised manner.

