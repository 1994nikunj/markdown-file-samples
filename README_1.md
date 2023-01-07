<img src="client/public/favicon.png" align="right" height=100/>

# OpenGlass: Showcase yourself through your work

> OpenGlass is a web app with the primary goal of serving as an application showcase platform where developers can exhibit their work and receive feedback from others via comments, likes, and contribution prospects.
- - - -
## Core Features
- [ ] Main Page: Search/Filter projects based on technologies.
2.Post Project: Authenticated users can add projects as per the defined schema.
3.My projects: Allows users to retrieve their project(s).
4.Individual project page:Displays details for the selected project and show relevant outline of information.
5.User Profile page:Displays the user’s project and other details.
6.Saved projects:Displays all the project(s) saved/bookmarked by the user.
7.Portfolio:Turn the Profile-Pageinto an portfolio website with an option to upload the resume.
8.Idea section: Post project ideas and allow contributors.
9.Edit/Delete project:Authenticated users can modify/delete their project(s).
10.Interaction:Authenticated users can Upvote/Comment on any project or Save/Bookmark them.

## Setup

### Clone from git repository
```
URL: https://github.com/khatri7/cs546-group36-final-project.git
```

### Setup

Install npm dependencies in both the `client` and `server` subdirectories and also the root directory using `npm install`.

```shell
> npm install
> cd server && npm install
> cd client && npm install
```

The root directory has been initialized as an npm project and installs [`concurrently`](https://www.npmjs.com/package/concurrently) as a dev dependency to start both the client and the server with a single command

Set up a MongoDB database either locally or online via <a href='https://www.mongodb.com/cloud/atlas'>MongoDB Atlas</a>

Create a `.env` file in both the `client` and `server` subdirectories as shown in the `.env.example` files

Set up the following environment variables

In `client/.env`:

```js
REACT_APP_SERVER_URL=http://localhost:3005/
```

In `server/.env`:

```js
MONGO_URL= //MongoDB database endpoint
MONGO_DATABASE= //name of the database
```

### Run

Finally, to run the code, from the root directory you can start the application using:

```shell
$ npm run dev
```
