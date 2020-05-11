Course: SENG 513

Project: Eventica

Authors: Brian, James, Satyaki, Sadat, Albert, Andy 

Year: 2020

---

## Eventica

An event management application based on Eventbrite and built using [React](https://reactjs.org/), 
[Material-UI](https://material-ui.com/), [Redux](https://redux.js.org/), 
[Express](https://expressjs.com/), and [node.js](https://nodejs.org/en/). 
This repository is divided into two folders, one for the client-side
code and one for the server-side code.

### Steps to Run

#### Client

1. `cd client`
2. `npm ci` (only for the first time to install dependencies)
3. `npm start`
4. Visit `https://localhost:3000` on a browser to view the application

#### Server

1. `cd server`
2. `npm ci` (only for the first time to install dependencies)
3. `npm start`
4. Hit the endpoint `https://localhost:3001` for responses

Run `npm run watch` if you're modifying the server and want the server to restart upon changes.
