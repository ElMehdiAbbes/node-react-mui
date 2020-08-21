

# Express React with Material UI Starter


[![npm](https://img.shields.io/npm/v/github-buttons)](https://www.npmjs.com/github-buttons)

This is a template for using Express and React with Material UI installed in the same project. It is based on [Create React App](https://github.com/facebookincubator/create-react-app)

## Installing

```bash
git clone https://github.com/ElMehdiAbbes/node-react-mui.git
cd app-name
npm install
```

## Running The App

The template can be run in development, or in production. For development, use the following workflow.

### Start the Express Server

```bash
node server/server.js
```

### Start Create React App

In a different terminal tab...

```bash
npm start
```

![Imgur](http://i.imgur.com/f7Nlvx4.png)

The "Welcome to React" is a message that comes from the Express server. 

## Building For Production

In production, you want Express to serve up your app.

### Build React App

```bash
npm build
```

Now simply visit the Express app at 'http://localhost:3001' and you will see your app served from the 'build' folder. That's all there is to it!
