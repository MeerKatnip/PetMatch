<p align="center">
<img src="images/petMatchLogo.png">

#### Purpose of the app:
This app was created to simplify the process of locating a pet for your family from the Houston, TX area. There are many shelters and rescues in this city, and we have aggregated all of the cats and dogs in the Houston area available for adoption.

#### How to use:
A user may view all available animals with or without creating an account. From the Home page, a user can navigate to either Dogs, Cats, or Both to display available animals. The user will then click on the photo of the desired animal, which will bring up the specific animal's details page. Pertinent information from the PetFinder database is displayed, including name, description, breed, age, gender, size, color, location and any special needs information.

#### Features on the app:
Utilizing the PetFinder API, both dogs and cats have a dedicated page displaying the 20 most recently-listed animals from local shelters. 
  - A user can login and access their account on the site. 
  - An account can be made securely as the password information is stored on the server as a hash string with bcrypt.
  - A user can select Both to view the 20 most recently-listed cats and dogs in the Houston area together on one page.

  
  Planned features for future development:
  - Utilize the Favorites designator and assign a favorited animal to the user's account.
  - Find My Match! filtering quiz that allows the user to narrow down animals based on search criteria relevant to their household composition and family needs.

## Site Preview

**Home Page:**
![PetMatch](/images/petMatchPreview.gif)

**Log-in screen:**
![PetMatch](/images/loginPreview.gif)

## Live Link

[PetMatch live link](https://serene-mountain-01139.herokuapp.com/home)

## This site was built by:

* [Rickelle Tackitt](https://github.com/RickelleDawn)
* [Hannah Lima](https://github.com/#)
* [Keith Willis](https://github.com/WillisK-0)
* [Amy Roy](https://github.com/MeerKatnip)

## Database and API used:

* This project was built with [Amazon RDS](https://aws.amazon.com/rds/) and deployed on [Heroku](https://www.heroku.com/)
* The API used for this project is [PetFinder API](https://www.petfinder.com/developers/)

## Language and Frameworks used:

JavaScript, PostgreSQL, Sequelize, Node.js, Mustache, Bootstrap, bcrypt, EXPRESS, HTML, CSS