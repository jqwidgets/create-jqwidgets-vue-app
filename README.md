# create-jqwidgets-vue-app
Please refer to its documentation:
  - [Getting Started](https://github.com/jqwidgets/create-jqwidgets-vue-app/blob/master/README.md#getting-started) 
  - [jQWidgets Vue Documentation](http://www.jqwidgets.com/vue-components-documentation/)

This project is based on [Vue CLI](https://cli.vuejs.org/).

## Quick Overview
```sh
npm i -g create-jqwidgets-vue-app

create-jqwidgets-vue-app my-app
cd my-app
npm run serve
```

Then open [http://localhost:8080/](http://localhost:8080/) to see your app.<br>
When you’re ready to deploy to production, create a minified bundle with `npm run build`.

## Getting Started

### Installation

Install it once globally:

```sh
npm install -g create-jqwidgets-vue-app
```

**Make sure you have the latest version of [Node](https://nodejs.org/en/) on your machine**.

### Creating an App

```sh
create-jqwidgets-vue-app my-app
cd my-app
```

It will create a directory called `my-app` inside the current folder.<br>
Inside that directory, it will generate the initial project structure and install the transitive dependencies:

```
my-app
├── node_modules
├── public
├── src
├── .gitignore
├── babel.config.js
├── package.json
├── package-lock.json
├── README.md
```

Subfolders are not shown in order to keep it short.<br>
Once the installation is done, you can run some commands inside the project folder:

### `npm run serve`
Builds the app in development mode and starts a web server. <br />
Open [http://localhost:8080](http://localhost:8080) to view it in the browser. <br />
The page will reload if you make edits.

### `npm run build`
Builds the app and stores it in the `dist/` directory.

## Why Use This?

**If you’re getting started** with `jQWidgets` and `Vue`, using `create-jqwidgets-vue-app` is the easiest way to do this.  <br />
Just install, run and you will see an Vue jQWidgets Grid on your page. <br />
Then you can customize the project as much as you want, making something great.
