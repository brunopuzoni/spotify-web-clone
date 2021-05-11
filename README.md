# Spotify Functional Clone

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

It seeks to clone/enhance Spotify Web functionalities, such as Song/Artist search, lyrics display and login/authentication.

This is not an UI Clone. It has little to no styling, and was made to train skills on NodeJS, ReactJS and API usage.

## Installation - Execution

This project contains two directories, client and server. Each one has it's own set of dependencies, which need to be installed seperately.

### On one terminal

```
git clone https://github.com/brunopuzoni/spotify-web-clone.git

cd spotify-clone-reactjs/client

yarn install

yarn start
```

### Second terminal

```
cd spotify-clone-reactjs/server

yarn install

yarn start
```

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

## Dependencies

### Server

- Express
- Cors
- Dotenv
- Lyrics-Finder
- Spotify-Web-API-Node

### Client

- React, React DOM
- Bootstrap, React-Bootstrap
- React-Spotify-Web-Playback
- Spotify-Web-API-Node
- Axios
