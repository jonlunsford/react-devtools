# The Stand-Alone App

This is useful for working on a React Native app *without* debugging in
chrome. The js runs in jscore, and the devtools talk to it through a
websocket.

You'll need webpack, and [electron](http://electron.atom.io/#get-started) (`npm install electron-prebuilt -g`).

- `npm install`
- `npm run build`
- `electron .`

Start up the packager, start up your app, and things *should* just connect
happily.

