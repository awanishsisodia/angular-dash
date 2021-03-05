


 Install express

 ``` bash
    $ npm install express
 ```
 Run Node.js server

 ``` bash
    $ node app.js
 ```
 Application will be available at http://localhost:3000.

2. Simple web server way

 Start any web server in "dist" directory, e.g. with Python
 ``` bash
    $ python -m SimpleHTTPServer 8080
 ```
 Application will be available at http://localhost:8080

In both cases static files (including bundled JS/CSS) will be served from "dist" directory.

## Running Application (development mode)
 Install dependencies:

 ``` bash
    $ npm install
 ```

 Install Bower dependencies:

 ``` bash
    $ bower install
 ```

 Run Grunt server task:

 ``` bash
    $ grunt server
 ```

 Application will be available at http://localhost:9000

## Building Application

 Application is built with Grunt.

 ``` bash
    $ npm install -g grunt-cli
    $ grunt
 ```

