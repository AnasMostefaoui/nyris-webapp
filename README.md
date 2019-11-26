# nyris-webapp

## Getting started

1. Create a `settings.js` file in `public/js/`
2. run `npm ci` (clean install)
3. run `npm start`
3. Go to http://localhost:3000

Following Browser extensions are recommended for developing:

* React Developer Tools
* Redux DevTools

## Configuration

The configuration file is `public/js/settings.js`. You can use the example file as a guide.
Look at `SearchServiceSettings` in `src/types.ts` for a complete list.

## Architecture

This app uses react and redux. The main components are App and AppMD with `index.tsx` as the composition root.
The file `NyrisAPI.ts` contains the interface to the [nyris vision API](https://docs.nyris.io/).

## Available Scripts

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run mockserver`

Start a server for local testing. Change the URLs prefix to `http://localhost:8080` in your `settings.js` to use it.

