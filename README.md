Bedly Coding Challenge
===========================

The Bedly Coding Challenge is meant to be an exercise in understanding your workflow
through a small sample app. Please write and document code as if it were production
code and send us a link to the live application and a link to the Github (or Bitbucket, etc.) repository.

Readme
------

Regardless of whether it's your own code or our coding challenge, write your
README as if it was for a production service. Include the following items:

* Description of the problem and solution.
* Whether the solution focuses on back-end, front-end or if it's full stack.
* Reasoning behind your technical choices, including architectural. Trade-offs
  you might have made, anything you left out, or what you might do differently
  if you were to spend additional time on the project.
* Link to other code you're particularly proud of.
* Link to your resume or public profile.
* Link to to the hosted application where applicable.

How we review
-------------

Your application will be reviewed by at least three of our engineers. The aspects of your code we will judge include:

* **Architecture**: how clean is the separation between the front-end and the back-end?
* **Clarity**: does the README clearly and concisely explains the problem and solution? Are technical tradeoffs explained?
* **Correctness**: does the application do what was asked? If there is anything missing, does the README explain why it is missing?
* **Code quality**: is the code simple, easy to understand, and maintainable?  Are there any code smells or other red flags? Does object-oriented code follows principles such as the single responsibility principle? Is the coding style consistent with the language's guidelines? Is it consistent throughout the codebase?
* **Security**: are there any obvious vulnerability?
* **Testing**: how thorough are the automated tests? Will they be difficult to change if the requirements of the application were to change?
* **UX**: is the web interface understandable and pleasing to use? Is the API intuitive?
* **Technical choices**: do choices of libraries, databases, architecture etc. seem appropriate for the chosen application?


Functional spec
---------------

Prototype **one** of the following projects:
1) NYC Open Housing Data
2) NYC Rental Listings
The UX/UI is totally up to you. If you like, get creative and add additional features a user might find useful!

##### NYC Open Housing Data

Create a service that shows on a map some interesting insights using NYC housing  data. The user should be able to filter the view in at least one way.

The data is available on [NYC Open Data](https://nycopendata.socrata.com/data?cat=housing%20%26%20development)

##### NYC Rentals

Create a service that adds a rental listing to a Google Doc and sends an alert via SMS when a new rental is listed that hits key parameters(3 bedroom, <$3000, Midtown, etc.). The user should be able to adjust the key parameters.
The data is available on [Streeteasy](http://streeteasy.com/api/info).


Technical spec
--------------

The architecture will be split between a back-end and a web front-end, for instance providing a JSON in/out RESTful API. We will reccomend a few technologies but feel free to use any other technologies as well provided that the general client/service architecture is respected.


### Back-end
We reccomend using Node.js for the backend. That being said you’re welcome to use other backend technologies you might be more comfortable with. Feel free to mention in your README how much experience you have with the technical stack you choose, we will take note of that when reviewing your challenge.
You are also free to use any web framework. If you choose to use a framework that results in boilerplate code in the repository, please detail in your README which code was written by you (as opposed to generated code).


### Front-end
We recommend using [React](https://facebook.github.io/react/) as a framework on the front-end. 

**If you're not comfortable with React, that's okay.** While we'd prefer to see the front-end implemented with React, we know the learning curve can be steep especially for someone that hasn't used it before. 

#### Styling
Feel free to use one of the popular CSS frameworks for styling if you'd like, but if your specialty is creating beautiful html/css then don't limit yourself to a framework!

Host it!
--------

When you’re done, host it somewhere (e.g. on Amazon EC2, Heroku, Google AppEngine, etc.).



