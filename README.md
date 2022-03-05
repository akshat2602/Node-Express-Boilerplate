

# Node-Express-Boilerplate!
This is a basic starter template for a Node.js backend app with basic dependencies installed already. The app is dockerised with MongoDB and PostgreSQL support out-of-the-box.


## Getting Started
To get a local copy of this template up and running on your machine, follow these simple steps.
### Prerequisites
- Docker
`curl -fsSL https://get.docker.com -o get-docker.sh`
`sudo sh get-docker.sh`

### Installation
- Clone the repo `git clone https://github.com/PICT-ACM-Student-Chapter/Node-Express-Boilerplate.git`
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

Project Link: [https://github.com/PICT-ACM-Student-Chapter/Node-Express-Boilerplate](https://github.com/PICT-ACM-Student-Chapter/Node-Express-Boilerplate)


