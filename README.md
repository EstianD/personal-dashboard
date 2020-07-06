## Project Description

The Dashboard is a visualization tool that displays your activity details retrieved from the Strava API. It displays all activities recorded on strava and displays your callories burned for those activities. You can filter through your data by specified date. As my activity is mostly focused around running and cycling, I have added widgets that displays those data seperately at the top.
There are navigation links in a sidebar pointing to nutrition, blood and sleep. These are stats that are not yet added but I want to still incorporate into the dashboard in the future.

## Running the App

### `npm install`

Installs dependancies for app.

### `Add .env file`

To run this app you will need to add a few things to the .env file.

MONGODB_URI=mongodb://localhost:27017/personal-dashboard-db<br />
STRAVA_CLIENT_ID=<br />
STRAVA_CLIENT_SECRET=<br />
SESSION_KEY=<br />
PORT=4000<br />

## Scripts

In the project directory:

### `npm run dev`

Runs the app in the development mode.<br />
Open [http://localhost:4000/login](http://localhost:4000/login) to view it in the browser.

### `npm run start`

Runs the app in the production mode.<br />
Open [http://localhost:4000/login](http://localhost:4000/login) to view it in the browser.
