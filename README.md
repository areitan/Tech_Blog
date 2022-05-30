# Tech_Blog

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

---
## Description

This is an MVC application tech blog built with [MySQL2](https://www.npmjs.com/package/mysql2), [Sequelize](https://www.npmjs.com/package/sequelize), [Express.js](https://www.npmjs.com/package/express), [express-session](https://www.npmjs.com/package/express-session), [express-handlebars](https://www.npmjs.com/package/express-handlebars), [bcrypt package](https://www.npmjs.com/package/bcrypt), and the [dotenv](https://www.npmjs.com/package/dotenv) package, and deployed with Heroku.
  

---
## Table of Contents

  - [Installation](#installation)
  - [Usage](#usage)
  - [Tests](#tests)
  - [Contribute](#contribute)
  - [Credits](#credits)
  - [License](#license)


---
## Installation

1. Clone the repo. 
2. In the terminal for the project, run "npm i" to install dependencies.
3. In MySQL, run ```source db/schema.sql```
4. Exit MySQL once the schema has successfully been sources.
5. Run ```node seeds/seed.js``` to bring in the seed data.
6. In the terminal run ```node server.js``` to start the server.

- [Tech Blog Git Hub Repository](https://github.com/areitan/Tech_Blog)
- [Tech Blog Deployed Link](https://obscure-earth-91382.herokuapp.com/)


---
## Usage

In order to use this application navigate to the deployed link above. The application should allow the user to view, create, and comment on blog posts.

### Homepage
![Tech Blog Homepage](/assets/1_schema.png)


---
## Tests

The routes were tested manually.

### Tech Blog Mock-ups Provided
![Tech Blog Mock-up 1](/assets/14-mvc-homework-demo-01.gif)


--- 
## Contribute

In order to create this application, I used the skills I have at the moment. I am open to suggestions, if there are ways to streamline the code or if any bugs are found.

---
## Credits

- [MySQL2](https://www.npmjs.com/package/mysql2)
- [Sequelize](https://www.npmjs.com/package/sequelize)
- [Express.js](https://www.npmjs.com/package/express)
- [dotenv](https://www.npmjs.com/package/dotenv) package.
- Trilogy Education Services, LLC for example code throughout the week 14 exercises and example mock-up.
- Chris Baird, my tutor


### Questions

For any question, please contact me on GitHub at: [areitan](https://github.com/areitan) or by email at <areitan@fredhutch.org>.

---

## License

Copyright (c) ```<2022> <copyright April Reitan>```

MIT License:
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.