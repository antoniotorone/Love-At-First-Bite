# Antonio Torone Milestone 3 - Python and Data Centric Development

[View here the live project]()

## Love At First Bite

Interactive website application where the main purpose is to share data and achieve the function CRUD.
Bright and friendly website with the ability to register, become a user and create, edit, delete and share personal recipes with the Wesite community. The ability to connect any recipe and increase interest and passion for cooking.


## User Experience (UX)

### User stories

#### First time visitor goals

1. As a first time visitor, I want to be attracted to the recipes, to the name, to the feeling of being in the right place about food and cooking.
2. As a first time visitor, I want to be able to easily understand the website settings and navigate without confusion.
3. As a first time visitor, I want to be able to find the registration area and sign in quickly and easily.

#### Returning visitors goals

1. As a returning visitor, I want to see more recipes, and I expect that delicious new food recipes will  make the site even more interesting and attractive.

#### Frequent visitors golas

1. As a frequent visitor, I want the website to always be smooth, intuitive and not lurid, with new images that increase the user's interest not to leave, but to check out all the recipes.


### Design

#### Color scheme

The main colours used around the website application are light grey and pink in various tones. Light tones are used for the navigation bar, carousel, login and registration form and darker tones for the buttons. The sign in link under the registration form and the register link under the sign in form have a red hover effect.

#### Tipography

The font is materialize default one

#### Imagery

The images were inserted by the developer with a URL within the src attribute through the cloudinary platform. At the same time, the user has the option to add their own image when creating the recipe through the field image within the "Create Recipe" form.

### Wireframes

