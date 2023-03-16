# E-commerce App
  ![License](https://img.shields.io/badge/license-MIT-red.svg)

## Description
This application provides the backend for an e-commerce website. Once the application is invoked, the user can open Insomnia Core to create, read, update, and delete data for products, categories, and tags. 

## Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Questions](#questions)

## Installation

Start in the root directory and run `npm i` in the terminal to install required dependencies. Next, run `mysql -u root -p` to login to MySQL shell. Create the schema by running `source ./db/schema.sql` and then run `quit` to exit MySQL shell. Seed the database by running `npm run seed` in the terminal. Lastly, run `npm start` in the terminal to start the server.

## Usage
All dependencies must be installed in the terminal. Next, login to MySQL and create the schema from the MySQL shell, followed by seeding the database. After this, start the server in order to use GET, POST, PUT, and DELETE requests in Insomnia Core. This [walkthrough video](https://drive.google.com/file/d/1J2wdIgZkra0TQqQbJlNK5qitrrksrrqj/view) will demonstrate the installation process and how to create, read, update, and delete data in Insomnia Core.

## License
  This application is licensed by the MIT license.


## Questions

For any questions, please contact me at jared.tichacek@gmail.com. Feel free to check out more of my projects at [jtich40](https://github.com/jtich40)!
