# Week 7 Assignment

## Elevator Pitch
 For the final project, I would like to create a dictionary word search and word memorization application - This application allows users to search words from the owlbot dictionary api, then add select words to their collection to review later. Words in the users collection can be reviewed as flashcards or as dynamically generated tests. This a handy application for individuals to both look up the meanings of words and then review those words later to improve their vocabulary.

The main inspiration for this application comes from existing websites like dictionary.com and quizlet.com. Quizlet.com is application that allows you to create your own flashcards and quizzes. I'm hoping to make a simplified version of this by using pre-existing data from the owlbot api and focusing specifically on words rather than other types of media which is allowed on quizlet.com

While brainstorming I was focused on finding a project that would allow me to integrate all of the topics we have discussed including react-router, fetch api, firebase authentication, and firebase firestore.

## Wireframes and Design Concept
My design concept for this project is a minimalist approach with lots of whitespace and some pops of color with the patterns found [here](https://products.ls.graphics/paaatterns/) as inspiration. As a stretch goal I would love to set up a themeing functionality in which the user can change the theme and switch between a light and dark mode. Mobile responsiveness will be in consideration throughout the process of design and implementation as well.

Here are some wireframes for the homepage, search results, and users' collection page. These are not all the view of the webpage, but a starting point to begin working on my final project.

![Wireframe](/images/Views.png) 



## Dependencies
  * React
  * Firebase Authentication
  * Firebase Firestore
  * [Owlbot API](https://owlbot.info/) (for dictionary queries)
  * [Wordnik API](https://developer.wordnik.com/) (to get "word of the day" functionality - still waiting to obtain the api key)
  * [Styled Components](https://styled-components.com/) for CSS in JS
  * React Router Dom for routing
  * [Paaatterns](https://products.ls.graphics/paaatterns/) for themeing
  * Proptypes
  * Github pages for deployment
## Tasks to Complete
  Here are a list of tasks necessary to meet MVP
  * Setup create-react-app scaffold
  * Connect application with Firebase firestore and Authentication
  * Set up react-router-dom routing to home, sign-in, and collection pages
  * Create essential components like: navbar, searchbar, login, cards, etc.
  * Set up fetch call to the owlbot api 
  * Map api data to individual definition cards to display data
  * Create function to save words to individual user's word collection through firestore
  * Create collection page which collects individual user's word collection and display's data
  * Create delete function to a remove individual word from a user's collection
  * Create update form and function to add user's own examples and updates to a word in their collection

  Once basic CRUD functionality and MVP tasks are met, I can begin working on some of the following bonus features
  * Create a review page which puts individual words into flashcards like the codepen example I've created [here](https://codepen.io/wandrew8/pen/jObqLzv?__cf_chl_jschl_tk__=12c4d3f0683918315125247d7155b581e3a4f3da-1590361913-0-AWuQhqAvHemKxS0pEVdHBTzlq9URrXHB5lqtfheXNtLnW6cXGIAUZY_W0CBegEiqb-hn6Z9azsmVmFyguVYoxjy_ICPFeYqkyIPp8mHRP_qxfT21doxn419CwhtqOxyvrVm5bCQ3KTfdHoxpF-yEwp5lmwfsLxtI9WpCa1JoE4xH8yiL6Ybnuy6vncUbKPHvh-pEqVbO59AQVNlVNrUNNxij0MOakCp4-e8IN2vKasJLnXV-3AOZ4lzn_QfWCN39CoSylym3RGyppKQPvCDsOeWuzLpdJS0m_HFqJmtBGMAvNkMad33OS1b5FnHlpM2DB_Nb7swdogsm9L13UmxcB4uMjDygb2xarqJzCHe_RX9q) 
  * Create a vocabulary test page in which words from a user's collection are randomly selected and used to dynamically generate a test. Similar functionality to the example [here](https://quizlet.com/22026755/test), but simplified. 

## Plan
| Week          | Tasks to Complete                                                      | 
| ------------- |----------------------------------------------------------------------| 
| Week 1        | Scaffold out project<br>Install dependencies<br>Set up global styles and variables for use with styled components<br>Connect app to firebase store and authentication<br>Route pages using react router<br>Verify that the owlbot api connects properly and data can be used as intended<br>Build core components   | 
| Week 2        | Build card components with data from owlbot API<br>Begin creating styled components<br>Make sure flow of core functionality is working and polished<br>Add create, update, and delete functionality to a user's word collection<br>      |  
| Week 3        | <br>Deploy app and work out any bugs that may arise<br>Add extra components like modals, toasts, etc that may add to user flow<br>Stretch Goal - Add review page with user's word collection accessible as flashcards<br>Stretch Goal - Create themeing and light / dark modes<br>Super Stretch Goal - Create test page to dynamically generate tests based on user's word collection  |  