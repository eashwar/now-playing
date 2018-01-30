# now-playing

This is a simple expressjs app that allows you to control spotify playback from the command line.

## Setup:

1. Clone this repository.
2. Add this repository to your `PATH`.
3. run `node app.js` from the `authorization-code` directory.
4. Navigate to localhost:8888 in your web browser, and authorize the app's access to your account.
5. If you see the success page, you should be good to go! Leave the server running in order to allow the app to function.

These are the available commands:

* `spotify` will echo the currently playing song.
* `spotify next` and `spotify prev` will skip one song forward and backward in the queue, respectively.
* `spotify pause` and `spotify play` will stop and start playback.