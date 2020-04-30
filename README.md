# pern-stack-course

Todo list app based on PosgreSQL, Express, React and Node.js

## Setup

* Database

```bash
docker build -t tododb:1.0 .\database
```

* Server

```bash
cd server
npm i
```

* Client

```bash
cd client
npm i
```

## Run

* Database

```bash
docker run -p 5432:5432 --detach --name db tododb:1.0
```

* Server

```bash
nodemon ./server/index
```

* Client

```bash
cd client
npm start
```
