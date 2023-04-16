App initialization and setup
============================

## Install boilerplate

The app can be initialized with a: <br>
`npx create-react-app@latest react-admin`
<br>It creates the structure with the code populated finishing with:
```
Success! Created react-admin at /home/<path-to-app>/react-admin
Inside that directory, you can run several commands:

  npm start
    Starts the development server.

  npm run build
    Bundles the app into static files for production.

  npm test
    Starts the test runner.

  npm run eject
    Removes this tool and copies build dependencies, configuration files
    and scripts into the app directory. If you do this, you can’t go back!

We suggest that you begin by typing:

  cd react-admin
  npm start

Happy hacking!
```

## Install dependencies:

The app will require a few more bits like [material UI](https://mui.com/material-ui/getting-started/installation/), data-grid, react-router, sidebar, and [calendar](https://fullcalendar.io) with some [packages](https://fullcalendar.io/docs/initialize-es6), and [charts](https://nivo.rocks/) with core and some [components](https://nivo.rocks/components/). 
Can be installed with:

`npm install @mui/material @emotion/react @emotion/styled @mui/x-data-grid @mui/icons-material react-router-dom@6 react-pro-sidebar formik yup  @fullcalendar/core @fullcalendar/daygrid @fullcalendar/timegrid @fullcalendar/list @nivo/core @nivo/pie @nivo/line @nivo/bar @nivo/geo`

## Removing some directories:

The directories removed:
- src/setupTests.js
- src/logo.svg
- src/App.test.js
- src/reportWebVitals.js

To finish with:
- src/App.js
- src/index.css
- src/index.js

In `index.js` remove: `reportWebVitals();` and its import: `import reportWebVitals from './reportWebVitals';`

In `App.js` remove all header and imports and import `BrowserRouter` to wrap `App` around it.

## Font

in [google fonts](https://fonts.google.com/) get [Source Sans Pro](https://fonts.google.com/specimen/Source+Sans+Pro?query=Source+Sans+Pro) click on the font (400, 600 italic, 700 italic), get `import` copy and paste in `index.css`