# E-commerce Back End

  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)]

  ## Desciption
  This app is a back-end setup to be used for an ecommerce website. The app allows data to be viewed, entered, modified, and/or deleted from the ecommerce database.

  ## Table of Contents
  * [Installation](#installation)
  * [Usage](#usage)
  * [Contriuting](contributing)
  * [License](#license)
  * [Support](support)
  
  ## Installation
  As this app is back-end only, it is run as a server. Instead of interacting with the front end, the app is currently set up in a way that it must be interfaced through an app such as Insomnia, which allows users to make http requests locally. There is a demo video below that shows the steps required. If you wish to run the app on your local machine, you will need to install Insomnia. Next, visit https://github.com/djbartolini/ecommerce-back-end to clone the repository to your local machine. Then run a few simple commands to get started: 
  ```
  npm i
  npm run db:sync
  npm run seed
  npm run env:copy 
  npm run start
  ```

  ## Usage
  Access https://docs.insomnia.rest/insomnia/get-started for information on Insomnia. If you wish to run, edit, or use this app locally you can follow the instruction above for installation. Once installed, use insomnia to interact with the database.

  ## Demo
  ![Demo](./assets/ecommerce-back-end-demo.gif)

  ## Contributing
  This app was made using: 
  * [Insomnia](https://insomnia.rest/)
  * [Node.js](https://nodejs.org/en/)
  * [Express.js](https://expressjs.com/)
  * [Sequelize](https://sequelize.org/)

  ## License
  This app is covered under the MIT license: [MIT](https://opensource.org/licenses/MIT)

  ## Support
  If you encounter problems with this README generator, please reach out to me on GitHub at: https://github.com/djbartolini, or email me at dan.barto@gmail.com
