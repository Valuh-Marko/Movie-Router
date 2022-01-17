# MOVIE ROUTER - MARKO VALUH - FRONT END

## About this application

This application is a showcase of a movie database API, it displays the latest movies, their current rating and much more. This app was used to learn react and styled components, along with working with API's.
**This is still in the development stage**.

## Steps to reproduce to start the TODO App

- In the console or the integrated terminal within the directory of the project run the following commands:

```
npm install
```

_Use this to install all the dependecies_

In the _src_ folder, create a **.env**, and add

```
REACT_APP_API_KEY=[api-key]
```

Replace **api-key** with your API key from the database

```
npm start
```

_This will start the development server._

## App workflow

- On the landing page, the most watch movie will be displayed up front, according to the database
- You can click on any individual movie to bring it to focus, switching to page to it's specific route
- You can search for any movie that you want in the search tab
- If you want to see more, just load more! :D

## Tech decisions

- [ReactJS](https://reactjs.org/)
- [Prop-Types](https://www.npmjs.com/package/prop-types/)
- [React Router](https://reactrouter.com/)

## Project Structure

- All of the components are structurized in the **components** folder
- The **hooks** folder holds all of our custom hooks
- _placeholder_ images and _svg_'s are in the images folder
- **GlobalStyle.js** is the main theme, basic styles are located there
- **helpers.js** is the holder for our helper functions
- **API.js** has all the API call operations
- **config.js** contains all the URLs used in the **API.js**

## Points of improvement

- Add the login sistem and allow the user to rank the movies
