# now-playing

![now-playing demo](https://eashwar.github.io/images/now-playing-demo.gif)


This is a simple [Express](https://expressjs.com) app that allows you to control spotify playback from the command line. Feel free to modify it however you want!

## Prerequisites:

* [jq](https://stedolan.github.io/jq/)
* [npm](https://www.npmjs.com/)
* [node](https://nodejs.org/en/)


## Setup:

1. Clone this repository.
2. Add this repository to your `PATH`.
3. Run `npm install` from the root directory to take care of dependencies.
4. Run `node app.js` from the root directory.
5. Navigate to localhost:6290 in your web browser, and authorize the app's access to your account.
6. If you see the success page, you should be good to go! **NOTE: Leave the server running in order for the app to function.**

## Currently Available Commands:

* `spotify` will echo the currently playing song.
* `spotify next` and `spotify prev` will skip one song forward and backward in the queue, respectively.
* `spotify pause` and `spotify play` will stop and start playback.
