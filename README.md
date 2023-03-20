# E-commerce-Back-End
This is an e-commerce website site which uses Express.js API, Sequelize, and a MySQL database.


## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)


## Features

There are three objects in the system: Products, Tags, and Categories.
Categories can have multiple Products, but a Product can only belong to one Category.
Products are allowed to have multiple Tags and Tags to have many products.

## Installation

Download or clone this project, open it in your local, and run ```npm start```

## Usage

Use an API client to access to the end points listed below, and perform CRUD operations:
- http://localhost:3001/api/categories
- http://localhost:3001/api/tags
- http://localhost:3001/api/products


This is a [demo video](https://drive.google.com/file/d/1Kg96XFRrVO53FWK_5XPIOU5beRb7Llmy/view)


## License

![license](https://img.shields.io/badge/license-MIT-green)


