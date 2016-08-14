# Demo D8 component-based theme
This demo theme was built using [yeoman](http://yeoman.io/), [gulp](http://gulpjs.com/), [node.js](https://nodejs.org/en/), [npm](https://www.npmjs.com/), [kss](https://github.com/kss-node/kss-node), and other front-end tools.

This theme was created by [Mediacurrent](https://www.mediacurrent.com).

## Getting Started
If you haven't yet, install nvm:
https://github.com/creationix/nvm

### Run the following commands from the theme directory

#### Use the right version of node with:
`nvm use`

_This command will look at your `.nvmrc` file and use the version node.js specified in it. This ensures all developers use the same version of node for consistency._

#### If that version of node isn't installed, install it with:
`nvm install`

#### Install npm dependencies with
`npm install`

_This command looks at `package.json` and installs all the npm dependencies specified in it.  Some of the dependencies include gulp, autoprefixer, gulp-sass and others._

#### Runs default task
`npm run build`

_This will run whatever the default task is._

#### Compiles Sass
`npm run compile`

_This will perform a one-time Sass compilation._

#### Compiles Styleguide
`npm run styleguide`

_This will perform a one-time styleguide compilation._

#### Runs the watch command
`npm run watch`

_This is ideal when you are doing a lot of Sass changes and you want to make sure every time a change is saved it automatically gets compiled to CSS_

#### Cleans complied directory
`npm run clean`

_This will perform a one-time deletion of all compiled files within the dist/ directory._
