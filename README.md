<a href="https://courses.toddmotto.com" target="_blank"><img src="https://toddmotto.com/img/ua.png"></a>

# Ultimate Angular: Master App

> This repo serves as the seed project for the master course as well as the final solution in a separate branch, come and [learn advanced Angular](https://courses.toddmotto.com) 1.5 architecture and components!

[Setup and install](#setup-and-install) |
[Tasks](#tasks) |
[Resources](#resources)

----

## Setup and install

Fork this repo from inside GitHub so you can commit directly to your account, or simply download the `.zip` bundle with the contents inside.

#### Dependency installation

During the time building this project, you'll need development dependencies of which run on Node.js, follow the steps below for setting everything up (if you have some of these already, skip to the next step where appropriate):

1. Download and install [Node.js here](https://nodejs.org/en/download/) for Windows or for Mac.
2. Install firebase CLI on the command-line with `npm install -g firebase-tools`
3. Install Gulp CLI on the command-line with `npm install -g gulp`

That's about it for tooling you'll need to run the project, let's move onto the project install.

#### Project installation and server

Now you've pulled down the repo and have everything setup, you'll need to `cd` into the directory that you cloned the repo into and run some quick tasks:

```
cd <master-seed-app-folder>
npm install
```

This will then setup all the development and production dependencies we need.

Now simply run this to boot up the server:

```
npm start
```

Everything you do will be inside of `/src`, and everything is compiled and outputted inside `/dist`, this is the same for both local development and deployment.

## Tasks

A quick reminder of all tasks available:

#### Running the local server

```
npm start
```

#### Running the tests

```
npm test
```

#### Deploying to firebase

You'll need to ensure you're logged into firebase first (if you are prompted, otherwise skip to next step):

```
firebase login
```

To deploy:

```
npm deploy
```

This will then use the `gulpfile.babel.js` tasks to build the project and deploy it all fully minified to your Firebase account. You'll then be shown the full URL of your project in the terminal for viewing your live app!

## Resources

There are several resources used inside this project, of which you can read further about to dive deeper or understand in more detail what they are:

* [Firebase Docs](https://firebase.google.com/docs/)
* [AngularFire Repo/Docs](https://github.com/firebase/angularfire)
* [npm](https://www.npmjs.com/)
* [Gulp.js](http://gulpjs.com)
* [ngAnnotate](https://github.com/olov/ng-annotate)
* [ngTemplateCache](https://github.com/miickel/gulp-angular-templatecache)
