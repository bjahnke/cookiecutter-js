# cookiecutter-js
A template for creating web applications. It uses webpack for bundling and building the application, and the codebase primarily consists of JavaScript, HTML, and CSS.

## Project Structure
The project structure includes a source directory (`src/`) containing the main HTML, JavaScript, and CSS files. Configuration for webpack is split into common, development, and production files. The project also includes an ESLint configuration file for maintaining code quality.



### `src/`
- `index.html`: Main HTML file for the application.
- `index.js`: Main JavaScript file for the application.
- `styles.css`: Main stylesheet for the application.


## Project Management Files
- [webpack.common.js](command:_github.copilot.openSymbolInFile?%5B%22package.json%22%2C%22webpack.common.js%22%5D "package.json")
- [webpack.dev.js](command:_github.copilot.openSymbolInFile?%5B%22package.json%22%2C%22webpack.dev.js%22%5D "package.json")
- [webpack.prod.js](command:_github.copilot.openSymbolInFile?%5B%22package.json%22%2C%22webpack.prod.js%22%5D "package.json")
- [eslint.config.mjs](command:_github.copilot.openSymbolInFile?%5B%22package.json%22%2C%22eslint.config.mjs%22%5D "package.json")
- package.json
- LICENSE
- .gitignore

## Building and Running the Project
The `package.json` file contains various scripts for running and building the application:
- `npm start`: Starts the webpack development server.
- `npm run watch`: Builds the project with webpack in watch mode.
- `npm run build`: Builds the project with webpack for production.

## License
The project is licensed under the ISC License, as indicated in the LICENSE file.
