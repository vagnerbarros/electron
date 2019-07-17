# Vue Electron with backend Node.js Application

In the frontend folder there is an initial design skeleton in Vue.js using Electron to generate installer that communicates with the backend using axios.
In the backend folder there is the initial skeleton of a Node.js project that has an API-REST using Express. In this project, the persistence layer uses MongoDB, through the Mongoose framework.
The main differential of this project is the Docker configurations and docker-compose at the root of the project. On a machine with docker installed it is possible to start the frontend and backend services on the same machine. Just install Docker first.

## Getting started



## Buy me a coffee

If I could contribute in any way and you want to help me, buy me a coffee. :coffee:

<a href="https://www.buymeacoffee.com/ghJFcwaeQ" target="_blank"><img src="https://bmc-cdn.nyc3.digitaloceanspaces.com/BMC-button-images/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a>

## Requirements

-   Node.js

## How to install

### Using Git (recommended)

1.  Clone the project from github.

```bash
git clone https://github.com/vagnerbarros/vue-electron.git
```

### Using manual download ZIP

1.  Download repository
2.  Uncompress to your desired directory

### Setting up environments

1. Open a new Terminal

```bash
cd vue-electron
cd backend
node app.js
```

2. Open a new Terminal

```bash
cd vue-electron
cd frontend
npm run electron:serve
```
### Login

```bash
email: vagner@gmail.com
password: 123
```

## License

This project is open-sourced software licensed under the MIT License. See the LICENSE file for more information.
