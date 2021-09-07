14 Model-View-Controller (MVC): Tech Blog
License: MIT

Description
Build a CMS-style blog site similar to a Wordpress site, where developers can publish their blog posts and comment on other developers’ posts as well. The site is built from scratch and deployed to Heroku. It follows the MVC paradigm in its architectural structure, using Handlebars.js as the templating language, Sequelize as the ORM, and the express-session npm package for authentication.

Motivation
This project provided fun opportunities to develop a site from scratch. I really enjoyed getting all of the routes to work properly and updating the UI to match my own aesthetic.

Learning Targets
This exercise provided our fist solo opportunity to build a full-stack web application from scratch. I learned so much while working on this project, including a lot of small nuances that I will know to look for in the future. A blogging site has so much possilbility and I struggled not to spend more time adding on other features that I would love to see (upvotes, an admin account, topics, more developed user profiles, threaded comments).

Table of Contents
Core Objectives Met
Technologies Used
Local Installation & Usage
Deployed App
Demo
License
Questions
Core Objectives Met
When a user visits the site for the first time, they are presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in.
When a user clicks on the homepage option, they are taken to the homepage.
When a user clicks on any other links in the navigation, they are prompted to either sign up or sign in.
When a user chooses to sign up, they are prompted to create a username and password.
When a user clicks on the sign-up button, their user credentials are saved and they are logged into the site.
When a user revisits the site at a later time and choose to sign in, they are prompted to enter their username and password.
When a user is signed in to the site, they see navigation links for the homepage, the dashboard, and the option to log out.
When a user clicks on the homepage option in the navigation, then they are taken to the homepage and presented with existing blog posts that include the post title and the date created.
When a user clicks on an existing blog post, they are presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment.
When a user enters a comment and clicks on the submit button while signed in, the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created.
When a user clicks on the dashboard option in the navigation, they are taken to the dashboard and presented with any blog posts they have already created and the option to add a new blog post.
When a user clicks on the button to add a new blog post, they are prompted to enter both a title and contents for my blog post.
When a user clicks on the button to create a new blog post, the title and contents of their post are saved and they are taken back to an updated dashboard with the new blog post.
When a user clicks on one of their existing posts in the dashboard, they able to delete or update their post and are taken back to an updated dashboard.
When a user clicks on the logout option in the navigation, they are signed out of the site.
When a user is idle on the site for more than a set time, they are able to view comments but are prompted to log in again before they can add, update, or delete comments.
Technologies Used
JavaScript
MySQL
Node.js
NPM Express.js Package
NPM Handlebars.js Package
NPM Sequelize ORM Package
NPM Express-Session Package
NPM Cookies Package
NPM bcrypt Package
NPM Router Package
NPM dotenv Package
NPM mysql2 Package
NPM nodemon Package
NPM connect-session-sequelize Package
Local Installation & Usage
To use this app, you will need a MySQL Workbench account, and to have the app installed on your machine. Documentation with installation instructions are available here.

STEP 1

1.1 Clone this Tech-Blog repo to your machine.
STEP 2

From Visual Studio Code or the code editor of your choice:

2.1 Open the repo.  
2.2 Locate and open the .env.EXAMPLE file, located in the root directory.
2.3 Add your own MySQL Workbench Username and Password to the env.EXAMPLE file.
2.4 Re-name the file to .env (i.e. remove .EXAMPLE).
2.5 Save your changes.
2.6 Locate and open db\schema.sql.
2.7 Copy and paste the database schema into a new MySQL Workbench query tab and run it. Refresh and view your updated schemas to ensure that techblog_db now appears.
STEP 3

From your terminal, run:

3.1 npm i
3.2 npm run watch
STEP 4

From the modern browser of your choice, visit:

4.1 http://localhost:3001
Deployed App
This Tech Blog app has been deployed on Heroku and is available here. https://intense-dawn-84284.herokuapp.com/

Demo
Homepage in a logged-out state, with appropriate links displayed. Comments on articles cannot be updated or deleted at this stage. After logging in, the option to add comments is made available.
![28A4D650-C8AD-4300-B99A-2108DF09A1B2_1_105_c](https://user-images.githubusercontent.com/80792502/132409267-098baf0c-0f33-4f0f-8015-d5ab6a6bd4f0.jpeg)
![FADE42C7-BF0B-4132-B761-3AB6D9AF2DC9_1_105_c](https://user-images.githubusercontent.com/80792502/132409505-e8fd599a-a6d6-4811-a633-408bfdd5fa13.jpeg)
![3AC6855D-922F-4D3F-81F1-7B277FCAFCB1_1_105_c](https://user-images.githubusercontent.com/80792502/132409511-77918742-980a-4f66-9039-fec3a375f547.jpeg)
![F05B604F-F94B-438A-B15A-D5CA51A3448E_1_105_c](https://user-images.githubusercontent.com/80792502/132409517-35dd14b5-b42a-4798-a48e-39883f9d99e2.jpeg)



Tech Blog Homepage.

Updating and deleting comments while logged in. Only the user's own comments may be updated or deleted.

Tech Blog Updating or Deleting Comments.

The Dashboard while in a logged-in state. The user can add new articles, as well as viewing, updating, or deleting other articles that they have posted. Article fields (title and content) may not be left empty.

Tech Blog Add Update Delete Articles.

MIT License
©2021 Alice Waweru

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Questions
For inquiries, please contact Alice Waweru.

About
UW Full-Stack Bootcamp Homework, Week 14, MVC: Tech Blog


Handlebars
34.4%
 
CSS
12.4%
© 2021 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
