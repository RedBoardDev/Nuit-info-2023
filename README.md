<div align="center">
<h1 align="center">
<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" />
<br>NUIT-INFO-2023</h1>
<h3>◦ Unleashing Codes of Tomorrow: Nuit-info-2023</h3>
<h3>◦ Developed with the software and tools below.</h3>

<p align="center">
<img src="https://img.shields.io/badge/Chart.js-FF6384.svg?style=flat&logo=chartdotjs&logoColor=white" alt="Chart.js" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=flat&logo=JavaScript&logoColor=black" alt="JavaScript" />
<img src="https://img.shields.io/badge/HTML5-E34F26.svg?style=flat&logo=HTML5&logoColor=white" alt="HTML5" />
<img src="https://img.shields.io/badge/React-61DAFB.svg?style=flat&logo=React&logoColor=black" alt="React" />
<img src="https://img.shields.io/badge/Axios-5A29E4.svg?style=flat&logo=Axios&logoColor=white" alt="Axios" />
<img src="https://img.shields.io/badge/JSON-000000.svg?style=flat&logo=JSON&logoColor=white" alt="JSON" />
<img src="https://img.shields.io/badge/Express-000000.svg?style=flat&logo=Express&logoColor=white" alt="Express" />
</p>
<img src="https://img.shields.io/github/license/RedBoardDev/Nuit-info-2023?style=flat&color=5D6D7E" alt="GitHub license" />
<img src="https://img.shields.io/github/last-commit/RedBoardDev/Nuit-info-2023?style=flat&color=5D6D7E" alt="git-last-commit" />
<img src="https://img.shields.io/github/commit-activity/m/RedBoardDev/Nuit-info-2023?style=flat&color=5D6D7E" alt="GitHub commit activity" />
<img src="https://img.shields.io/github/languages/top/RedBoardDev/Nuit-info-2023?style=flat&color=5D6D7E" alt="GitHub top language" />
</div>

---

