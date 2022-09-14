<h1 align="center"><img alt="NLW eSports Server" title="NLW eSports Server" src=".github/logo.svg" width="250" /></h1>

# NLW eSports Server

## 💡 Project's Idea

This project was developed during the RocketSeat's Next Level Week - eSports event. It aims to create a *backend* server application for providing advertisements for players which are loooking for other players to play online games with.

## 🔍 Features

* Available games listing;
* Available advertisements listing;
* New advertisements creation;

## 💹 Extras

* 

## 🛠 Technologies

During the development of this project, the following techologies were used:

- [Node.js](https://nodejs.org/en/)
- [Express](https://expressjs.com/pt-br/)
- [Prisma](https://www.prisma.io/)
- [TypeScript](https://www.typescriptlang.org/)

## 💻 Project Configuration

### First, install the dependencies for the project

```bash
$ yarn
```

## 🌐 Setting up config files

Create an *.env* file on the root directory, with all needed variables, credentials and API keys, according to the sample provided (*.env example*).

## ⏯️ Running

To run the project in a development environment, execute the following command on the root directory.

```bash
$ yarn dev
```

In order to view and update the database contents, we can use the [Prisma Studio](https://www.prisma.io/studio), which can be laucnhed with the following command:

```bash
$ npx prisma studio
```

## 🔨 Project's *Build* for *Deploy*

In order to deploy the app online, there are some steps to be done. First, you must *build* the project, since it was developed using *TypeScript*, and *Node* can only run *JavaScript*.

To *build* the project for the production server, execute the following command on the root directory.

```bash
$ yarn build
```

### Documentation:
* [zod: TypeScript-first schema validation with static type inference](https://github.com/colinhacks/zod)

## 📄 License

This project is under the **MIT** license. For more information, access [LICENSE](./LICENSE).
