# Moleculer template: `project`
:mortar_board: Moleculer-based microservices project template.

## Features
- Moleculer v0.13.x with full-detailed `moleculer.config.js` file.
- Common project with a demo `greeter` service.
- Optional API Gateway service.
- Optional Transporter & Cacher.
- Docker & Docker Compose files.
- Unit tests with [Jest](http://facebook.github.io/jest/).
- Lint with [ESLint](http://eslint.org/).
- Launch file for debugging in [VSCode](https://code.visualstudio.com/).


## Install
To install use the [moleculer-cli](https://github.com/moleculerjs/moleculer-cli) tool.

```bash
$ moleculer init project my-project
```

## Prompts
```
$ moleculer init project moleculer-demo

Template repo: moleculerjs/moleculer-template-project
? Add API Gateway (moleculer-web) service Yes
? Would you like to communicate with other nodes? Yes
? Select a transporter TCP
? Would you like to use cache? No
? Add Docker files? Yes
? Use ESLint to lint your code? Yes
? Setup unit tests with Jest? Yes
Create 'moleculer-demo' folder...
? Would you like to run 'npm install'? Yes
```

## NPM scripts
- `npm run dev`: Start development mode (load all services locally with hot-reload & REPL)
- `npm run start`: Start production mode (set `SERVICES` env variable to load certain services)
- `npm run cli`: Start a CLI and connect to production. Don't forget to set production namespace with `--ns` argument in script
- `npm run lint`: Run ESLint
- `npm run ci`: Run continuous test mode with watching
- `npm test`: Run tests & generate coverage report
- `npm run dc:up`: Start the stack with Docker Compose
- `npm run dc:down`: Stop the stack with Docker Compose

## License
moleculer-template-project is available under the [MIT license](https://tldrlegal.com/license/mit-license).

## Contact
Copyright (c) 2018 MoleculerJS

[![@moleculerjs](https://img.shields.io/badge/github-moleculerjs-green.svg)](https://github.com/moleculerjs) [![@MoleculerJS](https://img.shields.io/badge/twitter-MoleculerJS-blue.svg)](https://twitter.com/MoleculerJS)
