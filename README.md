<div id="top"></div>

<!-- PROJECT LOGO -->
<br />

<!-- TABLE OF CONTENTS -->
## Table of Contents
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#requirements">Requirements</a></li>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#setup-env-example">Setup .env example</a></li>
      </ul>
    </li>
    <li><a href="#rest-api">REST API</a></li>
    <li><a href="#related-project">Related Project</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project
Create a Node.js app for building realtime chat RESTful APIs using Express.


### Built With
This app was built with some technologies below:
- [Node.js](https://nodejs.org/en/)
- [Express.js](https://expressjs.com/)
- [JSON Web Tokens](https://jwt.io/)
- [Nodemailer](https://nodemailer.com/about/)
- [PostgreSQL](https://www.postgresql.org/)
- [Socket.io](https://socket.io/)
- and other

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

* [Node.js](https://nodejs.org/en/download/)

### Requirements
* [Node.js](https://nodejs.org/en/)
* [Postman](https://www.getpostman.com/) for testing
* [Database](./blanja.sql)

### Installation

- Clone the Repo
```
git clone https://github.com/PabloMazurkiewicz/React-Realtime-Chat-API.git
```
- Go To Folder Repo
```
cd React-Realtime-Chat-API
```
- Install Module
```
npm install
```
- Make a new database and import [telegram.sql](./blanja.sql)
- <a href="#setup-env-example">Setup .env</a>
- Type ` npm run dev` To Start Development
- Type ` npm run start` To Start Production

<p align="right">(<a href="#top">back to top</a>)</p>

### Setup .env example

Create .env file in your root project folder.

```env
# app
APP_NAME=
NODE_ENV=
PORT=
API_URL=
APP_CLIENT=

# database
DB_HOST=
DB_USER=
DB_PASSWORD=
DB_NAME=
DB_PORT=

# jwt
JWT_SECRET=
JWT_EXPIRED=

# google
EMAIL_FROM=
EMAIL_USER=
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
REDIRECT_URI=
GMAIL_REFRESH_TOKEN=
DRIVE_REFRESH_TOKEN=
```

<p align="right">(<a href="#top">back to top</a>)</p>

## REST API

You can view my Postman collection [here](https://www.postman.com/warped-shadow-374852/workspace/realtime-chat/overview)
</br>
[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/19659051-c6105e73-8adf-43fa-ac97-915206fd49cd?action=collection%2Ffork&collection-url=entityId%3D19659051-c6105e73-8adf-43fa-ac97-915206fd49cd%26entityType%3Dcollection%26workspaceId%3D48100499-9974-4c89-8d1f-e53a8d5f8511)

<p align="right">(<a href="#top">back to top</a>)</p>


## Related Project
:rocket: [`Backend Chatting`](https://github.com/PabloMazurkiewicz/React-Realtime-Chat-API.git)

:rocket: [`Frontend Chatting`](https://github.com/PabloMazurkiewicz/React-Realtime-Chat-Front.git)


<p align="right">(<a href="#top">back to top</a>)</p>
