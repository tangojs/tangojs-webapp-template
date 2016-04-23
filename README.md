# tangojs-webapp-template

Basic TangoJS application template.

## Browser support

Due to utilization of bleeding-edge web standards, browser support is limited.
Your browser should support:

* ECMAScript 2015
* Web Components
* CSS Grid Layout

Latest versions of Mozilla Firefox and Chromium (including derivatives) will
work.

In Firefox, you have to enter `about:config` in the address bar, and toggle
following flags:
* `dom.webcomponents.enabled`,
* `layout.css.grid.enabled`.

In Chromium, you have to enter `chrome://flags/` in address bar, and enable
*Experimental Web Platform features*.

## Getting Started

1. Make sure you have [Node.js](https://nodejs.org/) installed.

1. Clone this project:
   ```bash
   $ git clone https://github.com/tangojs/tangojs-webapp-template.git && cd tangojs-webapp-template/
   ```

1. Alter the `package.json` file - you probably want to change the `name`,
   `author` and `description` fields.

1. Pull the dependencies:
   ```bash
   $ npm install
   ```
   Note that this also installs `devDependencies`. If you want a bare minimum
   without e.g. a http-server, then add the `--production` flag.

1. TangoJS has to be accessed from a web server (components are loaded via
   AJAX calls). You already have one, assuming you installed `devDependencies`.
   Just start it and visit `localhost:8080` in your browser:
   ```
   $ npm run server
   ```

1. Start building your app by editing the `index.html` file in your editor of
   choice. Remember to check the
   [TangoJS API Docs](https://tangojs.github.io/apidocs) and the
   [TangoJS Web Components Specs](https://github.com/tangojs/tangojs-web-components#readme).

1. Learn more about [connectors](https://tangojs.github.io) when you are
   ready for communication with real TANGO infrastructure.
