

# Node-Express-Boilerplate!
This is a basic starter template for a Node.js backend app with basic dependencies installed already. The app is dockerised with MongoDB and PostgreSQL support out-of-the-box.

<a href="https://www.codefactor.io/repository/github/akshat2602/Node-Express-Boilerplate/overview/master" target="_blank"> <img src="https://img.shields.io/codefactor/grade/github/akshat2602/Node-Express-Boilerplate?style=flat-square" /> </a>
<a href="https://github.com/akshat2602/Node-Express-Boilerplate/blob/master/LICENSE" target="_blank"> <img src="https://img.shields.io/github/license/akshat2602/Node-Express-Boilerplate?style=flat-square" /> </a>
<a href="https://github.com/akshat2602/Node-Express-Boilerplate" target="_blank"> <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/akshat2602/Node-Express-Boilerplate?style=flat-square"> </a>

## About the template 
-   PostgreSQL used as the primary database.
-   Containerized using Docker and managed using docker-compose.
-   DB Connection already established in the NodeJS app.


## Getting Started
To get a local copy of this template up and running on your machine, follow these simple steps.
### Prerequisites
- Docker
`curl -fsSL https://get.docker.com -o get-docker.sh`
`sudo sh get-docker.sh`

### Installation
- Clone the repo `git clone https://github.com/akshat2602/Node-Express-Boilerplate.git`
- Change the current directory to the template `cd node-express-boilerplate`
#### Development Environment
- To get started with development first build the dev containers using the following command `docker-compose -f docker-compose.dev.yml build`
- The env file being used for development is called `.env.dev`
- Run the containers using the command `docker-compose -f docker-compose.dev.yml up`
#### Production Environment
- To get started with development first build the dev containers using the following command `docker-compose -f docker-compose.prod.yml build`
- The env file being used for production is called `.env` which can be created using the command `cp ./.env.dev ./.env`
- Run the containers using the command `docker-compose -f docker-compose.prod.yml up -d`
#### Installing new npm packages
- New packages can be installed through your preferred terminal using the normal `npm i` command following which the containers need to be rebuild for the app to start working again.

## Technologies used
<a href="https://nodejs.org/en/" target="_blank"><img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white"/> </a>
<a href="https://www.docker.com/" target="_blank"><img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/> </a>
<a href="https://www.postgresql.org" target="_blank"> <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/></a>

## Contributing
Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request


## License
Distributed under the MIT License. See `LICENSE` for more information.


## Contact
Akshat Sharma - [akshatsharma2602@gmail.com](mailto:akshatsharma2602@gmail.com)
Project Link: [https://github.com/akshat2602/Node-Express-Boilerplate](https://github.com/akshat2602/Node-Express-Boilerplate)


