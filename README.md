** Electron?
Electron makes javascript developer build desktop app with javascript skills.

** How to start?
start with 
`
# Clone the Quick Start repository
$ git clone https://github.com/electron/electron-quick-start

# Go into the repository
$ cd electron-quick-start

# Install the dependencies and run
$ npm install && npm start
`

** Electron file structure
*** index.html
As always, index.html is window screen of app as html is. You can make your app with html tags. Don't forget add script with src='./renderer.js'.
*** main.js
It decides electron app's window size and events or it can be optimised for Mac too.
*** package.json
Same for npm package
*** preload.js
All of the Node.js APIs are available in the preload process.
*** renderer.js
 This file is required by the index.html file and will
 be executed in the renderer process for that window.
 No Node.js APIs are available in this process because
 `nodeIntegration` is turned off. Use `preload.js` to
 selectively enable features needed in the rendering
 process.
