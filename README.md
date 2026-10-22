# Campus Events

## Requirements

- Node.js 24 LTS or newer, including npm
- Git
- Visual Studio Code
- Angular CLI 22

Install the Angular CLI globally if needed:

```bash
npm install -g @angular/cli@22
```

## Start the server

From the project root:

```bash
cd server
npm install
node hello.js
```

The server will be available at `http://localhost:3000`.

The available endpoints are:

- `GET /` returns a welcome message.
- `GET /time` returns the current server time.

Stop the server with `Ctrl+C`.

## Start the client

In another terminal, from the project root:

```bash
cd client
npm install
npm start
```

The client will be available at `http://localhost:4200`.

Stop the client with `Ctrl+C`.