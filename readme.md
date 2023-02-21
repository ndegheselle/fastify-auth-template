# API template

Fastify to handle http request, Prisma to handle database connection. Authentification is based on JWT with a refresh token to facilitate API consumption.

## Setup

Install the dependencies and generate the Prisma client :
```
npm install
npx prisma generate
```

## More informations

* [Fastify](https://www.fastify.io/docs/latest/)
  * [@fastify/autoload](https://www.npmjs.com/package/@fastify/autoload)
  * [@fastify/cors](https://www.npmjs.com/package/@fastify/cors)
  * [@fastify/cookie](https://www.npmjs.com/package/@fastify/cookie)
* [Prisma](https://www.prisma.io/docs/getting-started/quickstart)
* [JWT](https://www.npmjs.com/package/jsonwebtoken)