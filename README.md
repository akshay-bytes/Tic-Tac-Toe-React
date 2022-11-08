# Nano React App Default Javascript Template

The default template project for [nano-react-app](https://github.com/nano-react-app/nano-react-app).

- `npm start` — This will spawn a development server with a default port of `5173`.
- `npm run build` — This will output a production build in the `dist` directory.
- `npm run preview` — This will run the production build locally with a default port of `5173` (this will not work if you haven't generated the production build yet).

## Adding styles

You can use CSS files with simple ES2015 `import` statements anywhere in your Javascript:

```js
import "./index.css";
```

## Babel transforms

The Babel preset [babel-preset-nano-react-app](https://github.com/nano-react-app/babel-preset-nano-react-app) is used to support the same transforms that Create React App supports.

The Babel configuration lives inside `package.json` and will override an external `.babelrc` file, so if you want to use `.babelrc` remember to delete the `babel` property inside `package.json`.

##OVERVIEW

A movie search app that consumes an external API to display data.

Stack:

React
Styles with Styled Components
Develop locally
Clone this repo by running git clone https://github.com/Psycho-Patch/box-office.git
Install dependencies by running npm install
Run npm run start
Deployment
Deployed to github pages:

Open package.json and change homepage from https://github.com/Psycho-Patch/box-office.git to "https://YOUR_USERNAME.github.io/REPOSITORY_NAME"

Run npm run deploy
