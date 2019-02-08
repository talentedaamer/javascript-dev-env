# javascript-dev-env
JavaScript Development Envoirment

### EditorConfig
Add `.editorconfig` for unifying coding style. For more details visit <a href="http://editorconfig.org">http://editorconfig.org</a>. 

### Development Webservers

* http-server
* live-server
* express
* budo
* webpack dev server
* browsersync
 highly configurable is express.
 
`node buildScripts/srcServer.js` to start webserver.

### Share work with public

* localtunnel: simple and easy to use
* ngrok : same as localtunnel but password protected
* now: no firewall hole 
* surge: no firewall hole

#### usage localtunnel : 
* `npm install localtunnel -g`
* `ls --port 3000`
* or subdomain `ls --port 3000 --subdomain aamer`

### Task Automation

* grunt

write files to the disk. has a large plugin eco system.
* gulp

faster, no need to write to disk. also has large plugin ecosystem.

* npm scripts

easy to use, declared in package.json. directly use npm packages. largest package manager. simplicity of using npm package directly.
no need of seperate plugin, seperate docs, simple debuging, easy to learn. learn more bit.ly/npmvsgulp

#### using npm scripts

write scripts in `scripts {}` object of your package.json file. e.g `"start": "node buildScripts/srcServer.js"`

`prestart` will run before start `poststart` will run after start. 

you can use `pre` & `post` with scripts to run before and after.
