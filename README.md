# Shop-online
WELCOME TO SHOP-ONLINE
## Mục tiêu
-Xây dựng một trang web bán hàng với các chức năng cơ bản.
-Làm quen với lập trình front end
-Frontend:react js
-Backend:node js
## Công nghệ sử dụng
-Frontend:react js
-Backend:node js
* [AngularJS] - HTML enhanced for web apps!
* [Ace Editor] - awesome web-based text editor
* [markdown-it] - Markdown parser done right. Fast and easy to extend.
* [Twitter Bootstrap] - great UI boilerplate for modern web apps
* [node.js] - evented I/O for the backend
* [Express] - fast node.js network app framework [@tjholowaychuk]
* [Gulp] - the streaming build system
* [Breakdance](https://breakdance.github.io/breakdance/) - HTML to Markdown converter
* [jQuery] - duh
## Hướng dẫn cài đặt

Install the dependencies and devDependencies and start the server.

// Load module
var mysql = require('mysql');
// Initialize pool
var pool      =    mysql.createPool({
    host     : 'your host',
    user     : 'root',
    database : 'your database',
    debug    :  false
});
module.exports = pool;
For production environments...

```sh
$ npm install --production
$ NODE_ENV=production node app
```

## Plugins

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |


## Development

Want to contribute? Great!

Dillinger uses Gulp + Webpack for fast developing.
Make a change in your file and instantaneously see your updates!

Open your favorite Terminal and run these commands.

First Tab:
```sh
$ node app
```

Second Tab:
```sh
$ gulp watch
```

(optional) Third:
```sh
$ karma test
```
### Building for source
For production release:
```sh
$ gulp build --prod
```
Generating pre-built zip archives for distribution:
```sh
$ gulp build dist --prod
```

   
   
