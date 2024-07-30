### GrubDash Backend Server

#### Installation

All installation scripts are in the [`package.json`](package.json) "prestart" script. To begin running the development server. Choose which option to use:

1. Production: `npm start`
2. Development: `npm run start:dev` // utilizes [`nodemon`](https://www.npmjs.com/package/nodemon) to hot-reload after saving changes.

#### Testing

Unit tests for both the `/dishes` and `/orders` controllers and routers are available in the `/test` directory. From the project root run:

```bash
cd server && npm test
```
