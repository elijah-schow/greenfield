# Grocery List

Stay within budget while shopping.

## Team

  - __Product Owner__: Elijah Schow
  - __Scrum Master__: Cory Grinstead
  - __Development Team Members__:
    - Burk McRae
    - Jonathan Granstaff

## Table of Contents

1. [Team](#team)
1. [Usage](#Usage)
1. [Requirements](#requirements)
1. [Development](#development)
    1. [Installing Dependencies](#installing-dependencies)
    1. [Run Locally](#run-locally)
    1. [Tasks](#tasks)
1. [Contributing](#contributing)

## Usage

> TODO: add some usage instructions

## Requirements

- Node 5.xx.x +
- ReactJS
- Webpack
- (see `package.json` for details)

## Development

### Tasks

View the [project roadmap](https://github.com/EliJoBurCo/greenfield/issues)

### Installing Dependencies

From within the root directory:

```sh
npm install
```

### Run Locally

1. Run the back-end:

  ```sh
  npm start
  ```

2. Build the front-end (in another tab):

  ```sh
  npm run dev
  ```

3. Visit `http://localhost:8080` (or whichever port the server started on).

### Deploy

Follow [this guide](https://www.digitalocean.com/community/tutorials/how-to-set-up-automatic-deployment-with-git-with-a-vps) to configure your deployment server. When you're ready to deplay:

**Run locally:**

1. `git pull --rebase upstream master`
2. `git push live master`

**Run on your server:**

1. `npm install`
2. `webpack -p`
3. `pm2 start server/server.js`

Make sure that you are in the same directory as the application. Also make sure that PM2 is install globally. If not, run: `npm install pm2 -g`

## Contributing

See [CONTRIBUTING.md](https://github.com/unexpected-lion/ourglass/blob/master/contributing.md) for contribution guidelines.
