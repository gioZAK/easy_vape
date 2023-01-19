# [Easy Vape](https://easyvape.herokuapp.com/)

EasyVape is a E-Commerce webpage, produced as my final project in [CodeInstitute](https://codeinstitute.net/global/). This is a fullstack website, which "sells" Vapes and E-Juices made by EasyVape, which is a fictional company.

The main technologies used were HTML, CSS, JS, Jquery, Python and Django. All images were created using [Dall-E-2](https://openai.com/dall-e-2/)

<img src="https://github.com/gioZAK/easy_vape/blob/1a012a31e3a82345e0cf7346b98fc98ff0967919/docs/ss/responsive-img-easy-vape.png">
 
[Click here](https://easyvape.herokuapp.com/) to visit the deployed website.


---

# Table of contents

1. [Website presentation](#website-presentation)
2. [Structure](#structure)
3. [UX](#ux)
4. [Agile Workflow](#agile-workflow)
5. [Business Plan](#business-plan)
6. [Technologies Used](#technologies-used)    
8. [Testing](#testing)
8. [Deployment](#deployment)
9. [Credits](#credits)

## Website presentation

In this section, I want to show you how to navigate this website, how to check for products, add products, check out, how to add a review, add to products to the wishlist and fill the contact form.

### Home

This is the Home Page, it includes the navigation bar, a jumbotron image with an invitation to shop and the footer.

<details>
<summary>
Home Page Image
</summary>
<img src="https://github.com/gioZAK/easy_vape/blob/991f111d0027fc5f231878ee8414ec5b9dce2c03/docs/ss/home-page.png">
</details>

### Navigation Bar

In the Navigation Bar the user is able to user the search bar, check for products, access the contact form, check his bag and by clicking on the account, he can access his profile and wishlist.

<details>
<summary>
Nav-Bar Image
</summary>
<img src="https://github.com/gioZAK/easy_vape/blob/991f111d0027fc5f231878ee8414ec5b9dce2c03/docs/ss/nav-bar-search.png">
</details>

<details>
<summary>
Search-Bar Results Image
</summary>
This is the result if the user searchs for "mint" in the search bar.
<img src="https://github.com/gioZAK/easy_vape/blob/main/docs/ss/search-bar-result.png">
</details>

<details>
<summary>
Account Image
</summary>
Here you can access your Profile, Wishlist. Register, Login or Logout.
<img src="https://github.com/gioZAK/easy_vape/blob/main/docs/ss/wishlist-access.png">
</details>

### Products

Here is the product list page, the user is able to see a list of products and choose which one he is interested.

<details>
<summary>
Products List image
</summary>
<img src="https://github.com/gioZAK/easy_vape/blob/main/docs/ss/all_products.png">
</details>

### Products Detail

Here in the Product Detail page, the user is able to select the product quantity, add it to the bag, add to the wishlist and write a review.

<details>
<summary>
Product Image
</summary>
<img src="https://github.com/gioZAK/easy_vape/blob/991f111d0027fc5f231878ee8414ec5b9dce2c03/docs/ss/product-detail.png">
</details>

### Adding Products to the Bag

Inside the Product Detail page, the user can add products to the bag, by clicking on the add to the bag

<details>
<summary>
Product Image
</summary>
<img src="https://github.com/gioZAK/easy_vape/blob/991f111d0027fc5f231878ee8414ec5b9dce2c03/docs/ss/product-detail.png">
</details>

After this, go to the bag icon on the top left, here in the bag page, you can increase the quantity or remove the products.
If the user is satisfied he can click on Secure Checkout to be redirected to the checkout page.

<details>
<summary>
Bag Page Images
</summary>
<img src="https://github.com/gioZAK/easy_vape/blob/main/docs/ss/bag-1.png">
<img src="https://github.com/gioZAK/easy_vape/blob/main/docs/ss/bag-2.png">
</details>

### Checkout

Here in the Checkout Page, the user is able to see his order items and total.
To complete the checkout you need to fill in the necessary forms.
If you want to test your purchase you can type "4242 4242 4242 4242" in the card field, Stripe will know this is a test

<details>
<summary>
Checkout Images
</summary>
<img src="https://github.com/gioZAK/easy_vape/blob/main/docs/ss/checkout.png">
<img src="https://github.com/gioZAK/easy_vape/blob/main/docs/ss/checkout-success.png">
</details>

Also, the user will receive an email with the purchase information.

<details>
<summary>
Checkout Email Image
</summary>
<img src="https://github.com/gioZAK/easy_vape/blob/main/docs/ss/order-confirmation-email.png">
</details>

<details>
<summary>
Checkout Email Images
</summary>
<img src="https://github.com/gioZAK/easy_vape/blob/main/docs/ss/checkout.png">
<img src="https://github.com/gioZAK/easy_vape/blob/main/docs/ss/checkout-success.png">
</details>

### Contact Form

If needed, the user can also write a Contact form. 
The site owner will be able to read in the admin page and he will also receive a email with your name and subject.

<details>
<summary>
Contact Form Image
</summary>
<img src="https://github.com/gioZAK/easy_vape/blob/main/docs/ss/contact-form.png">
</details>

### Wishlist

In the product detail page the user can add a product to the wishlist. In order to access the wishlist, you can click on manage wishlist or in the account menu in the top left of the nav bar.
Inside the Wishlist page you can see your favorite products there and remove them if necessary. 

<details>
<summary>
Wishlist Images
</summary>
Click on "Add to Wishlist" button <br />
<img src="https://github.com/gioZAK/easy_vape/blob/991f111d0027fc5f231878ee8414ec5b9dce2c03/docs/ss/product-detail.png">
In order to access your wishlist click on the "Manage Wishlist" <br />
<img src="https://github.com/gioZAK/easy_vape/blob/main/docs/ss/wishlist-access-product-detail.png">
Or you can click here. <br />
<img src="https://github.com/gioZAK/easy_vape/blob/main/docs/ss/wishlist-access.png">
This is your wishlist page <br />
<img src="https://github.com/gioZAK/easy_vape/blob/main/docs/ss/wishlist.png">
In order to remove click on the "Remove from Wishlist" Button. <br />
<img src="https://github.com/gioZAK/easy_vape/blob/main/docs/ss/wishlist-remove-item-1.png">
<br />
<img src="https://github.com/gioZAK/easy_vape/blob/main/docs/ss/wishlist-remove-item-2.png">
</details>

### Reviews

Inside the product detail page, the user can also add a review, which will be posted after the admin analyzes the review.

<details>
<summary>
Review Images
</summary>
<img src="https://github.com/gioZAK/easy_vape/blob/main/docs/ss/add-review.png">
<img src="https://github.com/gioZAK/easy_vape/blob/main/docs/ss/review-submited.png">
</details>

### Footer

The footer can be found on the bottom of every page. Here the user can access our [facebook](https://www.facebook.com/profile.php?id=100089498293818) and instagram or twitter, which were not created. The user can also see how to reach us and where to find, which are "fake" locations. And also, the user can subscribe to our Newsletter by adding his email and clicking on the subscribe button.

<details>
<summary>
Footer Image
</summary>
<img src="https://github.com/gioZAK/easy_vape/blob/main/docs/ss/footer.png">
</details>

## Structure

### Wireframe

Wireframe created using [Balsamiq](https://balsamiq.com/)


<details>
<summary>
Wireframe Home
</summary>
<img src="https://github.com/gioZAK/easy_vape/blob/main/docs/wireframe/home-wireframe.png">
</details>

<details>
<summary>
Wireframe Products List
</summary>
<img src="https://github.com/gioZAK/easy_vape/blob/main/docs/wireframe/product-list-wireframe.png">
</details>

<details>
<summary>
Wireframe Product Detail
</summary>
<img src="https://github.com/gioZAK/easy_vape/blob/main/docs/wireframe/product-detail-wireframe.png">
</details>

<details>
<summary>
Wireframe Bag
</summary>
<img src="https://github.com/gioZAK/easy_vape/blob/main/docs/wireframe/bag-wireframe.png">
</details>
</details>

<details>
<summary>
Wireframe Checkout
</summary>
<img src="https://github.com/gioZAK/easy_vape/blob/main/docs/wireframe/checkout-wireframe.png">
</details>
</details>

<details>
<summary>
Wireframe Profile
</summary>
<img src="https://github.com/gioZAK/easy_vape/blob/main/docs/wireframe/profile-wireframe.png">
</details>
</details>


### Data Scheme

## ERD

<details>
<summary>
ERD image
</summary>
<img src="https://github.com/gioZAK/easy_vape/blob/main/docs/ERD/models.png">
</details>
</details>


## UX


### Site User Goal

- 

### Site Goal

- 

## Agile Workflow

This project was created using Agile techniques during development, such as:

- User stories: displayed using GitHub Issues.
- MoSCoW method: by adding a priority to each issue and display it using tags.
- ToDo, In Progress and Done: using the GitHub Kanban board.

You can access the Kanban board that was used during the project development [here]().

You can access the list of issues/user stories used during the development of this project [here]()
<img src="">


[Back to Table of contents](#table-of-contents)

## Business Plan

## Technologies Used

### Main Tech

 - [Django](https://www.djangoproject.com/) 
 - [JavaScript](https://www.javascript.com/)
 - [Bootstrap](https://getbootstrap.com/)

[Back to Table of contents](#table-of-contents)
### Applications, Libraries and Platforms

- Git
    - Used for version control to commit to Git and Push to GitHub.
- Gitpod
    - Used as the IDE to write all the code used in this project.
- Github
    - GitHub is used to store the projects code after being pushed from Git.
- Heroku
    - Used to deploy the application.
- Google Fonts
    - Used to import the fonts.
- FontAwesome
    - Used to import icons.
- Balsamiq Wireframes
    - Used to create the project's wireframe.
- Amazon Web Services
    - Used to host all images.
- Django AllAuth
    - Used to deal with user account registration.
- Chrome DevTool
    - Used to debug and test new styles.
- ChatGTP
    - Used to debug.
- Dall-E-2
    - Used to create all Images.


## Testing
- I have used automated test and manual testing to check if all the website's functionalities were working as intended.
   -

### Python Testing
- I have tested all python files and they all passed
- Tested with [CI pep8](https://pep8ci.herokuapp.com/)
<img src="">

### JavaScript Testing
- I have tested the script.js and it passed with no major error.
- The undefined variable is not a glitch.
- Tested with [JSHint](https://jshint.com/)
<img src="">

### CSS Testing
- I have tested the script.css file and it passed.
- Tested with [Jigsaw](https://jigsaw.w3.org/css-validator/)
<img src="">

### HTML Testing
- I have tested all templates and they all passed.
- Tested with [Validator.w3](https://validator.w3.org/nu/#textarea)
<img src=">

### LightHouse
- I have tested the all webpages with LightHouse

[Back to Table of contents](#table-of-contents)
### Manual Testing
 - Here is the sequence of manual test I have applied to check if all applications work.

#### As a user I want to register.
- Steps: 
    1. 
    2. 
    3. 
    4. 

- Outcome:
    -

#### As a user I want to 
- Requirements:

- Steps: 
    

- Outcome:
    

#### As a user I want.


[Back to Table of contents](#table-of-contents)
## Deployment
- In order to Deploy this project:
    1. Either fork or clone this project.
    2. Heroku setup.
    3. Follow the [link](https://docs.google.com/document/d/1P5CWvS5cYalkQOLeQiijpSViDPogtKM7ZGyqK-yehhQ/edit) to set up your ide. Credit do Code Institute

### Forking

- In order to Fork this repository:

    1. Access your GitHub account and find the relevant repository.
    2. Click on 'Fork' on the top right of the page.
    3. You will find a copy of the repository in your own Github account.

### Clone

- In order to Clone this repository:

    1. Create repository where you will work with this clone.
    2. Copy "https://github.com/gioZAK/easy_vape.git".
    3. Run the directory you want the clone to be.
    6. In your IDE's terminal type 'git clone' and the paste the URL you just copied.
    7. Press Enter.
    8. You now have a local clone.

### Heroku.
-To setup with Heroku:

   1. Create an account at heroku.com
   2. Create a new app, add app name and your region
   3. Click on create app
   4. Go to "Settings"
   5. Under Config Vars, add your sensitive data (creds.json for example)
   6. Now go to your IDE and connect your enviroment with heroku
   7. heroku login -i
   8. Then run the following command: heroku git:remote -a your_app_name_here
   9. Finally: git push heroku main

### Follow the instructions here.
- Further instructions can be follow from [here](https://docs.google.com/document/d/1P5CWvS5cYalkQOLeQiijpSViDPogtKM7ZGyqK-yehhQ/edit)
    - All credits to Code Institute.


## Credits

### Code Institute
- I have relied on the Code Institute Boutique Ado Walktrough Project in order to make my own.
- Special Thanks to all Code Institute staff for the support throughout the course.

### ChatGPT
- I have used [ChatGPT](https://chat.openai.com/chat) as a tool to debug and to guide me on how to apply new functionalities.

### Dall-E-2
- I have created all images using [Dall-E-2](https://openai.com/dall-e-2/)

[Back to Table of contents](#table-of-contents)