![Thiago Marinho](https://pbs.twimg.com/profile_banners/41742474/1490016588/1500x500)

# MeetApp

> Meetapp (an acronym for Meetup + App): App for organizing, viewing and subscribing meetups for developers.

Link to each projects are below:

* Backend API NodeJS: [https://github.com/tgmarinho/meetapp-api](https://github.com/tgmarinho/meetapp-api)
* Frontend React (CRA): [https://github.com/tgmarinho/meetapp-react](https://github.com/tgmarinho/meetapp-react)
* Mobile (React Native): [https://github.com/tgmarinho/meetappRN](https://github.com/tgmarinho/meetappRN)


![Details web](screenshots/details-web.png)


## Getting Started

These instructions will get you a copy of the full project up and running on your local machine for development and testing purposes.

The project can be built with npm or yarn, so choose one of the approach bellow in case you don't have any installed on your system.

* **Npm** is distributed with Node.js which means that when you download Node.js, you automatically get npm installed on your computer. [Download Node.js](https://nodejs.org/en/download/)

* **Yarn** is a package manager built by Facebook Team and seems to be faster than npm in general.  [Download Yarn](https://yarnpkg.com/en/docs/install)

* **React Native CLI** is a package that contains tools and helpers for React Native projects in form of a command line tool.  [Download React Native CLI](https://facebook.github.io/react-native/docs/getting-started)

## Setting up Databases and Services

The project uses [PostgreSQL](https://www.postgresql.org), [MongoDB](https://www.mongodb.com) and [Redis](https://redis.io).

I recommend use [Docker](https://www.docker.com) to install and run the databases and services above.

## How to Install

### Backend (API)

* To download the project follow the instructions bellow:

```
1. git clone https://github.com/tgmarinho/meetapp-api.git
2. cd meetapp-api
```

* Install the dependencies and start the server:

```
3. yarn install
4. yarn dev
```

or

```
3. npm install
4. npm dev
```

Rename the file `.env.example` to `.env` and create yours environment variables and replace them. It's is very important for running the server.

Also, I'm sending the Insomnia file for call the API, download it [here](https://github.com/tgmarinho/meetapp/blob/master/Insomnia_2019-10-27.json).

### Frontend (React)

* To download the project follow the instructions bellow:

```
1. git clone https://github.com/tgmarinho/meetapp-react.git
2. cd meetapp-react
```

* Install the dependencies and start the project:

```
3. yarn install
4. yarn start
```

or

```
3. npm install
4. npm start
```

### Mobile

* To download the project follow the instructions bellow:

```
1. git clone https://github.com/tgmarinho/meetappRN.git
2. cd meetappRN
```

* Install dependencies

```
1. yarn install
```

* Start the application:

```
3. react-native run-ios
```


## Keep in Touch

Thiago Marinho
* [tgmarinho@gmail.com](mailto:tgmarinho@gmail.com)
* [tgmarinho.com](http://tgmarinho.com)
* [twitter/tgmarinho](http://twitter.com/tgmarinho)
* [github.com/tgmarinho](http://github.com/tgmarinho)
* [linkedin.com/in/tgmarinho](http://linkedin.com/in/tgmarinho)


## Screen Shots


* Editing Meetup

![Editing Web](screenshots/edit-web.png)

* Listing Meetups

![Insomnia](screenshots/listMeetup-werb.png)

* Profile Frontend

![Insomnia](screenshots/profile-web.png)

* SignIn Web

![Insomnia](screenshots/sign-web.png)

* SignUp Web

![Insomnia](screenshots/signup-web.png)

* Inscrições Mobile

![Insomnia](screenshots/inscricoes-mobile.png)

* Meetups Mobile

![Insomnia](screenshots/meetups-mobile.png)

* SignIn Mobile

![Insomnia](screenshots/sign-mobile.png)

* SignUp Mobile

![Insomnia](screenshots/signup-mobile.png)

* Infinite Scroll Mobile

![Insomnia](screenshots/sroll-mobile.png)


* Insomnia API

![Insomnia](screenshots/insomnia-api.png)


That's it! =)

## Thank you

Thanks [Rocketseat](https://rocketseat.com.br/) I really liked the bootcamp!

## License

This project could be used by anyone! MIT License
