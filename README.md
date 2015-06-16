# FoodMe App — a workshop app built with AngularJS

Simplified meal ordering app for local restaurants built with AngularJS
and node.js backend.

Check out this doc for more info about the app: http://goo.gl/Xa0Ea

Also check out the commit history to see how the app was built piece by piece:

https://github.com/IgorMinar/foodme/commits/master

---

The app is build on top of [angular-seed](http://github.com/angular/angular-seed),
check out seed's README to understand what the scripts under `scripts/` are doing.

---

#### from http://goo.gl/Xa0Ea

### Dependencies:

- git: http://git-scm.com/
- node: http://nodejs.org/ (must be 0.8.x)
- On Linux, we recommend using NVM for installing Node.js

### Grab the code

- git clone git://github.com/IgorMinar/foodme.git
- cd foodme
- git checkout step-0

### Install local dependencies

- npm install

### Run Web Server (in separate terminal window)

- Mac/Linux
- ./scripts/web-server.sh
- Windows
- ./scripts/web-server.bat
- This will start a Node.js server and open your default browser on http://localhost:3000, where the app should be served.

### Run the unit tests (in a separate terminal window)

- Mac/Linux
- ./scripts/test.sh
- Windows
- ./scripts/test.bat
This will start Testacular, that will keep watching the files and whenever you make any change to a file, it will re-run all the unit tests.
It will also try to start Chrome. If you don’t have Chrome installed, you can specify another browser for Testacular to use. Eg. --browsers Firefox
