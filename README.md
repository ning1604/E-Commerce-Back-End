# E-Commerce-Back-End
## Description
The purpose of this project was to configure a working Express.js API to use Sequelize to interact with a MySQL database. Users will be able to perform calls to get, create, update and delete data. <br />

GitHub repository: https://github.com/ning1604/E-Commerce-Back-End

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Questions](#questions)

## Installation
To use the application, the repository should be cloned and node should be installed. Click on the link to be directed to guides for [cloning a respository](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) and [node installation](https://nodejs.org/en/download/).<br />

Open terminal and run the following command to install necessary dependencies:
```
npm i
```
Create database by running the following command and entering password when prompted.
```
mysql -u root -p
```
After password is entered, run the following commands:
```
source ./db/schema.sql
```
```
quit
```
To seed the database, run the following commands:
```
npm run seed
```
To run the application, in the terminal run the following command (in directory of the cloned repository).
```
npm start
```

## Usage
The following video demonstrates usage of application:<br />

https://user-images.githubusercontent.com/100749559/185776917-2a22a5fa-3cf7-43a3-a95d-5bdf29be00d4.mp4

[video link](https://drive.google.com/file/d/1AU42u5V1BnciQCsb_6Qwblj_lFPnRNUM/view)

## License
This project has no license.

## Contributing
To contribute, follow the steps under [Installation](#installation).

## Questions
For further questions about the repository, open an issue or contact me directly at [ningzhawb@gmail.com](mailto:ningzhawb@gmail.com). You can find more of my work at [ning1604](https://github.com/ning1604?tab=repositories).
