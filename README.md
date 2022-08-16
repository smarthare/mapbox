<p align="center">
    <a href="https://www.mapbox.com/n">  
        <img alt="mapbox-img" width="200px" src="https://camo.githubusercontent.com/fb4b319edc8e4001cf633fca4c2c6d93e77595159e1450c8f825eca3f41499a9/68747470733a2f2f7374617469632d6173736574732e6d6170626f782e636f6d2f7777772f6c6f676f732f6d6170626f782d6c6f676f2d626c61636b2e706e67" />
    </a>
</p>

## React Mapbox GL JS

React Component Library for Mapbox GL JS. Mapbox GL JS is a JavaScript library that renders interactive maps from vector tiles and Mapbox styles using WebGL.

This example generates random coordinates within a given bounding area and display them on the map.

<p align="center">
    <img alt="screenshot" width="100%" src="https://github.com/smarthare/mapbox-frontend/blob/main/images/mapbox.png" />
</p>

- [Backend](#backend)
  - [Installation](#installation)
  - [Running](#run-the-server)
  - [Endpoints](#endpoints)
- [Frontend](#frontend)
  - [Installation](#installation)
  - [Getting Started](#getting-started)
  - [Usage](#usage)

### Backend

- Built by Express and TypeScript.
- Supports API documentation.

#### Installation

Install the node modules.

```
yarn
```

#### Run the server

Runs the backend in the dev mode.

```
yarn serve
```

#### Endpoints

- API Documentation - [`http://127.0.0.1:8000/docs`](http://127.0.0.1:8000/docs)

- Generate Random Coordinates - [`http://127.0.0.1:8000/api/mapbox/coordinates`](http://127.0.0.1:8000/api/mapbox/coordinates)

### Frontend

- Built by React.js, Tailwind CSS, and TypeScript.
- Implemented Mapbox using [`react-map-gl`](https://www.npmjs.com/package/react-map-gl)
- Interacts with backend using [`axios`](https://www.npmjs.com/package/axios)

#### Installation

Install the node modules.

```
yarn
```

Set `MAPBOX_ACCESS_TOKEN` to enviroment variable.

- Add variable in `.env`
- Or add temporary variable in your shell

Your can take a closer look at this [reference](https://create-react-app.dev/docs/adding-custom-environment-variables/).

#### Getting started

Run the app in the development mode. Open [`http://127.0.0.1:3000`](http://127.0.0.1:3000) to view it in the browser.

```
yarn start
```

#### Usage

Enter the width and height of the bounding area and the number of coordinates, and then click `Plot` button.

```
width: 0 - 1200
height: 0 - 800
number: 0 - 100
```

Click where you want to know the coordinates.
