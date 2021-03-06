# Project #2: Building Your First Backend Application

## RoadMap
 * Intro - 4/9
 * Proposals Due - 4/13
 * Proposal Finalized - 4/16
 * Attend initial mandatory standup - 4/16
 * Attend standups or use progress form - Tu/We/Sa
 * Attend Office Hours at least once
 * Submit Your Work + Present - 4/30

## Technical Requirements
For this project, you will be making a full CRUD app using the technologies outlined below. When thinking of an app idea, try to frame the project in terms of trying to solve a "problem" and think about the purpose of the app, who would use it, etc. The problem doesn't have to be anything intense and can be something small and simple! For example:

  >**Problem:** I have a huge enamel pin collection and want to organize it all in one place<br>
  >**General App Idea/Purpose:** An app that allows me to catalogue all my pins by category <br>
  >**Who Would Use It:** Pin collectors
  
You will use Handlebars, or EJS to build templates that do server-side rendering, or build a frontend that uses fetch or axios and DOM-manipulation based on JSON from your backend (in the style of the [GAphy app](https://git.generalassemb.ly/flex-125/express-api-lab))

Do Not Do Non-CRUD Applications Such As:
 - Games
 - Portfolio, or presentational pages
 - Marketing or content oriented websites

### &#128994; Proposals:
#### Proposal Requirements

* User stories detailing app functionality
* MVP + Stretch Goals
* Wireframes with basic page layouts
* Models including field names and their datatypes
* A list of routes (e.g. `POST /pins/ allows users to post a picture of a pin`)

You will meet with an squad leader to get your app idea approved. Be sure to write out what features you will need to build in order to meet MVP and some stretch goal ideas.

**Submit Project proposal [here](https://git.generalassemb.ly/flex-125/project-2/issues/new?assignees=&labels=&template=project-proposal-submission.md&title=Your+Name+%7C+Section+Color) by Tuesday April 13 6:00pm ET.**

### &#x1F534; Mandatory to pass:
#### MVP - Minimum Viable Product

* A working full-stack application, built by you, using **Node.js, Mongoose, Express and {EJS || HBS || DOM manipulation}**
* Adhere to the **MVC** file structure: Models, Views, Controllers
* At least one model with all 5 **RESTful routes** and full **CRUD**.
* :heavy_exclamation_mark: A git repository **not inside the class repo**.  (to github.com)
* At **least one** Github commit per "day of class".
* **Be deployed online** and accessible to the public via **Heroku**
* **A ``README.md`` file** with explanations of the technologies used, the approach was taken, unsolved problems, and notes to yourself so you can come back to your project later in the course and be able to pick up your train of thought, etc
* Inside Your `README.md`:
    * Include User Stories
    * Include **wireframes** that you designed during the planning process
    * Have a **link to your hosted working app**.

### &#x1F535; Stretch Goals (Not Mandatory):

* Add a second model that are associated in some way (e.g. one-to-many, many-to-many, etc) see [this lesson for notes](https://git.generalassemb.ly/flex-125/express-apis-json#crud-with-two-related-models)
* Include portfolio-quality styling
* Use a CSS framework like Skeleton, Bootstrap, Materialize, etc...
* Use a third party API
* Incorporate **Google Maps**
* Allow users to upload files with **Multer** (note, this can be tricky with heroku)
* Enable user authentication with **passport.js**

## GitHub Project Repo

:heavy_exclamation_mark: **REMEMBER:** For all projects, you will be creating the new repo's on [GitHub](https://github.com/), **not** GitHub Enterprise!


## Setup for Heroku Deployment


We will walk through deploying your app to production next week. We'll use a service called Heroku. Feel free to read through the docs and see if you can deploy on your own.

[Heroku Node App Deployment Docs](https://devcenter.heroku.com/categories/nodejs-support)

To prepare for the Heroku deployment lesson on **April 16th**.


## Technical Demonstration

All projects will be presented to the class. Your presentation should be:

* **Approximately 5-10 minutes in length**
* Save some time for Q&A at the end
* Shows off all features of the app
* Explains the technical details
* Explains the technical challenges
* Explains which improvements you might make
* Talk about one new thing you learned during this project (can be something technical, or even something more open ended like time management, etc.)

You will be sharing your app and your code.  Be prepared to answer questions from the instructors and other students.


## How to Submit Your Project


Your project is due on saturday, April 30 at 9:00 AM ET. You will present your project and show your code to classmates and instructors.

:heavy_check_mark: Submit your project by adding an issue to [this repo](https://git.generalassemb.ly/flex-125/project2-gallery/issues).

Your issue should include:

- Link to your GitHub Repo
- Link to your deployed Heroku app.

<br>


## Where to go for help during project week

We ask that you take the following steps when dealing with technical questions...

- Google your exact problem or error
- Reference the appropriate lesson plan
- Use the [rubber duck method](https://rubberduckdebugging.com/)
- After this steps if you still facing the issue, post your question on the Debuging Channel. (Explain your issue and post a piece of your code in the thread, so the channel don't get to much clutter.)

If your question is non-technical -- you're feeling overwhelmed, or you have questions about a homework or project prompt -- please reach out directly to an **Section Lead + IA** as soon as possible.

Also:
- Use your squad standup and Study Room to work with people on the same problem.
- Use in-class and out-of-class Office Hours*

*: token required

### Office Hours Tokens

Each student will get *6* tokens to utilize Office Hours during Project 2. Tokens are designed to get you industry ready and be ready to debug issues yourself. 

Each time a student signs up for Office Hours - during in-class office hours, or inidividual insturctor office hours outside of class time - takes 1 token. Office hours get you 15 minutes of debugging support.

To maximize your time, make sure to prepared to discuss: 1.) "expected behavior" 2.) "observed behavior" 3.) debugging tried so far - console-logs server side, developer tools on the frontend, etc. 4.) solutions already tried.

Squad standups, and logistical questions (e.g. about requirements, project proposal, times, etc) to you squad-lead to not take a token. Study Rooms do not take a token.



## Etc.

<details><summary><strong>Suggested Ways to Get Started</strong></summary>

* **Wireframe** Make a drawing of what your app will look like in all of the stages of the app(what does it look like as soon as you log on to the site? What does it look like while the player is playing? What does it look like when the player wins / loses?).

* **Break the project down into different components** (data, presentation, views, style, DOM manipulation) and brainstorm each component individually.

* **Commit early, commit often.** Don???t be afraid to break something because you can always go back in time to a previous version.

* **Consult documentation resources** (MDN, jQuery, etc.) at home to better understand what you???ll be getting into.
</details>


<details><summary><strong>Think about...</strong></summary>

- **Creativity**  
Did you add a personal spin or creative element into your project submission? Did you deliver something of value to the end user?

- **Code Quality**  
Did you follow code style guidance and best practices covered in class, such as spacing, indentation, modularity, and semantic naming? Did you comment your code as your instructors have in class?

- **Problem Solving**  
Are you able to defend why you implemented your solution in a certain way? Can you demonstrate that you thought through alternative implementations?
</details>

## Exercise - Proposal + Elaborate on GAphy

Let's use Gaphy and think about how we'd build a sample proposal and also think about how we'd elaborate it into stretch goals. What kind of things would be cool to add? What would be the difficulty associated with them?

## Planning Resources + Advanced

Check out this [guide](./planning.md)


<details><summary><strong>Useful Resources</strong></summary>

* **[Heroku](http://www.heroku.com)**
* **[Good User Story Guide](https://www.atlassian.com/agile/project-management/user-stories)**
* **[Presenting Information Architecture](http://webstyleguide.com/wsg3/3-information-architecture/4-presenting-information.html)**
* **[Mongo Documentation](https://docs.mongodb.com/manual/)**
* **[Mongoose Documentation](http://mongoosejs.com/docs/guide.html)**
</details>
<hr>  
# sLib
