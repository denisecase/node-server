# node-server

> Node.js makes it easy to create a folder-based web server using JavaScript

## Links

- [Demo](https://denisecase.github.io/node-server/)
- [Source](https://github.com/denisecase/node-server)

## Requirements

- A browser (e.g., Chrome)
- A text editor (e.g., VS Code, or Notepad++, or Chrome)

## Benefits

- Folder-based
- Easy to write
- More practice with JavaScript
- Node.js non-blocking event loop supports many concurrent requests

## Install Node.js

1. Install the lastest LTS version from the Node.js website
2. Recommended for Windows Users: Add ["Open PowerShell here as Administrator"](https://www.tenforums.com/tutorials/60177-add-open-powershell-window-here-administrator-windows-10-a.html).
3. Verify installation. Open Powershell in your working folder and run:

```PowerShell
node -v
npm -v
```

## Start your Server

Start your Server with either of these options. See the package.json for configuring npm scripts.

```PowerShell
node server.js
npm start
```

## Open a Browser Client

1. Open a web browser.
2. Go to the URL: <http://127.0.0.1:3001/> or <http://localhost:3001/>.

## Modify and Restart

1. Make changes to the server logic.
1. Use CTRL-C, CTRL-C to stop your server.
1. Restart the server to see your changes.

## Install Nodemon to enable live updates

1. Install nodemon globally - this is one of the rare packages to install globally.
1. In your folder, open PowerShell here as Administrator, install and check the version.

```PowerShell
npm install nodemon -g
nodemon -v
```

## Optional: Create a server from scratch

1. Create a folder for server-side code.
1. In the folder, create a file named server.js.
1. In the folder, open PowerShell and run npm init to generate a package.json with app information.

## Optional: Host your service

Running a service from your machine isn't usually the best. (Why?)

To make your service available, host it on a server running 24/7 (24 hours a day, 7 days a week). 
Explore Heroku for free, easy hosting.

## Terms

- Node.js platform
- npm (Node package manager)
- nodemon
- npm install {packagename}
- npm install -g {packagename}
- npm start
- package.json
- localhost (127.0.0.1)
- host
- port
- URL
- web server
- web service
- web client
- web request
- web response

## Reference

- [About Node.js](https://nodejs.org/en/about/)

## See Also

- [js-console](https://github.com/profcase/js-console)
- [js-gui](https://github.com/profcase/js-gui)
- [js-gui-vue](https://github.com/denisecase/js-gui-vue)
- [js-gui-storage](https://github.com/profcase/js-gui-storage)
- [node-server](https://github.com/denisecase/node-server)
- [node-express-app](https://github.com/denisecase/node-express-app)
- [node-express-chat](https://github.com/denisecase/node-express-chat)
- [node-express-mvc](https://github.com/denisecase/node-express-mvc)
