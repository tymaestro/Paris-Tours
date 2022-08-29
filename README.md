# Paris Tours

Paris Tours is an e-commerce website that allows users to browse potential tours of Paris and the surrounding area. Users can add tours to their basket and checkout including all e-commerce functionality.

![Responsive Pages](/media/readme/readme/responsive-image.png)


Live link can be found [here](https://biketours-2022.herokuapp.com/)

## User Stories
<br>

### Logged-Out User
<br>

As a standard (not logged-in) user, I would like to:
<br>

1. View the landing page and know that I'm on a website for tourists to Paris who want a guided tour of the city/suburbs

2. View available tours

3. Have a unique sign-up option with username and password

4. Be able to purchase tours without signing up for an account

5. Subscribe to the newsletter
<br>
<br>

### Logged-In User
<br>

As a registered (logged-in) user, I would like to:
<br>

1. Have a login option to log in to my previously registered account/profile

2. Choose from a range of tours and add them to my basket

3. Create a profile and have my details pre-filled for payment for efficiency

4. View my order history
<br>
<br>

### Superuser
<br>

As a superuser, I would like to:

1. Have the ability to add, edit and delete tours without being on the django admin page

## Project Goals

- Create a company for tourists to come together and explore the wonderful city of Paris and all it has to offer. Users of this site will be able to purchase tours that cater to all tastes. On the database side, CRUD functionality will be implemented so that superusers can create tours (with the ability to both edit and delete them as well) that allow both the business to flourish and visitors to the site to have a steady stream of updated tours at their disposal.

- Create a website for people in search of a walking or cycling tour of Paris and the suburbs. A combination of exploration, learning, and exercise.

## Facebook Screenshots

![Facebook Screenshot](/media/readme/readme/facebook-home-pp5.png)

![Facebook Screenshot](/media/readme/readme/facebook-post-pp5.png)

Link to the Facebook page can be found [here](https://www.facebook.com/Paris-Tours-105734778937431)

## Flowchart

![Paris Tours Flowchart](/media/readme/readme/flowchart-pp5.png)

## Entity Relationship Diagram

![Entity Relationship Diagram](ADD ENTITY RELATIONSHIP DIAGRAM HERE!!!)

## Business Model

- I chose a traditional B2C (Business to Customer) site to execute this project and sell my tours to my target market. This site has a clean and user-friendly interface that allows users to flow from page to page with no obstruction to them making a purchase. 

- Visitors to my site can purchase up to 10 of each tour (a limit of 10 allows tour guides to control numbers)

![Business Model](/media/readme/readme/business-model-pp5.png)

## Wireframes

[Home Web](/media/readme/wireframes/home-wire-web.png)

[Home iPad](/media/readme/wireframes/home-wire-ipad.png)

[Home iPhone](/media/readme/wireframes/home-wire-iphone.png)

[Basket Web](/media/readme/wireframes/basket-wire-web.png)

[Basket iPad](/media/readme/wireframes/basket-wire-ipad.png)

[Basket iPhone](/media/readme/wireframes/basket-wire-iphone.png)

[Newsletter Web](/media/readme/wireframes/newsletter-wire-web.png)

[Newsletter iPad](/media/readme/wireframes/newsletter-wire-ipad.png)

[Newsletter iPhone](/media/readme/wireframes/newsletter-wire-iphone.png)

[Payment Web](/media/readme/wireframes/payment-wire-web.png)

[Payment iPad](/media/readme/wireframes/payment-wire-ipad.png)

[Payment iPhone](/media/readme/wireframes/payment-wire-iphone.png)

[Profile Web](/media/readme/wireframes/profile-wire-web.png)

[Profile iPad](/media/readme/wireframes/profile-wire-ipad.png)

[Profile iPhone](/media/readme/wireframes/profile-wire-iphone.png)

[Tour Detail Web](/media/readme/wireframes/tour-detail-web.png)

[Tour Detail iPad](/media/readme/wireframes/tour-detail-wire-ipad.png)

[Tour Detail iPhone](/media/readme/wireframes/tour-detail-web-iphone.png)

[Tours Web](/media/readme/wireframes/tours-wire-web.png)

[Tours iPad](/media/readme/wireframes/tours-wire-ipad.png)

[Tours iPhone](/media/readme/wireframes/tours-wire-iphone.png)

[Sign-Up Web](/media/readme/wireframes/sign-up-wire-web.png)

[Sign-Up iPad](/media/readme/wireframes/sign-up-wire-ipad.png)

[Sign-Up iPhone](/media/readme/wireframes/sign-up-wire-iphone.png)

## Agile Methodology

The agile development of this project used issues in the project environment on [Github](https://github.com/users/tymaestro/projects/2)

## Features

### Navbar

The navigation bar gives you access to the tours page as well as an opportunity to either login with a previously created account or create an account via the sign up option. You can also purchase tours without creating an account and view your basket.

![Navbar Logged-Out](/media/readme/readme/navbar-notloggedin-pp5.png)

The navigation bar once you are logged in gives you the opportunity to create an account that will store your details for future visits, have an order history with us, as well as log out of your account.

![Navbar Logged-In](/media/readme/readme/navbar-detail-user-pp5.png)

The navigation bar as a superuser gives you the ability to add, edit or delete tours from the database in the Tour Management section.

![Navbar Superuser](/media/readme/readme/navbar-detail-superuser-pp5.png)

### Sign Up Page

The sign up page allows you to create an account by providing a username and password for authentication.

![Sign-Up Page](/media/readme/readme/signup-detail-pp5.png)

### Login Page

As with the sign up page, the login page allows previously registered users to access the extra functionality that having an account provides.

![Login Page](/media/readme/readme/signin-detail-pp5.png)

### Logout Page

The logout page allows you to confirm if you are sure you would like to logout

![Logout Page](/media/readme/readme/signout-detail-pp5.png)

### Home Page

The home page welcomes users to the site and gives information on the concept behind the site and encourages you to sign-up to gain access to features where you can create a profile and have a stored order history.

![Home Page](/media/readme/readme/homepage-detail-pp5.png)

### Tours Page

This page presents an ordered list of tours created by the superuser.

![Tours Page](/media/readme/readme/tours-pp5.png)

### Tour Detail Page

The tour detail page presents the selected tour in greater detail so users can gain more information about the tours.

![Tour Detail Page](/media/readme/readme/tour-detail-pp5.png)

As a superuser, there is functionality to edit and delete tours

![Tour Detail Page Superuser](/media/readme/readme/tour-detail-superuser-pp5.png)

### Add Tour Page

As a superuser, this page allows you to add a tour to the database.

![Add Tour Page](/media/readme/readme/add-tour-top-pp5.png)
![Add Tour Page 2](/media/readme/readme/add-tour-bottom-pp5.png)

### Edit Tour Page

As a superuser, this page allows you to add a tour to the database.

![Edit Tour Page](/media/readme/readme/edit-tour-superuser-pp5.png)


### Basket Page

This is a detail of the empty basket.

![Empty Basket](/media/readme/readme/empty-basket-pp5.png)

This is a detail of a basket with items in it. The total price is calculated and there is the option to update tours or delete them from the basket, as well as an option to proceed to the checkout.

![Basket with Items](/media/readme/readme/basket-detail-pp5.png)

### Checkout Page

The checkout page as a logged out user presents you with a summary of your basket and a form to fill out to pay for your items.

![Checkout Detail (logged out)](/media/readme/readme/checkout-detail-logged-out-pp5.png)

The checkout page as a logged in user allows you to have the payment fields pre-filled on the form.

![Checkout Detail (logged in)](/media/readme/readme/checkout-detail-user-pp5.png)

### Order Summary Page

The order summary page displays a summary of your order once successful payment has been received.

![Order Summary](/media/readme/readme/order-summary-pp5.png)

### Profile Page

The profile page allows you to view your profile details and order history. It also provides the option to unsubscribe from the newsletter.

![Profile Page](/media/readme/readme/profile-detail-pp5.png)

### Newsletter Pages

The newsletter signup page allows you to subscribe to our newsletter by providing an email address.

![Newsletter Signup](/media/readme/readme/newsletter-signup-pp5.png)

The newsletter unsubscribe page allows you to unsubscribe from the newsletter if you wish by providing your email to be removed from our database.

![Newsletter Unsubscribe](/media/readme/readme/newsletter-unsubscribe-pp5.png)

### Footer Detail

The footer displays social media links and the option to subscribe to the newsletter if you haven't already done so, or unsubscribe if you no longer wish to receive the newsletter.

![Footer Detail](/media/readme/readme/footer-detail-pp5.png)


## Features Left To Implement

- A review section so users can give feedback on how they felt about the tour. This has the mutual benefit of highlighting to site owners what is working well and what can be improved and to users so that they can have a fine-tuned and fresh range of tours to choose from.

- A calendar function so users can reserve a time slot in advance and company owners can know in advancce the numbers they will have for the tour

## Languages Used

Python

JavaScript

CSS

HTML

## Libraries, Frameworks, and Programs Used

Django.

Github was used for version control to store commit history.

Heroku was used to deploy our final project.

Balsamiq was used for wireframes.

FontAwesome for social media icons in footer.

Stripe was used for payments.

AWS was used to host media and static files.

## Testing

### Validator Testing

Python: Several "line too long" errors were returned when passing through the official [Pep8](http://pep8online.com/) linter.

These refer to:

- 

- 

HTML: No errors were returned when passing through the official [W3C](https://validator.w3.org/) validator.

CSS: No errors were returned when passing through the official [Jigsaw](https://jigsaw.w3.org/css-validator/) validator.

<hr>

### HTML Validation



<hr>

### CSS Validation

Base.CSS

[CSS Page](/media/readme/readme/css-validation-pp5.png)

Checkout.CSS

[Checkout CSS](/media/readme/readme/css-checkout-validation-pp5.png)

<hr>

### JavaScript Validation

<hr>

### Python Validation

#### Biketours Project

[ASGI](/media/readme/pep8/asgi-biketours-pep8-pp5.png)
[Settings](/media/readme/pep8/settings-biketours-pp5.png)
[URLs](/media/readme/pep8/urls-biketours-pp5.png)
[WSGI](/media/readme/pep8/wsgi-biketours-pp5.png)

#### Checkout App

[Admin](/media/readme/pep8/checkout-admin-pp5.png)
[Apps](/media/readme/pep8/checkout-apps-pp5.png)
[Forms](/media/readme/pep8/checkout-forms-py-pp5.png)
[Models](/media/readme/pep8/checkout-models-pp5.png)
[Signals](/media/readme/pep8/checkout-signals-pp5.png)
[URLs](/media/readme/pep8/checkout-urls-pp5.png)
[Views](/media/readme/pep8/checkout-views-pp5.png)
[Webhook Handler](/media/readme/pep8/checkout-webhook-handler-pp5.png)
[Webhooks](/media/readme/pep8/checkout-webhooks-pp5.png)

#### Home App

[Apps](/media/readme/pep8/home-apps-pp5.png)
[URLs](/media/readme/pep8/home-urls-pp5.png)
[Views](/media/readme/pep8/home-views-pp5.png)

#### Newsletter App

[Admin](/media/readme/pep8/newsletter-admin-pp5.png)
[Apps](/media/readme/pep8/newsletter-apps-pp5.png)
[Forms](/media/readme/pep8/newsletter-forms-pp5.png)
[Models](/media/readme/pep8/newsletter-models-pp5.png)
[URLs](/media/readme/pep8/newsletter-urls-pp5.png)
[Views](/media/readme/pep8/newsletter-views-pp5.png)

#### Products App

[Admin](/media/readme/pep8/products-admin-pp5.png)
[Apps](/media/readme/pep8/products-apps-pp5.png)
[Forms](/media/readme/pep8/products-forms-pp5.png)
[Models](/media/readme/pep8/products-models-pp5.png)
[URLs](/media/readme/pep8/products-urls-pp5.png)
[Views](/media/readme/pep8/products-views-pp5.png)

#### Profiles App

[Apps](/media/readme/pep8/profiles-apps-pp5.png)
[Forms](/media/readme/pep8/profiles-forms-pp5.png)
[Models](/media/readme/pep8/profiles-models-pp5.png)
[URLs](/media/readme/pep8/profiles-urls-pp5.png)
[Views](/media/readme/pep8/profiles-views-pp5.png)

#### Shop App

[Apps](/media/readme/pep8/shop-apps-pp5.png)
[Contexts](/media/readme/pep8/shop-contexts-pp5.png)
[URLs](/media/readme/pep8/shop-urls-pp5.png)
[Views](/media/readme/pep8/shop-views-pp5.png)

<hr>



<hr>

### Testing and debugging code

I have used Docstrings throughout my code to identify each function and its purpose.
<br>



## Lighthouse Accessibility

ADD LINKS TO LIGHTHOUSE SCREENSHOTS!!!

## Bug Fixes

- 

- 

- 

- 

## Deployment

### Heroku Deployment

1. Create a new app in the Heroku dashboard. Choose a name and location for your app.

2. Click the resources tab to add the Heroku Postgres database.

3. Click on the settings tab and reveal config vars. Copy the DATABASE_URL and paste it into the env.py file in your project. Make sure that the env.py file is in the .gitignore file.

4. Add a SECRET_KEY both to the env.py file and in the config vars on Heroku.

5. In the Gitpod settings.py file, remove the insecure SECRET_KEY and replace it with the environment variable (SECRET_KEY) that was created.

6. Replace existing DATABASES section in settings.py file with the DATABASE_URL environment variable that is located in the env.py file.

7. Ensure that all static and files have been added to the settings.py file in Gitpod.

8. Add the TEMPLATES_DIR to settings.py file in Gitpod and link it in the TEMPLATES section.

9. Make sure that the project name for the Heroku app has been added as an allowed host in Gitpod.

10. Ensure to create a Procfile and add web: gunicorn activities.wsgi to this file

11. Make sure that the DEBUG flag is set to False in settings.py file in Gitpod

12. Add X_FRAME OPTIONS = 'SAMEORIGIN' to the settings.py file to ensure that the Summernote editor works once the project is deployed.

13. Make sure that all dependencies have been added to the requirements.txt file using the command pip3 freeze > requirements.txt

If deploying through the CLI:

Using the CLI, enter the following commands to deploy to Heroku

1. Login to Heroku using the command heroku login -i

2. Enter your email address and password

3. Find the relevant app using the command heroku apps

4. Set the Heroku remote using the command heroku git:remote -a <app_name>

5. Add, commit and push to Github using the command git add . && git commit -m "Deploy to Heroku via CLI"

6. Push to both Github and Heroku using the command git push origin main (for Github) and the command git push heroku main (for Heroku)

## Credits

[Bootstrap](https://getbootstrap.com/) for some layout and styling features.

[TableConvert](https://tableconvert.com/markdown-generator) for the creation of tables in markdown.

## Acknowledgements

A very big thank you to my mentor Daisy McGirr who gave me very helpful feedback and was very encouraging during our mentor sessions.

Also, a big thank you to the Slack community over the course of this entire module.

Stack Overflow for any troubleshooting over the course of this project.