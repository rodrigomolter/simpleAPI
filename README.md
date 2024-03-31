# Motion Hub API 🎬
It's a simple API where you can store the details of your videos, like title, description and duration.<br>
It uses `in-memory database`. It means it will only store data while running and when you stop the application **all data will be lost**.


## Docs 📋
You can check the API Documentation while running the application on<br>

**http://localhost:3333/documentation**

Or enter the [swagger.yaml](./src/swagger.yaml) in the [SwaggerEditor](https://editor-next.swagger.io/)


## Test Plan 👨‍🔬
The avaiable **Test Plans** for the application are located here: <br>
**[🎬 Motion Hub API Testing Plans](https://dynamic-keeper-66c.notion.site/Motion-Hub-fe69d08e0e23419baf06ceeb23e669c9)**
## Installation 🏗️
To run this project you will need

- [Node.js](https://nodejs.org/en/) (I've used version `v18.17.1` while writing this doc)

**Note:** When installing Node.js, npm is automatically installed. 🚀

Run to install the dev dependencies
```bash
npm install
```


Start the API with the command
```bash
npm run start
```

## Running the tests ✔️

In this project, you can run tests in interactive and headless mode

### Headless mode </>

Run `npm test` (or `npm t` for short) to run all tests in headless mode.
```bash
npm test
```

### Interactive mode 🕹️

Run `npm run cy:open` to open the __Cypress App__ to run tests in interactive mode.
```bash
npm run cy:open
```

## Support this project 🙌

If you want to support this project, leave a ⭐.

___

Made with love 🧡 by [Rodrigo Molter](https://www.linkedin.com/in/rodrigo-molter/)
