<div align="center">  
  <img src="https://github.com/allanfantoni/proffy/blob/master/web/src/assets/images/banner.png?raw=true" alt="Proffy" />
</div>

***

<div align="right">
  <img src="https://i.imgur.com/CKgKBvN.png" alt="readme">
</div>

# Proffy

Proffy is an app which allows students to contact teachers of their interest based on the subject, day of week and time. It also allows teachers to sign up to the app.

<div align="center">

![GitHub last commit](https://img.shields.io/github/last-commit/allanfantoni/proffy?label=Last%20commit)
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)
[![Open Source? Yes!](https://badgen.net/badge/Open%20Source%3F/Yes%21/blue?icon=github)](https://github.com/Naereen/badges/)

</div>

## Table of contents

- [Proffy](#proffy)
  - [Table of contents](#table-of-contents)
  - [Project status](#project-status)
  - [Features](#features)
  - [Technologies](#technologies)
  - [How to run](#how-to-run)
    - [Requirements](#requirements)
    - [Cloning](#cloning)
    - [Running server app](#running-server-app)
    - [Running web app](#running-web-app)
    - [Running mobile app](#running-mobile-app)
  - [Author](#author)
  - [License](#license)

## Project status

:rocket: Current version: 1.0

:construction: Version 2.0 in development

## Features

- [x] contact a teacher via whatsapp
- [ ] user authentication
- [ ] password recovery
- [ ] teacher profile
- [ ] splash screen (mobile version)
- [ ] teacher list pagination
- [ ] teacher available time display
- [ ] favorite teachers on database
- [ ] application logout

## Technologies

This project is powered by:

- [React](https://reactjs.org/)
- [React Native](https://reactnative.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Expo](https://expo.io/)
- [Express](https://expressjs.com/)

## How to run

### Requirements

Before starting, you'll need to install on your PC the following tools: [Git](https://git-scm.com/), [Node.js](https://nodejs.org/en/) / [Yarn](https://yarnpkg.com/). In addition, it is a good idea to have a code editor like [VS Code](https://code.visualstudio.com/).

For the following commands, use the command line terminal of your choice.

### Cloning

```bash
$ git clone https://github.com/allanfantoni/proffy.git
```

### Running server app

```bash
# Go to server folder
$ cd proffy/server

# Installing dependencies
$ yarn install
# or
$ npm install

# Running application
$ yarn start
# or
$ npm start
```

Your server app will be running at http://localhost:3333/

### Running web app

```bash
# Go to web folder
$ cd proffy/web

# Installing dependencies
$ yarn install
# or
$ npm install

# Running application
$ yarn start
# or
$ npm start
```

Your web app will be running at http://localhost:3000/


### Running mobile app

In order to run the mobile app you need to install Expo app on your smartphone or an Android / iOS emulator on your PC.

```bash
# Go to mobile folder
$ cd proffy/mobile

# Installing dependencies
$ yarn install
# or
$ npm install

# Running application
$ yarn start
# or
$ npm start
```

If you choose to run on your smartphone you need to read the QR Code which is displayed on your PC screen using the smartphone camera.

## Author

Made by [Allan Fantoni](https://github.com/allanfantoni).

## License

Released in August 2020 under the [MIT license](https://github.com/allanfantoni/proffy/blob/master/LICENSE).