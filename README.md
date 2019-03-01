# Angular Trello Board

## Features

- Trello Like Applcation!
- Angular FrontEnd Application | Material Design
- Node.js BackEnd | Express.js
- MongoDB Integration
- Boards
	- Add | Update | Delete
- Lists
	- Add | Update | Delete
- Cards
	- Add | Update | Delete


## Development Server

In order for you to use this Project, you need to have a [MongoDB](https://www.mongodb.com/) Account, and a Database Created.

After that, create a `config.json` inside the **backend** folder with the following data:

`{"mongo_url": "url to your database", "database": "database name"}`

With that done, you are good to run the project.

### FrontEnd

> Angular Application | Inside *frontend* folder

Run with `ng serve --open`.

Will open the Application in your Browser. If it doesn't navigate to `http://localhost:4200/`.


### BackEnd

> Node.js Application | Inside *backend* folder

First run `npm install`
Run with `nodemon app.js`.