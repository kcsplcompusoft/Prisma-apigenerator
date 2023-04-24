# prisma-apigenerator

This package Auto generates the CRUD endpoints for mysql, postgres and sqlserver using prisma and it also support the apollo GraphQL and swagger. Swagger is auto generates when user selects the RestAPI type.

## Installation & Usage

To install this package enter this command on your terminal:
```bash
npm install prisma-apigenerator
or
yarn add prisma-apigenerator
```

To use the functionality of this node module in your project you need to run the following command in terminal:
```bash
npx generatePrismaAPI
```

or else you can download this package globally in your system with this command:
```bash
npm install -g prisma-apigenerator
or
yarn global add prisma-apigenerator
```

To use the functionality of this node module Globally in your project you need to run the following command in terminal:
```bash
generatePrismaAPI
```

After run that command it will ask for some input regarding database and api type like:
```
Database Driver:
Database name:
Database port:
Database user:
Database password:
Database Host:
what you want to use?
1. RestAPI
2. GraphQL
```

user needs to enter that information to make auto generation possible.