All devices wireframes pdf file [view](https://github.com/antoniotorone/cookbook/blob/main/Documentation/Wireframes/wireframes-pdf.pdf)


## Features

* Interactive
* Friendly
* Tidy


## Technologies used 

### Language used

[HTML5](https://it.wikipedia.org/wiki/HTML5)
[CSS3](https://it.wikipedia.org/wiki/CSS#CSS_3)
[JAVASCRIPT](https://it.wikipedia.org/wiki/JavaScript)
[PYTHON](https://it.wikipedia.org/wiki/Python)


### Frameworks Libraries & Programs Used

1. [Materialize](https://materializecss.com/)
2. [Jquery](https://jquery.com/)
3. [FontAwesome](https://fontawesome.com/)
4. [Git](https://git-scm.com/)
5. [Github](https://github.com/)
6. [Heroku](https://id.heroku.com/)
7. [Flask](https://flask.palletsprojects.com/en/2.0.x/)
8. [MongoDB](https://www.mongodb.com/)
9. [Werkzeug](https://werkzeug.palletsprojects.com/en/2.0.x/)
10. [PyMongo](https://pymongo.readthedocs.io/en/stable/)
11. [Cloudinary](https://cloudinary.com/)
12. [Balsamiq](https://balsamiq.com/)


## Testing

### Testing user stories from user experience (UX section)

#### First time visitor goals

1. As a first time visitor, I want to be attracted to the recipes, to the name, to the feeling of being in the right place about food and cooking.

   1. When the site loads, a carousel with food recipes image give you a welcome. Images in my opinion very interesting, delicious look that the website need to entertain the user and not leave. The home page is directly to the purpose, the carousel and recipes already located in the middle of the page with the name of the recipe larger. [View here](https://res.cloudinary.com/anto8913/image/upload/v1628273432/3rd%20milestone/testing%20screenshot%20/first-time_1.-carousel_sl6d0j.jpg),
   [view here](https://res.cloudinary.com/anto8913/image/upload/v1628273432/3rd%20milestone/testing%20screenshot%20/first-time_1.-center-page_npztf8.jpg)


2.  As a first time visitor, I want to be able to easily understand the website settings and navigate without confusion.

    1. The best part of the website is that the homepage is not confused at all is so straightpoint with a navbar that contain 3 section like: Home, Login and Register which are very useful for a registered user. On the other hand, if the user is not registered but is on the login page, there is a link below the form that is very visible and thanks to the red hover effect the user just needs to click for naviagate to the login page. The same goes for the registration page, there is a link under the form that takes the user to the login page. The website is built with logic and is very well connected between the login page and the registration page. In the end regarding to search recipes, the search bar in the middle is set up for to research by name recipe, ingredients and category name.[View here](https://res.cloudinary.com/anto8913/image/upload/v1628273433/3rd%20milestone/testing%20screenshot%20/first-_time-2_navbar_vmsxwj.jpg),
    [View here](https://res.cloudinary.com/anto8913/image/upload/v1628273433/3rd%20milestone/testing%20screenshot%20/first-_time-2_login_page_grwxfj.jpg),
    [View here](https://res.cloudinary.com/anto8913/image/upload/v1628273432/3rd%20milestone/testing%20screenshot%20/first-time-2-register_page_kumc8g.jpg),
    [View here](https://res.cloudinary.com/anto8913/image/upload/v1628273432/3rd%20milestone/testing%20screenshot%20/manual_testing-_searc_bar_ghe942.jpg)


3. As a first time visitor, I want to be able to find the registration area and sign in quickly and easily.

   1. The registration page is on the right side of the navigation bar. The 3 sections have a gray hover effect that contrasts nicely with the pink color in the background, making all pages like the registration page stand out. One click and the user is to the page , finding a classic and simple form to fill. [View here](https://res.cloudinary.com/anto8913/image/upload/v1628273433/3rd%20milestone/testing%20screenshot%20/first-_time-2_navbar_vmsxwj.jpg),
   [View here](https://res.cloudinary.com/anto8913/image/upload/v1628273432/3rd%20milestone/testing%20screenshot%20/first-time-2-register_page_kumc8g.jpg)


#### Returning visitor goals

1. As a returning visitor, I want to see more recipes, and I expect that delicious new food recipes will  make the site even more interesting and attractive.

   1. The website functionality gives the opportunity, this is also the more important, I can say the heart of the application, which is to create and add recipe. This feature is only available to registered users and can only be used when the user is logged in. The recipe created is displayed directly on the home page and can be shared with anyone who visits the site, and at the same time is added to the user's profile. In this way, the website becomes more and more extensive, interesting and full of different recipes.[View here](https://res.cloudinary.com/anto8913/image/upload/v1628273433/3rd%20milestone/testing%20screenshot%20/returning-create_recipe-1_b0p3vd.jpg),
   [View here](https://res.cloudinary.com/anto8913/image/upload/v1628273432/3rd%20milestone/testing%20screenshot%20/returning-create_recipe-2_lnv8ej.jpg)
   

#### Frequent user goals

1. As a frequent visitor, I want the website to always be smooth, intuitive and not lurid, with new images that increase the user's interest not to leave, but to check out all the recipes.

   1. The website was created using Materialize, which helps it look so friendly and not heavy, also the colors I chose are not heavy. The site has a recipe creation form with an image field, which means the home page for frequent users is not will be always the same. With new recipes images, it will look different. Not being ripetitive also means not being boring, with new recipes to look at and try at home.[View here the image field](https://res.cloudinary.com/anto8913/image/upload/v1628273431/3rd%20milestone/testing%20screenshot%20/frequent-user-image-field_vf5gpi.jpg)


### Validator Testing

The W3C Markup Validator  W3C CSS validator and JAVASCRIPT services were used to validate every page and ensure there were no syntax errors in the project. 
The Lighthouse test was used to check the performance, best practices and accessibility.

* [W3C Markup Validator results](https://github.com/antoniotorone/cookbook/tree/main/Documentation/Validation-test-PDF)
* [W3C CSS Validator result](https://github.com/antoniotorone/cookbook/blob/main/Documentation/Validation-test-PDF/Css.style.pdf.pdf)
* [Java Script validator results](https://github.com/antoniotorone/cookbook/blob/main/Documentation/Validation-test-PDF/script.js.pdf.pdf)
* [Lighthouse test](https://github.com/antoniotorone/cookbook/blob/main/Documentation/Validation-test-PDF/lighthouse.pdf.pdf)


### Manual testing

#### Search bar

##### Expected 

1. I was expected to get the research by food category_name, food recipe_name and food ingredients.

##### Results

1. As a result, I achieved all functionalities that I was expected. [View here](https://res.cloudinary.com/anto8913/image/upload/v1628273432/3rd%20milestone/testing%20screenshot%20/manual-_testing-search_bar_bmyzxe.jpg) [View here](https://res.cloudinary.com/anto8913/image/upload/v1628273432/3rd%20milestone/testing%20screenshot%20/manual_testing-_searc_bar_ghe942.jpg) [View here](https://res.cloudinary.com/anto8913/image/upload/v1628273432/3rd%20milestone/testing%20screenshot%20/manual-testing-search-bar_wuqcxv.jpg)

#### Delete button

##### Expected

1. I was expected to delete the recipe chosen by click the proper button.

##### Results

1.  As a result, I achieved all functionalities that I was expected. [View here](https://res.cloudinary.com/anto8913/image/upload/v1628442650/3rd%20milestone/manual%20testing/delete_recipe_qzdl2n.jpg) [View here](https://res.cloudinary.com/anto8913/image/upload/v1628685749/3rd%20milestone/manual%20testing/delete_recipe_message_g7fykv.jpg) [View here](https://res.cloudinary.com/anto8913/image/upload/v1628442650/3rd%20milestone/manual%20testing/delete_recipe2_juizms.jpg)

#### Edit button

##### Expected

1. I was expected to edit the recipe chosen by click the proper button.

##### Results

1. As a result, I achieved all functionalities that I was expected. [View here](https://res.cloudinary.com/anto8913/image/upload/v1628442650/3rd%20milestone/manual%20testing/edit-recipe2_rsr3e9.jpg) [View here](https://res.cloudinary.com/anto8913/image/upload/v1628442651/3rd%20milestone/manual%20testing/edi-recipe-message_jgosja.jpg)

#### Create recipe form

##### Expected

1. I was expected to create a recipe filling up all fields and click the proper button.

##### Results

1.  As a result, I achieved all functionalities that I was expected. [View here](https://res.cloudinary.com/anto8913/image/upload/v1628273433/3rd%20milestone/testing%20screenshot%20/returning-create_recipe-1_b0p3vd.jpg) [View here](https://res.cloudinary.com/anto8913/image/upload/v1628442651/3rd%20milestone/manual%20testing/create-recipe_ypfgbr.jpg)

#### Log in and the required attribute

##### Expected

1. I was expected to log in filling up the form fields and to get the required pop up message in case of any mistake.

##### Results

1.  As a result, I achieved all functionalities that I was expected. [View here](https://res.cloudinary.com/anto8913/image/upload/v1628442649/3rd%20milestone/manual%20testing/login_to_profile_hqa6r1.jpg) [View here](https://res.cloudinary.com/anto8913/image/upload/v1628442649/3rd%20milestone/manual%20testing/login_username_wz4keu.jpg).

#### Log out

##### Expected

1. I was expected to log out clicking the log out link inside the nav bar

##### Results

1. As a result, I achieved all functionalities that I was expected. [View here](https://res.cloudinary.com/anto8913/image/upload/v1628442649/3rd%20milestone/manual%20testing/logout_unwzdg.jpg)

#### Register and the required attribute

##### Expexted

1.  I was expected to register filling up the form fields and to get the required pop up message in case of any mistake.

##### Results

1.  As a result, I achieved all functionalities that I was expected. [View here](https://res.cloudinary.com/anto8913/image/upload/v1628442651/3rd%20milestone/manual%20testing/register_username_tgzzij.jpg) [View here](https://res.cloudinary.com/anto8913/image/upload/v1628682479/3rd%20milestone/manual%20testing/register_to_mongo_rlzfiv.jpg) [View here](https://res.cloudinary.com/anto8913/image/upload/v1628682614/3rd%20milestone/manual%20testing/mongo_db_user_p4sefr.jpg).


### Known Bugs

1. During the testing process I got 1 repeating error and 1 warning, which I already mentioned here in the validation test [view here](Documentation/Validation-test-PDF/validation-test.md). The error is the following: div and h4 elements are not allowed to be child of ul element, and the warning is a suggestion to consider to use h2 or h6 elements for identifying headings. As I mentioned in the validation test, I decided not to do this because they can break the layout of the website and can not fulfil the developer's idea. I checked the website with these errors and they do not affect the functionality of the application, so I decided to leave everything unchanged.


## Deployment 

### Heroku Deployment

To deploy Family Hub to heroku, take the following steps:


1. Create a `requirements.txt` file using the terminal command `pip freeze > requirements.txt`.

2. Create a `Procfile` with the terminal command `echo web: python app.py > Procfile`.

3. `git add` and `git commit` the new requirements and Procfile and then `git push` the project to GitHub.

3. Create a new app on the [Heroku website](https://dashboard.heroku.com/apps) by clicking the "New" button in your dashboard. Give it a name and set the region to Europe.

4. From the heroku dashboard of your newly created application, click on "Deploy" > "Deployment method" and select GitHub.

5. Confirm the linking of the heroku app to the correct GitHub repository.

6. In the heroku dashboard for the application, click on "Settings" > "Reveal Config Vars".

7. Set the following config vars:

| Key | Value |
 --- | ---
DEBUG | FALSE
IP | 0.0.0.0
MONGO_URI | `mongodb+srv://<username>:<password>@<cluster_name>-qtxun.mongodb.net/<database_name>?retryWrites=true&w=majority`
PORT | 5000
SECRET_KEY | `<your_secret_key>`

- To get you MONGO_URI read the MongoDB Atlas documentation [here](https://docs.atlas.mongodb.com/)

8. In the heroku dashboard, click "Deploy".

9. In the "Manual Deployment" section of this page, made sure the master branch is selected and then click "Deploy Branch".

10. The site is now successfully deployed.


## Credits

### Code

[FontAwesome](https://fontawesome.com/)

The icons were taken form here 

[Materialize 1.0.0](https://materializecss.com/)

The navigation bar, carousel, collapsible menu, log in, register, create and edit recipe form, buttons, grid system and colours were taken here.

### Content

The recipes contents were taken form the website [giallo zafferano](https://www.giallozafferano.com/).

### Media

All photos were taken form the website [unsplash](https://unsplash.com/).

## Acknowledgements

My mentor gave me a lot of advice during our meeting call

Tutor support from CodeInstitute was essential.







