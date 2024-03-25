# webpack-demo

Demo following webpack use

# Basic Setup (getting-started)

- npm init -y
- npm install webpack webpack-cli --save-dev
- Create new project structure
  > webpack-demo
  > |- package.json
  > |- package-lock.json
  > |- index.html
  > |- /src
  > &nbsp;|- index.js

# HTML/JS implemented (getting-started)

- src/index.js coded
- index.html coded
- package.json coded

# Updated structure (creating-bundles)

- Updated project structure
  > webpack-demo
  > |- package.json
  > |- package-lock.json
  > |- /dist
  > &nbsp;|- index.html
  > |- /src
  > &nbsp;|- index.js
- npm install --save lodash

# Import lodash (creating-bundles)

- Updated src/index.js
- Updated dist/index.html
- Run npx webpack (generates dist/main.js)

# Config file added (using-configuration)

- Updated project structure
  > webpack-demo
  > |- package.json
  > |- package-lock.json
  > |- webpack.config.js
  > |- /dist
  > &nbsp;|- index.html
  > |- /src
  > &nbsp;|- index.js
- Implemented webpack.config.js
- Run npx webpack --config webpack.config.js

# Scripts added (npm-scripts)

- Updated package.json to run npm run build command

# Asset Management setup

- Updated dist/index.html
- Updated webpack.config.js
