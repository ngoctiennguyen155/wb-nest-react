### Install package

if you want install package for api or client, you can:

```js
cd apps/api
npm i package-name
----or---
cd apps/client
npm i package-name
```

other way, you can using:

```js
npm install --workspace api (or client) package-name
```

### scripts

#### developer mode

```js
npm run dev
```

This script start both frontend and backend.

#### build

```js
npm run build
```

This script build both frontend and backend inside both folder dist of api and client.

### production mode

#### build

```js
npm run prod
```

This script start production, using both dist folder of api and client.
