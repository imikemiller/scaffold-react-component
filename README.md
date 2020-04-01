![npm](https://img.shields.io/npm/v/scaffold-react-component)

# scaffold-react-component

Scaffold a React component with styles, tests and a story.

This tool is reasonably opionated and assumes you are using:

* React
* SCSS modules
* Jest (unit tests)
* Storybook (document components) 

Feel free to fork and modify if you're using something else.

## Installation
It's recommend to install this globally, so it's available across all projects.

`npm install -g scaffold-react-component`

## Usage

To scaffold a functional React component use, e.g.

`scaffold Modal`

To scaffold a ES6 class React component use, e.g.

`scaffold Modal --type class`

By default, the Storybook category will be set to 'Common', you can override this with the `--storybookCategory`/`--sb` argument, e.g.

`scaffold Modal --sb UI`

## Publishing a new version of this package
Make sure you have `np` installed globally: 

`npm install -g np`.

Run `np` and follow the instructions to publish the new package.