# webpack-babel-boilerplate
A webpack boilerplate that can be used at the start of future projects.


Webpack comes pre-configed for JS modules and Babel.


Package.json includes Babel CLI, Babel Loader, Env preset, Live-Server, Webpack, Webpack-CLI, and Webpack Dev Server.

<h3> Installing app </h3>
Install dependencies by using <code>npm install</code>

<h3>Scripts</h3>
<code>npm run dev-server</code> is to be run whenever in development mode.


<code>npm run build</code> is to be run in in production mode.

<h3>Webpack / JS Modules </h3>

Entry point is in /src/index.js. Any additional JS files in /src/ need to be exported and imported into index.js.


Running webpack compiles these files and outputs in /public/scripts/bundle.js. 


Babel turns any ES6 into ES5.
