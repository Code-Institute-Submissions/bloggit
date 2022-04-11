# Bloggit-Blog

The Bloggit blog is a full-stack application made mainly by Django full-stack web framework.

My goal was to create a functioning and responsive blog that allows users to sign in and make posts,
users are also able to like and comment on post.

As there are no limitiations in subjects that are posted on blog site users can choose any subject to post.

Site purpose is to allow users to share their knowledge about what they find interesting like hobbies, music, crtypto etc...

For this project i have many plans to expand site features, improve general code and add more modern design.

* This project is created using:

1.Django 3.2

2.Heroku (Deployement)

3.Heroku PostgresSQL

4.Bootstrap 4

5.Github(repository hosting)

6.Gitpod(deployement environment)


# UX User Experience

**User Stories**

* As a page user I want to be able to navigate the website intuitively
* As a page user, I want to easily find the signup section
* As a page user, I want to post comment and like relevant comment
* As a page user, I want to see when is post uploaded so i can see is it up to date
* As a admin user, I can log in so i can access ther site's backend
* As a admin user, I can see list of users
* As a admin user, I can edit or delete posts
* As a admin user, I can search for relevant post's to change it

# Agile approach

* I have taken an Agile approach to make my user stories as instructed in module by Code Institute.

![AgileApproach](/images/user-stories-finish.png)

# User testing

* I have tested the site functionality and created a Admin and non admin account.

Testing:
* Login/register/logout
* Creating post
* Comment on post
* Like on post
* Admin access to delete,edit, reupload the post

All features worked as expected.

---

# Design

**Color Scheme**

![main-colors.png](/images/bloggit-color-pallete.png)

