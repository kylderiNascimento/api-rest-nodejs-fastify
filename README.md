
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