<img src="https://upload.wikimedia.org/wikipedia/commons/3/36/Fortnite.png" alt="fortnite" width="250" align="right" />

A simple, easy to use module for interacting with the [FortniteTracker](https://fortnitetracker.com/) [API.](https://fortnitetracker.com/site-api)

## Setup and Installation
```
$ npm i simple-fortnite-api
```

1. Signup at [FortniteTracker](https://fortnitetracker.com/)
2. Generate an [API Key](https://fortnitetracker.com/site-api)

## Getting Started
```js
// Bring in the Fortnite module
const fortnite = require('simple-fortnite-api');
// Create an instance of the client with your API Key
const client = new fortnite('Your-API-Key');

// All methods
client.find('username').then(console.log);
```

## Issues
If you run into any issues, have any queries or concerns or would just like to make a few suggestions please do not hesitate to join our [discord support server](https://discord.gg/7yhv7CW)
