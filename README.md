
# API REST - Node.js - Fastify

### Libs
Install Fastify
```sh
npm install fastify
```

Install typescript
```sh
npm install -D typescript
npm install -D @types/node
```

To run the server, we need to convert the TS file to JS with the command line below:
```sh
npx tsc src/server.ts
```

Now after the JS file is created, we can send the node to execute the JS file:
```sh
node src/server.js
```

To make the TS file conversion process more efficient and run node on the converted file, we will install a tool called TSX. But we must remember that this tool is only for "development mode".
```sh
npm install tsx -D
```
```sh
npx tsx src/server.ts
```
```sh
npm run dev
```

We will use the query builder Knex.js for the database.
https://knexjs.org
```sh
npm install knex sqlite3
```
To create a migration:
```sh
npm run knex -- migrate:make create-documents
```

Environment variables:
Install DotENV
```sh
npm install dotenv
```

we will use the ZOD lib for data validation in our environment variables
```sh
npm install zod
```