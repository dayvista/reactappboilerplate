# React App Boilerplate

## with Babel, Live Server, and PostCSS

## Create your own React App without the bloat of create-react-app. Compiled with Webpack.

## First things first:

- Clone repository:

  _git clone https://github.com/dayvista/reactappboilerplate_

- Install dependencies:

  _npm install_

## Now you may begin!

- To start, run:

  _npm run start_
  to begin the live server. It will open at [http://localhost:8080](http://localhost:8080).

- For dev mode:

  _npm run dev_

- For production build:

  _npm run build_

## Security Vulnerability Warning:

- There is a security vulnerability that may appear because of some packages being dependent on an outdated version of the package _chokidar_. Chokidar in turn uses an outdated version of the _minimist_ package To find out if the security vulnerability is present, run:

_npm audit_

- If your app has the security vulnerability, run:

_npm install chokidar_
