# docker-express-mongodb

Generated by [OSS Project Generator](http://bit.ly/generator-oss-project).

[![License][license-badge]][license-url]

> A playground for Docker with Express and MongoDB.

# Development

* Cloning the repo

```bash
$ git clone https://github.com/robertoachar/docker-express-mongodb.git
```

* Installing dependencies

```bash
$ npm install
```

* Running scripts

| Action                    | Usage          |
| ------------------------- | -------------- |
| Starting development mode | `npm start`    |
| Linting code              | `npm run lint` |

# Docker

* Building an image

```bash
$ docker-compose build
```

* Running a container

```bash
$ docker-compose up
```

* Stopping a container

```bash
$ docker-compose down
```

# Rest API

### User Service

| Method | Endpoint       | Description               |
| ------ | -------------- | ------------------------- |
| GET    | /api/users     | Retrieves a list of users |
| POST   | /api/users     | Retrieves a specific user |
| GET    | /api/users/:id | Creates a new user        |
| PUT    | /api/users/:id | Updates user              |
| DELETE | /api/users/:id | Deletes user              |

# Postman

* postman/docker-express-mongo.postman.json

# Author

[Roberto Achar](https://twitter.com/robertoachar)

# License

[MIT](https://github.com/robertoachar/docker-express-mongodb/blob/master/LICENSE)

[license-badge]: https://img.shields.io/github/license/robertoachar/docker-express-mongodb.svg
[license-url]: https://opensource.org/licenses/MIT