## 📖 Table of Contents
- [📖 Table of Contents](#-table-of-contents)
- [📍 Overview](#-overview)
- [📦 Features](#-features)
- [📂 repository Structure](#-repository-structure)
- [⚙️ Modules](#modules)
- [🚀 Getting Started](#-getting-started)
    - [🔧 Installation](#-installation)
    - [🤖 Running Nuit-info-2023](#-running-Nuit-info-2023)
    - [🧪 Tests](#-tests)
- [🛣 Roadmap](#-roadmap)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [👏 Acknowledgments](#-acknowledgments)

---


## 📍 Overview

The Nuit-info-2023 repository hosts a full-scale web application built to manage and monitor user data. It has a robust frontend built with React that includes different components, themes, views, layouts and routing for a seamless UI/UX. The backend, built with Node.js, handles data management, including a MySQL database for user information, an authentication system, and capabilities to manage users' weekly data updates. Additionally, the app has emailing functionalities for account activations and form-based questionnaires for data collection. Overall, this data-focused application presents a solid solution for managing and tracking user data while ensuring a user-friendly interface.

---

## 📦 Features

HTTPStatus Exception: 429

---


## 📂 Repository Structure

```sh
└── Nuit-info-2023/
    ├── Front/
    │   ├── .env_example
    │   ├── package-lock.json
    │   ├── package.json
    │   ├── public/
    │   │   ├── index.html
    │   │   ├── manifest.json
    │   │   └── robots.txt
    │   └── src/
    │       ├── App.js
    │       ├── Assets/
    │       ├── Compenent/
    │       ├── Layouts/
    │       ├── Request/
    │       ├── Theme/
    │       ├── Views/
    │       ├── index.js
    │       └── routes.js
    └── Server/
        ├── .env_example
        ├── db.sql
        ├── package-lock.json
        ├── package.json
        └── src/
            ├── dbLink.js
            ├── email.js
            ├── global.js
            ├── index.js
            └── routes/

```

---


## ⚙️ Modules

<details closed><summary>Server</summary>

| File                                                                                                  | Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| ---                                                                                                   | ---                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [.env_example](https://github.com/RedBoardDev/Nuit-info-2023/blob/main/Server/.env_example)           | The code describes the structure of the Nuit-info-2023 server, containing two primary directories-Front and Server. Front features environment files, package details, JavaScript files, and directories for specific components, themes, and views. Server also has environment files, a SQL database, package files, and server-side scripts. The provided env_example file initiates MySQL database details under different variables, along with email credentials and some other configuration information-all hinting towards a full-scale web application structure.              |
| [db.sql](https://github.com/RedBoardDev/Nuit-info-2023/blob/main/Server/db.sql)                       | The project Nuit-info-2023 consists of a front-end (set up with package.json, public/static files, and various JS/React code files for app structure) and back-end (set up with similar package.json and JavaScript files for server tasks). A MySQL database is created with user and user_daily_data tables, where user_daily_data references user through a foreign key. The database handles user data and timestamps. It's designed for weekly updates of user data.                                                                                                                |
| [package-lock.json](https://github.com/RedBoardDev/Nuit-info-2023/blob/main/Server/package-lock.json) | The given code is part of a web application framework divided into a Front and Server directory. The front-end uses various assets, components, layouts, requests, themes, views, and routes. The back-end (Server) connects to a database and accommodates additional functions like emailing. Its `package-lock.json` shows installed dependencies including axios, bcryptjs, cors, dotenv, express, jsonwebtoken, mysql2, and nodemailer.                                                                                                                                             |
| [package.json](https://github.com/RedBoardDev/Nuit-info-2023/blob/main/Server/package.json)           | The code represents a web application directory structure named Nuit-info-2023 organized into front-end (Front) and server-side (Server) folders. Inside the server folder, a package.json file indicates that this is a Node.js application. It uses several dependencies like express for building the server, axios for making HTTP requests, bcryptjs for password hashing, cors for Cross-Origin Resource Sharing, dotenv for environment variable management, jsonwebtoken for token-based authentication, mysql2 for MySQL database connection and nodemailer for sending emails. |

</details>

<details closed><summary>Src</summary>

| File                                                                                      | Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| ---                                                                                       | ---                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| [dbLink.js](https://github.com/RedBoardDev/Nuit-info-2023/blob/main/Server/src/dbLink.js) | The provided JavaScript code defines a `DbManager` class used to interface with a MySQL database. It utilizes the `mysql2` and `dotenv` libraries for database interactions and environment configuration, respectively. The class methods facilitate various database operations, such as establish/disconnect the connection, execute SQL queries, and manage entries in user and user_daily_data tables. The operations include insert, update, delete, and retrieve user data, with support for special cases based on user's ID or email. |
| [index.js](https://github.com/RedBoardDev/Nuit-info-2023/blob/main/Server/src/index.js)   | The code forms part of an API, running on a server leveraging the Express framework. It includes three main routing modules: auth, user, and form, which handle authentication, user-related actions, and form-related operations respectively. Main functionality is listening on a host and port defined in the environment variables, printing a confirmation message once running. A simple root endpoint sends back Area API when accessed.                                                                                               |
| [email.js](https://github.com/RedBoardDev/Nuit-info-2023/blob/main/Server/src/email.js)   | The provided code constitutes a functionality in Node.js for sending account activation emails. It uses nodemailer and dotenv modules, defines a class EmailSender with a constructor that configures the email transporter using environment variables. A method sendEmail is added to define the email content and recipient, and then utilize the transporter to dispatch the email. It handles potential errors occurring during the email sending process.                                                                                |
| [global.js](https://github.com/RedBoardDev/Nuit-info-2023/blob/main/Server/src/global.js) | This code sets up an express server with cors and body-parser middleware. It can send emails using EmailSender and interacts with data using DbManager. It encrypts and decrypts strings using crypto and can verify Google captcha codes. The code also provides functions to verify if a user-provided token is valid, if the user is authorized to access a resource, and to check if an input is numeric. It also extracts a username from an email.                                                                                       |
| [routes.js](https://github.com/RedBoardDev/Nuit-info-2023/blob/main/Front/src/routes.js)  | HTTPStatus Exception: 429                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [index.js](https://github.com/RedBoardDev/Nuit-info-2023/blob/main/Front/src/index.js)    | This code serves as the main entry point for a React application called Nuit-info-2023, initializing and rendering the app in the root element of the website. The project includes both a Front-end and a Server-side, and follows a modular structure, with components, layouts, requests, themes, views and other distinct entities each having their own directories.                                                                                                                                                                      |
| [App.js](https://github.com/RedBoardDev/Nuit-info-2023/blob/main/Front/src/App.js)        | HTTPStatus Exception: 429                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |

</details>

<details closed><summary>Routes</summary>

| File                                                                                                           | Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| ---                                                                                                            | ---                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| [userDailyData.js](https://github.com/RedBoardDev/Nuit-info-2023/blob/main/Server/src/routes/userDailyData.js) | The code presents an Express Server managing user's daily data in a week. It includes routes to get all user data, retrieve/update/add users' specific week-year data encrypted in the database, and to process weekly data to report environmental footprint. It uses the JWT token for authorization and for getting userID. Database operations are performed using the global.js and dbLink.js files. User's weekly data covers metrics like kilometers_car, area_of_living, time_spent_on_internet, number_of_cigarettes, etc. |
| [form.js](https://github.com/RedBoardDev/Nuit-info-2023/blob/main/Server/src/routes/form.js)                   | The code consists of two JavaScript objects, test and daily, that define questionnaires with various types of questions to be distributed to users. The test questionnaire is generic, while daily relates to users’ daily environmental impact. Two Express.js routes, /test and /daily, allow users with verified tokens to retrieve each questionnaire's contents. The code is part of a server-side application providing backend support to a frontend in Nuit-info-2023.                                                      |
| [user.js](https://github.com/RedBoardDev/Nuit-info-2023/blob/main/Server/src/routes/user.js)                   | HTTPStatus Exception: 429                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| [auth.js](https://github.com/RedBoardDev/Nuit-info-2023/blob/main/Server/src/routes/auth.js)                   | HTTPStatus Exception: 429                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |

</details>

<details closed><summary>Front</summary>

| File                                                                                                 | Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| ---                                                                                                  | ---                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| [.env_example](https://github.com/RedBoardDev/Nuit-info-2023/blob/main/Front/.env_example)           | The provided code is a project directory for a full-stack web application, consisting of front-end and server-side parts. The front end is a JavaScript application, possibly built with React, while the server-side could be a Node.js server. The directory also includes setup files (.env_example, packages, and DB scripts), component, layout, theme directories, public assets like index.html, and routing scripts for both front and back ends. The `.env_example` file sets up environment variables needed by the app. |
| [package-lock.json](https://github.com/RedBoardDev/Nuit-info-2023/blob/main/Front/package-lock.json) | HTTPStatus Exception: 429                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| [package.json](https://github.com/RedBoardDev/Nuit-info-2023/blob/main/Front/package.json)           | HTTPStatus Exception: 429                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |

</details>

<details closed><summary>Public</summary>

| File                                                                                                | Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| ---                                                                                                 | ---                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| [index.html](https://github.com/RedBoardDev/Nuit-info-2023/blob/main/Front/public/index.html)       | HTTPStatus Exception: 429                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| [manifest.json](https://github.com/RedBoardDev/Nuit-info-2023/blob/main/Front/public/manifest.json) | HTTPStatus Exception: 429                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| [robots.txt](https://github.com/RedBoardDev/Nuit-info-2023/blob/main/Front/public/robots.txt)       | The code represents the directory structure of the Nuit-info-2023 project, segregating Front-end and server-related files. The Front-end is created with JavaScript and uses packages. It contains settings, layout, themes, views, and other necessary components. In the server directory, there's provision for environment settings, a SQL database, and server-level routing. The robots.txt file allows all web robots unrestricted access to crawl the website, as indicated by User-agent: * and Disallow: settings. |

</details>

<details closed><summary>Theme</summary>

| File                                                                                         | Summary                   |
| ---                                                                                          | ---                       |
| [theme.js](https://github.com/RedBoardDev/Nuit-info-2023/blob/main/Front/src/Theme/theme.js) | HTTPStatus Exception: 429 |

</details>

<details closed><summary>Compenent</summary>

| File                                                                                               | Summary                   |
| ---                                                                                                | ---                       |
| [graph.jsx](https://github.com/RedBoardDev/Nuit-info-2023/blob/main/Front/src/Compenent/graph.jsx) | HTTPStatus Exception: 429 |

</details>

<details closed><summary>Request</summary>

| File                                                                                         | Summary                                                                                                                                                                                                                                                                                                                                                                                                                  |
| ---                                                                                          | ---                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [Auth.js](https://github.com/RedBoardDev/Nuit-info-2023/blob/main/Front/src/Request/Auth.js) | The code provides functionalities for interaction with local storage and user authentication. It includes methods to read from and write data to local storage, as JSON objects. It also has a function that checks the user authentication status by sending a GET request with a bearer token fetched from local storage to a specified API endpoint. Any occurring error during the process is logged in the console. |

</details>

<details closed><summary>Views</summary>

| File                                                                                         | Summary                   |
| ---                                                                                          | ---                       |
| [quiz.jsx](https://github.com/RedBoardDev/Nuit-info-2023/blob/main/Front/src/Views/quiz.jsx) | HTTPStatus Exception: 429 |

</details>

<details closed><summary>Layouts</summary>

| File                                                                                                   | Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| ---                                                                                                    | ---                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| [oui.jsx](https://github.com/RedBoardDev/Nuit-info-2023/blob/main/Front/src/Layouts/oui.jsx)           | HTTPStatus Exception: 429                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| [mainPage.jsx](https://github.com/RedBoardDev/Nuit-info-2023/blob/main/Front/src/Layouts/mainPage.jsx) | The provided code represents a React file called MainPage, which checks the user authentication status, then navigates to the homepage if they are not authenticated. Using siteRoutes, it maps out navigation routes for the application and generates related components accordingly. It utilizes the ThemeProvider and CssBaseline to manage layout and styling, all wrapped inside the ColorModeContext.Provider to manage the application's color mode. |
| [home.jsx](https://github.com/RedBoardDev/Nuit-info-2023/blob/main/Front/src/Layouts/home.jsx)         | HTTPStatus Exception: 429                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| [Login.jsx](https://github.com/RedBoardDev/Nuit-info-2023/blob/main/Front/src/Layouts/Login.jsx)       | HTTPStatus Exception: 429                                                                                                                                                                                                                                                                                                                                                                                                                                    |

</details>

---

## 🚀 Getting Started

***Dependencies***

Please ensure you have the following dependencies installed on your system:

`- ℹ️ Dependency 1`

`- ℹ️ Dependency 2`

`- ℹ️ ...`

### 🔧 Installation

1. Clone the Nuit-info-2023 repository:
```sh
git clone https://github.com/RedBoardDev/Nuit-info-2023
```

2. Change to the project directory:
```sh
cd Nuit-info-2023
```

3. Install the dependencies:
```sh
npm install
```

### 🤖 Running Nuit-info-2023

```sh
node app.js
```

### 🧪 Tests
```sh
npm test
```

---


## 🛣 Project Roadmap

> - [X] `ℹ️  Task 1: Implement X`
> - [ ] `ℹ️  Task 2: Implement Y`
> - [ ] `ℹ️ ...`


---

## 🤝 Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Submit Pull Requests](https://github.com/RedBoardDev/Nuit-info-2023/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.
- **[Join the Discussions](https://github.com/RedBoardDev/Nuit-info-2023/discussions)**: Share your insights, provide feedback, or ask questions.
- **[Report Issues](https://github.com/RedBoardDev/Nuit-info-2023/issues)**: Submit bugs found or log feature requests for REDBOARDDEV.

#### *Contributing Guidelines*

<details closed>
<summary>Click to expand</summary>

1. **Fork the Repository**: Start by forking the project repository to your GitHub account.
2. **Clone Locally**: Clone the forked repository to your local machine using a Git client.
   ```sh
   git clone <your-forked-repo-url>
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear and concise message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to GitHub**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.

Once your PR is reviewed and approved, it will be merged into the main branch.

</details>

---

## 📄 License


This project is protected under the [SELECT-A-LICENSE](https://choosealicense.com/licenses) License. For more details, refer to the [LICENSE](https://choosealicense.com/licenses/) file.

---

## 👏 Acknowledgments

- List any resources, contributors, inspiration, etc. here.

[**Return**](#Top)

---
