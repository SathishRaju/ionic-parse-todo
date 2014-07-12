Parse Todo
===========

A simple todo app powered by [Ionic Framework](http://ionicframework.com/getting-started/) and [Parse](https://www.parse.com/) data storage.

## Using this project

Make sure the `ionic` utility is installed:

```bash
$ sudo npm install -g ionic cordova
```

And **register an application at Parse**. https://www.parse.com/.

Add your Parse application ID and Key, then open and edit file `www/js/services.js` and change the values with your parse app ID and key.

```javascript
var parseAppId = 'myappid',
    parseAppKey = 'myappkey';
```

Then run it:

```bash
$ ionic serve
```

Then open your browser at http://localhost:8100

If you want to run it as Android application, you should install the platform first.

```bash
$ ionic platform add android
$ ionic build android
$ ionic emulate android
```

More info on this can be found on the Ionic [Getting Started](http://ionicframework.com/getting-started) page.