# crudNodeJS
A simple CRUD in NodeJS example 

### Routes

- `POST /projects`: The route should get `id` and` title` inside the body and register a new project into an array in the following format: `{id:" 1 ", title: 'New project', tasks: []}`; Be sure to submit both the project ID and title in double-quoted string format.

- `GET /projects`: Route that lists all projects and their tasks;

- `PUT /projects/:id`: The route should only change the project title with the id present in the route parameters;

- `DELETE /projects/:id`: The route should only change the project title with the `id` present in the route parameters;

- `POST /projects/:id/tasks`: The route must receive a `title` field and store a new task in the task array of a specific project chosen through the` id` present in the route parameters;

### Run

- Install [yarn](https://yarnpkg.com/lang/en/)

- `yarn install` to install the dependencies 

- `yarn dev` to run server(you can find the script in package.json)

- You need to set in [Insomnia](https://insomnia.rest/download/) or[Postman](https://www.getpostman.com/) to test the routes


