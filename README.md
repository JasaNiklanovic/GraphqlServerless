# Serverless GraphQL

Showcase of different ways you can use GraphqQL on Serverless

This example uses the following technologies:

## Quick Setup

```
npm install -g serverless
npm install -g yarn
npm install -g netlify-cli
```

Install Dependencies.
```
yarn install
```

## Quick Start (Serverless Offline)
Please note: AWS CLI is required to be installed on your system

1. **Select Backend** (Twitter Rest API or DynamoDB)

- *Twitter Rest API*
    ```
    cd app-backend/rest-api
    yarn start
    ```

- *DynamoDB*
    ```
    cd app-backend/dynamodb
    yarn start
    ```

2. **Start FrontEnd**

```
cd app-client
yarn start
```

3. **Start GraphQL Playground (GraphiQL replacement)**

```
http://localhost:4000/playground
```