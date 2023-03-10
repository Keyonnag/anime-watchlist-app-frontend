# Animuse

This is the Client Side React applications to see the RESTFULL API and server side code refer to https://github.com/Keyonnag/anime-watchlist-app-backend

Animuse is an anime watchlist app that allows users to keep track of the anime they want to watch or have already watched. This application was built using PostgresSQL, Express, PG, Axios, React, and Bootstrap CDN.

The app uses Jikan API to display a list of 9 random animes on the home page, filtered by only PG-13 animes to avoid any adult content. Users can generate a new list of 9 animes by clicking on the "More Anime" button. Users can also add an anime to their watchlist by clicking on the "Add to Watchlist" button on an anime card.

The watchlist page displays all the animes that the user has added to their watchlist. Users can update their review of the anime and also delete an Anime from the watchlist showing full CRUD functionality.

## Installation

To run the application locally, follow these steps:

1. Clone the repository to your local machine.
2. Install the necessary dependencies by running `npm install`.
3. If you would like to edit the backend view my other repository labeled react-mvp-backend
4. Start the server by running `npm start`.

## Dependencies

The following dependencies were used in this project:

- Express (react-mvp-backend)
- pg (react-mvp-backend)
- dotenv (react-mvp-backend)
- cors (react-mvp-backend)
- nodemon (devDependency) (react-mvp-backend)
- React
- bootstrap CDN
- axios

## API

The app uses the Jikan API to generate the list of animes on the home page. Visit the [Jikan API documentation](https://jikan.moe/docs) to learn more about the API.

## Future Improvements

- Add user authentication and authorization.
- Allow users to rate an anime and sort their watchlist by rating.
- Allow users to search for an anime and add it to their watchlist.
- Allow users to share their watchlist with friends.

## Authors

- Keyonna Garfine

## Acknowledgments

- The creators of Jikan API.
- The creators of PostgresSQL, Express, React, and Bootstrap.