* Colors were sourced from [Coolors](https://coolors.co/)
* To achieve good and simple contrast 6 colours were used: #361134, #B0228C, #FFFFFF, #E3E1E1, #445261, #F33F03.

---

**Typography**

* The main font's used in the site are Roboto & Lato.

---

**Favicon Icon**

* Favicon icon has been used from website [Icons8](https://icons8.com/icons/set/blog)

**Wireframes**

* [Balsamiq](https://balsamiq.com/) has been used to showcase the concept of the website.
>**Desktop version**
![wire1.JPG](/images-readme/wire1.JPG)
![wire2.JPG](/images-readme/wire2.JPG)
![wire3.jpg](/images-readme/wire3.JPG)
>**Mobile and Tablet version**
![wiremobile1.JPG](/images-readme/wiremobile1.JPG)
![wiremobile2.JPG](/images-readme/wiremobile2.JPG)
![wiremobile3.JPG](/images-readme/wiremobile3.JPG)

---

# Features


**Home Page**

![home-page.png](/images/home-page.png)


**Nav-bar**

![nav-bar.png](/images/nav-bar.png)


**Blog page**

![blog-page.png](/images/blog-page.png)


**Footer**

![footer.png](/images/footer.png)


**Like button**

![like.png](/images/like.png)


**Comments section**

![comments-section.png](/images/comments-section.png)


**SignIn**

![sign-in.png](/images/sign-in.png)


**SignUp**

![sign-up.png](/images/sign-up.png)


**Password reset**

![password-reset.png](/images/password-reset.png)


---

## Technologies Used

**Languages used**
* [HTML5](https://en.wikipedia.org/wiki/HTML5)
* [CSS3](https://en.wikipedia.org/wiki/CSS)
* [Python3](https://en.wikipedia.org/wiki/Python_(programming_language)

**Programs, Libraries, Frameworks & tools**
* [GitHub](https://github.com/) Github was used to store the project.
* [GitPod](https://www.gitpod.io/) GitPod was used for writing code.
* [GoogleFonts](https://fonts.google.com/) Google Fonts was used to import the fonts "Roboto" and "Lato".
* [FontAwesome](https://fontawesome.com/) Font Awesome was used to add icons to footer of website.
* [ChromeDeVTools](https://developer.chrome.com/docs/devtools/) Chrome Dev Tools used during development of website and to test responsiveness.
* [Django](https://www.djangoproject.com/)Framework used to build the site and Admin page
* [HerokuSQL](https://www.heroku.com/postgres)(Database used in project)

**Testing technologies**
* [W3C HTML Validator](https://validator.w3.org/nu/) W3C HTML Validator was used to validate HTML Code.
* [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) W3C CSS Validator was used to validate CSS Code.
* [Python Validator](http://pep8online.com/) Pep8 Validator was used to validate Python code.

**Hosting technologies**
* [Heroku](https://www.heroku.com/) Deployment and hosting environment.
* [Cloudinary](https://cloudinary.com/) Storing images and static files.
* [Github](https://github.com/) Hosting repository code.

---
## Testing

* I completed testing of the website application in multiple browsers: Brave, Chrome, Firefox and also used DevTools to confirm that the project is responsive and functional.
* I tested the website on different devices and operating systems Laptop (Windows), Tablet, (Android), and Galaxy Note 20 Ultra 5G (Android). The website worked perfectly on all devices.
* I confirmed that navigation, about section, and contact are all readable, and easy to understand.
* I can confirm that the login, SignIn, SignUp and SignOut works correctly but CSS Styling was not successfully implemented.
* The Website was tested on [ResponsiveDesign](http://ami.responsivedesign.is/#) but it was showing that website has X-Frame options set to same Origin or Deny, that was the reason why i was not showed with result of page responsive information.

**Code Validation**

[Nu Html Checker](https://validator.w3.org/nu/#textarea)

All tests were performed but Html Validator and results were showing some errors.

INDEX HTML

![index.html-testing1.png](/images/index.html-testing1.png)

INDEX HTML

![index.html-testing2.png](/images/index.html-testing2.png)

INDEX HTML

![index.html-testing3.png](/images/index.html-testing3.png)

BASE HTML

templates-base.html-testing 1

TEMPLATES BASE HTML

![templates-base.html-testing 1.png](/images/templates-base.html-testing%201.png)

TEMPLATES BASE HTML

![templates-base.html-testing 2.png](/images/templates-base.html-testing%202.png)

POST DETAIL

![post_detail-testing1.png](/images/post_detail-testing1.png)

POST DETAIL

![post_detail-testing2.png](/images/post_detail-testing2.png)

---


No errors were returned when passing through the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)
![css-testing.png](/images/css-testing.png)

---


**Lighthouse Report**

DESKTOP TEST

![lighthouse desktop testing.png](/images/lighthouse%20desktop%20testing.png)

MOBILE TEST

![lighthouse mobile testing.png](/images/lighthouse%20mobile%20testing.png)


## Unresolved bugs

**Gitpod terminal problems**

![models-problems.png](/images/models-problems.png)

![env-problems.png](/images/env-problems.png)

![manage-problems.png](/images/manage-problems.png)

![forms-problems.png](/images/forms-problems.png)

![urls-problems.png](/images/urls-problems.png)

![views-problems.png](/images/views-problems.png)

![settings-problems.png](/images/settings-problems.png)

![tests-problems.png](/images/tests-problems.png)

---

**Pep8**

All files that passed pep8 tests without errors.

![forms.py-testing.png](/images/forms.py-testing.png)

![apps.py-testing.png](/images/apps.py-testing.png)

![urls.py-testing.png](//images/urls.py-testing.png)

![views.py-testing.png](/images/views.py-testing.png)

![models.py-testing.png](/images/models.py-testing.png)

![admin.py-testing.png](/images/admin.py-testing.png)

---
---
## Deployment

**GitHub Pages**

The live deployed site can be viewed on Heroku Page [Bloggit](https://bloggit2022.herokuapp.com/)

**The site was deployed to Github pages** 
> These are the steps to deploy this project:
* Login to Github and go into repository [Bloggit](https://github.com/SirJarvis/bloggit)
* Click on settings and scroll down to Pages section on the page
* Under the source heading select the master branch option and click save
* The project has now been deployed and wait for approximate 10 minutes for the link to become active
* Refresh the page and click on the link to view the live site.
**Forking The Github Repository**

> By forking the GitHub repository, we create a clone of the original repository in our Github account. This allows us to make modifications to the files without affecting the original repository.
These are the steps:
* Please sign in to your GitHub account.
* Locate the repository to be duplicated, in this case [Bloggit](https://github.com/SirJarvis/bloggit).
* Locate and click the “Fork” button at the top of the [Bloggit](https://github.com/SirJarvis/bloggit) repository page.
* This creates a copy of the repository in our account, allowing us to make modifications.
**Making A Local Clone**
* Please sign in to your GitHub account.
* Locate the desired repository in this case [Bloggit](https://github.com/SirJarvis/bloggit).
* Locate the “Code” button at the top of the [Bloggit](https://github.com/SirJarvis/bloggit)   repository page. Click it and copy the HTTPS link that appears.
* Activate your local IDE terminal.
* Change the current working directory to the location where you wish the cloned file to be saved.
* In the terminal, type “git clone” and then paste the link copied from HTTPS.
* e.g "git clone [Bloggit](https://github.com/SirJarvis/bloggit)
* Clone has been made once you press enter.

---
**Deployment using Heroku**

  * Development Environment

    1. Create env.py it needs to contain these 4 variables.

      * Cloudinary can be obtained here [Cloudinary](https://cloudinary.com/)

      * Secret key is a password of your choosing make it a strong one [Djecrety](https://djecrety.ir/)

      * Obtain Heroku postgreSQL [Heroku](https://dashboard.heroku.com/apps)

        ```
        import os
        os.environ['DATABASE_URL'] = 'postgres: '...'
        os.environ['SECRET_KEY'] = '...'
        os.environ['CLOUDINARY_URL'] = '...'
        os.environ["DEVELOPMENT"] = "True"
        ```

    2. Create requirements.txt ```pip3 freeze --local > requirements.txt```
    
    3. Create Procfile containing application name to ensure proper formatting or deployment will fail.

    4. Commit and push changes to Github.

    5. Move to Heroku part of deployment.

  * Heroku
    6. Create an account with [Heroku](https://signup.heroku.com/).

    7. Create a new app, with an appropriate region and name.

    8. In **Resources** add **Heroku Postgres**.

    9. Within your newly created app
    go to settings go to **Config Vars**
    use the **DATABASE_URL** Value and add it to your env.py file and connect it via settings.py.

    10. Create a **SECRET_KEY** Key and the Value as the desired key.

    11. Next go to the **Deploy** tab next to **Deployment Method** click **GitHub** connect your account and repository.

    12. **Recommended** enable automatic deploys.

    13. At the bottom of the page hit deploy branch making sure it is set to **main**

---
---

## Credits

**Media**
* 1st test post image: https://pixabay.com/images/id-6531146/
* 2nd blog post image: https://pixabay.com/images/id-3052119/
* 3rd blog post image: https://www.gettyimages.ie/
* 4th blog post image: https://refreshmiami.com/lets-grab-the-future-of-finance-by-the-crypto-horns/
* The site fonts were taken from [GoogleFonts](https://fonts.google.com/)
* Icons were sourced from [FontAwesome](https://fontawesome.com/)
* Website colors were sourced from [Coolors](https://coolors.co/)


**Blog post Content**
* MICHAEL SAYLOR ON WHY THE FUTURE IS BRIGHT FOR BITCOIN blog content taken from: https://bitcoinmagazine.com/industry-events/the-future-is-bright-for-bitcoin
* WHAT IS BLOCKCHAIN content taken from: https://bitcoinmagazine.com/guides/what-is-blockchain
* WE ARE ALL SATOSHI NAKAMOTO content taken from: https://bitcoinmagazine.com/culture/we-are-all-satoshi-nakamoto


**Code**
* [MDN](https://developer.mozilla.org/en-US/), [W3SCHOOLS](https://www.w3schools.com/), [STACKOVERFLOW](https://stackoverflow.com/) were used on daily basis, to better understand the code.

* This readme document was based on research on several readme documents such as the Code Institute's readme [Sample](https://github.com/Code-Institute-Solutions/SampleREADME).

* I used the lessons learned during the Code Institute "Love Running" project to help with the structure of contact form.

**Acknowledgements**

* My partner, for her time, patience and effort and huge support.
* My mentor, Chris Quinn, for all valuable sessions, all advices and guidance.
* Code Institute and Slack community for their help and support at any time.