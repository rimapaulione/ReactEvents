# ReactEvents project

<p> ReactEvents is a React application built with react-router-dom, designed to assist users in adding and removing their events and maintaining a list of events with dates and descriptions. Users can view the events list without signing in, but signing in is required for adding, editing, or removing events, and this is only accessible to registered users. Users can also sign up for a newsletter, although it is currently not fully functional; users will receive an alert upon registration. This functionality was added to illustrate the use of the useFetch hook. This application is an educational project offered as part of a course by Maximilian Schwarzmüller.</p>

<img src="/src/assets/reacteventslogin.png" alt="ReactEvents login" >
<img src="/src/assets/reactevents.png" alt="ReactEvents events list" >

## Used in App:

- react-router-dom with hooks;
- layouts and nested routs;
- loader and action in the router;
- query parameters;
- authentication for login and logout( with timer);
- localstorage for authentication token and expire time.

In the project directory, you have to run:

### `npm start`

Runs the backend in the development mode.\

### `npm start`

Runs the frontend in the development mode.\
Open [http://localhost:3000/](http://localhost:3000/) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.
