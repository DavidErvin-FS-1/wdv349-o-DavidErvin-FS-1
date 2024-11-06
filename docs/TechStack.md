# Tech Stack

## Application Design

What tool(s) will you use to create click-through designs of the application? List any UI kits you would like to utilize as well.

- To create designs for the RPG game, I plan on utilizing Figma for creating wireframes and mockups. I will also utilize UI kits like Tailwind CSS and React Icons to help with the design process.
## Front End Framework

List your approach for front end development. For example, React is an often used front-end solution for projects in addition to using moduleCSS, PropTypes, and an ESLint style guide.

 - [React](https://reactjs.org/): Used for building the front end of the application.
 - [Tailwind CSS](https://tailwindcss.com/): Used for styling the application.
 - [React Icons](https://react-icons.github.io/react-icons/): Used for adding icons to the application.
 - [Axios](https://axios-http.com/): Used for making HTTP requests to the backend.


## State Management

What is your proposed solution for managing data? This could mean utilizing a database, local-storage, and in general state management libraries for the application (e.g. Redux).

- To manage state in the application, I plan on using [Redux](https://redux.js.org/). Redux will be used to manage the state of the application and to handle data flow between components.

## Node

Node is often used to serve both an API and to render a front-end. This includes using best practices, npm, and npx. What do you propose?

- Node.js will be used to serve both the API and render the front end of the application. I will be using yarn for managing packages/dependencies and npx for running scripts.


## Express

Express is a popular framework to power an API. Describe your idea for building similar functionality offered by express: e.g. middleware, routes, controllers, sending and receiving JSON data.

- Express will be used to build the API for the application. It will be used to manage data like user data, character data, and game data.
- Middleware:
  - [Cors](https://www.npmjs.com/package/cors): Used to enable CORS with various options.
  - [Passport](http://www.passportjs.org/): Used for authentication.
  - [Bcrypt](https://www.npmjs.com/package/bcrypt): Used for hashing passwords.
  - [Dotenv](https://www.npmjs.com/package/dotenv): Used for loading environment variables from a .env file.
  - [MongoDB](https://www.mongodb.com/): Used for storing data.


## SQL/Postgres/Sequelize

A popular solution for relational database work is to utilize Sequelize as an ORM. Are you familiar with migrations, models, and seeding? What tools and solutions do you propose for your application? For example, utilizing an ORM to build out models with full validated CRUD.

- I plan on using MongoDB for the database. I will be using Mongoose to interact with the database. Mongoose will be used to create models, perform CRUD operations, and validate data. This choice was made due to its flexibility and ease of managing data.
